
### Change `string_a` to `string_b` for all files in`defined` path  (find + sed)
`find defined_path -type f -exec sed -i 's/string_a/string_b/g' {} \;`

narrow to files only for specified extension  `. -regex '.*\.\(extension\)'`


### Change the `some` string in `defined` path  (find + sed)
`find defined_path -type f -exec sed -i 's/string_a/string_b/g' {} \;`

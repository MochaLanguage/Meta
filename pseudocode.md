## Tokenizer
1. Remove comments: replace everything starting with a / without a \ before it up until a \n. Regex: `[^\\]\/.*\n`
2. Replace every space inside of a string with a null character. Regex: `(".*")` to capture a string.
3. Split text by newline
4. Split each line by space: `\s+`
5. Replace every null character with a space and written `\n` with an actual newline.
6. Remove any blank lines 
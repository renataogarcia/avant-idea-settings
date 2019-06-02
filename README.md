# Notes

- "Ensure right margin is not exceeded" will wrap comments but a lot of times will break it as well. You can join the comments and reformat but wrap to column plugin seems to do a better job. It will also wrap the code more aggressively like long message strings or long urls.  

Add new line before opening and closing parens:
- Method doesn't work correctly when "keep line breaks" is disabled
- `if` does not have an option


# Useful
-  Remove blank line after {
```regexp
\{\n^\s*$\n
\{\n
```

- Remove blank line after JavaDoc
```regexp
(/\*\*([^\*]|\*(?!/))*\*/)(\n^\s*$\n)
$1\n
```


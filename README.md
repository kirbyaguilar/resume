## Compiling

To compile the `.typ` files, use either:

```bash
# constant compilation
typst watch resume.typ

# or, use one-time compilation
typst compile resume.typ
```

You may have to add fonts via typst compilation:

```bash
# if needed, replace ./EB_Garamond/static with /path/to/font/folder
typst compile --font-path ./EB_Garamond/static resume.typ

# lists all of the discovered fonts in the system and the given directory.
typst fonts --font-path path/to/fonts
```

## Sources and references

For the EB Garamond font file, get the zip through google fonts [here](https://fonts.google.com/specimen/EB+Garamond) and extract it to this project's root directory
# Pretty Json in Vim

To prettify json in vim you do not need to install additional plugins. If you have python installed adding this command to your .vimrc file will do it:
```viml
com! FormatJSON %!python -m json.tool
```

Then you can prettify your current file with:
`:FormatJSON`

---

#### Tags
`vim` `json` `prettyfy`

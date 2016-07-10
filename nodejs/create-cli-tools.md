
# Create command line tools

You can create cli tools for node.js specifying the `bin` parameter in your `package.json` where the key is the executable name and the value is the path to the file to execute with node.

```json
{
  "bin": {
    "<binaryname>": "<filepath>"
  }
}
```

After that you can try it in your system with `npm link`. You can also distribute it as a module and let other people install it with `npm i -g <modulename>`

---

#### Tags
`node.js` `cli` `javascript`

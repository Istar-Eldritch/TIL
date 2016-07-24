
# Curl binary data

You can use curl to stream binary data.

From a file with:

```bash
curl -XPOST --data-binary @binaryfile.ext http://domain.com
```

From another unix stream:
```bash
echo -e '...data...\n' | curl -XPOST --data-binary @- http://domain.com
```

---

#### Tags
`curl` `unix` `cli` `stream`

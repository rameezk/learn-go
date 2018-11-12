# NOTES

## Large compiled go binary?

Can strip the binary with the following:

```bash
go build -ldflags "-s -w"
```

This repo is a demonstration of the current sizes of an app with `relay` vs `apollo-client`.

A `react` + `react-dom` base is used as a comparison. Each library is then added and the resulting bundle sizes are compared.

Run `sh sizes.sh` to generate:
```
react size in bytes after min and gzip:
   42446
relay size in bytes after min and gzip:
  116157
apollo size in bytes after min and gzip:
   63869
```

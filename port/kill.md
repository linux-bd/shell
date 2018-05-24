## Find a port an kill listening process
```sh
lsof -i :8089
```
* Returned Process ID ` 8984 `
```sh
kill -9 8984
```

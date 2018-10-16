## Locate a file, grep a pattern & open in editor
* ` app.js ` locate with directory name matching ` nodeapp ` and open in ` gedit `
```sh
file=$(locate app.js | grep nodeapp) && gedit $file
```

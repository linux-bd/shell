## date commands
* Current Date Time in String Format
```sh
date '+%Y-%m-%d-%H-%M-%S'
```    
* Current Directory Size to Date Formated File Name

```sh
du -sh > size-$(date '+%Y-%m-%d-%H-%M-%S').txt
```

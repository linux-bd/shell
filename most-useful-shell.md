## Handling files and directories

* Create a directory:
```sh
mkdir dir
```

* Create nested directories:
```sh
mkdir -p dir1/dir2
```

* Changing directories:
```sh
cd newdir
cd .. (parent directory)
cd - (previous directory)
cd (home directory)
cd ~bill (home directory of user bill)
```

* Print the working (current) directory:
```sh
pwd
```

* Copy a file to another:
```sh
cp source_file dest_file
```

* Copy files to a directory:
```sh
cp file1 file2 dir
```

* Copy directories recursively:
```sh
cp -r source_dir dest_dir
rsync -a source_dir/ dest_dir/
```

* Create a symbolic link:
```sh
ln -s linked_file link
```

* Rename a file, link or directory:
```sh
mv source_file dest_file
```

* Remove files or links:
```sh
rm file1 file2
```

* Remove empty directories:
```sh
rmdir dir
```

* Remove non-empty directories:
```sh
rm -rf dir
```

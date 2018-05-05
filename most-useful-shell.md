Handling files and directories 
Create a directory: 
mkdir dir 
Create nested directories: 
mkdir -p dir1/dir2 
Changing directories: 
cd newdir 
cd .. (parent directory) 
cd - (previous directory) 
cd (home directory) 
cd ~bill (home directory of user bill) 
Print the working (current) directory: 
pwd 
Copy a file to another: 
cp source_file dest_file 
Copy files to a directory: 
cp file1 file2 dir 
Copy directories recursively: 
cp -r source_dir dest_dir 
rsync -a source_dir/ dest_dir/ 
Create a symbolic link: 
ln -s linked_file link 
Rename a file, link or directory: 
mv source_file dest_file 
Remove files or links: 
rm file1 file2 
Remove empty directories: 
rmdir dir 
Remove non-empty directories: 
rm -rf dir 

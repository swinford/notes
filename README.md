# Notes

### Entry Template


__command__ - _Description_

__Examples:__

```
bash code in here
```
---

## File Management

__mv__ - _Move file or Rename file_

__Examples:__

```
mv sourceFile destinationFile
mv sourceFile destinationLocation
mv myFile.txt myFolder/
```
---

__cp__ - _Copy file or folder_

__Examples:__

```
cp filename.cpp myCopy.cpp
cp -r myFolder/ myNewFolder
```
---

_rm_ - (file and directories) _Remove files or directories_

_Examples:_

```
rm file/directory
rm myFile.txt
rm Files
```
---

_rmdir_ - _Remove empty directories_

_Examples:_

```
rmdir emptydirectory
rmdir Lab1
```
---

_ln -s_ - _Making links between files_

_Examples:_

```
ln -s link file
ln -s c:\my_links\contacts.doc contracts.txt
```
---

_scp_ - _secure copy (remote file copy program)_

_Examples:_

```
scp source_file username@destination_host:destination_folder
scp newfile.cpp your_username@seawolf.sonoma.edu:Lab1
```
---

_pwd_ - _Print name of current/working directory_

_Examples:_

```
pwd [options]
```
---

_ls_ - (hidden files and files starting or ending with specific patterns like all files ending in txt or all files starting with the letter b) _List directory contents_

_Examples:_

```
ls [options] [file]
```
---


_tar_ - _The GNU version of the tar archiving utility (Add or Extract files)_

_Examples:_

```
tar -cvwf file.tar myfile.cpp
tar -xvwf myfile.tar
```
---

## File Transfer

_curl_ - _Transfer a URL_

_Examples:_

```
curl [options] URL
curl http://www.google.com/
curl -o file1.html http://www.google.com/

```
---

_wget_ - _The non-interactive network downloader_

_Examples:_

```
wget [options] URL
wget linex.about.com 
wget -t 10 linex.about.com
```
---

_scp_ - _Copies files to or from a remote Linux system_

_Examples:_

```
scp file user@host.domain:path
scp file.cpp username@linux.edu:/home/usr/directory
```
---

_rsync_ - _A fast, versatile, remote (and local) file_copying tool_

_Examples:_

```
rsync [option] user@host:destination
rsync -v username@sonoma.edu:Lab1
```
---

## Pipe tools

_cat_ - _Concatenate files and print on the standard output_

_Examples:_

```
cat [options] filename
[options] filename | cat
cat > file.txt | cat
file.txt | cat
```
---

_sort_ - _Sort lines of text files_

_Examples:_

```
sort [options] filename
filename | sort
sort -r file.txt
file.txt | sort
```
---

_uniq_ - _Report or omit repeated lines_

_Examples:_

```
uniq [options] filename
uniq file.txt
uniq -c file.txt
```
---

_grep_ - _Print lines matching a pattern_

_Examples:_

```
grep [options] pattern filename
grep user file.txt
grep -w "hope" myfile.txt
```

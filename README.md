# chromium-issue-473618
OSX filesystems use Unicode Normalization Form D (NFD), and entry.file(…) can't read the files with the same names

# Examples of names

 - йЙёЁ
 - йод
 - файл

![osx_filename_fail](https://dl.dropboxusercontent.com/u/8763532/screenshots/osx_filename_encoding_fail.png)

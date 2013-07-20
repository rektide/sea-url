`urlize` - accepts a url and an optional filename. saves a file with the basename + .url or the specified filename with that url as the contents, and emits the file name on stdout.

`seaurli` - accepts a list of .url files to download, and uses the basename as the download file name

`uget` - accepts a list of url's and runs urlize on each url, and then calls seaurli on the resultant .url files

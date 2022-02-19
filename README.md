# Opencart Extension Packer

## Description
A simple tool to pack source files of an OpenCart extension and their addons into zip archives. Has a autoreplace feature for files into the `src/` dir. Words wrapped by the special tag `<insertvar>` will be replaced with corresponding constants defined into the file `oemconf.php`. For example: `<inservar>VERSION</insertvar>`. It can also inserts the contents of files using the `<insertfile>` tag. For example `<insertfile>path/filename.txt</insertfile>`. `<inservar>` also works in such files.

The tool also can create an encrypted archive of source files. This feature is not yet available to the public (requires special tools) and may be ignored.

See tests - just run `$ php oemaker.php` and read the help.

# docsify-sidebar-generator
This repo consists of a basic bash script to auto-generate a _sidebar.md file for Docsify

## Heads up

* This script is made for Mac and Linux environments. If you want to use it on Windows, you will need to modify the script to fit the file structure/paths.

* Change the DOCSIFYDIR variable to point to your docsify installation

* Don't use spaces in filenames for your .md files

The current version of Docsify's sidebar doesn't work well when .md files have spaces in the file name.
For that reason, use underscores instead.

Bad example of file names:
My doc file.md

Good example of file names:
My_doc_file.md

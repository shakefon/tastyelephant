TastyElephant
=============

A utility to convert an HTML file generated by the Delicious export
functionality to an Evernote archive file, to enable the transfer of
your Delicious bookmarks to individual notes in an Evernote notebook.

1. Export bookmarks from Delicious to HTML file here:
   [http://export.delicious.com/settings/bookmarks/export](export.delicious.com)
2. Install TastyElephant (requires [http://nodejs.org](node.js) or
   [http://iojs.org](io.js) ):
   ```
   npm install -g tastyelephant
   ```
3. Run TastyElephant:
  ```
  tastyelephant -i /PATH/TO/DELICIOUS/HTML_FILE
  ```
4. Import generated `deliciousimport.enex` to Evernote by selecting it in the
   dialog that appears when you click `File > Import Notes...`

Usage: `tastyelephant -i <PATH_TO_DELICIOUS_HTML_FILE> [-o <PATH_TO_OUTPUT_DIRECTORY>]`

Options:                      
```
  -h, --help         Show help
  -i, --infile       Delicious HTML File to Import
  -o, --outputdir    Output Directory for Evernote enex File
```

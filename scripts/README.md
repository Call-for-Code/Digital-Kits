## Scripts for building kits

These scripts are designed to automate the building process for digital kits. Scripts are to be run from the root level of the repository and take a single argument, the kit download folder name (by convention this is all CAPS).

`create_pdfs COMMIT|PUSH|WHATEVER`  
This script goes through all markdown files in the `src/KITNAME` folder and creates updated pdf files as needed.

`build_kit COMMIT|PUSH|WHATEVER`  
This script takes the content in `src/KITNAME` and builds a new zip file for the kit, places the zip file into the download folder and copies any updated files into the download folder

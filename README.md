# npm-package-downloader
Script that downlaods all of the dependecies in all of thier version in package.json (nested)

The script contains inside of it a package.json object, it will download all of the dependensies (and thier dependesises, requesivly) in the packages.json object with all of thier avilable versions in the last couple of years. Follow the instructions of how to run the script, the downloaded packages will be found in the folder "create-react-app-deps" as .tgz files.

For the script to work you need the following:

1. execute npm install command before running the script.
2. open the script in notepad++ or any other editor and replace the package.json object( right now it is hardcoded).
3. you need to create an empty folder name "create-react-app-deps"
4. may god be with you, run the script.

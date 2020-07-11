# tracker-ui
UI:
To run the UI Server for the first time, create an empty file in /dist. The script in the package.json needs to remove all files in dist but won't work if there are no files in there.
- npm install
- mklink /J public\bootstrap node_modules\bootstrap\dist
- npm run dev-all
# Forikfy-updatedVersion
<h3>Local Installation </h3>
- git clone <repo url>
- npm init 
- npm i parcel -D or npm i parcel@2 -D 
- Remove "main" from package.json
- Do this in file package.json
  "scripts": {
    "start": "parcel index.html",
    "build": "parcel build index.html"
  },
- npm start 
> forkify@1.0.0 start
> parcel index.html

Server running at http://localhost:1234
✨ Built in 9ms
......

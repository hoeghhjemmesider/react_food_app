# react_todo


INSTALLATION

- Git clone this repo
- open terminal and run npm install
- opens in browser
- happy coding!


ERRORS
Error on 'react-native start' , "error Invalid regular expression: "

- Navigate to this folder: 
  C:\xampp\htdocs\[foldername]\node_modules\metro-config\src\defaults
- open the blacklist.js file and 'edit'
- Replace this line with:
  var sharedBlacklist = [
  /node_modules[\/\\]react[\/\\]dist[\/\\].*/,
  /website\/node_modules\/.*/,
  /heapCapture\/bundle\.js/,
  /.*\/__tests__\/.*/
];
- save file and run npm start again!

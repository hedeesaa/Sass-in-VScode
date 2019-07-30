# Sass-in-VScode

#1 install node-js 

#2 in VScode terminal type : `npm init`

#3 npm install `node-sass`

#4 replace the script in `package.json` with : 

    "scripts": {
    "sass": "node-sass -w scss/ -o dist/css --recursive"
  },
  
 #5 `npm node sass`

# Node.js
this is a read me file


use proxy for npm 
npm config set proxy http://www-3g.dienste.telekom.de:8080
npm config set https-proxy http://www-3g.dienste.telekom.de:8080

Install babel
npm install --global babel-cli
npm install --save-dev babel-preset-es2015

Create .babelrc in the root of the project
{
    "presets": ["es2015","stage-0"]
}
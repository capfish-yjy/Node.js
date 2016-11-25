# Node.js
this is a read me file


use proxy for npm
npm config set proxy http://www-3g.dienste.telekom.de:8080
npm config set https-proxy http://www-3g.dienste.telekom.de:8080

Create .babelrc in the root of the project
{
    "presets": ["es2015","stage-0"]
}

init
npm init


Install babel and modules
npm install --global babel-cli
npm install --save-dev babel-preset-es2015 babel-preset-stage-0
npm install babel-polyfill --save-dev
npm install request cheerio --save-dev



# 转码结果输出到标准输出
$ babel example.js

# 转码结果写入一个文件
# --out-file 或 -o 参数指定输出文件
$ babel example.js --out-file compiled.js
# 或者
$ babel example.js -o compiled.js

# 整个目录转码
# --out-dir 或 -d 参数指定输出目录
$ babel src --out-dir lib
# 或者
$ babel src -d lib

# -s 参数生成source map文件
$ babel src -d lib -s


for node4
{
    "presets": ["es2015-node4","stage-0"]
}
npm install --save-dev babel-preset-es2015-node4


babel example.js -o output.js 

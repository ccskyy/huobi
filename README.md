# 火币 Javascript SDK（非官方版)
这个项目的目的是提供一个JS环境的火币API接口

## 免责申明
本项目是出于个人兴趣爱好而开发制作，因为本项目涉及到货币交易，对使用者而言存在一定风险，因此在此特此申明，因为使用本项目而对使用者造成财产损失，本项目以及项目成员对此概不负责，一旦您使用本项目便代表您同意本免责申明，否则您无权使用本项目

## 安装方法
```
npm install --save huobi
```

## 使用指南
```Javascript
const Huobi = require('huobi')

let huobi = new Huobi({serectKey:'Your Serect Key', accessKey:'Your Access Key'})

huobi.getAccountInfo()
.then(data => console.log(data))
.catch(err => console.log(err))

...
```

## API指南

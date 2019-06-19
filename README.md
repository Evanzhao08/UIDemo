


## 技术栈

react+react-router+redux+ webpack + ES6 + fetch+antd

## 项目结构

```
│  .babelrc
│  .editorconfig
│  .eslintrc
│  .gitignore
│  .yo-rc.json
│  karma.conf.js
│  package.json
│  prod.server.js
│  server.js
│  shop.json
│  tree.txt
│  webpack.config.js
│  
├─cfg
│      base.js
│      defaults.js
│      dev.js
│      dist.js
│      test.js
│      
├─dist
│          
├─src
│  │  favicon.ico
│  │  index.html
│  │  index.js
│  │  routes.js
│  │  
│  ├─actions
│  │      index.js
│  │      README.md
│  │      
│  ├─api
│  │      shop.json
│  │      
│  ├─components
│  │      Destination.js
│  │      Detail.js
│  │      Index.js
│  │      Main.js
│  │      Plan.js
│  │      
│  ├─config
│  │      base.js
│  │      dev.js
│  │      dist.js
│  │      README.md
│  │      test.js
│  │      
│  ├─constants
│  │      ActionTypes.js
│  │      
│  ├─images
│  │      
│  ├─reducers
│  │      cart.js
│  │      count.js
│  │      history.js
│  │      index.js
│  │      
│  ├─sources
│  │      
│  ├─stores
│  │      
│  └─styles
│          App.css
│          
└─test
            
```

## 目标功能

- [x] 商品浏览页面 -- 完成
- [x] 商品详细页面-- 完成
- [x] 购物车页面-- 完成
- [x] 历史记录页面 -- 完成

## 项目运行
**注意：由于涉及大量的 ES6 等新属性，nodejs 必须是 6.0 以上版本 。**


cd react-shopping

npm install

npm run start //运行

npm run dist //打包
```
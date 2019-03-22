# bysj

> bysj

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

## 项目搭建步骤

vue init webpack bysj
cnpn i
npm install echarts --save
npm install axios --save
npm install node-sass -D
npm install sass-loader -D
npm i element-ui -S

### 部分库的引入

const echarts = require("echarts/lib/echarts") --- 组件中
require("echarts/lib/chart/line")

const echarts = require("echarts/lib/echarts") --- echarts配置中引入
require("echarts/lib/component/tooltip")
require("echarts/lib/component/title")
require("echarts/lib/component/legend")
require("echarts/lib/component/dataZoom")
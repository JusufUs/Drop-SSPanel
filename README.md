### 仅可以对接 SSPanel v2b 不支持

### 如何使用？

> 开发环境你需要修改的
> src/public/assets/js/node.js 9行和11行根据环境进行注释
> 该问题是我开发时未想到的，可以解决但是我懒

> 你需要修改 src/public/config/index.js
>
> baseURL: 你的面板地址，如 https://www.qq.com
>
> selector:  Clash 规则名称 如 <🔰国外流量> < 其他流量> 等不限，别设置 <自动选择>

### 如何跑起来

我这里使用 yarn

> 1. 进入目录
> 2. yarn install
> 3. yarn start

### 如何编译

> yarn dist

# didi-reimbursement
滴滴出行行程报销单  => 打车报销单

每次手动操作都要花费十几分钟，甚至还有可能出错...

现在,麻麻再也不用担心我填错打车报销单了。

## 示例
![avatar](https://jingguangyan.github.io/example-images/didi-examlpe.png)

## 快速开始
### 环境
安装 node.js, 版本大于8.0，建议下载 Latest release [去下载](http://nodejs.cn/download/)

### 安装依赖
```bash
$ npm i
```

### 配置
1.config.js
``` javascript
module.exports = {
  name: '张三',              // 姓名
  username: '',             // mis账号
  password: '',             // 密码
  autoTime: true,           // true: 自动获取上个月的加班申请; false: 使用startTime和endTime
  startTime: '2019-12-01',  // 启示日期， autoTime为true时不生效
  endTime: '2019-12-31'     // 结束日期， endTime 为true时不生效
}
```

2.将 "滴滴出行行程报销单.pdf" 放至项目根目录

### 运行

```bash
$ npm run start
```





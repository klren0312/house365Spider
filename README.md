# 治电爬虫程序

#### 功能

 - 夜间模式
 - 创建/修改应用
 - 导入/导出应用
 - 数据采集
 - 数据发布 (MySQL), 可导出Excel, JSON文件
 - 本地应用上传, 远程应用获取
 - 客户端与服务端通信
 - 新增代码应用

#### 代码应用相关调用类库和方法
```javascript
{ name: 'reqest', info: 'HTTP请求库' },
{ name: 'request-promise', info: '基于Promise的HTTP请求库' },
{ name: 'cheerio', info: 'HTML解析库' },
{ name: 'cheerio-tableparser', info: 'HTML表格解析库' },
{ name: 'mysql2', info: 'MySQL操作库' }
{ name: 'dataDb', info: '操作本地JSON数据存储, 用于本地存储数据' }
```

#### 开发与打包

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:9080
npm run dev

# build electron application for production
npm run build


# lint all JS/Vue component files in `src/`
npm run lint

```

#### 运行截图
![](./imgs/1.jpg)
![](./imgs/7.jpg)
![](./imgs/2.jpg)
![](./imgs/3.jpg)
![](./imgs/4.jpg)
![](./imgs/5.jpg)
![](./imgs/6.jpg)
![](./imgs/8.jpg)

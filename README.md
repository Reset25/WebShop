#
`


##### 服务器端

全局安装`nodemon`

 `cd web-server`

将`web-server`文件夹下的`webshop.sql`导入`MySQL`数据库中
`npm install` 安装依赖
修改`web-server/src/config.js`文件，，根据数据库信息修改它们的值
 `npm run dev` 在本地运行，启动服务器

##### 客户端

- `cd web-client`
- `mkdir static` 新建static文件夹
- `npm install` 安装依赖
- `npm run dev` 在本地运行
- 接着在`http://localhost:8080`下访问

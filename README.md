# forum_ui
### pm2部署 `https://nuxtjs.org/deployments/pm2/`
1. 项目配置
   - `package.json` 配置服务端口
   - 创建`ecosystem.config.js`配置文件
2. 项目打包 
   - `npm run build`
   - `npm run start`
3. 安装 `node.js 16.14.0`
4. `npm install -g pm2`
5. 创建`forum_ui`文件夹，复制资源文件到目录下
   - `.nuxt`
   - `node_modules`
   - `static`
   - `ecosystem.config.js`
   - `package.js`
6. 服务维护
   - `pm2 start`
   - `pm2 ls`
   - `pm2 log`
   - `pm2 stop forum_ui`

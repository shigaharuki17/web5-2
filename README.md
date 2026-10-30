# Quiz 构建文件

根目录是独立静态演示版，对应源码项目的 `dist-demo`，保持现有 Vercel 页面可用，数据仅保存在当前浏览器。

`fullstack/` 是默认 `npm run build` 生成的真实后端联动前端（`dist`）。请与源码仓库 `web5-1` 的 Java 后端一起运行；Maven 会将此版本打进 JAR，由本机 8080 服务提供页面和 API。

Java 后端与 MySQL 数据库不能由静态文件托管服务直接运行。数据库版请在本机启动 Java 后端后访问 http://127.0.0.1:8080/ 。

源码与启动说明：https://github.com/shigaharuki17/web5-1/tree/main/backend

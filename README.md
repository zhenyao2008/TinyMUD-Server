# TinyMUD
C#实现的高性能纯异步服务器，类似Node.js，业务逻辑写在主线程

- Core 服务器核心库，服务器的基础实现
    - Network 网络基础实现
    - System 其他各类接口，如服务启动、时间、控制台、日志和线程循环
- Startup 服务器启动程序，用于启动服务器业务逻辑DLL(目前还未完善)
- Extension 服务器扩展功能
    - Log 常用日志扩展
- Sample 简单的业务逻辑用例，展示接口的使用方式
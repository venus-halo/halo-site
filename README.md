命令行使用
docsite集成的主要命令只有三个，主要如下：

docsite init
在项目根目录下执行该命令，会在目录下初始化一个站点开发模板并安装好相关依赖。

docsite start
执行该命令，会在本地启动一个开发服务器，默认端口号为8080（可在site_config/site.js中的port字段进行更改）。同时会在浏览器中自动打开该页面。在开发过程中，修改源代码包括markdown文档时，会自动进行编译，刷新浏览器即可看到更新后的结果。

docsite build
待本地开发完成后，运行该命令，将对源码和markdown文档进行编译和构建，生成构建后的文件。

其他
执行docsite -h获取更多命令的使用。
# gitbook
> Personal notes based on typroa + GitHub + gitbook

+ [线上网址](http://47.101.133.103:4000/)

+ 发现一个比较好的构建笔记的工具gitbook，由于gitbook官网要科学上网，所以使用typroa在本地编辑，上传到github，然后linux上拉取项目渲染。

+ 缺点：每次更新都要提交、拉取、编译，后期尝试用jekins持续集成。

+ 常用命令

  ```shell
  git clone
  git add .
  git commit -m ""
  git push origin
  
  gitbook init #初始化
  gitbook install #下载插件
  setsid gitbook serve #启动服务 默认4000端口
  ```

  


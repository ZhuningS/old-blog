<h2 align="center">法术部落</h2>

此博客原作者博文地址： [http://www.jeffjade.com](http://www.jeffjade.com)

个人博客地址: [http://szhang.github.io](http://szhang.github.io)

### Fork说明
站在前辈的肩膀上搭建此Blog，Jekyll框架直接fork的[晚晴幽草轩,天意人间舫](http://www.jeffjade.com/2016/01/22/2016-01-22-jeffjade-and-nicejade/)的代码框架,项目地址是[nicejade.github.io](https://github.com/nicejade/nicejade.github.io)，感谢Github的Fork功能和开放自由性让搭建个人Blog不再是技术问题，同样感谢所有搭建Blog过程中直接和间接受惠的前辈们。

### 安装说明

1. fork库到自己的github
2. 修改名字为：`username.github.io`
3. clone库到本地，参考`_posts`中的目录结构自己创建适合自己的文章目录结构
4. 修改CNAME，或者删掉这个文件，使用默认域名
5. 修改`_config.yml`配置项
6. It's done!

### 分支说明

- 三栏布局（master分支，基于[3-Jekyll](https://github.com/P233/3-Jekyll)）
- 三栏布局 (bootstrap-based分支，基于Bootstrap)
- 单栏布局（first-ui分支，基于Bootstrap）

>**微注：** 对 `.scss` 文件的转化，只需执行： `sass --watch _sass\style.scss:css\style.css --trace`,当然，这需要注意下相对路径；具体可参见[SASS用法指南](http://www.ruanyifeng.com/blog/2012/06/sass.html),如是生产环境，执行 `　sass --style compressed .\_sass\style.scss .\css\style.css` 命令即可。

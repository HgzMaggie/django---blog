#基于Django实现的个人项目关于博客：

技术栈：
Django 2.x
mysql
html+css+js/jquery
bootstrap4
第三方库（用了别人的轮子，有时候可以更快地开发）

开发环境：
Pycharm2019.1
Navicat Premium 12
实现了博客的基本功能：
几大模块：用户模块，评论模块，文章模块，信息模块
用户模块：正常的注册和登录，完善用户信息，可以上传图片作为头像，可以编辑修改；
          在管理后台，超级管理员可以区别普通用户和管理员，并可以给与不同的权限。
          
评论模块：用来富文本评论，可以有多级评论，回复的时候，信息模块也可以通过通知来通知，支持表情和代码块等等的评论。

文章模块：通过模型创建，可以在mysql上存取数据，在后台可以实现增添标签和栏目，通过标签和栏目可以方便搜索快速在到相关的文章；
         在前台，用户在创建文章的时候，同样可以进行文章的编辑，实现增添标签和栏目，只可以编辑用户自己创建的文章，其他人的文章
         并不可以更改。超级管理员的授权的用户可以获得相应的权限。

信息模块：主要管理前后要的信息的正常，主要用来概况上下文。

小功能合集：回到顶部浮动按钮、矢量图标、页脚沉底和粘性侧边栏
..


（ps:基本功能完成，后期会更新，优化代码，同时完成nginx部署）

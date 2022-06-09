# uniapp-vantUI

#### 介绍
初始化uni-app项目使用vant ui简易教程


#### 安装教程
1.新建一个uniapp项目
2.安装vantUI库
npm init //初始化
npm i vant-weapp -S --production
3.新建wxcomponents文件夹（和pages平级）,将node_modules下的vant-weapp下的dist复制到wxcomponents下，改名为vant
4.在App.vue中引入样式文件  @import "/wxcomponents/vant/common/index.wxss";
5.pages.json中使用组件（只展示了两种 button 和 toast）ps：只使用了全局引入，根据自己情况改变
![](README_files/1.jpg)
6.组件具体使用方法在pages/index/index中使用

#### 特技

1.  使用 Readme\_XXX.md 来支持不同的语言，例如 Readme\_en.md, Readme\_zh.md
2.  Gitee 官方博客 [blog.gitee.com](https://blog.gitee.com)
3.  你可以 [https://gitee.com/explore](https://gitee.com/explore) 这个地址来了解 Gitee 上的优秀开源项目
4.  [GVP](https://gitee.com/gvp) 全称是 Gitee 最有价值开源项目，是综合评定出的优秀开源项目
5.  Gitee 官方提供的使用手册 [https://gitee.com/help](https://gitee.com/help)
6.  Gitee 封面人物是一档用来展示 Gitee 会员风采的栏目 [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)

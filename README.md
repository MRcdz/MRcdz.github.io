<h1 align="center">整理的资料</h1>

## 0、Git操作

> **本地操作：**

```js
1、git add xxx.js 

2、git status  -看状态（可有可无）

3、git commit -m “xxxx描述提交信息”

4、git status   -看状态
```



> **提交远程：**

1、git push 

先配置 git：

git config --global  user.name "MRcdz"

git config --global  user.email "2463066771@qq.com"

git remote set-url origin https://<your_token>@github.com/<USERNAME>/<REPO>.git 

git config --list 查看 git 下面的 remote 配置信息。

注意：以前的 git 通过 user.name 和 password 方式已更改为 token 方式，需要在 github 个人主页上的

Settings -> DevelopSettings ->  Personal access tokens 生成一个 tokens 需要记住，刷新页面后消失了。

token 可以设置时效，权限等等，需第一时间复制下来。

最后  git push

2、GitHub_token : 

**限时token: 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**
MRcdz、2463066771@qq.com

3、git rm test.txt (删除文件) 、git rm -r test (删除文件夹)  => git commit -m "删除操作"  => git push 推送提交

4、重命名文件：git mv test.txt test1.txt /  文件夹 ：git mv -v test test1  => 然后 git add -u '新文件名'   git commit  -m ‘’ git push 即可

5、**git pull** 命令用于从远程获取代码并合并本地的版本 master 分支

```bash
git pull origin master
```

6、新建分支：git branch test  ，推送分支：git push origin test，分支推送：git push --set-upstream origin test

​	 删除本地分支：git branch  -d test  ，删除远程分支：git push origin -d new_a

​	 远程分支拉到本地：1、git fetch origin dev（dev即分支名）2、创建并切换分支：git checkout -b LocalDev origin/dev  （LocalDev 为本地分支名，dev为远程分支名）3、git pull origin dev（dev为远程分支名）

​	 更新远程分支： git push origin HEAD:test（test为远程分支名）

7、查看远程所有分支：git branch -a 远程分支会用红色表示出来 git branch 本地分支

> **Github 快速搭建个人网站：**

1、新建 repo 仓库，必须 MRcdz.github.io 为仓库名字，MRcdz 为你的账户名

2、然后在 该仓库中，添加 index.html 文件

3、直接访问 https:MRcdz.github.io 即可看见内容。

> **Github 操作仓库完整流程：**

1、新建文件夹，并 git init 初始化

2、git clone <code 下https://......git> 克隆到本地

3、cd 仓库

4、git remote set-url origin https://<your_token>@github/MRcdz/....git. 配置

5、创建，修改仓库中的文件，git add ，git commit -m 登操作

6、git push ，推送至默认master分支，更新

7、GitHub端更新，git pull （origin master）master 分支括号可省略，git pull 可以拉去最新远程仓库文件。 

## 1、技术文档

Boostrap5 CSS框架：

https://v5.bootcss.com/docs/getting-started/introduction/

Tailwind CSS框架:

https://www.tailwindcss.cn/docs

ECharts可视化图表库：

https://echarts.apache.org/handbook/zh/get-started/

Swipper滑动插件：

https://www.swiper.com.cn/api/index.html

BetterScroll滚动插件：

https://better-scroll.github.io/docs/zh-CN/guide/

Element Plus 基于vue3:

https://element-plus.gitee.io/zh-CN/component/layout.html

ElementUI 基于vue2：

https://element.eleme.cn/#/zh-CN/component/installation

Mint移动端框架：

https://mint-ui.github.io/docs/#/zh-cn2

Axios文档：

https://www.kancloud.cn/yunye/axios/234845

Animate.css动画库：

https://animate.style/

Velocity.js动画库：

http://velocityjs.org/

Express后段框架：

https://www.expressjs.com.cn/

ArtTemplate模版引擎：

http://aui.github.io/art-template/zh-cn/docs/syntax.html

Pug模版引擎：

https://www.pugjs.cn/api/getting-started.html

Vite构建工具:

https://vitejs.cn/guide/

Vue3:

https://v3.cn.vuejs.org/guide/introduction.html#vue-js-%E6%98%AF%E4%BB%80%E4%B9%88

Vue2:

https://cn.vuejs.org/v2/guide/

Babel编译器：

https://www.babeljs.cn/docs/

TypeScript类型系统:

https://typescript.bootcss.com/

Nuxt框架SSR:

 https://www.nuxtjs.cn/guide/installation

webpack:

https://webpack.docschina.org/concepts/

docsify文档生成利器:

https://docsify.js.org/#/zh-cn/quickstart

Discuz! Q 拥有完全开源、提供丰富接口、前后端分离、轻量化、数据独立可控、敏捷上云、快速变现七大能力:

https://discuz.com/docs/

Ant Design 框架（vue、react.....)：

https://ant.design/index-cn

Cube UI（基于vue移动组件库）：

Egg 一款Node框架：

https://www.eggjs.org/zh-CN

Koa框架后段框架：

https://koa.bootcss.com/#

## 2、资源

前段知识：

http://iwenwiki.com/webdoc/guide/

阿里图标：

https://www.iconfont.cn/

腾讯云开发手册：

https://cloud.tencent.com/developer/devdocs

后盾人学习：

https://doc.houdunren.com/

Bootstrap模版：

https://sc.chinaz.com/tag_moban/bootstrap.html

各种模版之家：

http://www.cssmoban.com/

站长素材：

https://aspx.sc.chinaz.com/query.aspx?keyword=bootstrap5&classID=12

谷歌商店：

https://www.gugeapps.net/


## 3、项目

高仿知乎 ：

http://docs.vikingship.xyz/

高仿网易云：

http://iwenwiki.com/NeteaseCloudMusicApi/


## 4、Api

（免费访问不限次数）
一个关于猫的接口：
https://docs.thecatapi.com/

一个关于狗的接口：
https://dog.ceo/dog-api/

个人的接口:
http://iwenwiki.com/api/

网易云搜索歌名接口（keywords=''）：
http://iwenwiki.com:3000/search?keywords=%E6%B5%B7%E9%98%94%E5%A4%A9%E7%A9%BA

网易云各种接口：
http://iwenwiki.com:3000/

（每日免费访问100次）
疫情详细数据：
http://iwenwiki.com/wapicovid19/ncov.php?key=62e34ad34025d5d5127135efa58d4ca8

全国各个城市疫情数据：
http://iwenwiki.com/wapicovid19/all.php

国外疫情数据：
http://iwenwiki.com/wapicovid19/foreign.php

****国内省市详情**：**
http://iwenwiki.com/wapicovid19/guonei.php?city=%E5%86%85%E8%92%99%E5%8F%A4

****疫情曲线图**：**
http://iwenwiki.com/wapicovid19/ncovimg.php

****城市列表清单**：**
http://iwenwiki.com/wapicovid19/citys.php?key=171e165a7d991c5f6ecd5194c54778ef

出行防疫政策：
http://iwenwiki.com/wapicovid19/query.php?from=10003&to=10004&key=171e165a7d991c5f6ecd5194c54778ef

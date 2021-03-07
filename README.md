# 程序媛汇介绍

程序媛汇 Coding Girls Club (CGC)诞生于 2016 年 6 月 1 日，是一家为女性数字化赋能为己任的社会企业。CGC 通过编程科普、启蒙工作坊、职业培训等线上线下结合的形式，鼓励更多女性体验编程并进入 STEM 领域。至今，CGC 已在全国 10 个城市举办了超过 20 场编程城市活动，并联合全国 17 所高校举办“一日编程”活动，累计参与的学员近 4000 人，得到了来自中国日报、环球时报、CCTV 等媒体的报道关注。2018 年，CGC 入选由联合国开发计划署发起的“科技与慈善”项目案例集，2019 年成为共青团中央"全国青年社会组织「伙伴计划」"获奖项目。CGC 聚集着一群正直、善良且富有才华的小伙伴，致力建构互联互助的信息学习平台，为女性和女性自我提升数字化赋能，我们相信数字赋能女性，多元改变世界。
官网：http://codingirlsclub.com/about

## [点击这里预览网站效果](https://codinggirlsclub.github.io/Girls-Coding-Day-Jekyll-blog-2)

## 搭建网站

### 第一步：注册 GitHub

请点击这里[注册 GitHub](https://github.com/join?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home), 注册成功之后，登录 GitHub。

如果你已经有 GitHub 账户，请跳过这一步！

### 第二步：Use this template

登录到 GitHub 之后，点击这里进入仓库 [girls-coding-day](https://github.com/CodingGirlsClub/Girls-Coding-Day-Jekyll-blog-2)，点击右上角的 `Use this template` 按钮。  
![2021-03-07-qdaVeD-1](https://cdn.jsdelivr.net/gh/sddtc/upic-cloud@main/images/2021/2021-03-07-qdaVeD-1.png)   

之后进入到新页面  
![2021-03-07-g1qfDd-2](https://cdn.jsdelivr.net/gh/sddtc/upic-cloud@main/images/2021/2021-03-07-g1qfDd-2.png)  

填写相应的信息，并点击 `Create repositorye from template` 按钮    
![2021-03-07-u9fidt-3](https://cdn.jsdelivr.net/gh/sddtc/upic-cloud@main/images/2021/2021-03-07-u9fidt-3.png)

最终效果如下:  
![2021-03-07-Pwp7I3-ScreenShot2021-03-07at11.28.38AM](https://cdn.jsdelivr.net/gh/sddtc/upic-cloud@main/images/2021/2021-03-07-Pwp7I3-Screen Shot 2021-03-07 at 11.28.38 AM.png)  

### 第三步：搭建 GitHub Pages

首先进入此仓库 Settings 页面：  
![2021-03-07-dRO2gD-5](https://cdn.jsdelivr.net/gh/sddtc/upic-cloud@main/images/2021/2021-03-07-dRO2gD-5.png)  

找到 GitHub Pages 设置区域, 点击 `Source` 下面的下拉框，选择 `main` 分支之后，点击 `Save` 按钮:  
![2021-03-07-XkwQNp-7](https://cdn.jsdelivr.net/gh/sddtc/upic-cloud@main/images/2021/2021-03-07-XkwQNp-7.png)

稍后在配置完毕之后, 点击链接就可以访问你的 GitHub Page 静态网站啦！

可能由于 `GitHub Pages` 需要生成页面等操作, 有延迟和缓存的问题，你可以等一会儿访问:  
在编译并部署网站:  
![2021-03-07-GN5iWF-8](https://cdn.jsdelivr.net/gh/sddtc/upic-cloud@main/images/2021/2021-03-07-GN5iWF-8.png)  
编译成功可以访问网站:  
![2021-03-07-drbrAh-9](https://cdn.jsdelivr.net/gh/sddtc/upic-cloud@main/images/2021/2021-03-07-drbrAh-9.png)
  
## 编辑你的静态页面

### 第一步：修改网站的主题和标题

你可以在 [`_config.yml`](_config.yml) 文件中修改网站主题和副标题等一些信息。  

![2021-03-07-BHupX4-geQAL7](https://cdn.jsdelivr.net/gh/sddtc/upic-cloud@main/images/2021/2021-03-07-BHupX4-geQAL7.png)

> **注意⚠️**
> 1. `_config.yml` 文件中使用的都是英文标点，请不要使用中文标点；
> 2. 冒号后面有一个空格；
> 请严格遵守上述要求，否则网站配置会不成功，导致无法访问；

1. 修改 `baseurl`. `baseurl` 是 "/" + 仓库的名字. 是资源文件的路径组成部分  
将 `baseurl: /Girls-Coding-Day-Jekyll-blog-2` 修改为 `baseurl: 你的仓库名字`  
找到仓库名字：    
![2021-03-07-7GHTvd-10](https://cdn.jsdelivr.net/gh/sddtc/upic-cloud@main/images/2021/2021-03-07-7GHTvd-10.png)
修改值:  
`baseurl: my-first-blog`

2. 修改个人信息

```yml
title: "Sddtc's web"
name: "Sddtc"
description: "子标题"
paginate: 9
```

找到该文件，点击进入，文件的右上角有一个铅笔字样的编辑按钮，点击编辑按钮可以进行编辑。编辑完成后，点击下方的 `Commit Change` 按钮保存文件。文件保存之后，等几分钟刷新你网站的页面，你就可以看到效果啦！  
![2021-03-07-O3itCS-11](https://cdn.jsdelivr.net/gh/sddtc/upic-cloud@main/images/2021/2021-03-07-O3itCS-11.png)

### 第二步：创建博客

点击进入 `_posts` 文件夹下面，点击右上角的 `Add File` 按钮，选择 `Create new file` 之后进入编辑页面。

在编辑页面输入文件名称，名称符合如下格式：

- 文件名必须以日期开头，如 `2020-10-11`
- 文件名必须使用英文命名，多个单词之间用中划线 `-` 连接
- 日期与英文之间用 `-` 中划线连接
- 文件名必须以 `.md` 结尾

在 `Edit new file` 文件空白区域输入 `Markdown` 语法, 书写自己的故事，当然你可以通过 `Preview `按钮边书写故事边预览效果！


### 第三步：给博客添加属性

在你创建的博客的最上端，添加如下的内容，为你的博客添加头图，名称，作者等属性。

```yml
---
layout: post
title:  "记一次环球影城旅程！"
image: assets/images/5.jpg
---
```

将你准备好的图片放到 `assets/images` 文件夹下面，更新 `image` 为 `assets/images/图片名称`。

### 第四步：发表自己的博客

点击最下面的 `Commit new file` 按钮，提交该文件，进入网站首页，找到自己添加的图片，点击图片查看自己的博客。

到这里，相信你已经有了自己的网站，同时发表了自己的博客哦！
###Sharplife 2.0 大放异彩 [旧版本](https://github.com/enirehtac/sharplife)

####Beautiful stuff for Farbox, [Donate](https://me.alipay.com/chricy) may be good:)...

####使用(懒得用 interface.json 了)

git clone 或者直接下载后放在你的 template 目录下即可

需要修改 include/header.html 里的 个人社交网络信息

以及 include/comments.html 里的 disqus shortname，也可全部改为其他评论系统的代码

添加统计代码可在 include/footer.html 添加，或到 domain.com/admin 后台添加

####添加一个页面(只是举个栗子)

网站根目录下新建个 sample.md
内容为
```html
title: Sample Page
url: sample.md

<h1 style="text-align:center">Try it out</h1>
<p style="text-align:center">WOW! it's amazing!</p>
```

然后即可通过 domain.com/sample.md 访问，新建 about.md 不用修改 nav，会自动显示。

想在菜单显示修改 include/nav.html 即可

P.S. 页面请尽量用 html 书写避免错误。

**WTFPL License**


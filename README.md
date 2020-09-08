[![hugo](https://img.shields.io/badge/powered%20by-hugo-orange)](https://gohugo.io/)
[![GitHub Workflow Status](https://img.shields.io/github/workflow/status/ouuan/hugo-blog/Deploy)](https://github.com/ouuan/hugo-blog/actions)
[![Website](https://img.shields.io/website?url=https%3A%2F%2Fouuan.github.io)](https://ouuan.github.io)

这里是 ouuan 的博客的源码，访问地址：<https://ouuan.github.io>

旧版 hexo 博客：<https://github.com/ouuan/ouuan.github.io/tree/hexo-archive>

LICENSE
---

All components in the `content` folder, `static/post_doc` folder, `static/post_img` folder are distributed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/), other components except for third party submodules are distributed under [MIT License](LICENSE).

---

添加到PATH

```
set PATH=%PATH%;C:\hugo\
```

 Linux路径`/usr/bin/hugo`


```
cd
git clone https://github.com/ouuan/hugo-blog.git blog
git clone https://github.com/ouuan/hugo-theme-even.git blog/themes/even
git clone https://github.com/martignoni/hugo-video.git blog/themes/hugo-video
cd blog/themes/even
git checkout 709f99f
cd -
cd blog/themes/hugo-video
git checkout 2f7fc12
cd
rm -rf -blog/themes/even/.git
rm -rf -blog/themes/hugo-video/.git
rm -rf -blog/.git
```

初使化`.git`

```
cd blog
git init
git add .
git commit -m "test"
```

生成public

```
hugo
```

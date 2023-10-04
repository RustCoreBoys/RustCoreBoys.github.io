[Hux Blog](https://huangxuan.me)
================================

> I never expect this becomes popular.

![](http://huangxuan.me/img/blog-desktop.jpg)


[User Manual 👉](_doc/Manual.md)
--------------------------------------------------

### Getting Started

1. 你需要安装 [Ruby](https://www.ruby-lang.org/en/) and [Bundler](https://bundler.io/) 来使用[Jekyll](https://jekyllrb.com/). 按照 [Using Jekyll with Bundler](https://jekyllrb.com/tutorials/using-jekyll-with-bundler/) 这个文档来搭建环境 to fullfill the enviromental requirement.

2. 安装 `Gemfile`中的依赖:

```sh
$ bundle install 
```

3. 本地调试 (默认位于`localhost:4000` ):

```sh
$ bundle exec jekyll serve
```
4. 生成一篇博文
```sh
rake post title="Hello 2023" author="HuangXu" subtitle="Hello World, Hello Blog"

```
参数解释: title是本文主标题，subtitle是本文副标题，author是作者










# 项目规划

为了让项目有更好**可读性、可维护性、可扩展性**,对项目做以下规划:

## 文件方面:

1. 前后端分离或者部分分离(这个具体讨论决定);
2. 目录结构清晰,便于**维护和扩展**;
3. 项目整体采用`gulp`工具构建,可以生成两个版本,具体查看项目目录结构.

## code方面

`js`模块化采用`Commonjs`规范,初步在`requirejs`(AMD框架),`seajs`(CMD框架),`browserify`(Commonjs规范工具)中选定`browserify`.
相关文档:
- [关于 CommonJS AMD CMD UMD](http://my.oschina.net/felumanman/blog/263330?p=1);
- [seajs和requirejs区别](http://www.douban.com/note/283566440/);
- [Browserify Document](https://github.com/substack/node-browserify#usage);
- [Browserify gulp](http://www.tuicool.com/articles/AVzyMn6).

2. `css`初步决定采用`less`,相对于传统的`css`,`less`具有更好的可维护性和扩展性以及`css`"模块化"的编程,更利于团队合作,有助于更快地输出同一个模板不同样式的`css`(针对卖家店铺模板选择这块,以及以后过节等整体换肤等).相对于`sass`而言,`less`的学习成本更低.
相关文档:
- [less css 框架中文](http://www.ibm.com/developerworks/cn/web/1207_zhaoch_lesscss/);
- [less 快速入门](http://less.bootcss.com/);
- [less gulp](http://www.dtao.org/archives/34).


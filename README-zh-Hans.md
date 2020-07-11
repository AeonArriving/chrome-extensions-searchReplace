<h1 align="center">一款搜索并且替换文本的谷歌插件</h1>
<div align="center">

[简体中文](https://github.com/Summer-andy/chrome-extensions-searchReplace/blob/master/README.md) &#124; English

</div>



## 介绍

`chrome-extensions-searchReplace` 是一款搜索并且替换文本的谷歌插件。


🎉![image](https://github.com/Summer-andy/chrome-extensions-searchReplace/blob/master/demo.gif)


## 为什么会有这个项目？

在做产品ppt的时候,需要对某些个页面中的一些名词进行统一替换。在谷歌拓展商店也查找了一些插件,比如下载量高一点的两个插件: 1. Find & Replace for Text Editing 2.FindR。但是这两个插件都有问题, 第一个插件替换完文本后, 所有的按钮超链接都无法点击。第二个插件完全替换不了, 貌似也不维护了。因此我决定自己开发一个插件来完成这个任务。


## 如何使用？
> 由于本人暂时没有谷歌上架所需的信用卡,因此在谷歌插件商店查找不到此插件。只能用以下方式使用插件。

- 第一步: git clone https://github.com/Summer-andy/chrome-extensions-searchReplace
- 第二步: 在谷歌浏览器输入 ``` chrome://extensions/ ```, 进入插件管理,打开开发者模式。
- 第三步: 点击加载已解压的程序按钮, 选择chrome-extensions-searchReplace目录即可。

## 待做事项
- [X] 完成文本替换
- [x] 优化替换方式
- [ ] 替换模板后, 执行script脚本
- [ ] 优化交互体验


## 🤝 提交规范

- perf: 优化相关，比如提升性能、体验
- feat: 新功能(feature)
- fix: 修补 bug
- docs: 文档(documentation)
- style: 格式(不影响代码运行的变动)
- refactor: 重构(即不是新增功能，也不是修改 bug 的代码变动)
- test: 增加测试
- chore: 构建过程或辅助工具的变动
- upgrade: 第三方库升级
- revert: 回滚
- scope: commit 影响的范围, 比如: route, component, utils, build...
- merge: Merge branch ? of ?.

## ❤️ 分支管理

- 模块功能开发(feature/xxx)
- Bug 修改(bug/xxx)
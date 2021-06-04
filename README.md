# 简介

> 这只是一个简单的学习Demo
>
> 记录自己学习的一些工程化相关的项目文件

## v.1.0.0 

> 关于对 conventional-changelog 生态的学习

**目标**

+ 规范提交 git 指令
+ 使用git log 生成项目的changelog


## 项目本地构建
```shell
npm i | npm install
```
**npm WARN lifecycle engineering@1.0.0~prepare: cannot run in wd 错误请使用下列命令**

```shell
npm install --unsafe-perm
```


## commitlint verify commit message

**提交的message构成**

```shell
<type>(<scope>): <subject>
```

**type 为必填项，用于指定 commit 的类型。**
+ build : 更改构建系统和外部依赖项（如将 gulp 改为 webpack，更新某个 npm 包）
+ ci : 对 CI 配置文件和脚本的更改
+ docs : 仅仅修改文档说明
+ feat : 增加一个新特性
+ fix : 修复一个 bug
+ perf : 更改代码以提高性能
+ refactor : 代码重构时使用
+ style : 不影响代码含义的改动，例如去掉空格、改变缩进、增删分号
+ test : 增加新的测试功能或更改原有的测试模块

+ test : 提交功能

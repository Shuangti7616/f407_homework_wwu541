# STM32F407 Homework

看LOG.md了解每次完成的任务与任务截图。
本仓库是基于 STM32F407IGH6 (C板) 和 STM32F407VGT6 (最小系统板) 的作业仓库。

## Usage

克隆来源：

```bash
git clone https://github.com/HKUSTGZ-ROBOMASTER-PNX/stm32f407_hw_template.git
```


##操作备注

基础的操作包括以下几个：

```bash
git remote add upstream [your repository url]
```

设置项目的上游仓库，如果你是现在本地创建的文件夹希望同步到你的仓库

```bash
git add .
```

在每一次添加新内容之后，都需要执行这个命令让git了解你的更改

```bash
git commit -m "[init/feat/chore/fix/refactor]:[conclusion of change]"
```

添加完内容之后，需要对本次提交添加描述，描述请严格按照上面的格式进行，可以分为

- init: 初始化本仓库，用于第一次提交
- feat: 为仓库添加新功能
- fix: 修复了仓库的某些bug
- chore: 进行一些与主题代码无关的改动
- refactor: 对代码架构进行重构

后面接着对当前修改的简要描述。

```bash
git push origin
```

将修改推送到远端。
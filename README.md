# gemoji 记录些有趣github emoji

### 目录

+ [commit 格式](#commit-格式)
+ [emoji 指南](#emoji指南)
+ [如何在命令行中显示emoji](如何在命令行中显示emoji)
+ [参考](参考)

### commit 格式

`git commit` 时，提交信息遵循以下格式：

```sh
:emoji1: :emoji2: 不超过 50 个字的摘要，首字母大写，使用祈使语气，句末不要加句号

提交信息主体

引用相关 issue 或 PR 编号 <#110>
```

提交示例：

```sh
git commit -m ":tada: Initialize Repo"
```

### emoji 指南

emoji                                   | emoji 代码                   | commit 说明
:--------                               | :--------                    | :--------
:tada: (庆祝)                           | `:tada:`                     | 初次提交
:sparkles: (火花)<br>:new: (全新)       | `:sparkles:`<br>`:new:`       | 引入新功能
:bookmark: (书签)                       | `:bookmark:`                 | 发行/版本标签
:bug: (bug)                             | `:bug:`                      | 修复 bug
:ambulance: (急救车)                    | `:ambulance:`                | 重要补丁
:globe_with_meridians: (地球)           | `:globe_with_meridians:`     | 国际化与本地化
:lipstick: (口红)                       | `:lipstick:`                 | 更新 UI 和样式文件
:clapper: (场记板)                      | `:clapper:`                  | 更新演示/示例
:rotating_light: (警车灯)               | `:rotating_light:`           | 移除 linter 警告
:wrench: (扳手)                         | `:wrench:`                   | 修改配置文件
:heavy_plus_sign: (加号)                | `:heavy_plus_sign:`          | 增加一个依赖
:heavy_minus_sign: (减号)               | `:heavy_minus_sign:`         | 减少一个依赖
:arrow_up: (上升箭头)                   | `:arrow_up:`                 | 升级依赖
:arrow_down: (下降箭头)                 | `:arrow_down:`               | 降级依赖
:zap: (闪电)<br>:racehorse: (赛马)      | `:zap:`<br>`:racehorse:`      | 提升性能
:chart_with_upwards_trend: (上升趋势图) | `:chart_with_upwards_trend:` | 添加分析或跟踪代码
:rocket: (火箭)                         | `:rocket:`                   | 部署功能
:white_check_mark: (白色复选框)         | `:white_check_mark:`           | 增加测试
:memo: (备忘录)<br>:book: (书)          | `:memo:`<br>`:book:`          | 撰写文档
:hammer: (锤子)                         | `:hammer:`                   | 重大重构
:art: (调色板)                          | `:art:`                      | 改进代码结构/代码格式
:fire: (火焰)                           | `:fire:`                     | 移除代码或文件
:pencil2: (铅笔)                        | `:pencil2:`                  | 修复 typo
:construction: (施工)                   | `:construction:`             | 工作进行中
:wastebasket: (垃圾桶)                  | `:wastebasket:`              | 废弃或删除
:wheelchair: (轮椅)                     | `:wheelchair:`               | 可访问性
:construction_worker: (工人)            | `:construction_worker:`      | 添加 CI 构建系统
:green_heart: (绿心)                    | `:green_heart:`              | 修复 CI 构建问题
:lock: (锁)                             | `:lock:`                     | 修复安全问题
:whale: (鲸鱼)                          | `:whale:`                    | Docker 相关工作
:apple: (苹果)                          | `:apple:`                    | 修复 macOS 下的问题
:penguin: (企鹅)                        | `:penguin:`                  | 修复 Linux 下的问题
:checkered_flag: (旗帜)                 | `:checkered_flag:`           | 修复 Windows 下的问题
:twisted_rightwards_arrows: (交叉箭头)   | `:twisted_rightwards_arrows:`| 分支合并



### 如何在命令行中显示 emoji

默认情况下，在命令行中并不会显示出 emoji, 仅显示 emoji 代码。不过可以使用 [emojify](https://github.com/mrowa44/emojify) 使得在命令行也可显示 emoji, 它是一个 shell 脚本，安装与使用都很简单，在 [这里](https://github.com/mrowa44/emojify) 查看如何安装与使用。

### 参考

- [gitmoji](https://github.com/carloscuesta/gitmoji/)
- [emoji-cheat-sheet](http://www.webpagefx.com/tools/emoji-cheat-sheet/)
- [styleguide-git-commit-message](https://github.com/slashsBin/styleguide-git-commit-message)
- [atom git commit messages guide](https://github.com/atom/atom/blob/master/CONTRIBUTING.md#git-commit-messages)
- [An emoji guide for your commit messages](https://gitmoji.carloscuesta.me/)
- [程序员提交代码的 emoji 指南——原来表情文字不能乱用](https://www.h5jun.com/post/gitmoji.html)
- [Ant Design 更新日志 emoji 规范](https://github.com/ant-design/ant-design/wiki/%E8%BD%AE%E5%80%BC%E8%A7%84%E5%88%99%E5%92%8C%E7%89%88%E6%9C%AC%E5%8F%91%E5%B8%83%E6%B5%81%E7%A8%8B#emoji-for-changelog)

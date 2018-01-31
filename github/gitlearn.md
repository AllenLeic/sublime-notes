[TOC]
# 记录一下个人学习GitHub的经历
- [x]  为什么要学习GitHub？
- [ ]  GitHub入门
- [ ]  Git工具的基本使用
- [ ]  [markdown语法](../Markdown常用语法.txt)
- [ ]  git GUI工具
- [ ]  git 进阶教程
- [ ]  
## github 入门
### **.gitignore**
.gitignore 是一个纯文本文件，里面存放忽略被版本控制的文件
每行代表忽略一个文件，或一类文件，
注释： `# `所有的文字都可以算注释
直接vim .gitignore
如果想把.gitignore忽略的文件加入暂存区，可以git add -f [文件名]

可以不用自己编写自己的.gitignore
github 为我们编写了一些特定的 ![](image/ignore.png)

- 查看gitignore 忽略的规则
- git check-ignore -v [文件名]

### GitHub换行

---
layout: post
title: "灵异事件-来自亡者的信件"
author: "dusksnow"
---

```bash
> pwd
/home/dusksnow/
> ls
dead.letter ...
```

今天在回滚被删除主页的网站时，意外的在主目录里发现了这个文件。我揉了揉脑袋，从昨天的摸鱼想到了刚刚改的配置文件，确定自己从来没有没有起过这么诡异且不知所云的文件名。想到能让人快速阅读的量子神秘莫测的力量，一丝凉意从脚边升起（作者：哇哈哈哈哈～）。

首先排除了机房惨案的可能。这台运行着Arch Linux的电脑的操作界面是惊人的 **简洁**。这个没有任务栏没有桌面图标没有开始菜单，一切程序的启动都靠快捷键的系统，估计除了有界面洁癖的作者本人外没人玩的动了，况且简洁到鬼畜的纯图片登录界面还是让人比较放心的。

那会不会是从网上下载的文件呢？如果查看了Chrome的近几日的文件下载记录，会发现根本不存在这个文件。排除。

我叫来了另外三个小伙伴，在众人庄严的见证下，打开了这个文件。

```bash
> cat dead.letter 
From dusksnow Tue Oct 22 20:34:42 2019
Date: Tue, 22 Oct 2019 20:34:42 +0800
To: dusksnow
User-Agent: mail v14.9.15

Subject: editor saved ``/home/dusksnow/sumengxue.github.io/.git/COMMIT_EDITMSG''
You were editing the file "/home/dusksnow/sumengxue.github.io/.git/COMMIT_EDITMSG"
at <Tue Oct 22 20:34> on the machine ``gcxArch''
when the editor was killed.

You can retrieve most of your changes to this file
using the "recover" command of the editor.
An easy way to do this is to give the command "vi -r /home/dusksnow/sumengxue.github.io/.git/COMMIT_EDITMSG".
This method also works using "ex" and "edit".
```



emmmmm.......

好吧，我在git回滚的时候因为输出炸掉kill了一个进程，敢情这个进程死后还满怀怨念，诈尸给我发了一封这么诚恳的信，意图吓死操作者。

好吧表示涨姿势了...

(PS:dead letter 在百度翻译中表示死信，死消息，而并没有来自亡者的信件的意思)

(PPS: 看来是我想多了)
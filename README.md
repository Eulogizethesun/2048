# 2048游戏

简介
=====

本项目是浙江大学短学期课程“科研和工程中的C++编程”课程作业，主题是开发一个简单的2048游戏。开发的游戏仅作学习使用。


## 背景

2048是几年前一款风靡全球的小游戏。本项目旨在学习使用MVVM框架，用这一框架搭建实现2048游戏的基本功能。


## 开发计划

### 每轮迭代说明
第一轮迭代：利用github和appveyor实现持续集成和自动部署，为游戏开发基础的开始界面，搭建最基本的各个层使相互联系；

第二轮迭代：实现方块数字、分数的实时显示，添加动画；

第三轮迭代：界面美化和代码优化

### 最终效果说明
.实现了基本的2048游戏，包含开始界面和游戏界面。

.可以通过鼠标、键盘的操作，实现方块的移动。

  键盘使用W\S\A\D 或者 上\下\左\右 箭头来控制，鼠标需要单击左键停住，上\下\左\右滑动一定距离后松开左键实现控制。
  
.可以记录游戏最高分，在游戏失败或者成功后会有弹窗提醒。

.可以通过点击界面上的restart按钮重新开始。

.可以通过funny mode 按钮切换到娱乐模式，即表情包模式。

.在游戏进行过程中，实现了方块移动的平滑移动动画效果。

.在方块相撞或者出现时，会有缩放效果，提升用户体验。


## 最终成果展示
### 开始界面
![开始界面](https://github.com/blackwings0325/game/blob/master/picture/start.png)

开始界面包含一个logo 和两个按钮，点击start按钮，进入游戏界面，经典模式。点击exit按钮，退出游戏。
### 游戏失败
![失败界面](https://github.com/blackwings0325/game/blob/master/picture/lose.PNG)

游戏失败，弹窗提醒。
### 正常游戏界面
![正常游戏界面](https://github.com/blackwings0325/game/blob/master/picture/inthegame.PNG)

可点击右侧funny mode按钮进入娱乐模式，也可点击restart按钮重新开始。
###  Funny mode
![funny mode](https://github.com/blackwings0325/game/blob/master/picture/funny.png)

可点击右侧restart按钮重回经典模式。


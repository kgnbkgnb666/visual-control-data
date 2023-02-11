# visual-control-data
在平时场地操作手远程控制机器人的时候，想查看机器人内部数据，这种方法可以及其方便使数据显示在网站上，用手机或电脑输入链接即可实时查看。

#### 此项目是我用chatgpt辅助编写的，不得不说chatgpt真是程序员的神器。接下来我将分三部介绍此项目：作用，使用方法，代码解释。

### 1.作用
在我平常调机器人的时候，如果我想实时查看机器人的内部数据变化，那我只能进行debug，这样就相当于暂停机器人了，这样很不好，不方便。所以我基于此问题，我把机器人主机里的数据通过网络传到网页上，网页可以自己设计得符合各自的需求，我的项目把网页分为左右两部分，左边显示数据，右边显示机器人摄像头的图像。
### 2.使用方法
机器人主机要和您的可视化客户端处于一个局域网内，运行main.py,网页查看输入：http://127.0.0.1:5000（只能本地查看），或者：http://(本地ip地址):5000（可以其他主机查看）。
在手机查看时，建议设计网页全盘和手机设置自动旋转，这样观看效果更佳。
##### 电脑端：
![2023-02-11 10-20-50 的屏幕截图](https://user-images.githubusercontent.com/104723484/218234108-93389829-9489-40f4-b4ef-2c72213b7866.png)
##### 手机端：

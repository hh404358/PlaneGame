# Plane-Game
初学C#时开发的一个基于C# Winform窗体应用开发的飞机大战小游戏，主要通过键盘控制飞机移动及发射子弹等
# 开发工具
Visual Studio 2022
# 主要功能
本游戏主要由键盘控制操作
* WASD键控制飞机移动
* J键发射子弹（可以同时向不同角度发射子弹）
* 碰撞检测：当玩家子弹击中敌机后，敌机爆炸，并播放爆炸音效

# 游戏规则
* 界面上有两个矩形条，分别表示生命值和得分；
* 被敌机子弹击中则减少1分并减少1点生命值，若我方子弹击中敌机则增加1分；
* 当生命值或得分减到0，游戏结束。

# 项目目录结构
```
PlaneGame
|--- Resources 存放图片、音效文件
|--- EnemyBullet.cs 敌方子弹类
|--- Fighter.cs 敌方飞机类
|--- GameForm.cs 游戏主界面
|--- MyBullet.cs 我方子弹类
|--- MyPlane.cs 我方飞机类
|--- Program.cs 程序入口
|--- Resource.resx 资源文件
```
# 游戏效果图
![输入图片说明](screenshot/1.png "运行效果图1")
![输入图片说明](screenshot/2.png "运行效果图2")
![输入图片说明](screenshot/3.png "运行效果图3")


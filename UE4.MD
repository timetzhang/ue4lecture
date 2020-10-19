# UE4 课程

## 1.	关卡设计师入门

打开 /Content/StarterContent/Maps/StarterMap

了解：Actor, Pawn, Character, Static Mesh.

了解：ThirdPerson, FirstPerson, 

了解：Directional Light（定向光源）, Point Light（点光）, Spot Light（聚光）, Sky Light（天光）

了解：静态光照，Static Lighting Level Scale，Num Indirect Lighting Bounces

了解：Lightmass Importance Volume, Lightmass Portal

了解：Post Processing Volume

https://docs.unrealengine.com/zh-CN/Engine/QuickStart/index.html


## 2.	蓝图的Hello World

了解：BoxTrigger, Events

了解：数据类型string

了解：关卡蓝图

作业：灭火人

--------------------------

## 3.	使用蓝图控制

创建一个新“空工程”，来做一个滚动的球

* 创建一个灯光控制 (Actor)
  * 回忆：Box Collision
  * 创建一个地板按钮
  * 控制灯光开关
    * 了解：注释
  * 控制灯光颜色

* 创建一个玩家可以控制的滚动的球 (Pawn)
  * 创建一个Pawn蓝图, 并在蓝图里创建一个有物理系统的球体(Sphere)
    * 了解：Material 材质
    * 了解：Simulate Physics 模拟物理
    * 了解：Gravity 重力
    * 了解：Linear Damping 线性阻尼 / Angular Damping 角阻尼
    * 了解：MassInKg 质量(千克)
  * 创建一个GameMode, "RollingGameMode".
    * 了解：World Settings -> Game Mode
  * Mouse Input
    * Mouse X
    * Mouse Y
    * Left Button / Right Button / Wheel
    * 了解：Make Vector (3D向量)
    * 了解：Add Torque (扭矩)
  * Keyboard Input 
    * Space
    * Ctrl / Shift / Command / Alt
    * A~Z
    * 了解：Set Velocity (速度)
 
* 创建一个秒表
  * Text Render
  * Event BeginPlay (开始时只运行一次)
  * Event Tick (运行过程中不断执行)
  * 变量 (Float, Integer, String, Boolean, Vector)
  * Delay

* Spawn
  * Random 随机


### 5.	发射小人
https://docs.unrealengine.com/zh-CN/Engine/Blueprints/QuickStart/index.html
了解：branch(if)
了解：逻辑表达式>, <, >=, <=, ==, != 
了解：数据类型boolean

### 6.	使用Packs丰富场景
了解：目录结构




7.	控制一盏灯




8.	Interactive交互
了解：Keyboard, Mouse, Trigger, Collision




9.	Landscape and Foliage地形与植物




10.	Post Processing 后期处理

11.	Cinematic 过场动画




12.	Paper2D

13.	UI

14.	Materials

15.	粒子系统

16.	Animation

17.	Audio

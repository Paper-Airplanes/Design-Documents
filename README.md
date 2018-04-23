## 项目设计文档

### 项目名称

纸飞四季

![](素材\纸飞四季.png)

### 项目简介

	玩家站在纸飞机的视角，对构建的场景进行探索，并与场景元素有一定的交互。



	纸飞机设定：

		1）初始位置固定，按一定速度持续向前飞行；

		2）飞行路线固定；

		3）玩家可控制纸飞机进行旋转；

		4）纸飞机可与场景中的季节转换道具进行交互；

		5）纸飞机会留下轨迹



	场景元素设定：

		1）地图元素

			地图固有元素，用于呈现不同季节的场景；

		2）季节转换道具

			4种季节转换道具，纸飞机拾取后场景会发生相应改变



## 与涉及知识点关联（初步）

Basic:

	1.Camera Roaming

		玩家视角与纸飞机视角同步

	2.Simple lighting and shading（phong）

		场景光源（阳光）

	3.Texture mapping

		飞机材质（纸），及地图元素材质

	4.Shadow mapping

		与场景光源结合体现阴影

	5.Model import & Mesh viewing（Assimp）

		地图元素的搭建



Possible Bonus:

	1.Sky Box（天空盒）

		场景与地图元素构建

	2.Gravity System and Collision Detection（重力系统和碰撞检测）

		场景元素（雨、雪、雾）等

		玩家对飞机拥有完全控制权，路线不再固定

	3.Particle System（粒子系统）

		场景元素（雨、雪、雾）





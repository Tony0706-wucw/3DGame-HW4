1、基本操作演练 • 下载 Fantasy Skybox FREE，构建自己的游戏场景，并为场景设计地 形（含树木和草地等元素）

---

创建地形场景 Terrain，绘制地形场景、山、树、草等

![image-20221009114919792](C:\Users\tony0706\AppData\Roaming\Typora\typora-user-images\image-20221009114919792.png)

在asset store中搜索Fantasy Skybox FREE便可以找到需要的天空场景

然后在Assets 上下文菜单 -> create -> Material 起名为 mysky，在 Inspector 视图中选择 Shader -> Skybox -> 6Sided

在 Camera 对象中添加部件 Rendering -> Skybox，然后将天空盒拖放入 Skybox就可以看到想要的天空背景，结果如图

![image-20221009115456461](C:\Users\tony0706\AppData\Roaming\Typora\typora-user-images\image-20221009115456461.png)

---

参考：https://blog.csdn.net/weixin_43895819/article/details/125223372

​		   https://blog.csdn.net/TempterCyn/article/details/101614643
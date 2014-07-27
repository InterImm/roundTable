# 星际推进技术


目前的状况是，使用化学能，也就是外层电子跃迁的一丁点能量来推进。当然也有少量的离子推进器（实验性质，推力小）。


![Launch System](https://lh5.googleusercontent.com/-87sPWo8WSus/U9QThjrCGmI/AAAAAAAAC8A/S4QYSlrF9J0/s0/launchSystem.png)

[A mindmap, Mindmup](https://drive.google.com/file/d/0ByjhpSk2nUFpeVExTV9CWERpQjQ/edit?usp=sharing)



大纲

1. 推进技术要干什么
2. 推进技术需要什么
   * 工质
   * 能源
3. 其他


## 推进的目的

牛顿引力中，质点的轨道运动方程中，质点的质量被消掉了，只剩下引力源的质量，质点的速度和轨道几何。所以说，一般的推进技术实质上是要改变飞行器的速度。

而要改变飞船速度，需要一个推力。这个推力可用来自于飞船将自身的组成物质直接向运动改变相反方向扔掉，也可以使用外来的物体与飞船相互作用。


## 较为成熟的技术

* 等离子体工质
  物质电离，然后利用电磁场将物质推出。

* 核动力能源
  核反应作为能源。例如产生电能供给等离子体推进器。




### [Gridded electrostatic ion thrusters](https://en.wikipedia.org/wiki/Ion_drive#Gridded_electrostatic_ion_thrusters)

工质：[氙](https://zh.wikipedia.org/wiki/%E6%B0%99)，[氪](https://zh.wikipedia.org/wiki/%E6%B0%AA)

液体储存，容易气化，低污染低侵蚀（可以想想如果使用铯离子,早期使用汞和铯，但是这些东西都会在推进器上聚集，而且不安全），

示例：

Deep Space 1 使用的推进器

![](http://www.nasa.gov/centers/glenn/images/content/83551main_fs008_fig2.gif)

1. 电压 1280V.
2. 离子出口速度：146,000km/h= 40,556 m/s = 40.6 km/s
3. 最大功率2300W，仅仅产生 90 millinewtons 的推力

最为对照，飞行器上的化学燃料燃烧推进中，会产生 450 to 2250 newton的推力。

那么优势是什么？

1. 10 倍高的利用率（[化学燃料出口速度只有 5000 m/s 左右，只能作用 500s](http://web.mit.edu/aeroastro/labs/spl/aboutElectricPropulsion.html)）
   冲量决定动量改变，Ft.虽然力很小，但是如果时间很长，那么总的冲量就很大。2. 推进器本身质量小

DS1 的燃料有 81kg，以最大功率一半运行，可以持续20个月。时间是化学推进的 90000 倍，



### [Hall 效应推进器](https://en.wikipedia.org/wiki/Hall_effect_thruster)



利用电场来加速离子，同时使用磁场来限制粒子的运动轨迹（主要是限制电子，使电子在推进器内停留更长的时间，从而使得工质电离更加充分）。

![](https://upload.wikimedia.org/wikipedia/commons/thumb/8/8c/Lorentz_force.svg/675px-Lorentz_force.svg.png)

霍尔效应中，电场和磁场决定了带电粒子轨迹。

霍尔效应推进器可能是这样的：

![](https://upload.wikimedia.org/wikipedia/commons/thumb/2/2d/Wfm_hall_thruster.svg/800px-Wfm_hall_thruster.svg.png)
(来源：https://en.wikipedia.org/wiki/Hall_effect_thruster)

利用洛伦兹力公式，我们可以判断电子会螺旋向内运动，这样高能电子会有更多的机会碰到工质气体原子，并电离他们，使得电离更充分。因为电离的百分比可以决定我们的工质有多少被利用，所以这是非常重要的一项指标。

**相对于只用电场有什么优势？**

[空间电荷效应？](https://en.wikipedia.org/wiki/Hall_effect_thruster#Operation)不明白。


> [Specific impulse](https://en.wikipedia.org/wiki/Specific_impulse)：$$I_{\rm sp}=\frac{v_{\rm e}}{g_{\rm 0}}$$ 对于这真空中运行的时候的极限速度，

|推进器  | 有效的极限速度 |  SI  |
|-------|-----------|----------|
|Solid rocket | 2,500 |	250  |
|Bipropellant liquid rocket | 4,400  |	450  |
| Hall Effect | -  | 1600 |
|Ion thruster  |	29,000   |	3,000  |
|Dual-stage 4-grid electrostatic ion thruster  |	210,000  |	21,400  |
|VASIMR  |	30,000-120,000  |	3,000-12,000  |



示例：
[SMART-1](https://en.wikipedia.org/wiki/Hall_effect_thruster#Applications)

* Discharge power: 0.46–1.19 kW
* Specific impulse: 1,100–1,600 s
* Thrust: 30–70 mN
* Thruster operating time: 5,000 h
* Xenon throughput: 82 kg
* Total impulse: 1.1 MN·s
* Total ΔV: 3.9 km/s




### [FEEP](https://en.wikipedia.org/wiki/Field_emission_electric_propulsion)

![FEEP](https://lh3.googleusercontent.com/-lBHAviShXXE/U9PhLVFGUrI/AAAAAAAAC7Q/fdzzKce43r8/s0/feep.png)

大的电场强度->金属尖端金属被电离->被电场加速到 10km/s

通常使用的电压在 10kV 的量级。



### [VASIMR](https://en.wikipedia.org/wiki/VASIMR)


![](https://upload.wikimedia.org/wikipedia/en/thumb/7/7b/Multi-megawatt_VASIMR_spacecraft.jpg/800px-Multi-megawatt_VASIMR_spacecraft.jpg)


![](https://upload.wikimedia.org/wikipedia/en/thumb/9/94/VASIMR_system.jpg/776px-VASIMR_system.jpg)



![VASIMR](https://lh4.googleusercontent.com/-fv9T4M-wsOU/U9P3n92FdCI/AAAAAAAAC7o/iiZQADN0nzg/s0/VSIM.png)

(来源：[Magnetohydrodynamic scenario of plasma detachment in a magnetic nozzle](http://scitation.aip.org/content/aip/journal/pop/12/4/10.1063/1.1875632) 【[PDF](http://www.adastrarocket.com/PoP2005.pdf)】)




将来可能用大功率的 VASIMR 来组建货运轨道（[Projected Lunar Cargo Capabilities of High-Power VASIMRTM Propulsion ](http://www.adastrarocket.com/Tim_IEPC07.pdf)）。


### [Quantum vacuum plasma thruster](https://en.wikipedia.org/wiki/Quantum_vacuum_plasma_thruster)




### 燃料

现在大多使用 Xe 因为

1. 惰性气体不腐蚀
2. 原子数还算大，这样同样的电压动量改变大。$$\sqrt{2mqE}=p$$
3. 相对容易电离。


### 其他非火箭类


#### [质量投射器](https://en.wikipedia.org/wiki/Mass_drivers)


例如炮姐投射器。


##### [StarTram](http://www.startram.com/home)

![](https://upload.wikimedia.org/wikipedia/commons/thumb/f/f3/Startram.jpg/800px-Startram.jpg)

例如 [StarTram](https://en.wikipedia.org/wiki/StarTram) ，是一种磁悬浮发射系统（第一代设计中没有磁悬浮）。


第一代的设计是一种地面的设计：

1. 6km 高的山顶
2. 8.78 km/s 的发射速度（地面的第一宇宙速度7.9km/s）
3. 发射角度：10°

![](https://upload.wikimedia.org/wikipedia/commons/thumb/b/bc/Maglifter2.jpg/800px-Maglifter2.jpg)


轨道在一个真空管道内：

![](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c0/Maglifter1.jpg/750px-Maglifter1.jpg)

> [Plasma window](https://en.wikipedia.org/wiki/Plasma_window)：利用电磁场限制空气进入。


第二代是在低轨道：

![](https://upload.wikimedia.org/wikipedia/commons/thumb/7/77/Startramgeneration2.jpg/800px-Startramgeneration2.jpg)


#### [其他不需要火箭的发射系统](https://en.wikipedia.org/wiki/Non-rocket_spacelaunch)





##### [Skyhook](https://en.wikipedia.org/wiki/Orbiting_skyhooks)

![Skyhook](https://upload.wikimedia.org/wikipedia/commons/1/15/Mature_non-rotating_Skyhook.png)

（图源：[wikipedia](https://en.wikipedia.org/wiki/File:Mature_non-rotating_Skyhook.png)）



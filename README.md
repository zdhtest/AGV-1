# AGV小车

## 0. 现阶段需求

最终目的为了完成工厂运输钢瓶的目的，现阶段想要实现一辆由手柄随动控制的AGV小车。

## 1. 硬件方案

### 1.1 全向轮方案

#### 1） 麦克纳姆轮（Mecanum Wheel）

麦克纳姆轮优点和缺点都是非常明确。采用麦克纳姆轮的车子大都移动异常灵活，机动性能非常好；但是这种轮胎的越野性能却非常差，跨越障碍的能力甚至不如普通轮胎，特别是当坡度较大的时候，甚至还会溜坡。所以配备这种车胎的设备大多是一些场地竞技机器人和室内仓储机器人等。

https://wenku.baidu.com/view/94f3c91717fc700abb68a98271fe910ef12dae8e.html?from=search
https://zhuanlan.zhihu.com/p/20282234?utm_source=qq&utm_medium=social 知乎专栏讲解
https://v.qq.com/x/page/o06206wwirk.html 直观动画演示

#### 2）全向轮（Omni Wheel）

### 1.2 机械结构方案

#### 1）悬挂系统设计

https://wenku.baidu.com/view/80e067aea0c7aa00b52acfc789eb172dec639950.html

### 1.3 电机方案

- JGB37-520带编码器减速直流电机

### 1.4 测速编码器



## 2. 电控方案

### 2.1 控制器方案

### 2.2 底盘电机调速

四个电机独立的PID闭环，速度位置双环PID控制

### 2.3 通信方案

CAN

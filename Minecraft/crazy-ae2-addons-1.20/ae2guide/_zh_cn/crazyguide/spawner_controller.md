---
navigation:
  parent: crazyae2addons_index.md
  title: 刷怪笼控制器
  icon: crazyae2addons:spawner_controller_wall
categories:
  - Mob Storage
item_ids:
   - crazyae2addons:spawner_controller_wall
---

<BlockImage id="crazyae2addons:spawner_controller_wall" scale="4"></BlockImage>

# 刷怪笼控制器

刷怪笼控制器是一个多方块系统，用于模拟真正的刷怪笼刷出生物的过程，刷到的生物会被存入ME网络。如此就可在无实体生成的情况下自动化捕捉生物，还可避免卡顿。

- **W** – 刷怪笼控制器墙壁
- **G** – 聚能石英玻璃
- **A** – 空气
- **S** – Minecraft刷怪笼

#### 第1层：
W W W W W <br/>
W W W W W <br/>
W W W W W <br/>
W W W W W <br/>
W W W W W 

#### 第2层：
W G G G W <br/>
G A A A G <br/>
G A A A G <br/>
G A A A G <br/>
W G G G W

#### 第3层：
W G G G W <br/>
G A A A G <br/>
G A S A G <br/>
G A A A G <br/>
W G G G W

#### 第4层：
W G G G W <br/>
G A A A G <br/>
G A A A G <br/>
G A A A G <br/>
W G G G W

#### 第5层：
W W W W W <br/>
W W W W W <br/>
W W W W W <br/>
W W W W W <br/>
W W W W W



## 使用方法

1. **搭建多方块结构**
   - 按照上述模式搭建多方块。注意要在刷怪笼周围搭建。

2. **为控制器供能**
   - 将刷怪笼控制器接至启动的ME网络。

3. **安装升级卡（可选）**
   - 可用速度卡加快生物的生成速度。

---

## 工作原理

- 结构成形之后，其内部的刷怪笼即会被禁用。
- 刷怪笼每20刻会向ME网络存入一些生物。
- 控制器读取生物类型。
- 整个过程不会真正生成生物，只有利落、可重复进行的生物捕捉。

---

## 重要注意事项

- **需要正确搭建多方块结构**：刷怪笼结构缺损即停工。
- **不会真正生成生物**：没有卡顿，万事大吉。
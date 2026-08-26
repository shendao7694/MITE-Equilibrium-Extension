# MITE Equilibrium Extension
> 原作者：[https://github.com/Lithewings](https://github.com/Lithewings) 原作者仓库：[https://github.com/Lithewings/MITE_Equilibrium](https://github.com/Lithewings/MITE_Equilibrium)

本模组是 MITE Equilibrium 的扩展，基于原作者 Lithewings 的硬核生存模组进行内容扩充。原模组以 Minecraft Fabric 1.21.1 为框架，重塑了经典整合包 MITE-R196 的核心机制，并提供了从零开始挑战末影龙的线性进度体验。而本扩展则在原版硬核的基础上，添加了全新的后期内容，让挑战更加深入。

## 扩展内容一览

1. 全新材料与装备：添加了振金、无尽、精华、奇异物质等多套从中期到毕业的完整材料线，以及对应的工具、武器和盔甲。

2. 更强的Boss与生物：在原有怪物基础上，新增了持振金/无尽装备的骷髅领主、终焉骷髅等强大敌人，带来新的挑战。

3. 实用道具与系统：增加了“飞行之戒”等便利道具，以及用于合成高级物品的“奇点”和“精华”系统，丰富了后期玩法。

4. 深入游戏后期：扩展包的目标是让玩家在挑战完原版末影龙后，仍有新的目标可追求，如挑战更强的Boss、打造终极装备等。

## 一、新增物品

### 1. 振金系列 (Vibranium)

#### 材料
| 物品 | ID | 说明 |
|------|-----|------|
| 振金锭 | `vibranium` | 合成材料 |
| 振金粒 | `vibranium_nugget` | 合成材料 |

#### 工具
| 物品 | ID | 说明 |
|------|-----|------|
| 振金斧 | `vibranium_axe` | 斧头 |
| 振金镐 | `vibranium_pickaxe` | 镐子 |
| 振金铲 | `vibranium_shovel` | 铲子 |
| 振金剑 | `vibranium_sword` | 剑 |
| 振金锄 | `vibranium_hoe` | 锄头 |
| 振金锤 | `vibranium_hammer` | 锤子 |
| 振金匕首 | `vibranium_dagger` | 匕首 |

#### 盔甲
| 物品 | ID | 说明 |
|------|-----|------|
| 振金头盔 | `vibranium_helmet` | 头盔 |
| 振金胸甲 | `vibranium_chest_plate` | 胸甲 |
| 振金护腿 | `vibranium_leggings` | 护腿 |
| 振金靴子 | `vibranium_boots` | 靴子 |


---

### 2. 精华系统 (Essence)

#### 其他精华
| 物品 | ID | 获取方式 |
|------|-----|----------|
| 世界精华 | `essence_world` | 4个维度精华合成 |
| 铁砧精华 | `essence_anvil` | 铁砧 + 秘银锭 → 8个 |
| 龙之精华 | `essence_dragon` | 龙蛋 → 8个 / 龙息 → 1个 |
| 经验精华 | `essence_exp` | 9个铁币合成 |

#### 维度精华
| 物品 | ID | 合成材料 |
|------|-----|----------|
| 主世界精华 | `essence_overworld` | 9种主世界生物精华 |
| 下界精华 | `essence_nether` | 7种下界生物精华 + 下界之心 |
| 地下世界精华 | `essence_underworld` | 8种地下世界生物精华 |
| 末地精华 | `essence_the_end` | 4种末地生物精华 + 龙之精华 |

#### 生物精华（7% 掉落率）
| 分类 | 物品 | 对应生物 |
|------|------|----------|
| **主世界** | `essence_zombie` | 僵尸 |
| | `essence_skeleton` | 骷髅 |
| | `essence_creeper` | 苦力怕 |
| | `essence_spider` | 蜘蛛 |
| | `essence_pig` | 猪 |
| | `essence_sheep` | 羊 |
| | `essence_cow` | 牛 |
| | `essence_guardian` | 守卫者 |
| | `essence_pillager` | 掠夺者 |
| **地下世界** | `essence_longdead` | 古尸 |
| | `essence_wight` | 白色食尸鬼 |
| | `essence_ghoul` | 食尸鬼 |
| | `essence_shadow` | 黑色食尸鬼 |
| | `essence_invisible_stalker` | 隐形潜伏者 |
| | `essence_pudding` | 黑色史莱姆 |
| | `essence_revenant` | 亡魂 |
| | `essence_stone_elemental` | 石元素 |
| **下界** | `essence_piglin` | 猪灵 |
| | `essence_magma_cube` | 岩浆怪 |
| | `essence_piglin_brute` | 猪灵蛮兵 |
| | `essence_zombified_piglin` | 僵尸猪灵 |
| | `essence_wither_skeleton` | 凋零骷髅 |
| | `essence_ghast` | 恶魂 |
| | `essence_blaze` | 烈焰人 |
| | `essence_netherrack_elemental` | 下界岩元素 |
| **末地** | `essence_enderman` | 末影人 |
| | `essence_shulker` | 潜影贝 |
| | `essence_end_rock_elemental` | 末地岩元素 |
| | `essence_obsidian_elemental` | 黑曜石元素 |
| **模组生物** | `essence_bone_lord` | 骷髅领主 |
| | `essence_wooden_spider` | 木蜘蛛 |

#### 合成配方
| 配方 | 材料 | 产物 |
|------|------|------|
| 经验修补附魔书 | 经验精华 + 铁砧精华 | 经验修补附魔书 x1 |

---

### 3. 奇异矿石系统 (Strange Ore)

| 物品 | ID | 说明 |
|------|-----|------|
| 奇异矿石 | `strange_ore` | 地下世界生成，与艾德曼矿石相同几率 |
| 奇异物质 | `strange_material` | 烧制奇异矿石获得 |

#### 生成参数
| 参数 | 值 |
|------|-----|
| 维度 | 地下世界 |
| 矿脉大小 | 5 |
| 生成次数 | 1 |
| 生成高度 | Y: 0-20 |

---

### 4. 银符黑曜石 (Silver Rune Obsidian)

| 物品 | ID | 说明 |
|------|-----|------|
| 银符黑曜石 α | `silver_rune_obsidian` (variant=alpha) | 银色符文 |
| 银符黑曜石 β | `silver_rune_obsidian` (variant=beta) | 金色符文 |
| 银符黑曜石 γ | `silver_rune_obsidian` (variant=gamma) | 紫色符文 |

#### 特性
- 硬度 0，空手秒破
- 掉落自身
- 三种变种通过 NBT 区分

---

### 5. 无尽系列 (Infinity)

#### 材料
| 物品 | ID | 说明 |
|------|-----|------|
| 无尽锭 | `infinity_ingot` | 合成材料 |
| 钻石奇点 | `infinity_singularity_diamond` | 合成材料 |
| 铁奇点 | `infinity_singularity_iron` | 合成材料 |
| 矿物奇点 | `infinity_singularity_mineral` | 合成材料 |
| 秘银奇点 | `infinity_singularity_mithril` | 合成材料 |
| 银奇点 | `infinity_singularity_silver` | 合成材料 |

#### 工具
| 物品 | ID | 说明 |
|------|-----|------|
| 无尽镐 | `infinity_pickaxe` | 镐子（可挖掘任何方块，包括基岩） |
| 无尽剑 | `infinity_sword` | 剑 |

#### 盔甲
| 物品 | ID | 说明 |
|------|-----|------|
| 无尽头盔 | `infinity_helmet` | 头盔 |
| 无尽胸甲 | `infinity_chest_plate` | 胸甲 |
| 无尽护腿 | `infinity_leggings` | 护腿 |
| 无尽靴子 | `infinity_boots` | 靴子 |

#### 特性
- 全套无尽盔甲效果：生命恢复 V、抗性提升 III、速度 V、急迫 V、饱和 V、跳跃提升 II、夜视 V
- 自动消除所有负面效果

---

### 6. 飞行之戒 (Flight Ring)

| 物品 | ID | 说明 |
|------|-----|------|
| 飞行之戒 | `flight_ring` | 右键切换飞行模式 |

#### 特性
- 右键点击切换飞行模式
- 可在生存/冒险模式使用

---

## 二、新增方块

| 方块 | ID | 说明 |
|------|-----|------|
| 奇异矿石 | `strange_ore` | 地下世界生成 |
| 银符黑曜石 | `silver_rune_obsidian` | 三种变种 |
| 振金块 | `vibranium_block` | 待添加 |

---

## 三、新增创造模式物品栏

| 物品组 | ID | 说明 |
|------|-----|------|
| 精华物品组 | `essencegroup` | 存放所有精华物品 |

---

## 四、新增配方

### 1. 精华相关配方

| 配方 | 材料 | 产物 |
|------|------|------|
| 主世界精华(无序) | 9种主世界生物精华 | `essence_overworld` x1 |
| 下界精华(无序) | 7种下界生物精华 + 下界之心 | `essence_nether` x1 |
| 地下世界精华(无序) | 8种地下世界生物精华 | `essence_underworld` x1 |
| 末地精华(无序) | 4种末地生物精华 + 龙之精华 | `essence_the_end` x1 |
| 世界精华(无序) | 4个维度精华 | `essence_world` x1 |
| 经验精华(无序) | 9个铁币 | `essence_exp` x1 |
| 龙之精华(无序) | 1个龙蛋 | `essence_dragon` x8 |
| 龙之精华(无序) | 1个龙息 | `essence_dragon` x1 |
| 铁砧精华(无序) | 铁砧 + 秘银砧 | `essence_anvil` x8 |
| 经验修补附魔书(无序) | 经验精华 + 铁砧精华 | 附魔书 x1 |

### 2. 振金相关配方

| 配方 | 材料 | 产物 |
|------|------|------|
| 振金锭 | 龙之精华x3 + 奇异物质 + 铁砧精华 + 世界精华 + 经验精华 + 艾德曼 | `vibranium` x1 |

### 3. 无尽相关配方

| 配方 | 材料 | 产物 |
|------|------|------|
| 无尽锭(无序) | 矿物奇点x4 + 世界精华x5 | `infinity_ingot` x1 |
| 矿物奇点(无序) | 钻石奇点x2 + 秘银奇点x2 + 铁奇点x2 + 银奇点x2 + 艾德曼块 | `infinity_singularity_mineral` x1 |
| 钻石奇点(无序) | 钻石块x9 | `infinity_singularity_diamond` x1 |
| 银奇点(无序) | 银块x9 | `infinity_singularity_silver` x1 |
| 铁奇点(无序) | 铁块x9 | `infinity_singularity_iron` x1 |
| 秘银奇点(无序) | 秘银块x9 | `infinity_singularity_mithril` x1 |
| 无尽剑(无序) | 无尽锭x1 + 振金剑 | `infinity_sword` x1 |
| 无尽镐(无序) | 无尽锭x1 + 振金镐 + 振金斧 + 振金锹 | `infinity_pickaxe` x1 |

### 4. 飞行之戒配方

| 配方 | 材料 | 产物 |
|------|------|------|
| 飞行之戒 | 幻翼膜 + 龙之精华 + 鞘翅 + 奇异物质 | `flight_ring` x1 |


## 五、新增生物

### 1. [Boss] 黑暗骷髅领主 (Dark Bone Lord)

| 属性 | 详情 |
|------|------|
| 注册名 | `dark_bone_lord` |
| 类型 | 亡灵生物 / Boss |
| 生成维度 | **下界**（地狱） |
| 生成方式 | 自然刷新 |
| 生成权重 | 1（稀有） |

#### 装备
| 槽位 | 物品 |
|------|------|
| 头盔 | 振金头盔 |
| 胸甲 | 振金胸甲 |
| 护腿 | 振金护腿 |
| 靴子 | 振金靴子 |
| 主手 | 振金剑 或 振金锤 |

#### 属性
| 属性 | 值 |
|------|-----|
| 生命值 | 80 |
| 攻击力 | 2.0 |
| 护甲 | 4.0 |
| 移动速度 | 0.3 |
| 跟随范围 | 40 格 |
| 掉落经验 | 10000 XP |

#### 技能
| 技能 | 说明 |
|------|------|
| 振金锤攻击 | 施加缓慢 III（200 tick）+ 虚弱 I（100 tick） |
| 召唤军队 | 发现玩家时召唤 **12个古尸** + **3个骷髅领主** |
| 远程/近战切换 | 距离 ≥ 8 格使用弓，< 8 格切换近战武器 |

#### 掉落物
| 物品 | 概率 |
|------|------|
| 经验 | 10000 XP |

#### 特点
- 使用骷髅王的材质
- 穿着振金全套盔甲
- 召唤的军队带有强化效果（抗性、生命恢复、力量、速度）

---

### 2. [Boss] 终焉骷髅 (Endless Skeleton)

| 属性 | 详情 |
|------|------|
| 注册名 | `endless_skeleton` |
| 类型 | 亡灵生物 / Boss |
| 生成维度 | **下界**（地狱） |
| 生成方式 | **不自然刷新** |
| 触发条件 | 挖掘烈焰人刷怪笼时 **100%** 生成 |

#### 装备
| 槽位 | 物品 |
|------|------|
| 头盔 | 无尽头盔 |
| 胸甲 | 无尽胸甲 |
| 护腿 | 无尽护腿 |
| 靴子 | 无尽靴子 |
| 主手 | 无尽剑 |
| 副手 | 弓 |

#### 属性
| 属性 | 值 |
|------|-----|
| 生命值 | 300 |
| 攻击力 | 20.0 |
| 护甲 | 20.0 |
| 护甲韧性 | 5.0 |
| 移动速度 | 0.35 |
| 击退抗性 | 100% |
| 掉落经验 | 20000 XP |

#### 技能
| 技能 | 说明 |
|------|------|
| 无尽剑攻击 | 造成 **致盲**（100 tick）+ **凋零 II**（200 tick）+ **缓慢 II**（100 tick） |
| 召唤军队 | 发现玩家时召唤 **30个古尸**（带强化效果） |
| 远程/近战切换 | 距离 ≥ 8 格使用弓，< 8 格切换无尽剑 |

#### 掉落物
| 物品 | 概率 |
|------|------|
| 经验 | 20000 XP |

#### 特点
- 使用骷髅王的材质
- 穿着无尽全套盔甲
- 手持无尽剑，攻击附带多重负面效果
- 召唤的30个古尸带有强力强化效果（抗性 II、生命恢复 II、力量 II、速度 I）
- **不会自然刷新**，只能通过破坏烈焰人刷怪笼触发

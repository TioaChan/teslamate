# Grafana 仪表盘中文汉化说明

## 概述

本文档说明了 Grafana 仪表盘的中文汉化工作。所有仪表盘的标题、面板标题、标签和显示名称都已从英文翻译成中文。

## 已翻译的仪表盘

### 主仪表盘（19个）

| 英文标题 | 中文标题 |
|---------|---------|
| Battery Health | 电池健康 |
| Charge Level | 充电等级 |
| Charges | 充电记录 |
| Charging Stats | 充电统计 |
| Database Information | 数据库信息 |
| Drive Stats | 驾驶统计 |
| Drives | 行驶记录 |
| Efficiency | 效率 |
| Locations | 位置 |
| Mileage | 里程 |
| Overview | 概览 |
| Projected Range | 预计续航 |
| States | 状态 |
| Statistics | 统计 |
| Timeline | 时间线 |
| Trip | 行程 |
| Updates | 更新 |
| Vampire Drain | 吸血鬼耗电 |
| Visited | 已访问 |

### 内部仪表盘（3个）

| 英文标题 | 中文标题 |
|---------|---------|
| Charge Details | 充电详情 |
| Drive Details | 行驶详情 |
| Home | 主页 |

### 报告仪表盘（1个）

| 英文标题 | 中文标题 |
|---------|---------|
| Drives - Dutch tax | 行驶记录 - 荷兰税 |

## 翻译内容

以下元素已被翻译：

1. **仪表盘标题**：所有仪表盘的主标题
2. **面板标题**：仪表盘内各个面板的标题
3. **导航链接**：如"Dashboards"（仪表盘）
4. **注释标签**：如"Annotations & Alerts"（注释和警报）
5. **变量标签**：如"Car"（车辆）
6. **字段显示名称**：在字段配置中的显示名称

## 常见翻译对照

### 电池和充电

- Battery Level → 电池电量
- Charging Power → 充电功率
- Charging Voltage → 充电电压
- Charge Level → 充电等级
- Battery Capacity → 电池容量
- Battery Health → 电池健康

### 驾驶和行程

- Drive Stats → 驾驶统计
- Drives → 行驶记录
- Distance driven → 行驶距离
- Max Speed → 最高速度
- Drive Duration → 驾驶时长

### 能耗和效率

- Efficiency → 效率
- Ø Consumption (net) → 平均能耗（净值）
- Ø Consumption (gross) → 平均能耗（总值）
- Energy consumed (net) → 能耗（净值）

### 温度

- Driver Temp → 驾驶员温度
- Outside Temp → 室外温度
- Inside Temp → 室内温度

### 其他

- Range → 续航
- Firmware → 固件
- Odometer → 里程表
- Mileage → 里程
- States → 状态
- Timeline → 时间线

## 技术细节

- 所有翻译都保持了 JSON 文件的有效性和结构完整性
- 变量引用（如 `$car_id`, `$preferred_range` 等）保持不变
- 技术术语（如 TeslaMate）保持英文原文
- 使用 UTF-8 编码以正确显示中文字符

## 验证

所有翻译后的 JSON 文件都已通过验证：
- JSON 结构完整性检查通过
- 文件编码正确（UTF-8）
- 所有 23 个仪表盘文件已成功翻译

## 维护

如需添加新的翻译或修改现有翻译，请确保：
1. 保持 JSON 文件的有效性
2. 使用 UTF-8 编码
3. 测试翻译后的仪表盘显示效果
4. 保持翻译的一致性

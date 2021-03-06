# 可视化期末项目

## 主题：研究影响不同省份的年收入的因素
### 主要调查方向：省份人口总数、地区生产总值、省份氮氧排放量、省份钢铁生产总量
### 项目合作成员：17网新2班王楚滢、18网新3班周雨
### 数据来源：国家统计局
### pythonanywhere：http://cangjingren.pythonanywhere.com/

## 猜想：
- 氮氧排放量可间接证明省份的快速发展（如经济上涨），因为在城市建设过程中，地区难免会产生会环境有不利影响的气体。试图证实国内氮氧排放量高的省份有着较高的平均年收入。
- 钢铁生产量可看出省份的重工业水平，猜想生产钢材较多的省份有较高的平均年收入（即重工业的省份比非重工业的省份能获取更多的经济效益）。
- 地区生产总值可直接体现一个地区的生产水平，猜想生产总值越高的地区，年收入越高。
- 人口数量可说明地区的发展程度（人们更愿意去一线城市发展而不是三四线城市），猜想人口数量与平均年收入有一定程度的关系。

## 数据分析：
- 与省份年收入有明显关系的两个因素为**省份人口总数**和**地区生产总值**。
- 平均年收入最高的三个省份分别是北京、上海、西藏。
- 氮氧排放量与钢铁生产量有明显的相关关系，钢铁生产较多的省份所排出的氮氧化物气体也较多（如山东、河北，江苏）。但这几个省份的平均年收入并未列入全国前三。**即氮氧排放量**与**钢铁生产总量**与省份平均年收入没有明显的相关关系。
- 2018年，广东的生产总值位居全国第一，但广东的平均年收入却没有位于前三。猜想理由与广东的人口数量过多有关，即便有着让其他省份难以超过的经济效益，广东的平均年收入也没有位于全国前三。

## 总结：
- 年收入较高的省份都是非重工业的省份，说明省份主要经济来源已经脱离了重工业产物。
- 需要对人口密集的省份添加一定的人口进入设置，以防地区人口过多。
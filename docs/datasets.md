# 常用数据集

这里整理了一些常用的示例数据集，点击链接即可下载 `.dta` 格式文件。

## 说明

- 所有数据文件都存放在本项目的 `docs/data/` 目录下。
- 点击表格中的“下载”链接即可将 `.dta` 文件保存到本地。
- `.dta` 为 Stata 格式，也可以用以下方式读取：
  - **Stata**：`use "titanic3.dta", clear`
  - **R**：`haven::read_dta("titanic3.dta")`
  - **Python**：`pandas.read_stata("titanic3.dta")`

## 数据集列表

| 数据集 | 说明 | 文件大小 | 下载 |
|---|---|---|---|
| **Titanic** | 泰坦尼克号乘客数据，包含舱位等级、性别、年龄、票价、登船港口、是否生还等变量。 | 268 KB | [下载](https://zhuxi97.github.io/Docs/data/titanic3.dta) |
| **MRW 1992** | Mankiw、Romer 与 Weil（1992）跨国经济增长经典数据集，包含各国人均 GDP、投资率、人口增长率、教育水平等变量。 | 12 KB | [下载](https://zhuxi97.github.io/Docs/data/MRW1992.dta) |
| **CK 1994** | Card 与 Krueger（1994）最低工资与就业经典研究数据集，包含新泽西州和宾夕法尼亚州快餐店在最低工资调整前后的就业、工资、价格等信息。 | 100 KB | [下载](https://zhuxi97.github.io/Docs/data/CK1994.dta) |
| **Maddison 2023** | Maddison Project Database 2023，包含各国/地区长期的 GDP、人均 GDP、人口等历史宏观经济数据。 | 10.9 MB | [下载](https://zhuxi97.github.io/Docs/data/maddison2023_web.dta) |

## 如何新增数据集

1. 将准备好的 `.dta` 文件放入 `docs/data/` 目录。
2. 在上表中新加一行，写明数据集名称、说明、文件大小和下载链接。
3. 如果文件很大（超过几 MB），建议优先使用网盘或 Releases，再在表格中放外部链接。
4. 提交并推送到 GitHub，线上页面会自动更新。

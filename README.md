# 水处理工具箱 · WaterKit

> 给水处理工程师的精准计算工具箱 · [waterkit.cn](https://waterkit.cn)

**WaterKit** 是一套面向水处理工艺工程师、水厂运行人员、环保公司技术员的在线计算工具集合。所有计算在浏览器本地完成,无需后端、无需注册、完全免费。

由海南登登科技咨询有限公司([dengdengtech.cn](https://dengdengtech.cn))出品与维护。

## ✨ 特点

- **纯静态 · 即开即用** — 10 个 HTML 文件,双击即可离线使用
- **规范优先** — 每个工具都标注依据的国标、行业标准与公式出处
- **实时联动** — 改任意输入结果立即重算,像 Excel 一样顺滑
- **移动适配** — 工地、水厂、会议室、手机上都能用
- **参数完整** — 温度 / 海拔 / 介质 / 工艺参数一一到位,不做简化

## 📐 工具目录

### 水力计算 · Hydraulics

| 工具 | 说明 |
|------|------|
| [管道水力](pipe-hydraulic-calculator.html) | Q/v/D 互算 · Colebrook-White 迭代 · 9 种管材粗糙度 |
| [明渠水力](open-channel-calculator.html) | Manning 公式 · 梯形/矩形/圆形断面 · 临界水深 · Fr 判流 |
| [堰流计算](weir-flow-calculator.html) | 矩形 / 三角 / 梯形 / 宽顶 四种堰型 · 淹没出流修正 |
| [孔口管嘴出流](orifice-nozzle-calculator.html) | 薄壁孔 / 圆柱管嘴 / 锥形管嘴 / 大孔口 · 变水头泄流时间 |

### 工艺计算 · Process

| 工具 | 说明 |
|------|------|
| [曝气量](aeration-calculator.html) | 活性污泥法 AOR/SOR · α-β 修正 · 碳化+硝化需氧 |
| [污泥产量](sludge-production-calculator.html) | 生物+化学+原生污泥 · 脱水前后体积 · 处置成本 |
| [加药量](dosing-calculator.html) | PAC/PAM/次氯酸钠/碳源/除磷/pH 调节 六大类药剂 |

### 设备选型 · Equipment

| 工具 | 说明 |
|------|------|
| [水泵选型](pump-selection-calculator.html) | 系统扬程 / 轴功率 / NPSH 校核 / 并联变频 |

### 基础换算 · Utilities

| 工具 | 说明 |
|------|------|
| [水质单位换算](water-quality-unit-converter.html) | 硬度/碱度/pH/氮磷/电导/通用离子 六大模块实时联动 |

## 🚀 本地运行

```bash
git clone https://github.com/<your-username>/waterkit.git
cd waterkit
# 双击 index.html 即可,无需任何构建或依赖
```

或者使用任意静态文件服务器:

```bash
# Python
python -m http.server 8000

# Node.js
npx serve .

# 然后访问 http://localhost:8000
```

## 📋 技术说明

- 纯原生 HTML + CSS + JavaScript,**零依赖**
- 所有计算在浏览器端完成,不上传数据
- 支持离线使用,下载后断网可用
- 响应式设计,适配桌面与手机

## 📖 引用规范

本工具计算基于以下现行国家/行业标准:

- **GB 50013** 室外给水设计标准
- **GB 50014** 室外排水设计标准
- **HJ 576** 厌氧-缺氧-好氧活性污泥法污水处理工程技术规范
- **GB 18918** 城镇污水处理厂污染物排放标准
- **GB 5749** 生活饮用水卫生标准
- 《给水排水设计手册》第 1-11 册
- Metcalf & Eddy《Wastewater Engineering: Treatment and Resource Recovery》

## ⚠️ 免责声明

本工具为工程方案阶段估算与参考使用,**实际工程设计须按相关规范进行详细计算,并由注册工程师复核**。开发者不对因使用本工具造成的任何直接或间接损失承担责任。

## 🤝 贡献

欢迎提 Issue 报告计算错误、建议新工具或改进用户体验。

想贡献新工具?请在 [Issues](../../issues) 开一个讨论说明想做的工具类型和计算依据,我们一起评估。

## 📄 License

本项目采用 **GNU Affero General Public License v3.0 (AGPL-3.0)** 开源许可证。

这意味着:

- ✅ **可自由使用、修改、分发** — 包括商业用途
- ⚠️ **必须开源衍生作品** — 任何基于本项目的修改版(包括通过网络提供服务的 SaaS)必须以相同 AGPL-3.0 协议开源
- 📝 **必须保留版权声明** — 分发时需保留原作者信息与本许可证
- 🌐 **网络使用也受约束** — 将本项目修改后部署为在线服务(如搭建自己的水处理计算网站),同样需要向用户提供修改后的完整源代码

完整协议内容见 [LICENSE](LICENSE) 文件或 <https://www.gnu.org/licenses/agpl-3.0.html>

> 如需商业授权(例如闭源集成到私有系统中),请通过 [登登科技官网](https://dengdengtech.cn) 联系商务合作。

© 2026 海南登登科技咨询有限公司 Hainan Dengdeng Technology Consulting Co., Ltd.

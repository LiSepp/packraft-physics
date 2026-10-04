# Packraft Physics Lab｜论文目录与阅读路线

原路线更新：2026-10-04；仓库索引整理：2026-10-04。

整理依据：本地资料库根目录中的 `README_阅读路线.md`，收录其论文表中的全部 24 篇 PDF。以下分类、题名展示名、年份、阅读优先级、“对 packraft 的价值与边界”和建议阅读顺序均沿用原路线；新增 source_id、引用定位和文件 SHA-256。本次未研究具体物理结论，也未将阅读建议转成已核实主张。

## 使用与本地定位

- source_id 的分配与引用规则见[来源索引](index.md)。本文件的 `src-001`～`src-024` 锚点保持稳定。
- PDF 本体保留在仓库外。每条“本地 PDF”都是相对于个人论文资料库根目录的路径，保留原分类目录和原文件名；换设备时只需定位资料库根目录，不修改 source_id。路径不是仓库内下载链接。
- 本次已核对 24 个路径均存在，并记录各自 SHA-256；尚未建立与 `C-...` 主张的证据关联。
- 原路线记载依据 PDF 首页、摘要和相关结论整理。本次未重新查阅论文内容；题名展示名、作者标签、年份及阅读评价均为原路线信息，部分题名为简称，完整书目信息待原文核对。
- S/A/B/C 是阅读收益排序，不代表论文质量或证据强度。S：优先精读；A：下一轮重点读；B：先看摘要、图和结论；C：需要时查。A（选读）保留原标记。

## 分类目录

| 分类目录（相对资料库根目录） | 解决的问题（原路线） | 篇数 |
|---|---|---:|
| `01_桨叶推进与划桨力学` | 桨叶怎样受力；一桨的力随时间怎样变化 | 3 |
| `02_艇体水动力与性能` | 阻力、速度、稳定性、转弯；充气艇与柔性结构的对照 | 7 |
| `03_激流回旋与控船` | 选线、上水门、回旋技术及其证据 | 3 |
| `04_白水河流流体力学` | 回流、剪切层、水跃、波列、河床湍流 | 7 |
| `05_人体生物力学与训练` | 人、桨、艇协同的总览 | 1 |
| `90_低优先级或参考` | 特定竞速桨技术、测量方法及迁移距离较远的模型 | 3 |

## 每篇论文与迁移价值

### 01｜桨叶推进与划桨力学

#### SRC-001

- source_id：`SRC-001`
- 类型：论文
- 分类：`01_桨叶推进与划桨力学`
- 题名（原路线展示名）：Sea kayak paddles
- 作者标签（原路线）：Hémon
- 年份（原路线）：2018
- 阅读优先级：**S**
- 对 packraft 的价值与边界（原路线）：用桨周围水的惯性及阻力/升力解释“抓水”；研究的是海艇传统桨与现代桨，不能把效率排名照搬到白水桨。
- 本地 PDF：`01_桨叶推进与划桨力学/Hemon2018_Sea_Kayak_Paddles.pdf`
- 文件 SHA-256：`3b15a44433f404b58936526b70d875bfb7a0c58c5485fe798fab03586c862448`

#### SRC-002

- source_id：`SRC-002`
- 类型：论文
- 分类：`01_桨叶推进与划桨力学`
- 题名（原路线展示名）：Paddling Force Profiles
- 作者标签（原路线）：Gomes
- 年份（原路线）：2015
- 阅读优先级：**A**
- 对 packraft 的价值与边界（原路线）：看不同桨频下的力—时间曲线，理解有效发力阶段；样本是精英静水竞速桨手。
- 本地 PDF：`01_桨叶推进与划桨力学/Gomes2015_Paddling_Force_Profiles.pdf`
- 文件 SHA-256：`b2ac167bc40429a0c1c641b7557f994dad3120444ce2060e470ef3e511c2c4e4`

#### SRC-003

- source_id：`SRC-003`
- 类型：论文
- 分类：`01_桨叶推进与划桨力学`
- 题名（原路线展示名）：Kayak blade–hull interactions
- 作者标签（原路线）：Banks
- 年份（原路线）：2014
- 阅读优先级：**B**
- 对 packraft 的价值与边界（原路线）：提醒桨与艇体流场相互影响；计算对象是竞速艇，文中的小幅阻力差不是 packraft 实测。
- 本地 PDF：`01_桨叶推进与划桨力学/Kayak blade–hull interactions - A body force approach for self-propelled simulations.pdf`
- 文件 SHA-256：`15c7d04e503b2fdd271ce3e382137fecacd35c7606802ddec43bd7a157e2cf8b`

### 02｜艇体水动力与性能

#### SRC-004

- source_id：`SRC-004`
- 类型：论文
- 分类：`02_艇体水动力与性能`
- 题名（原路线展示名）：Performance prediction for Olympic kayaks
- 作者标签（原路线）：Jackson
- 年份（原路线）：1995
- 阅读优先级：**A**
- 对 packraft 的价值与边界（原路线）：建立“桨效率—艇体阻力—功率—艇速”的预测链；参数属于奥运竞速艇。
- 本地 PDF：`02_艇体水动力与性能/Performance prediction for Olympic kayaks.pdf`
- 文件 SHA-256：`aa401496d9f2851ee8a8bf6eb3c447068e853bf10ef97e1fa9620cee88824ad6`

#### SRC-005

- source_id：`SRC-005`
- 类型：论文
- 分类：`02_艇体水动力与性能`
- 题名（原路线展示名）：On the Physics of Kayaking
- 作者标签（原路线）：Prétot 等
- 年份（原路线）：2022
- 阅读优先级：**S**
- 对 packraft 的价值与边界（原路线）：用实测桨力、放任减速和起步试验连接推力、阻力、加速度；模型是静水 K1。
- 本地 PDF：`02_艇体水动力与性能/论皮划艇运动的物理学-english.pdf`
- 文件 SHA-256：`5aab1fb1184fadad2a8ad7ec8de203d808d503888043f9ba747f46761a870701`

#### SRC-006

- source_id：`SRC-006`
- 类型：论文
- 分类：`02_艇体水动力与性能`
- 题名（原路线展示名）：Inflatable Kayak Evaluation Method
- 作者标签（原路线）：Ki
- 年份（原路线）：2012
- 阅读优先级：**B**
- 对 packraft 的价值与边界（原路线）：借鉴倾斜、转弯和阻力测试的设计，作为充气艇系列的方法篇；试验艇与背包船不同。
- 本地 PDF：`02_艇体水动力与性能/Ki2012_Inflatable_Kayak_Evaluation_Method.pdf`
- 文件 SHA-256：`84cce15e17d99b81a3ae9f692ada72077de8285eca24574ffd76a20c2eea6992`

#### SRC-007

- source_id：`SRC-007`
- 类型：论文
- 分类：`02_艇体水动力与性能`
- 题名（原路线展示名）：Inflatable Kayak Hydrodynamics
- 作者标签（原路线）：Hah
- 年份（原路线）：2013
- 阅读优先级：**B**
- 对 packraft 的价值与边界（原路线）：比较不同充气艇的稳性、转弯与阻力，帮助识别设计取舍；与 2015 篇有内容重叠。
- 本地 PDF：`02_艇体水动力与性能/Hah2013_Inflatable_Kayak_Hydrodynamics.pdf`
- 文件 SHA-256：`c113e7cdf4c4dd524259ffbecae533aa34cff2cf408371012015c548f062c531`

#### SRC-008

- source_id：`SRC-008`
- 类型：论文
- 分类：`02_艇体水动力与性能`
- 题名（原路线展示名）：New Inflatable Kayak Hydrodynamics
- 作者标签（原路线）：Hah 等
- 年份（原路线）：2015
- 阅读优先级：**S**
- 对 packraft 的价值与边界（原路线）：同一框架比较不同船底充气艇的稳性、转弯和阻力；只迁移比较方法，不迁移绝对数值。
- 本地 PDF：`02_艇体水动力与性能/Hah2015_New_Inflatable_Kayak_Hydrodynamics.pdf`
- 文件 SHA-256：`a9eb409b5048edeff05219f8a4ff34ec660eb423dc8f31f11753e17ddaabb8c0`

#### SRC-009

- source_id：`SRC-009`
- 类型：论文
- 分类：`02_艇体水动力与性能`
- 题名（原路线展示名）：Hydroelastic Inflatable Boats
- 作者标签（原路线）：Halswell 等
- 年份（原路线）：2012
- 阅读优先级：**A（选读）**
- 对 packraft 的价值与边界（原路线）：补充“艇体变形与水动力相互影响”的水弹性框架；对象为机动滑行救生艇，不能据此证明背包船更软就更快、更稳或冲击更小。
- 本地 PDF：`02_艇体水动力与性能/Hydroelastic Inflatable Boats: Relevant Literature and New Design Considerations.pdf`
- 文件 SHA-256：`7234acea15b1ee2b0ccd86e4de3c63835eb7e6f8f48c8c5287e00cf589344340`

#### SRC-010

- source_id：`SRC-010`
- 类型：论文
- 分类：`02_艇体水动力与性能`
- 题名（原路线展示名）：Flexibility and Environmental Considerations
- 作者标签（原路线）：Halswell 等
- 年份（原路线）：2011
- 阅读优先级：**B**
- 对 packraft 的价值与边界（原路线）：同一团队的早期会议论文，柔性、船底变形与砰击内容和 2012 篇高度重叠；看摘要与结构图即可，发动机噪声部分当前可跳过。
- 本地 PDF：`02_艇体水动力与性能/Design and Performance of Inflatable Boats: Flexibility and Environmental Considerations.pdf`
- 文件 SHA-256：`7c5e5c65266acfc2d57e5917eb8ddf5383e100348e80de6a0080267ff43122b5`

### 03｜激流回旋与控船

#### SRC-011

- source_id：`SRC-011`
- 类型：论文
- 分类：`03_激流回旋与控船`
- 题名（原路线展示名）：Upstream Gate Trajectory
- 作者标签（原路线）：Hunter
- 年份（原路线）：2009
- 阅读优先级：**S**
- 对 packraft 的价值与边界（原路线）：用上水门轨迹分析选线与耗时，能启发进回水路径；**没有直接测量 eddy line 的流场**。
- 本地 PDF：`03_激流回旋与控船/Hunter2009_Upstream_Gate_Trajectory.pdf`
- 文件 SHA-256：`7663d17e2480e6bc312651a4951d5f21211bc1df830c23831eb92d688af672e0`

#### SRC-012

- source_id：`SRC-012`
- 类型：论文
- 分类：`03_激流回旋与控船`
- 题名（原路线展示名）：Canoe Slalom Review
- 作者标签（原路线）：Messias 等
- 年份（原路线）：2021
- 阅读优先级：**A**
- 对 packraft 的价值与边界（原路线）：快速找到回旋项目中机械、生理和技术证据及研究限制；不是具体控船动作的因果证明。
- 本地 PDF：`03_激流回旋与控船/Messias2021_Canoe_Slalom_Performance_Review.pdf`
- 文件 SHA-256：`a7021d8411558cba3684b3aff7184ce3e176fa7c502617a5c95864ac9ec8db8e`

#### SRC-013

- source_id：`SRC-013`
- 类型：论文
- 分类：`03_激流回旋与控船`
- 题名（原路线展示名）：Novel Paddle Stroke Analysis
- 作者标签（原路线）：Messias 等
- 年份（原路线）：2018
- 阅读优先级：**B**
- 对 packraft 的价值与边界（原路线）：了解精英回旋桨手的桨次与测力指标；系绳全力测试不等于真实过回水线。
- 本地 PDF：`03_激流回旋与控船/精英激流回旋皮划艇运动员的新型划桨动作分析：与力参数的关系-english.pdf`
- 文件 SHA-256：`b01087678d5eb78638c713ddaa4f210a5b6a90a3858dce388edc5a3ae5c1e8c9`

### 04｜白水河流流体力学

#### SRC-014

- source_id：`SRC-014`
- 类型：论文
- 分类：`04_白水河流流体力学`
- 题名（原路线展示名）：Lateral Cavity Mixing Interface
- 作者标签（原路线）：Mignot 等
- 年份（原路线）：2016
- 阅读优先级：**S**
- 对 packraft 的价值与边界（原路线）：看主流与侧向回流之间的剪切层和大尺度涡；水槽侧腔是回水的简化模型。
- 本地 PDF：`04_白水河流流体力学/Coherent turbulent structures at the mixing-interface of a square open-channel lateral cavity.pdf`
- 文件 SHA-256：`2c05ec050942156b70fab6a70ef2a31c45d6c0b02559377f604c786dbfdc9d67`

#### SRC-015

- source_id：`SRC-015`
- 类型：论文
- 分类：`04_白水河流流体力学`
- 题名（原路线展示名）：Crystal Rapid Hydraulic Jump
- 作者标签（原路线）：Kieffer
- 年份（原路线）：1985
- 阅读优先级：**S**
- 对 packraft 的价值与边界（原路线）：把天然急流大波、水跃和河道收缩放在同一案例中；个案不构成普遍行船规则。
- 本地 PDF：`04_白水河流流体力学/The 1983 Hydraulic Jump in Crystal Rapid - Implications for River-Running and Geomorphic Evolution in the Grand Canyon.pdf`
- 文件 SHA-256：`83c20b0dd0992c917d769ee8dea110caa35968dbd21a0c12d7d789e057178217`

#### SRC-016

- source_id：`SRC-016`
- 类型：论文
- 分类：`04_白水河流流体力学`
- 题名（原路线展示名）：Hydraulic Jumps Review
- 作者标签（原路线）：Chanson
- 年份（原路线）：2009
- 阅读优先级：**A**
- 对 packraft 的价值与边界（原路线）：区分起伏水跃、破碎水跃、滚水及掺气，建立浪和洞的概念框架。
- 本地 PDF：`04_白水河流流体力学/Current knowledge in hydraulic jumps and related phenomena. A survey of experimental results.pdf`
- 文件 SHA-256：`8569b879642a7700b5d252f41f21eb1c6589bb62744a9506e795864b340fbd40`

#### SRC-017

- source_id：`SRC-017`
- 类型：论文
- 分类：`04_白水河流流体力学`
- 题名（原路线展示名）：River Steps
- 作者标签（原路线）：Wyrick & Pasternack
- 年份（原路线）：2008
- 阅读优先级：**A**
- 对 packraft 的价值与边界（原路线）：理解同一落差随流量、淹没程度和河道几何变化而呈现不同水跃形态。
- 本地 PDF：`04_白水河流流体力学/Modeling energy dissipation and hydraulic jump regime responses to channel nonuniformity at river steps.pdf`
- 文件 SHA-256：`b8b9f3845525ac3a284e41214f0e88189534337d30227c581769d71e5e4bce9c`

#### SRC-018

- source_id：`SRC-018`
- 类型：论文
- 分类：`04_白水河流流体力学`
- 题名（原路线展示名）：Shallow Mixing Layer
- 作者标签（原路线）：Han 等
- 年份（原路线）：2017
- 阅读优先级：**A**
- 对 packraft 的价值与边界（原路线）：研究突然扩宽后的主流、回流及其边界，可接在 Mignot 后看；仍是理想化几何。
- 本地 PDF：`04_白水河流流体力学/Shallow Mixing Layer Downstream from a Sudden Expansion.pdf`
- 文件 SHA-256：`ebd31852220b24bbb2416a69991e3782fef6e1e20047960d39119fcecfac9857`

#### SRC-019

- source_id：`SRC-019`
- 类型：论文
- 分类：`04_白水河流流体力学`
- 题名（原路线展示名）：Submerged Boulder Arrays
- 作者标签（原路线）：Fang、Liu & Stoesser
- 年份（原路线）：2017
- 阅读优先级：**B**
- 对 packraft 的价值与边界（原路线）：帮助理解石块间距如何改变尾流及局部剪应力；固定水深、采用刚盖水面的大涡模拟，不能直接解释水位变化、水面浪洞或背包船停靠回水。
- 本地 PDF：`04_白水河流流体力学/Influence of Boulder Concentration on Turbulence and Sediment Transport in Open-Channel Flow Over Submerged Boulders.pdf`
- 文件 SHA-256：`41948a2a807722fdd64021fbd738914b21ccaedeab011c43be5d8d35b2126542`

#### SRC-020

- source_id：`SRC-020`
- 类型：论文
- 分类：`04_白水河流流体力学`
- 题名（原路线展示名）：Rough-bed Open-channel Flow
- 作者标签（原路线）：Cameron 等
- 年份（原路线）：2017
- 阅读优先级：**B**
- 对 packraft 的价值与边界（原路线）：提醒河床粗糙度和大尺度湍流会改变实际来流；当前控船学习先看图与结论。
- 本地 PDF：`04_白水河流流体力学/Very-large-scale motions in rough-bed open-channel flow.pdf`
- 文件 SHA-256：`c769a620816a104502c31c3b6d288e6e702dfb7e2e43d79b2b33b666f7c29929`

### 05｜人体生物力学与训练

#### SRC-021

- source_id：`SRC-021`
- 类型：论文
- 分类：`05_人体生物力学与训练`
- 题名（原路线展示名）：Determinants of Kayak Paddling Performance
- 作者标签（原路线）：Michael 等
- 年份（原路线）：2009
- 阅读优先级：**A**
- 对 packraft 的价值与边界（原路线）：把人、桨、艇与竞速表现串成知识地图；多是静水竞速证据。
- 本地 PDF：`05_人体生物力学与训练/Determinants of kayak paddling performance.pdf`
- 文件 SHA-256：`ff925bb6646cc3fdd2120709158c14a6fca442dd16065c1464c291b715e7e9e8`

### 90｜低优先级或参考

#### SRC-022

- source_id：`SRC-022`
- 类型：论文
- 分类：`90_低优先级或参考`
- 题名（原路线展示名）：Wing Paddle Technique
- 作者标签（原路线）：Kendal & Sanders
- 年份（原路线）：1992
- 阅读优先级：**C**
- 对 packraft 的价值与边界（原路线）：可看桨叶相对水的轨迹测量；翼桨和白水桨差异大，不按其动作练习。
- 本地 PDF：`90_低优先级或参考/The Technique of Elite Flatwater Kayak Paddlers Using the Wing Paddle.pdf`
- 文件 SHA-256：`c090f10915f18321605dbdf3ca63502e81d1a9023f6f64ebd0506456d091fd64`

#### SRC-023

- source_id：`SRC-023`
- 类型：论文
- 分类：`90_低优先级或参考`
- 题名（原路线展示名）：Instrumented Kayak Paddle
- 作者标签（原路线）：Helmer 等
- 年份（原路线）：2011
- 阅读优先级：**C**
- 对 packraft 的价值与边界（原路线）：若以后自制测力桨，可参考传感器布置；论文也说明单点压力并不能直接给出整桨力。
- 本地 PDF：`90_低优先级或参考/皮划艇桨的仪器化研究以探究桨叶:水的相互作用-english-Instrumentation-of-a-kayak-paddle-to-investigate-blade-_2011_Procedia-Engine.pdf`
- 文件 SHA-256：`ae1563e2fd53c13bf522ceab26d315d83b28765e138349d52b3491099461f261`

#### SRC-024

- source_id：`SRC-024`
- 类型：论文
- 分类：`90_低优先级或参考`
- 题名（原路线展示名）：Inflatable Boat Motion CFD
- 作者标签（原路线）：Aksoy & Kükner
- 年份（原路线）：2023
- 阅读优先级：**C**
- 对 packraft 的价值与边界（原路线）：自由水面 CFD 与惯性测量对照可作方法参考，但图 18 的工况是水滑道中的充气载具；忽略艇内空气作用与柔性变形，不补背包船水弹性或回水控船缺口。
- 本地 PDF：`90_低优先级或参考/Simulation of Inflatable Boat Motion with CFD on Free Surface Flows.pdf`
- 文件 SHA-256：`d09084f0c2365c48501589a6e924a448d71d42d56e8deca2acce0d11e5a7e63c`

## 建议阅读顺序（原路线，附 source_id）

1. **建立桨—船模型：**Hémon 2018（[SRC-001](#src-001)） → Prétot 2022（[SRC-005](#src-005)） → Jackson 1995（[SRC-004](#src-004)） → Gomes 2015（[SRC-002](#src-002)）。边读边画出“桨受力 → 身体传力 → 船加速 → 阻力让船减速”。
2. **把模型放到充气艇：**Hah 2015（[SRC-008](#src-008)） → Ki 2012（[SRC-006](#src-006)）/Hah 2013（[SRC-007](#src-007)） 的图表 → Halswell 2012（[SRC-009](#src-009)） 的结构、水弹性与砰击部分。前半段看稳性、阻力和转弯，后半段补“受水力后船形也会改变”的反馈；不要套用竞速艇或滑行救生艇的绝对数值。Halswell 2011（[SRC-010](#src-010)） 仅在需要早期背景或环境噪声议题时补读。
3. **理解主流与回水：**Mignot 2016（[SRC-014](#src-014)） → Han 2017（[SRC-018](#src-018)） → Hunter 2009（[SRC-011](#src-011)）。前两篇讲水流结构，Hunter 讲运动员选择的船轨迹；把两类证据分开。若想进一步理解石块群之间的尾流干扰，再插入 Fang 2017（[SRC-019](#src-019)） 的图 1、4、5。
4. **理解浪、洞与落差：**Kieffer 1985（[SRC-015](#src-015)） → Chanson 2009（[SRC-016](#src-016)） → Wyrick & Pasternack 2008（[SRC-017](#src-017)）。先看河流实例，再用综述补术语，最后看流量和几何条件如何改变水跃。
5. **按需补充：**Michael 2009（[SRC-021](#src-021)） 和 Messias 2021（[SRC-012](#src-012)） 用作索引；Banks（[SRC-003](#src-003)）、Messias 2018（[SRC-013](#src-013)）、Cameron 2017（[SRC-020](#src-020)） 看图和结论。Fang 2017（[SRC-019](#src-019)） 接在 Mignot/Han 之后看尾流图，重点辨认其“淹没石块、近河床”的研究范围；`90_` 暂不精读。

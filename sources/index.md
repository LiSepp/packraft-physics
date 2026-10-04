# 来源索引

资料应能被再次找到，并明确它能支持什么、不能支持什么。引用主张时使用稳定的 `source_id`；未查阅原文的资料须标明这一点。

## 编号与引用规则

- 所有来源使用 `SRC-三位数字`，本批为 `SRC-001`～`SRC-024`；按原阅读路线的论文表顺序首次分配。
- 编号一经分配不随分类、优先级、题名修订或文件改名而改变，也不因排序或删除而重新编号。停用的编号保留记录，不复用；未来新来源从 `SRC-025` 接续。
- 同一论文的重复 PDF 沿用同一编号；不同论文即使内容重叠也保留各自编号。文件 SHA-256 用于识别本次本地 PDF，不能单独证明版本关系。
- 在 `knowledge/claims.md` 的“证据与来源”中引用编号，并在实际研究时补充原文页码、章节、图表及对应证据。来源收录不表示任何主张已获支持或核实。

引用格式示例（仅展示格式，未建立或修改主张）：

```markdown
- 证据与来源：[SRC-001](../sources/reading-route.md#src-001)；原文定位：待查；对应证据：待查。
```

引用链：`knowledge/claims.md` 中的主张 → `source_id` → 本索引 → 阅读路线的来源记录 → 本地 PDF 相对路径及 SHA-256。

## 本批来源

整理日期：2026-10-04。依据本地 `README_阅读路线.md`（《Packraft Physics Lab｜论文目录与阅读路线》，更新于 2026-10-04），仅收录其中 24 篇实际 PDF。原路线记载曾查阅首页、摘要和相关结论；本次只整理已有资料、核对文件存在和计算文件标识，未重新阅读或核实论文内容。

题名沿用原路线展示名，其中部分为简称；年份和作者标签也沿用原路线，完整书目信息与 DOI 未在本次补充核验。分类、价值与边界、阅读顺序及本地文件定位见[阅读路线](reading-route.md)。

S/A/B/C 表示对理解背包船推进、控船和白水的阅读收益排序，不代表论文质量或证据强度。S：优先精读；A：下一轮重点读；B：先看摘要、图和结论；C：需要时查。`A（选读）` 保留原标记。

| source_id | 类别 | 论文题名（原路线展示名） | 作者标签 | 年份 | 优先级 |
|---|---|---|---|---:|---|
| [SRC-001](reading-route.md#src-001) | 01 桨叶推进与划桨力学 | Sea kayak paddles | Hémon | 2018 | S |
| [SRC-002](reading-route.md#src-002) | 01 桨叶推进与划桨力学 | Paddling Force Profiles | Gomes | 2015 | A |
| [SRC-003](reading-route.md#src-003) | 01 桨叶推进与划桨力学 | Kayak blade–hull interactions | Banks | 2014 | B |
| [SRC-004](reading-route.md#src-004) | 02 艇体水动力与性能 | Performance prediction for Olympic kayaks | Jackson | 1995 | A |
| [SRC-005](reading-route.md#src-005) | 02 艇体水动力与性能 | On the Physics of Kayaking | Prétot 等 | 2022 | S |
| [SRC-006](reading-route.md#src-006) | 02 艇体水动力与性能 | Inflatable Kayak Evaluation Method | Ki | 2012 | B |
| [SRC-007](reading-route.md#src-007) | 02 艇体水动力与性能 | Inflatable Kayak Hydrodynamics | Hah | 2013 | B |
| [SRC-008](reading-route.md#src-008) | 02 艇体水动力与性能 | New Inflatable Kayak Hydrodynamics | Hah 等 | 2015 | S |
| [SRC-009](reading-route.md#src-009) | 02 艇体水动力与性能 | Hydroelastic Inflatable Boats | Halswell 等 | 2012 | A（选读） |
| [SRC-010](reading-route.md#src-010) | 02 艇体水动力与性能 | Flexibility and Environmental Considerations | Halswell 等 | 2011 | B |
| [SRC-011](reading-route.md#src-011) | 03 激流回旋与控船 | Upstream Gate Trajectory | Hunter | 2009 | S |
| [SRC-012](reading-route.md#src-012) | 03 激流回旋与控船 | Canoe Slalom Review | Messias 等 | 2021 | A |
| [SRC-013](reading-route.md#src-013) | 03 激流回旋与控船 | Novel Paddle Stroke Analysis | Messias 等 | 2018 | B |
| [SRC-014](reading-route.md#src-014) | 04 白水河流流体力学 | Lateral Cavity Mixing Interface | Mignot 等 | 2016 | S |
| [SRC-015](reading-route.md#src-015) | 04 白水河流流体力学 | Crystal Rapid Hydraulic Jump | Kieffer | 1985 | S |
| [SRC-016](reading-route.md#src-016) | 04 白水河流流体力学 | Hydraulic Jumps Review | Chanson | 2009 | A |
| [SRC-017](reading-route.md#src-017) | 04 白水河流流体力学 | River Steps | Wyrick & Pasternack | 2008 | A |
| [SRC-018](reading-route.md#src-018) | 04 白水河流流体力学 | Shallow Mixing Layer | Han 等 | 2017 | A |
| [SRC-019](reading-route.md#src-019) | 04 白水河流流体力学 | Submerged Boulder Arrays | Fang、Liu & Stoesser | 2017 | B |
| [SRC-020](reading-route.md#src-020) | 04 白水河流流体力学 | Rough-bed Open-channel Flow | Cameron 等 | 2017 | B |
| [SRC-021](reading-route.md#src-021) | 05 人体生物力学与训练 | Determinants of Kayak Paddling Performance | Michael 等 | 2009 | A |
| [SRC-022](reading-route.md#src-022) | 90 低优先级或参考 | Wing Paddle Technique | Kendal & Sanders | 1992 | C |
| [SRC-023](reading-route.md#src-023) | 90 低优先级或参考 | Instrumented Kayak Paddle | Helmer 等 | 2011 | C |
| [SRC-024](reading-route.md#src-024) | 90 低优先级或参考 | Inflatable Boat Motion CFD | Aksoy & Kükner | 2023 | C |

合计 24 篇：S 6、A 8（含选读）、B 7、C 3。

## 新来源记录模板

```markdown
### SRC-025

- source_id：SRC-025
- 类型：论文 / 教材 / 书籍 / 专业教学资料 / 厂商资料 / 网页 / 其他
- 题名：
- 作者或机构：
- 发表年份、日期或版本：
- 分类与阅读优先级：
- 出版信息及定位：出版方、页码或章节等；未核对则注明。
- 链接或标识：DOI / ISBN / URL / 本地资料相对路径；未核对则注明。
- 查阅日期及范围：是否查阅原文；查阅了哪些部分。
- 对 packraft 的价值与边界：
- 与项目主张的关系：实际研究后填写 `C-...` 编号；尚未关联则注明。
- 可靠性与局限：资料性质、方法或利益关系等需要注意的因素。
```

<!-- ELUCENIA technical documentation · ipss · zh · no clinical/professional/rights approval -->

# IPSS（国际前列腺症状评分）

[条件、来源与许可](https://elucenia.org/zh/tools/ipss)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 排尿不尽：感觉膀胱未完全排空

`esvaz`

- `0` — 从未
- `1` — 每5次中少于1次
- `2` — 少于一半次数
- `3` — 约一半次数
- `4` — 超过一半次数
- `5` — 几乎总是

### 尿频：不足 2 小时后需再次排尿

`freq`

- `0` — 从未
- `1` — 每5次中少于1次
- `2` — 少于一半次数
- `3` — 约一半次数
- `4` — 超过一半次数
- `5` — 几乎总是

### 尿流间断：尿流多次停止并重新开始

`inter`

- `0` — 从未
- `1` — 每5次中少于1次
- `2` — 少于一半次数
- `3` — 约一半次数
- `4` — 超过一半次数
- `5` — 几乎总是

### 尿急：难以忍住尿意

`urg`

- `0` — 从未
- `1` — 每5次中少于1次
- `2` — 少于一半次数
- `3` — 约一半次数
- `4` — 超过一半次数
- `5` — 几乎总是

### 尿流细弱

`jato`

- `0` — 从未
- `1` — 每5次中少于1次
- `2` — 少于一半次数
- `3` — 约一半次数
- `4` — 超过一半次数
- `5` — 几乎总是

### 排尿费力：需用力才能开始排尿

`esforco`

- `0` — 从未
- `1` — 每5次中少于1次
- `2` — 少于一半次数
- `3` — 约一半次数
- `4` — 超过一半次数
- `5` — 几乎总是

### 夜尿：夜间起床排尿次数

`noct`

- `0` — 无
- `1` — 1 次
- `2` — 2 次
- `3` — 3 次
- `4` — 4 次
- `5` — 5次或以上

## 方法版本

AUASI/Barry 1992，IPSS 7项0–5，总分0–35；第8项生活质量单独记录

## 已记录的公式

针对最近一个月的七个问题，每项0至5分。总分0至35。

第8项（生活质量，从0“非常满意”到6“非常糟糕”）单独记录，不计入总分。

## 限制与适用人群

IPSS/AUA量化泌尿症状及其变化，但总分不能确定病因是良性前列腺增生。原始验证包括良性前列腺增生患者和对照。题目措辞、时间窗口、生活质量及语言版本的限制须保留，并分别核验。

## 参考文献

- [Barry MJ et al. The American Urological Association symptom index for benign prostatic hyperplasia. J Urol, 1992.](https://doi.org/10.1016/S0022-5347(17)36966-5)

- [Lerner LB et al. Management of lower urinary tract symptoms attributed to benign prostatic hyperplasia: AUA guideline part I, initial work-up and medical management. J Urol, 2021.](https://doi.org/10.1097/JU.0000000000002183)

## 复现技术测试

在此仓库的根目录中运行 node test.cjs，以重复已记录的合成案例。原始输入、预期结果和容差保持不变。技术测试不构成临床验证。

```sh
node test.cjs
```

tool.json 包含来源、版本和审查范围。examples.json 保留合成输入与预期结果；results.json 记录实际得到的结果。

[记录与参考文献](../tool.json) · [JavaScript代码](../calculator.js) · [参考案例](../examples.json) · [results.json](../results.json)

## 审查与使用条件

尚未开展独立临床审查。

此界面为自主编写的翻译，并非官方或认证版本。尚未完成独立临床审查、专业语言审查或工具权利授权。

公式或分类结果。解释、处理及适用性须结合专业评估和所选来源。

## 许可与署名

Apache-2.0 仅适用于 ELUCENIA 代码。工具、出版物、翻译和数据的权利仍归各自权利人所有。请保留 LICENSE 和 NOTICE。

ELUCENIA · Felipe Guedes · Copyright © 2026

## 已记录的结果

以下信息保留该方法对合成示例的输出，不构成独立的临床验证。

### 1

轻度症状（0 到 7）

一般而言，密切观察和行为指导。


### 2

中度症状（8 到 19）

根据困扰程度考虑药物治疗。


### 3

重度症状（20 到 35）

评估联合药物治疗或手术治疗。


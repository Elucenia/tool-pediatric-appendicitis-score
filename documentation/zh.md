<!-- ELUCENIA technical documentation · pediatric-appendicitis-score · zh · no clinical/professional/rights approval -->

# 儿童阑尾炎评分（PAS）

[条件、来源与许可](https://elucenia.org/zh/tools/pediatric-appendicitis-score)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 咳嗽、叩诊或跳跃时右髂窝疼痛

`tosse`

### 右髂窝压痛

`fid`

### 食欲减退

`anorexia`

### 发热（\> 38 °C）

`febre`

### 恶心或呕吐

`nausea`

### 疼痛迁移至右髂窝

`migra`

### 白细胞增多（\> 10000/mm³）

`leuco`

### 中性粒细胞增多（中性粒细胞 \> 7500/mm³）

`neut`

## 方法版本

PAS/Samuel 2002：8因素、0–10；非Alvarado或pARC

## 已记录的公式

2分：咳嗽、叩诊或跳跃时右髂窝疼痛；右髂窝压痛。1分：食欲减退、发热、恶心/呕吐、疼痛转移、白细胞增多及中性粒细胞增多。总分0至10。

## 限制与适用人群

Samuel（2002）的原始PAS是在4–15岁儿童中建立的。Goldman（2008）的验证研究纳入了1–17岁、腹痛持续不足7天的儿童；排除了既往接受过阑尾切除术者，以及到院时已通过超声或计算机断层扫描确诊阑尾炎者。对于尚不能表达自身症状的儿童，评估主观症状时须谨慎。本评分不是pARC，也不能单独决定诊断、出院、影像检查或手术。

## 参考文献

- [Samuel M. Pediatric appendicitis score. J Pediatr Surg, 2002.](https://doi.org/10.1053/jpsu.2002.32893)

- [Goldman RD et al. Prospective validation of the pediatric appendicitis score. J Pediatr, 2008.](https://doi.org/10.1016/j.jpeds.2008.01.033)

- [Samuel2002;DOI10.1053/jpsu.2002.32893](https://pubmed.ncbi.nlm.nih.gov/12037754/)

- [Goldman2008;DOI10.1016/j.jpeds.2008.01.033](https://emergency.med.ufl.edu/files/2013/02/prospective-validation-of-pediatric-appendicitis-score.pdf)

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

阑尾炎概率低（≤ 2）

在 Goldman 验证研究（2008）中，只有 2.4% 的阑尾炎儿童 PAS ≤ 2：可出院并告知返院指征。


### 2

中等概率（3 到 6）

进一步检查：观察并进行连续复评和超声检查（如超声检查结果不明确，则行 CT）。


### 3

阑尾炎高概率（≥ 7）

由儿科外科医生评估；在验证中，PAS ≥ 7 的手术患者中只有 4% 实际上没有阑尾炎。


### 4

阑尾炎高概率（≥ 7）

由儿科外科医生评估；在验证中，PAS ≥ 7 的手术患者中只有 4% 实际上没有阑尾炎。


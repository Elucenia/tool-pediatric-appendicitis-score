<!-- ELUCENIA technical documentation · pediatric-appendicitis-score · ja · no clinical/professional/rights approval -->

# 小児虫垂炎スコア（PAS）

[条件・出典・許諾](https://elucenia.org/ja/tools/pediatric-appendicitis-score)

## 使い方

ポータルでツールを使用するか、ローカルHTTPサーバー経由でindex.htmlを開いてください。言語を選択し、項目を入力して計算してください。

## 入力項目と単位

### 咳・打診・跳躍で右腸骨窩痛

`tosse`

### 右下腹部圧痛

`fid`

### 食欲不振

`anorexia`

### 発熱（\> 38 °C）

`febre`

### 悪心または嘔吐

`nausea`

### 右下腹部への疼痛移動

`migra`

### 白血球増多（\> 10000/mm³）

`leuco`

### 好中球増多（好中球 \> 7500/mm³）

`neut`

## 方法の版

PAS/Samuel 2002：8因子、0～10、Alvarado・pARCとは別

## 記載された計算式

2点：咳・打診・跳躍時の右下腹部痛、右下腹部圧痛。1点：食欲不振、発熱、悪心/嘔吐、疼痛移動、白血球増多、好中球増多。合計0～10。

## 限界・対象集団

Samuel（2002）の原版PASは4–15歳の小児から導出されました。Goldman（2008）の妥当性検証研究では、腹痛の持続期間が7日未満の1–17歳の小児を対象とし、虫垂切除の既往がある小児と、来院時に超音波検査またはCTで虫垂炎の診断が既に確立していた小児を除外しました。まだ症状を伝えられない小児では、主観的症状の評価に注意が必要です。このスコアはpARCではなく、それだけで診断、退院、画像検査、手術を決定するものではありません。

## 参考文献

- [Samuel M. Pediatric appendicitis score. J Pediatr Surg, 2002.](https://doi.org/10.1053/jpsu.2002.32893)

- [Goldman RD et al. Prospective validation of the pediatric appendicitis score. J Pediatr, 2008.](https://doi.org/10.1016/j.jpeds.2008.01.033)

- [Samuel2002;DOI10.1053/jpsu.2002.32893](https://pubmed.ncbi.nlm.nih.gov/12037754/)

- [Goldman2008;DOI10.1016/j.jpeds.2008.01.033](https://emergency.med.ufl.edu/files/2013/02/prospective-validation-of-pediatric-appendicitis-score.pdf)

## 技術テストの再現

このリポジトリのルートディレクトリでnode test.cjsを実行すると、記録された合成ケースを再実行できます。元の入力、期待結果、許容誤差は保持されています。技術テストは臨床的検証を意味しません。

```sh
node test.cjs
```

tool.jsonには出典、版、確認範囲が記録されています。examples.jsonには合成入力と期待結果が保持され、results.jsonには実際に得られた結果が記録されています。

[記録・参考文献](../tool.json) · [JavaScriptコード](../calculator.js) · [参照ケース](../examples.json) · [results.json](../results.json)

## 確認状況と使用条件

独立した臨床レビューは実施されていません。

このインターフェースは独自に作成した翻訳であり、公式版や認証済みの版ではありません。独立した臨床レビュー、専門家による言語レビュー、評価尺度等の権利許諾の確認は実施されていません。

式または分類の結果です。解釈、対応、適用可能性は専門家による評価と選択した出典に依存します。

## ライセンスと帰属表示

Apache-2.0はELUCENIAのコードにのみ適用されます。評価尺度等、出版物、翻訳、データの権利は、それぞれの権利者に帰属します。LICENSEとNOTICEを保持してください。

ELUCENIA · Felipe Guedes · Copyright © 2026

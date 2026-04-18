# Medical Academic English Trainer

医学研究者・臨床医のための学術英語トレーニング教材（Web App） — 英文ライティングの基礎から、IMRaD形式に準拠した論文執筆、国際学会での口頭・ポスター発表、セッション座長としての進行、救急診療でのケースプレゼンテーションまでを、日英対訳と練習問題で体系的に学べるインタラクティブ教材。

## Overview

日本の医療者・研究者の多くは、英語を義務教育で学んではいても、英語で学術的な文章を構成したり、国際学会で発表・質疑応答したりする体系的なトレーニングを受ける機会が限られています。本教材は、そうしたギャップを埋めることを目的として作成されました。

以下の点を特徴としています：

- **英文ライティングの基礎から専門表現まで** — パラグラフ構成・文の組み立て・語彙選択といったライティング基本作法と、医学領域特有の定型表現の両方をカバー
- **国際的な報告ガイドライン・スタイルガイドに準拠** — ICMJE、EQUATOR Network（CONSORT / STROBE / PRISMA 等）、AMA Manual of Style などを参照
- **国際学会での座長（Session Chair）としての英語表現** — セッション開始の挨拶、演者の紹介、時間管理、質疑応答の促進、議論のまとめ、トラブル対応、セッション終了まで、日本人が座長を担う際に必要な表現を網羅
- **救急・集中治療領域に特化した章** — Primary Assessment（ABCDE）、Secondary Assessment、Disposition を明示するケースプレゼンテーションの構造を提示
- **日本人研究者が陥りやすい間違いへの対応** — 和製英語・ドイツ語由来の医療用語・発音の誤りなど、日本独特の問題を整理
- **日英対訳とインタラクティブなクイズ** — 受動的な学習ではなく、選択式クイズで理解度を確認
- **シングルHTMLファイル** — 外部依存なし、ブラウザで開くだけで動作

## Features

| セクション | 内容 |
|---|---|
| **英文の基本 Basics** | パラグラフ構成（One Paragraph, One Idea）、文の組み立て、冗長さの排除、語彙のレジスター、略語のルール、数字・単位の表記 |
| **論文執筆 Writing** | IMRaD形式に沿った各セクション（Title/Abstract, Introduction, Methods, Results, Discussion, Cover Letter）の定型表現、報告ガイドライン（CONSORT/STROBE/PRISMA 等）、PICO/PECO |
| **学会発表 Presentation** | 口頭発表、ポスター発表、質疑応答、座長（Session Chair）、救急ケースプレゼンテーション（Stability → Primary/Secondary Assessment → Disposition）の表現 |
| **学術文法 Grammar** | 時制、能動態/受動態、Hedging、日本人研究者がよくする間違い、北米英語/英国英語の違い（スペル・用語・句読法） |
| **専門語彙 Vocabulary** | 研究デザイン、統計用語、接続表現、査読対応、和製英語・ドイツ語由来の医療用語、発音に注意すべき医学英語 |
| **練習問題 Quiz** | 各セクションに対応した選択式クイズ（ランダム出題、即時フィードバック） |

## Usage

### ローカルで開く

```bash
open index.html
```

ブラウザで `index.html` を直接開くだけで使用できます。サーバーやビルドツールは不要です。

### GitHub Pages で公開する

1. このリポジトリを GitHub にプッシュ
2. Settings → Pages → Source を `main` ブランチ、`/ (root)` に設定
3. `https://<username>.github.io/<repository-name>/` でアクセス可能

## File Structure

```
academic-english/
├── index.html    # アプリ本体（HTML/CSS/JS 単一ファイル）
├── README.md     # このファイル
└── LICENSE       # CC BY-NC-ND 4.0
```

## Technology

- HTML5 / CSS3 / Vanilla JavaScript
- 外部ライブラリ・フレームワーク不使用
- レスポンシブ対応（モバイル・タブレット・デスクトップ）

## References

本教材で言及しているガイドライン・基準の主な出典：

- **ICMJE** — International Committee of Medical Journal Editors. *Recommendations for the Conduct, Reporting, Editing, and Publication of Scholarly Work in Medical Journals.* Updated December 2023.
- **CONSORT** — Schulz KF, et al. CONSORT 2010 statement. *BMJ.* 2010;340:c332.
- **STROBE** — von Elm E, et al. The STROBE statement. *Lancet.* 2007;370(9596):1453-1457.
- **PRISMA** — Page MJ, et al. The PRISMA 2020 statement. *BMJ.* 2021;372:n71.
- **AMA Manual of Style** — 11th ed. Oxford University Press; 2020.
- **GCS** — Teasdale G, Jennett B. *Lancet.* 1974;2(7872):81-84.
- **ABCDEアプローチ** — Thim T, et al. *Int J Gen Med.* 2012;5:117-121; Resuscitation Council UK.

全参考文献はアプリ内フッターの「参考文献・出典」セクションに記載しています。

## Disclaimer

- 本教材のフレーズ・例文はすべてオリジナルに作成した汎用的な学術定型表現です
- 症例・データはすべて架空であり、実在の患者情報は含まれていません
- 本教材は言語学習を目的としており、臨床判断の根拠として使用しないでください

## AI Assistance

本教材の作成にあたり、生成AI（Claude, Anthropic）を活用しました。

## Contributing

Issue や Pull Request を歓迎します。

## License

© 2026 Shunichiro Nakao. Licensed under [CC BY-NC-ND 4.0](LICENSE).

Creative Commons 表示-非営利-改変禁止 4.0 国際ライセンス。教育目的での利用・共有は自由です。改変および商用利用はできません。

詳細: https://creativecommons.org/licenses/by-nc-nd/4.0/deed.ja

## Author

Shunichiro Nakao, MD, MSc, PhD  
Department of Traumatology and Acute Critical Medicine, The University of Osaka

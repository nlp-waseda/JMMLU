# JMMLU
日本語マルチタスク言語理解ベンチマーク Japanese Massive Multitask Language Understanding Benchmark

日本語🇯🇵 | [English🇬🇧](readme_en.md) | [中文🇨🇳](readme_ch.md)

JMMLUは、マルチタスク言語理解ベンチマークMMLU ([Paper](https://arxiv.org/abs/2009.03300), [Github](https://github.com/hendrycks/test))の一部を日本語に翻訳した問題(翻訳問題)、および、日本独自の文化的背景に基づく問題(日本問題)によって構成される4択問題である。大規模言語モデルの日本語能力の評価に用いられることを想定している。

翻訳問題は、MMLUの57タスク(科目)のそれぞれから最大150問を選択し、まず日本語に機械翻訳した。次に、翻訳者が機械翻訳結果を確認することによって、翻訳しにくい、もしくは、日本の文化と無関係または矛盾する問題やタスクを削除した。また、残った問題について、自然な日本語になるように修正した。

日本問題は、公民、日本史などの学校教科に基づく問題であり、日本人によって人手で作成されている。

フォーマットは、MMLUの形式と同じCSVで、

```
問題, 選択肢A, 選択肢B, 選択肢C, 選択肢D, 正解
```
である。

JMMLUは以下の56タスク(科目)、7,536問からなる。そのうち、CC BY-SA 4.0 ライセンスの53タスク、7,097問は JMMLUフォルダに、CC BY-NC-ND 4.0 ライセンスの3タスク 439問はJMMLU_NC_NDフォルダにある。

| タスク名 | 英語タスク名 | 件数 |
|---|---|---:|
| 専門医学         | professional_medicine        | 150 |
| 専門心理学        | professional_psychology      | 150 |
| 専門会計         | professional_accounting      | 150 |
| 哲学           | philosophy                   | 150 |
| 雑学           | miscellaneous                | 150 |
| 医学遺伝学        | medical_genetics             | 99  |
| 形式論理         | formal_logic                 | 125 |
| 先史学          | prehistory                   | 150 |
| 天文学          | astronomy                    | 148 |
| 熟語           | japanese_idiom               | 150 |
| 世界宗教         | world_religions              | 147 |
| 世界事実         | global_facts                 | 97  |
| 世界史          | world_history                | 150 |
| 社会学          | sociology                    | 150 |
| 栄養学          | nutrition                    | 149 |
| 日本史          | japanese_history             | 150 |
| 日本地理         | japanese_geography           | 139 |
| 人間の老化        | human_aging                  | 150 |
| 論理学          | logical_fallacies            | 150 |
| 倫理的議論        | moral_disputes               | 148 |
| 臨床知識         | clinical_knowledge           | 150 |
| 経営学          | management                   | 102 |
| 解剖学          | anatomy                      | 132 |
| 計量経済学        | econometrics                 | 113 |
| 機械学習         | machine_learning             | 111 |
| 国際法          | international_law            | 120 |
| 公民           | japanese_civics              | 150 |
| 公共関係         | public_relations             | 109 |
| 高校心理学        | high_school_psychology       | 150 |
| 高校物理         | high_school_physics          | 150 |
| 高校統計学        | high_school_statistics       | 150 |
| 高校数学         | high_school_mathematics      | 150 |
| 高校生物学        | high_school_biology          | 148 |
| 高校情報科学       | high_school_computer_science | 98  |
| 高校化学         | high_school_chemistry        | 149 |
| 高校地理         | high_school_geography        | 150 |
| 高校ヨーロッパ史     | high_school_european_history | 150 |
| 高校ミクロ経済学     | high_school_microeconomics   | 149 |
| 高校マクロ経済学     | high_school_macroeconomics   | 148 |
| 概念物理学        | conceptual_physics           | 150 |
| 法理学          | jurisprudence                | 107 |
| 電気工学         | electrical_engineering       | 144 |
| 大学医学         | college_medicine             | 150 |
| 大学物理         | college_physics              | 100 |
| 大学数学         | college_mathematics          | 99  |
| 大学生物学        | college_biology              | 143 |
| 大学化学         | college_chemistry            | 99  |
| 大学コンピュータ科学   | college_computer_science     | 99  |
| 初等数学         | elementary_mathematics       | 150 |
| 抽象代数         | abstract_algebra             | 99  |
| マーケティング      | marketing                    | 150 |
| ビジネス倫理       | business_ethics              | 86  |
| セクシュアリティ     | human_sexuality              | 130 |
| セキュリティ研究     | security_studies             | 150 |
| コンピュータセキュリティ | computer_security            | 99  |
| ウイルス学        | virology                     | 150 |


なお、日本史、世界史の著作権はステップ株式会社が保有するものであり、言語モデルの研究・評価以外の商業利用は禁止されている。

熟語、公民、日本地理の著作権はVIST学習塾が保有するものであり、ライセンスはCC BY-NC-ND 4.0である。ただし言語モデルの研究・評価における商業利用は許可されている。

Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
# 謝辞

本研究における翻訳に際し、理化学研究所からのご支援に深く感謝申し上げる。また、株式会社Stepには日本史及び社会史の内容提供について、VIST学習塾には熟語、公民、日本地理の提供について、心より御礼申し上げる。これらの支援がなければ、本研究の実施は困難であったことを認識し、関係各所のご協力に厚く謝意を表するものである。


# JMMLU v0.9
日本語マルチタスク言語理解ベンチマーク Japanese Multitask Language Understanding Benchmark

## 正式公開ではないためご注意ください
## ATTENTION: Not a formal version. May be changed in the future

JMMLUはMMLUの内容を日本語に翻訳したもの及び日本独自の文化的背景に基づく内容によって構成される。

MMLUの57タスクのそれぞれから最大150問を選択し、まず日本語に機械翻訳する。次に、翻訳者が機械翻訳結果を確認することによって、翻訳しにくい、もしくは、日本の文化と無関係または矛盾する問題やタスクを削除した。

残りの問題については自然な日本語になるように修正した。一方、追加したタスクは、欧米視点のMMLUにない公民、日本史などの学校教科に基づく問題である。

jaMMLU consists of two parts. 

Translation of MMLU: Professional translators first eliminated contents difficult to translate correctly then translated English into Japanese. Some questions or tasks that were clearly unrelated or conflicted with the Japanese cultural background are removed. 

Japanese school curricula questions: Mitigation for the western culture bias in MMLU. Contains Japanese, Japanese Civics, History and Japanese Geography.

Number of questions per task between 95 and 150.


| タスク名 | 英語名 | 件数 |
|---|---|---|
| 公共関係 | public_relations | 109 |
| 世界事実 | global_facts | 97 |
| 電気工学 | electrical_engineering | 144 |
| 天文学 | astronomy | 148 |
| ビジネス倫理 | business_ethics | 98 |
| 法理学 | jurisprudence | 107 |
| 高校化学 | high_school_chemistry | 150 |
| 大学物理 | college_physics | 101 |
| 専門心理学 | professional_psychology | 150 |
| マーケティング | marketing | 150 |
| 経営学 | management | 102 |
| ウイルス学 | virology | 150 |
| 国際法 | international_law | 120 |
| 高校マクロ経済学 | high_school_macroeconomics | 150 |
| 先史学 | prehistory | 150 |
| 抽象代数 | abstract_algebra | 99 |
| 高校物理 | high_school_physics | 150 |
| 形式論理 | formal_logic | 125 |
| 大学医学 | college_medicine | 150 |
| 倫理的議論 | moral_disputes | 150 |
| 高校ヨーロッパ史 | high_school_european_history | 150 |
| 臨床知識 | clinical_knowledge | 150 |
| 世界宗教 | world_religions | 147 |
| 高校ミクロ経済学 | high_school_microeconomics | 150 |
| 人間の老化 | human_aging | 150 |
| 医学遺伝学 | medical_genetics | 99 |
| 高校地理 | high_school_geography | 150 |
| 解剖学 | anatomy | 132 |
| 社会学 | sociology | 150 |
| 論理学 | logical_fallacies | 150 |
| 高校情報科学 | high_school_computer_science | 99 |
| 雑学 | miscellaneous | 150 |
| 世界史 | world_history | 150 |
|公民|japanese_civics|150|
|日本史|japanese_history|150|
|日本地理|japanese_geography|150|
|熟語|japanese_idiom|150|
| 専門医学 | professional_medicine | 150 |
| 高校生物学 | high_school_biology | 148 |
| 高校統計学 | high_school_statistics | 150 |
| 大学化学 | college_chemistry | 99 |
| 栄養学 | nutrition | 149 |
| 計量経済学 | econometrics | 113 |
| セクシュアリティ | human_sexuality | 130 |
| セキュリティ研究 | security_studies | 150 |
| 哲学 | philosophy | 150 |
| 初等数学 | elementary_mathematics | 150 |
| 大学生物学 | college_biology | 143 |
| 大学コンピュータ科学 | college_computer_science | 99 |
| 機械学習 | machine_learning | 111 |
| 専門会計 | professional_accounting | 150 |
| 大学数学 | college_mathematics | 99 |
| 高校数学 | high_school_mathematics | 150 |
| 高校心理学 | high_school_psychology | 150 |
| 概念物理学 | conceptual_physics | 150 |
| コンピュータセキュリティ | computer_security | 99 |


Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
# 謝辞

本研究における翻訳に際し、理化学研究所からのご支援に深く感謝申し上げます。また、株式会社Stepには日本史及び社会史の内容提供について、V-IST学習塾には熟語、公民、日本地理の提供について、心より御礼申し上げます。これらの支援がなければ、本研究の実施は困難であったことを認識し、関係各所のご協力に厚く謝意を表するものである。

このベンチマークをご利用になられた方はこの論文をご引用ください
## 論文のbibtex

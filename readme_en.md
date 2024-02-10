# JMMLU
Japanese Massive Multitask Language Understanding Benchmark


[日本語🇯🇵](README.md)　| English🇬🇧 | [中文🇨🇳](readme_ch.md)

JMMLU is a four-choice question set consisting of Japanese-translated questions of a portion of MMLU ([Paper](https://arxiv.org/abs/2009.03300), [Github](https://github.com/hendrycks/test)) (Translated questions) and questions based on unique Japanese cultural context (Japanese questions). It is designed to assess the performance of large language models in Japanese.

For the translated questions, a maximum of 150 questions from each of the 57 MMLU tasks (subjects) were selected and first machine-translated into Japanese. Next, the translators checked the machine translations and removed questions and tasks that were difficult to translate, irrelevant, or inconsistent with the Japanese culture. The remaining questions were modified to make them fluent.

The Japanese questions are based on school subjects, such as Japanese civics and history, and are manually created by Japanese teachers.

The format is the same as MMLU:
```
Question, Choice A, Choice B, Choice C, Choice D, Answer
```

The JMMLU consists of 7,536 questions in the following 56 tasks (subjects). There are 53 tasks and 7,097 questions in the JMMLU folder under the CC BY-SA 4.0 license and 3 tasks and 439 questions in the JMMLU_NC_ND folder under the CC BY-NC-ND 4.0 license.

| Japanese Task Name | English Task Name | Number |
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

The copyrights for Japanese and World History belongs to STEP Corporation. Commercial use other than for research and evaluation of language models is prohibited.

The copyrights for Japanese idioms, Japansese civics, and Japanese geography belong to New Style Cram School VIST and are licensed under CC BY-NC-ND 4.0. Commercial use is allowed only for research and evaluation of language models.

Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
# Acknowledgment
We express our gratitude to the RIKEN for their support in the translation of MMLU. We also acknowledge the contributions from Step Corporation, who provided materials on Japanese and World History, and from New Style Cram School VIST, who supplied resources on japanese_idioms, japansese_civics, and japanese_geography.



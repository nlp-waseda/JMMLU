
# JMMLU
日语多任务语言理解基准测试

[日本語🇯🇵](README.md) | [English🇬🇧](readme_en.md) | 中文🇨🇳


JMMLU由MMLU ([Paper](https://arxiv.org/abs/2009.03300), [Github](https://github.com/hendrycks/test))的日语翻译和基于日本独特文化背景的内容两部分构成的四选一问题基准测试。

我们首先从MMLU的57项任务中每项最多选取150个问题机器翻译成日语。 然后由翻译人员检查机器翻译结果并删除难以翻译或与日本文化不相关或冲突的问题和任务。

剩下的问题则经过校对和修改使之成为流畅的日语。 

此外还增加了公民和日本史等基于日本学校教纲的问题的科目。这些问题由日语母语的教师获教育工作者手工编写。


格式与MMLU相同:
```
问题, 选项A, 选项B, 选项C, 选项D, 答案
```

JMMLU有如下56个任务（科目）， 7,536 个问题。其中在JMMLU文件夹的53个任务，7,097问许可证为CC BY-SA 4.0，在JMMLU_NC_ND文件夹下的3个任务，439问许可证为CC BY-NC-ND 4.0。


| 任务名 | 英语任务名 | 件数 |
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

日语和世界历史的版权归 STEP Corporation 所有，除用于研究和评估语言模型外，禁止用于其他商业用途。

日语成语、公民和日本地理的版权归VIST学习塾所有，采用 CC BY-NC-ND 4.0 许可证。仅允许研究和评估语言模型的商业用途。

Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
# 致谢

本研究的MMLU翻译工作得到了理化学研究所的大力支持，在此深表感谢。 我们还衷心感谢 Step Corporation 提供的日本历史和社会历史内容，以及VIST学习塾提供的日语成语、公民和日本地理。 


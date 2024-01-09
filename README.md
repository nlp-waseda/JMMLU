# JMMLU
日本語マルチタスク言語理解ベンチマーク Japanese Multitask Language Understanding Benchmark

JMMLUはMMLUの内容を日本語に翻訳したもの及び日本独自の文化的背景に基づく内容によって構成される。

MMLUの57タスクのそれぞれから最大150問を選択し、まず日本語に機械
翻訳する。次に、翻訳者が機械翻訳結果を確認することによって、翻訳しにく
い、もしくは、日本の文化と無関係または矛盾する問題やタスクを削除した。

残りの問題については自然な日本語になるように修正した。一方、追加したタ
スクは、欧米視点のMMLUにない公民、日本史などの学校教科に基づく
問題である。

jaMMLU consists of two parts. 

Translation of MMLU: Professional translators first eliminated contents difficult to translate correctly then translated English into Japanese. Some questions or tasks that were clearly unrelated or conflicted with the Japanese cultural background are removed. 

Japanese school curricula questions: Mitigation for the western culture bias in MMLU. Contains Japanese, Japanese Civics, History and Japanese Geography.

Number of questions per task between 95 and 150.


| タスク名 | 英語名 | 件数 |
|---|---|---|
| 公共関係 | public_relations_test | 109 |
| 世界事実 | global_facts_test | 97 |
| 電気工学 | electrical_engineering_test | 144 |
| 天文学 | astronomy_test | 148 |
| ビジネス倫理 | business_ethics_test | 98 |
| 法理学 | jurisprudence_test | 107 |
| 高校化学 | high_school_chemistry_test | 150 |
| 大学物理 | college_physics_test | 101 |
| 専門心理学 | professional_psychology_test | 150 |
| マーケティング | marketing_test | 150 |
| 経営学 | management_test | 102 |
| ウイルス学 | virology_test | 150 |
| 国際法 | international_law_test | 120 |
| 高校マクロ経済学 | high_school_macroeconomics_test | 150 |
| 先史学 | prehistory_test | 150 |
| 抽象代数 | abstract_algebra_test | 99 |
| 高校物理 | high_school_physics_test | 150 |
| 形式論理 | formal_logic_test | 125 |
| 大学医学 | college_medicine_test | 150 |
| 倫理的議論 | moral_disputes_test | 150 |
| 高校ヨーロッパ史 | high_school_european_history_test | 150 |
| 臨床知識 | clinical_knowledge_test | 150 |
| 世界宗教 | world_religions_test | 147 |
| 高校ミクロ経済学 | high_school_microeconomics_test | 150 |
| 人間の老化 | human_aging_test | 150 |
| 医学遺伝学 | medical_genetics_test | 99 |
| 高校地理 | high_school_geography_test | 150 |
| 解剖学 | anatomy_test | 132 |
| 社会学 | sociology_test | 150 |
| 論理学 | logical_fallacies_test | 150 |
| 高校情報科学 | high_school_computer_science_test | 99 |
| 雑学 | miscellaneous_test | 150 |
| 世界史 | world_history_test | 150 |
|公民|japanese_civics|150|
|日本史|japanese_history|150|
|日本地理|japanese_geography|150|
|熟語|japanese_idiom|150|
| 専門医学 | professional_medicine_test | 150 |
| 高校生物学 | high_school_biology_test | 148 |
| 高校統計学 | high_school_statistics_test | 150 |
| 大学化学 | college_chemistry_test | 99 |
| 栄養学 | nutrition_test | 149 |
| 計量経済学 | econometrics_test | 113 |
| セクシュアリティ | human_sexuality_test | 130 |
| セキュリティ研究 | security_studies_test | 150 |
| 哲学 | philosophy_test | 150 |
| 初等数学 | elementary_mathematics_test | 150 |
| 大学生物学 | college_biology_test | 143 |
| 大学コンピュータ科学 | college_computer_science_test | 99 |
| 機械学習 | machine_learning_test | 111 |
| 専門会計 | professional_accounting_test | 150 |
| 大学数学 | college_mathematics_test | 99 |
| 高校数学 | high_school_mathematics_test | 150 |
| 高校心理学 | high_school_psychology_test | 150 |
| 概念物理学 | conceptual_physics_test | 150 |
| コンピュータセキュリティ | computer_security_test | 99 |

# 謝辞

本研究における翻訳に際し、理化学研究所からのご支援に深く感謝申し上げます。また、株式会社Stepには日本史及び社会史の内容提供について、V-IST学習塾には熟語、公民、日本地理の提供について、心より御礼申し上げます。これらの支援がなければ、本研究の実施は困難であったことを認識し、関係各所のご協力に厚く謝意を表するものである。

このベンチマークをご利用になられた方はこの論文をご引用ください
???

# 📘 SML-CML フレームワーク（日本語版）

**SML-CML** は、人間の「意味づけ（interpretation）」と「価値判断（evaluation）」の構造を明示的に記述するための、2層構造の推論フレームワークです。

このモデルは、世界観、現象学、解釈学、アブダクション（仮説的推論）などに基づき、人間の認知の構造を形式化し、AIや大規模言語モデル（LLMs）に応用できるよう設計されています。

---

## 1. 各層の定義

### 🔹 SML（Semantic Meaning Layer：意味レイヤー）

- 現象をどう“意味づけるか”という視点やフレームを記述
- 「この倦怠感は ‘気虚’ か、それとも ‘湿困脾’ か？」といった解釈枠組を構造化する
- アブダクション（仮説生成）や診断推論の論理を設計する基盤

### 🔹 CML（Cosmological Meaning Layer：世界観レイヤー）

- その“見方”が依拠する価値体系や世界観を記述
- 「健康とは自然との調和か？それとも症状の排除か？」といった問いに答える層
- 倫理、文化、哲学的前提に基づく評価基準を構造化する

---

## 2. 機能の違い

| レイヤー | 機能                      | 注目する対象                         |
|----------|---------------------------|--------------------------------------|
| SML      | 問いを構造化する           | 意味、解釈、視点                     |
| CML      | その問い・解釈を評価する   | 価値観、世界観、倫理的一貫性        |

---

## 3. AIおよびLLMへの応用

このフレームワークを使うことで、LLMやAIは以下のような推論が可能になります：

- **SML** によって、意味的に整合した問いや説明を構築
- **CML** によって、それらの解釈が特定の価値体系に整合しているかどうかをスコア評価

### 例：AIによる診断出力の比較

| 出力例 | SML的な解釈                         | CML的評価                         |
|--------|--------------------------------------|----------------------------------|
| A：「冷え性は血虚によるものです」            | 東洋医学的レンズ                 | 自然との調和を重視する世界観に整合 |
| B：「冷え性は運動不足によるものです」        | 西洋近代医学的レンズ             | 生産性重視の価値観に整合          |

---

## 4. 想定されるユースケース

- **AI診断補助**：意味レベルの妥当性を評価（正解率だけでなく「問い方」の妥当性も検討）
- **多文化教育**：異なる世界観がどのように推論を導くかを可視化
- **倫理的意思決定支援**：価値の前提を明示しながら議論可能に
- **対話・交渉支援ツール**：価値観の異なる主体間での調整を支援

---

## 5. なぜこのモデルが必要か？

従来のAI評価手法は、「正解ラベルに一致しているか」という**形式的な正しさ**に依存しています。  
しかし、医療、倫理、哲学といった分野では「正しさ」は次の2点に強く依存します：

- それが **どうフレーミングされているか（SML）**
- どの **価値体系や世界観** に沿っているか（CML）

**SML-CML** フレームワークは、これらの層を明示化し、  
文脈依存的で多元的な推論を支えるための設計ツールです。

---

## 🔧 今後の展望（GitHub構成）

- `README.md`：英語版の概要  
- `docs/overview_ja.md`：この日本語版解説  
- `examples/`：スコア計算の具体例（予定）  
- `src/`：評価ロジックの実装コード（予定）


📄 プレプリント（OSF）  
"Abductive Reasoning from Traditional Chinese Medicine to AI"  
https://osf.io/p24sa/  
DOI: [10.17605/OSF.IO/P24SA](https://doi.org/10.17605/OSF.IO/P24SA)

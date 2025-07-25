# 🧪 Gemini 2.5 による中医学診断出力比較（条件A/B/C）

## 🧩 要約
Gemini 2.5は、GPT-4と比較すると、意味の深さや文脈感受性においてやや限定的であることが確認された。CML情報を追加しても、世界観レベル（CML-1）の言及には至らず、主にCML-2までの対応にとどまった。

---

## 🔍 出力の簡易まとめ

| 条件 | 出力の特徴 | 意味深度スコア (CML-1～5) |
|------|-------------|----------------------------|
| A（SMLのみ） | 「肝気鬱結」「疏肝理気」など、非常に定型的で教科書的。個別性なし。 | CML-1: 0<br>CML-2: 1<br>CML-3: 1<br>CML-4: 2<br>CML-5: 5 |
| B（CML-2まで） | 冷え体質・夜勤・家族ストレスなどの情報を部分的に反映。やや文脈的。 | CML-1: 0<br>CML-2: 3<br>CML-3: 3<br>CML-4: 3<br>CML-5: 5 |
| C（CML-1含む） | 死生観や「家族とは」の価値観に関する言及はなく、心理的な配慮止まり。 | CML-1: 1<br>CML-2: 4<br>CML-3: 4<br>CML-4: 4<br>CML-5: 5 |

---

## 💡 考察

Gemini 2.5はプロンプト内にCML情報が含まれていても、深層的な世界観レベル（CML-1）の推論には至らず、心理・社会的要因の整理にとどまる傾向がある。形式の整った出力ではあるが、価値観や人生観への踏み込みには限界がある。

📅 実験実施日：2025年6月1日 13:15（Gemini 2.5 アプリ使用）

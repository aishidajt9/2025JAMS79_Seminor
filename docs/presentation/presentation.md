---
marp: true
theme: default
size: 4:3
paginate: true
footer: '20250827 JAMS79 Seminar'
style: |
  .red { color: red !important; }
  .blue { color: blue !important; }
  .green { color: green !important; }
  .orange { color: #FF6600 !important; }
  .highlight { color: #FF6600 !important; background: #FFFACD; padding: 2px; }
  .columns { display: flex; }
  .column { flex: 1; padding: 0 20px; }
  .column img { max-width: 100%; height: auto; }
  section {
    background-image: url('../figures/KGmoon.png');
    background-repeat: no-repeat;
    background-position: top right 10px;
    background-size: 50px auto;
  }
---

#### 2025JAMS79 数理社会学会ワンステップアップセミナー

# 生成AI時代にこの先生きのこ🍄るための数理社会学（再）入門

石田　淳（関西学院大学）
aishida@kwansei.ac.jp

---

## 講師について

- **石田 淳**（<span class="red">**A**</span>tsushi <span class="red">**I**</span>shida）
- 関西学院大学社会学部教授
- https://aishidajt9.github.io
- フリースタイル数理社会学者
- 数理社会学界のAI


---

## 本日の内容

- 数理社会学をこれから始める（再び始める）にあたっての心構え，考え方，tipsを共有する
- 生成AI（LLM）の研究への活用方法を模索する
  - Claude Codeをメインにデモ
- 参加者間での情報交換
- 配付資料（clone or download）
  - https://github.com/aishidajt9/2025JAMS79_Seminor

---

# 数理社会学（再）入門


---

## GPTとは？
- **OpenAI**が開発した大規模言語モデル（LLM）
- **<span class="red">G</span>enerative**：テキストを生成する
- **<span class="red">P</span>re-trained**：大量のデータで学習済みの
- **<span class="red">T</span>ransformer**：注意機構を使った深層学習モデル
- 2022年ChatGPT公開で一般に普及
  - https://chatgpt.com

---

## Transformerとは？（by claude 4 sonnet）
- **Attention Mechanism**を用いたニューラルネットワークアーキテクチャ (Vaswani et al., 2017)
- 自然言語処理（NLP）での性能向上に寄与
- **BERT**や**GPT**などのモデルで採用
- **自己注意**（Self-Attention）により，文脈を考慮した処理が可能
- **並列処理**が可能で，学習効率が向上

---

## LLMの本質

- 「LLMは本質的に，トレーニング中に提供されるテキストを模倣するテキスト補完エンジンにすぎない」 (Berryman & Ziegler, 2025)
- 現在のLLMは真の論理的推論を実行できず，訓練データから推論ステップを複製しているにすぎない (Mirzadeh et al., 2024)
- 真の意味での知性をモデル化しているかどうかはよくわからない，でも使えるから使おう
- イシダのLLMのイメージ：
  - 『葬送のフリーレン』における魔族
  - 『千と千尋』で釜爺に使われるススワタリ

---

## LLMのイメージ

<div class="columns">
<div class="column">


![魔族](../figures/1689741985919-1ezOJydleM.webp)

</div>
<div class="column">

![ススワタリ](../figures/susuwatari.jpeg)
![ススワタリ](../figures/susuwatari_konpeitou.jpg)

</div>
</div>

---
## Sociological GPT

- Inspired by the conversation with Kenji Kosaka

- LLMは基本的に予測（模倣）・応用のための生成モデル
- 数理社会学モデルは**理解**のための生成モデルであるべき


<!-- 
- sociological GPT
- generative model
- Boudon, Fararo, Coleman, Hedstrom
- 社会学モデルの特徴，ゲリラ戦
- モデリング技法，レイブ・マーチ
- アブダクション，ディダクション，インダクション
- カツカレーから始める
- オモローをみつける，理論と方法特集紹介
 -->




---
# Claude Codeの活用


---

## 質疑応答

ご質問・ご意見をお聞かせください

---
## 参考文献

Berryman, J., & Ziegler, A. (2025). *LLMのプロンプトエンジニアリング*. オライリー・ジャパン.

Mirzadeh, I., et al. (2024). GSM-Symbolic: Understanding the Limitations of Mathematical Reasoning in Large Language Models. *arXiv preprint arXiv:2410.05229*.

Vaswani, A., et al. (2017). Attention is all you need. *Advances in Neural Information Processing Systems*, 30.

---

## ありがとうございました

**連絡先**: [ここに連絡先を追加]
**資料**: [ここにリポジトリURLなどを追加]
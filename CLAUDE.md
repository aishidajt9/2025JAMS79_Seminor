# 2025JAMS79 数理社会学会ワンステップアップセミナー

## セミナー概要

**テーマ**: 生成AI時代にこの先生きのこるための数理社会学（再）入門  
**開催日**: 2025年8月27日  
**講師**: 石田淳（関西学院大学社会学部教授）  

数理社会学の基礎理解とAI活用研究手法を紹介するセミナーの配布資料です。

## このリポジトリの使い方

### プレゼンテーション資料
- **Markdown版**: `docs/presentation/presentation.md` 
  - [Marp](https://marp.app/)対応エディタで閲覧・編集可能
- **PDF版**: `docs/presentation/presentation.pdf`
  - 印刷・配布用

### ファイル構成
```
├── docs/presentation/     # プレゼンテーション資料
├── docs/figures/         # 図版・画像素材
└── README.md            # 基本情報
```

### Marpでスライドを表示する方法
```bash
# Marp CLIをインストール
npm install -g @marp-team/marp-cli

# HTMLに変換
marp docs/presentation/presentation.md --html

# PDFに変換
marp docs/presentation/presentation.md --pdf
```

## セミナーの学術的背景

### socGPT概念
- **GPT**: Generative Pre-trained Transformer（予測・模倣のための言語生成）
- **socGPT**: Generative Process-oriented Toy model（**理解**のための社会現象生成モデル）
- 数理社会学における生成モデルの位置づけ

### 数理社会学の生成モデル系譜
- **Fararo**: 生成プロセスによる理論構築
- **Boudon**: Generating Models as Research Strategy  
- **分析社会学**: Coleman's Boat, ミクロ-マクロリンク

### AI時代の研究姿勢
- 「理解すること」をAIに完全に任せない
- AIの得手不得手を理解した適切な活用
- 人間中心のオーサーシップ

## 技術情報

### Claude Code
- Anthropic社開発のCLI型AIアシスタント
- プロジェクト全体を理解して作業支援
- 研究活用例：プレゼン作成、データ分析、文献管理

### 導入方法
```bash
# macOS
brew install node
npm install -g @anthropic-ai/claude-code
claude
```

詳細：https://docs.anthropic.com/ja/docs/claude-code/

## 参考文献・学習リソース

### 主要文献
- Vaswani, A., et al. (2017). Attention is all you need. *Advances in Neural Information Processing Systems*, 30.
- Berryman, J., & Ziegler, A. (2025). *LLMのプロンプトエンジニアリング*. オライリー・ジャパン.
- Mirzadeh, I., et al. (2024). GSM-Symbolic: Understanding the Limitations of Mathematical Reasoning in Large Language Models. *arXiv preprint arXiv:2410.05229*.

### さらに学ぶために
- **数理社会学**: Coleman (1986), Fararo (1989), Manzo (2014)
- **AI研究活用**: Claude Code Documentation, Anthropic研究論文
- **生成モデル**: Transformer論文, 分析社会学文献

## 著者・連絡先

**石田 淳**（Atsushi Ishida）  
関西学院大学社会学部教授  
Email: aishida@kwansei.ac.jp  
Web: https://aishidajt9.github.io
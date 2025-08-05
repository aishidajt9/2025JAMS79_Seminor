# 2025JAMS79 数理社会学会ワンステップアップセミナー

## プロジェクト概要
- **開催日**: 2025年8月27日
- **テーマ**: 生成AI時代にこの先生きのこるための数理社会学（再）入門
- **目的**: 数理社会学の基礎理解とAI活用研究手法の紹介
- **講師**: 石田淳（関西学院大学社会学部教授）

## セミナー内容
1. **生成AI・LLMの基礎理解**
   - GPT/Transformerアーキテクチャの概要
   - LLMの本質と限界（Apple研究等最新知見）
   - 数理社会学における生成モデルの位置づけ

2. **数理社会学（再）入門**
   - Sociological GPTという発想
   - 理解のための生成モデル vs 予測のための生成モデル
   - 心構え・考え方・実践tips

3. **Claude Codeデモンストレーション**
   - エージェンティックAIの研究活用
   - プレゼンテーション作成・資料管理
   - 学術研究でのAI活用事例

## プロジェクト構成
```
2025JAMS79_Seminor/
├── CLAUDE.md              # プロジェクト概要・指示
├── settings.json          # Claude Code設定（hooks含む）
├── docs/
│   ├── presentation/      # marpプレゼン資料
│   │   └── presentation.md  # メインプレゼンテーション（完成）
│   └── figures/           # 図・画像資料
│       ├── KGmoon.png     # 関西学院ロゴ
│       ├── demon_image.webp    # 魔族イメージ
│       ├── susuwatari.jpeg     # ススワタリイメージ
│       ├── ColemanBoat.png     # Coleman図
│       ├── Manzo_2014.png      # Manzo図
│       └── hal-hefner-2001-the-monolith-hal-hefner-2.jpg  # HAL9000イメージ
└── resources/            # 参考資料・メモ
    ├── memo.md
    └── 各種PDF参考文献
```

## 主要参考文献
- Vaswani, A., et al. (2017). Attention is all you need. *Advances in Neural Information Processing Systems*, 30.
- Berryman, J., & Ziegler, A. (2025). *LLMのプロンプトエンジニアリング*. オライリー・ジャパン.
- Mirzadeh, I., et al. (2024). GSM-Symbolic: Understanding the Limitations of Mathematical Reasoning in Large Language Models. *arXiv preprint arXiv:2410.05229*.

## 開発ステータス
### プレゼンテーション完成状況（2025-08-05）
- ✅ **基本構造**: 29スライド構成完成
- ✅ **コンテンツ**: 理論・実践・デモの3部構成
- ✅ **視覚素材**: 比喩イメージ・図表配置完了
- ✅ **技術内容**: Transformer解説・Claude Code実演含む
- ✅ **学術品質**: 参考文献・数理社会学的観点統合済み

### プレゼンテーション特徴
- **marp使用**: Markdown→スライド変換
- **カラーテーマ**: 赤・青・緑・オレンジ・ハイライト設定済み
- **ロゴ配置**: 全スライド右上に関西学院ロゴ自動表示
- **2カラムレイアウト**: 画像・テキスト併置可能

### LLMの比喩的表現
- **魔族**（葬送のフリーレン）: 言語模倣・パターンマッチング特性の説明
- **ススワタリ**（千と千尋）: 並列処理・集合知の視覚化
- **HAL9000**: AI研究史・SF文脈での位置づけ

### 学術的視点
- **Sociological GPT**: 理解vs予測の生成モデル
- **Coleman図**: ミクロ-マクロリンク理論との接続
- **最新AI研究**: Apple/MIT論文による推論能力の限界指摘
- **実践的活用**: Claude Code等ツールの研究応用デモ

## Claude Code設定情報
- **言語**: 日本語メイン
- **出力形式**: Markdown優先
- **コードスタイル**: 学術研究向け
- **Github公開前提**: 学術発表品質維持
- **hooks設定**: settings.jsonで通知機能有効化済み

## 次回作業予定
- [ ] プレゼンテーション最終調整・リハーサル
- [ ] 実演デモ用サンプルコード準備
- [ ] 配布資料・参考リンク集作成
- [ ] 質疑応答想定問答準備

## Git管理指示
### コミット時の注意
- 全ファイルを必ずaddしてからコミット
- 学術発表資料として適切なコミットメッセージを使用
- プレゼンテーション更新時は内容の要約を含める
- 画像ファイル等のバイナリも含めて管理
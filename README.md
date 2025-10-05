# Fudoki（フドキ）

> **日本語学習者とNLP愛好家のための、インタラクティブな日本語テキスト解析＆音声読み上げWebアプリ**
>
> **An interactive Japanese text analysis and speech synthesis web app for language learners and NLP enthusiasts**
>
> **为日语学习者和NLP爱好者打造的交互式日语文本分析与语音朗读Web应用**

---
![alt text](static/fudoki.png)
## 🌟 主要特性 / Features / 主な機能

### 🔍 **智能文本分析**
- **形態素解析**: Kuromoji.jsベースの高精度な分かち書き
- **品詞タグ付け**: 名詞・動詞・形容詞など詳細な品詞情報
- **読み仮名表示**: 各単語のカタカナ・ひらがな読み
- **ローマ字変換**: 学習者に優しいローマ字表記

### 🗣️ **音声合成機能**
- **ネイティブ音声**: Web Speech APIによる自然な日本語TTS
- **単語別再生**: クリックで個別単語を発音
- **行単位再生**: 文ごとに音声確認
- **全文再生**: ドキュメント全体の連続再生
- **速度調整**: 0.5x～2.0xで自由に調整可能

### 📚 **辞書統合**
- **JMdict辞書**: 包括的な日英辞書データベース
- **詳細翻訳**: 複数の意味・用法・例文を表示
- **ワンクリック検索**: 単語カードをクリックで即座に翻訳

### 📝 **文書管理**
- **マルチドキュメント**: 複数の文書を管理
- **自動保存**: 編集内容をローカルストレージに自動保存
- **簡単切り替え**: サイドバーからワンクリックで文書切替

### 🎨 **カスタマイズ**
- **ダークモード**: 目に優しいダーク/ライトテーマ
- **表示切替**: ふりがな・ローマ字・品詞の表示/非表示
- **多言語UI**: 日本語・英語・中文インターフェース
- **ドラッグ可能**: ツールバーの位置・サイズを自由調整

---

## 🚀 使い方 / Usage / 使用方法

### オンライン版
🌐 **[https://fudoki.iamcheyan.com](https://fudoki.iamcheyan.com)**

### ローカル起動

```bash
# リポジトリをクローン
git clone https://github.com/iamcheyan/fudoki.git
cd fudoki

# HTTPサーバーを起動（例：Python）
python -m http.server 8000

# ブラウザで開く
# http://localhost:8000
```

### 基本操作

1. **テキスト入力**: 上部のテキストエリアに日本語を入力
2. **分析実行**: 「分析」ボタンをクリック
3. **結果確認**: 色分けされた単語カードで品詞を確認
4. **音声再生**: 単語・行・全文の再生ボタンをクリック
5. **辞書確認**: 単語カードをクリックして翻訳を表示

---

## 📖 日本語版ガイド

### Fudokiとは？

Fudoki（フドキ）は、日本語学習者やNLP研究者向けに開発された、ブラウザで動作する日本語テキスト解析ツールです。形態素解析エンジン「Kuromoji.js」を搭載し、入力した日本語文を自動的に単語に分割し、品詞・読み仮名・ローマ字を表示します。

### 主な用途

- **日本語学習**: 文章の構造理解、発音練習
- **教育現場**: 教材作成、読解指導
- **NLP研究**: トークナイゼーション、品詞タグ付けの検証
- **翻訳作業**: 語彙確認、用法チェック

### 技術スタック

- **形態素解析**: Kuromoji.js
- **辞書データ**: JMdict (Japanese-Multilingual Dictionary)
- **音声合成**: Web Speech API
- **フロントエンド**: Vanilla JavaScript, CSS3

### 品詞の色分け

| 色 | 品詞 |
|---|---|
| 🟢 緑 | 名詞 |
| 🔵 青 | 動詞 |
| 🟠 橙 | 形容詞 |
| 🟣 紫 | 副詞 |
| 🔴 赤 | 助詞 |
| 🟡 黄 | 感動詞 |

---

## 📖 English Guide

### What is Fudoki?

Fudoki is a browser-based Japanese text analysis tool designed for language learners and NLP enthusiasts. Powered by the Kuromoji.js morphological analyzer, it automatically segments Japanese sentences into words and displays part-of-speech tags, kana readings, and romaji transliterations.

### Key Use Cases

- **Language Learning**: Understanding sentence structure and pronunciation practice
- **Education**: Creating teaching materials and reading comprehension instruction
- **NLP Research**: Tokenization and POS tagging verification
- **Translation Work**: Vocabulary checking and usage verification

### Tech Stack

- **Morphological Analysis**: Kuromoji.js
- **Dictionary Data**: JMdict (Japanese-Multilingual Dictionary)
- **Speech Synthesis**: Web Speech API
- **Frontend**: Vanilla JavaScript, CSS3

### Part-of-Speech Color Coding

| Color | Part of Speech |
|---|---|
| 🟢 Green | Noun |
| 🔵 Blue | Verb |
| 🟠 Orange | Adjective |
| 🟣 Purple | Adverb |
| 🔴 Red | Particle |
| 🟡 Yellow | Interjection |

### Browser Compatibility

- ✅ Chrome 70+
- ✅ Firefox 62+
- ✅ Safari 14+
- ✅ Edge 79+

*Note: Speech synthesis availability depends on your OS and browser language settings*

---

## 📖 中文指南

### Fudoki是什么？

Fudoki（复读机）是一款专为日语学习者和自然语言处理研究者设计的浏览器端日语文本分析工具。采用「Kuromoji.js」形态素解析引擎，可自动将输入的日语句子分词，并显示词性、假名读音和罗马音标注。

### 主要应用场景

- **日语学习**: 理解句子结构、练习发音
- **教育教学**: 制作教材、阅读理解指导
- **NLP研究**: 分词、词性标注验证
- **翻译工作**: 词汇确认、用法检查

### 技术栈

- **形态素解析**: Kuromoji.js
- **词典数据**: JMdict（日语多语言词典）
- **语音合成**: Web Speech API
- **前端技术**: Vanilla JavaScript, CSS3

### 词性颜色标注

| 颜色 | 词性 |
|---|---|
| 🟢 绿色 | 名词 |
| 🔵 蓝色 | 动词 |
| 🟠 橙色 | 形容词 |
| 🟣 紫色 | 副词 |
| 🔴 红色 | 助词 |
| 🟡 黄色 | 感叹词 |

### 浏览器兼容性

- ✅ Chrome 70+
- ✅ Firefox 62+
- ✅ Safari 14+
- ✅ Edge 79+

*注意：语音合成功能的可用性取决于您的操作系统和浏览器语言设置*

---

## 🛠️ 开発情報 / Development / 开发信息

### プロジェクト構成

```
fudoki/
├── index.html              # メインHTML
├── static/
│   ├── main-js.js         # アプリケーションロジック
│   ├── segmenter.js       # 形態素解析ラッパー
│   ├── styles.css         # スタイルシート
│   └── libs/
│       ├── kuromoji.js    # 形態素解析エンジン
│       └── dict/          # 辞書データ
│           ├── *.dat.gz   # Kuromojiバイナリ辞書
│           └── jmdict_*.json  # JMdict翻訳データ
└── README.md
```

### ローカル開発

```bash
# 依存関係なし、静的ファイルのみ
# 任意のHTTPサーバーで起動可能

# Python
python -m http.server 8000

# Node.js (http-server)
npx http-server -p 8000

# PHP
php -S localhost:8000
```

### カスタマイズ

#### テーマカラーの変更

`static/styles.css`のCSS変数を編集:

```css
:root {
  --primary: #0066cc;  /* プライマリカラー */
  --bg: #ffffff;       /* 背景色 */
  --text: #333333;     /* テキスト色 */
}
```

#### 辞書データの更新

JMdictの最新版をダウンロードして`static/libs/dict/`に配置。

---

## 📄 ライセンス / License / 许可协议

MIT License

### 使用しているライブラリ / Third-party Libraries / 使用的第三方库

- **Kuromoji.js** - Apache License 2.0
- **JMdict** - Creative Commons Attribution-ShareAlike 3.0

---

## 👨‍💻 作者 / Author / 作者

**Cheyan**

- Website: [https://iamcheyan.com](https://iamcheyan.com)
- GitHub: [@iamcheyan](https://github.com/iamcheyan)

---

## 🤝 貢献 / Contributing / 贡献

プルリクエストを歓迎します！大きな変更の場合は、まずissueを開いて変更内容を議論してください。

We welcome pull requests! For major changes, please open an issue first to discuss what you would like to change.

欢迎提交 Pull Request！对于重大更改，请先开启 issue 讨论您想要更改的内容。

---

## ⭐ Star History

If you find Fudoki useful, please consider giving it a star! ⭐

[![Star History Chart](https://api.star-history.com/svg?repos=iamcheyan/fudoki&type=Date)](https://star-history.com/#iamcheyan/fudoki&Date)

---

## 📮 フィードバック / Feedback / 反馈

バグ報告や機能リクエストは [GitHub Issues](https://github.com/iamcheyan/fudoki/issues) までお願いします。

Bug reports and feature requests: [GitHub Issues](https://github.com/iamcheyan/fudoki/issues)

错误报告和功能请求：[GitHub Issues](https://github.com/iamcheyan/fudoki/issues)

---

<div align="center">

**Made with ❤️ for Japanese language learners worldwide**

**世界中の日本語学習者のために ❤️ を込めて**

**为全世界的日语学习者用心打造 ❤️**

</div>

---

## 📢 更新与现有功能补充说明（中文）

为便于用户快速了解当前版本的行为与使用方法，下面补充近期功能与交互细节（与代码保持一致）：

### 播放控制栏布局与按钮行为
- 播放控制栏左侧两个按钮水平排列并靠左显示；右侧为语音选择与速度滑条并靠右对齐。
- 全文播放按钮在播放状态下显示黑色方块“停止”图标，文本为 `Stop/停止`；再次点击将立即停止所有朗读。
- 暂停/继续请使用专用暂停按钮（不与“停止”按钮复用）。

### 语音与速度的即时切换（暂停后续播）
- 当播放过程中更改语音或速度时：会先短暂停顿并取消当前发声，然后以新的设置从当前段落的近似位置继续朗读。
- 当前位置估算优先使用浏览器 `onboundary` 事件给出的字符边界索引；若不可用，则回退到基于已播放时长的估算。
- 更改后的设置会写入本地存储，重新打开页面仍保留上次的语音与速度。

### 移动端优化（WAP）
- 在窄屏（≤480px）下压缩播放栏控件宽度：
  - 头部语速滑条 `#headerSpeedRange`：`width: 140px; max-width: 36vw`。
  - 头部语音下拉框 `#headerVoiceSelect`：`width: 160px; max-width: 44vw`，长文本使用省略号处理。
- 播放控制栏容器保留较小的 `gap`，避免控件在移动端占用过多空间。

### 无障碍与多语言
- 头部语速滑条包含 `aria-label="話速"`。
- 播放按钮的文本与提示已根据语言切换为 `Stop/停止`（中文/日文），以便用户直观理解当前行为。

### 使用小贴士
- 如果需要从头开始重播，请点击“停止”后再点击“播放”。
- 语速支持 `0.5x ~ 2.0x`，适合不同学习节奏；更改时会自动在当前位置续播，无需手动暂停。
- 若发现浏览器语音列表为空或质量不理想，请在系统偏好设置中启用或安装相应的语音包；Web Speech API 的可用性与平台相关。

### 已知限制
- 由于各浏览器对 Web Speech API 的实现差异，边界事件与语音列表在不同平台上可能存在行为不一致；断点续播位置为近似估算，长句中可能出现轻微偏移。
- Safari 的语音合成在某些版本中 `onboundary` 支持有限，续播位置可能更多依赖时间估算。

### 相关文件位置（便于检索）
- 播放与控制逻辑：`static/main-js.js`
- 样式与布局（含移动端压缩与左右对齐）：`static/styles.css`
- 页面结构：`index.html`

---

## 🏷️ 名称の由来 / Name Origin / 名称由来

### 日本語（ストーリー）
**フドキ**という名前は、奈良時代の地誌『**風土記（ふどき）**』へのオマージュです。日本人が「フドキ」と聞くと、多くの場合この古代の記録書を思い出します。そこには土地のようす、暮らし、風俗、文化が静かに、しかし丹念に記されています。

- 「**風土**」＝地域や文化の空気感・肌ざわり
- 「**記**」＝記すこと、記録すること

このアプリは、まさに「**言葉の風土**」を記録し、見える化するための道具です。文を分解し、品詞や読み、音のリズムを捉え、発音として再構成する――それは『風土記』が土地の景色を一つひとつ書き留めた営みによく似ています。

> フドキ：日本語を「見える化」するAIツール。

知的で静かな佇まいを保ちながら、言葉の風土（語感・リズム・声韻・文法）を淡々と記録していく。そんな願いを、この名前に込めています。歴史書そのものではなく、精神への敬意としての命名です。

### 中文（讲故事）
**Fudoki（フドキ）** 这个名字，向日本奈良时代的古代地志《**风土记**》致敬。

- 「**风土**」＝地域与文化的气息与肌理
- 「**记**」＝记录、书写

你的应用做的，正是“记录语言的风土”：把句子拆解成词语，标注词性与读音，把语感、节奏、声韵与语法结构重新组合，并以语音方式呈现。这与《风土记》逐条记录土地与民俗的工作，在结构上惊人地一致。

> Fudoki：让日语结构可视化的 AI 工具。

它不是历史书本身，而是向那种“安静而细致地记录世界”的精神致意——将语言的风土，一点点地显形出来。

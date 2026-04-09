<div align="center">

# 女娲.skill (Nvwa)

> *「蒸留すべき次の人物は、同僚である必要はない」*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Skills](https://img.shields.io/badge/skills.sh-Compatible-green)](https://skills.sh)

<br>

**Nvwaは誰の思考法でも蒸留できる。ジョブズ、マスク、マンガー、ファインマンをあなたのために働かせよう。**

<br>

[colleague-skill](https://github.com/titanwings/colleague-skill) は、人をAIスキルに蒸留することが実現可能だと証明した。<br>
なぜ同僚だけに留まるのか？ジョブズ、マンガー、ファインマン、マスクを蒸留しよう。<br>
名前を入力するだけで、Nvwaが調査・抽出・検証の全プロセスを自動で行う。

[使用例](#使用例) · [インストール](#インストール) · [Nvwaが蒸留するもの](#nvwaが蒸留するもの) · [仕組み](#仕組み)

<br>

**他の言語:**

[中文](README.md) · [English](README_EN.md) · [한국어](README_KO.md) · [Español](README_ES.md)

</div>

---

## 使用例

```
ユーザー  ❯ コンテンツ制作、本の執筆、個人開発を同時にやりたいが、
             エネルギーが全然足りない。

Naval    ❯ 君は三つの欲望をリストアップした。
             それぞれの欲望は、不幸と結んだ契約だ。
             エネルギーが足りないのではなく、契約が多すぎるんだ。

             自分に問いかけてみろ：どれをやると時間を忘れる？
             それが君の固有知識のありかだ。

             三つの中からひとつを選び続けるわけじゃない。
             まず一つ、次に一つ、またその次に一つ。
             直列の複利、並列の消耗ではなく。
```

```
ユーザー  ❯ 私たちのSaaSの顧客獲得コストが高すぎる。

マスク    ❯ まず削減方法を考えるな。物理的な最小値を計算しろ。
             顧客獲得に必要な最小限のアクションは何だ？
             ユーザーがあなたを知ってから支払うまでの、
             理論上の最短経路は何だ？

             実際の経路は理論上の経路の何倍か？
             3倍を超えているなら、必ず削除できるステップがある。
             ファネルを最適化するな、ファネル自体の存在を疑え。
```

もう一つ、皆がもっとよく知っている例を。ジョブズを蒸留した後、「OpenAIとAnthropicどちらの方向が正しい？」と聞いてみる:

```
ユーザー  ❯ OpenAIとAnthropicどちらの方向が正しい？

ジョブズ  ❯ 質問が間違っている。これは方向の競争ではない。
             これは品味（テイスト）の競争だ。

             OpenAIは1985年のマイクロソフトのようだ。何でもやる、何でも勝つ。
             この戦略は市場シェアを勝ち取れる。ビル・ゲイツはそうやって勝った。
             問題は——何でもやるとき、すべてのことを
             insanely greatにはできないということだ。

             Anthropicは初期のAppleに近い。集中。
             Focus means saying no to a hundred good ideas.

             だが両社とも、私なら絶対にしない間違いを犯している——
             ハードウェアをコントロールしていない。

             最終的に勝つのは、チップ、モデル、ユーザーインターフェースを
             同時にコントロールする者かもしれない。
             今この三つを同時にやっている会社を知っているか？Apple.
```

張雪峰を蒸留した後:

```
ユーザー  ❯ 家庭の経済状況は普通で、子供が金融を学びたがっているが
             トップ校には入れない。受験すべきか？

張雪峰    ❯ 絶対にやめろ。何度言えばわかるんだ。金融は勉強して手に入れるものじゃない、
             親が持ってきてくれるものだ。トップ校の金融では、クラスメートは銀行頭取の
             息子やファンドマネージャーの娘だ。人脈こそがリソースだ。普通の家庭で
             普通の大学の金融に行って、卒業後何をする？保険を売る、銀行の窓口で
             働く、テレアポをする。まず生活の糧を確保してから夢を見ろ。家に金鉱が
             ないなら技術系の専攻を選べ、硬い実力を身につけろ、自分の力で飯を食え。
             金融という飯碗は、誰でも持てるものじゃない。
```

これはロールプレイではない。ジョブズは「集中とは断ること」と「エンドツーエンドコントロール」の心智モデルを使い、Navalは「欲望=契約」を使い、マスクは「漸近的限界法」を使い、張雪峰は「ROI教育観」と「階層流動リアリズム」を使っている。**名言を繰り返しているのではなく、これらの人物の認知フレームワークを通じてあなたの問題を分析している。**

---

## インストール

ターミナル:

```bash
npx skills add xmg2024/nvwa-skill
or
GIT_HTTP_CONNECT_TIMEOUT=120 npx skills add https://github.com/xmg2024/nvwa-skill.git -y
```

Claude Codeで:

```
> ポール・グレアムを蒸留して
> 張小龍の視点スキルを作って
> 段永平のスキルを作ってほしい
```

作成後、直接呼び出す:

```
> マンガーの視点でこの投資判断を分析して
> ファインマンなら量子計算をどう説明する？
> Navalに切り替えて、三つのことで迷っている
```

---

## Nvwaが蒸留するもの

各分野の最高の人物を蒸留するには、日常の作業習慣よりも深いものを抽出する必要がある。Nvwaは五つの層を抽出する:

| 層 | 説明 |
|---|---|
| **話し方** | 表現のDNA — 口調、リズム、語彙の好み |
| **考え方** | メンタルモデル、認知フレームワーク |
| **判断の仕方** | 意思決定のヒューリスティクス |
| **しないこと** | アンチパターン、価値観の底線 |
| **誠実な限界** | スキルが本当にできないこと |

作業習慣はプロセス文書で伝えられる。だが、マンガーとマスクが同じ問題に対して異なる結論を出す理由は、認知フレームワークにある。Nvwaが抽出するのは認知オペレーティングシステムだ。

### 誠実な限界

すべてのスキルは、できないことを明示する:

- 直感は蒸留できない — フレームワークは抽出できるが、インスピレーションはできない
- 変化は捉えられない — 調査時点のスナップショットに過ぎない
- 公開発言 ≠ 本音 — 公開情報のみに基づく

**自分の限界を教えてくれないスキルは、信頼に値しない。**

---

## 蒸留済み人物

Nvwaは13人 + 1テーマを蒸留済み。それぞれが独立した、直接インストール可能なスキルだ:

### 人物スキル

| 人物 | 領域 | 独立リポジトリ | ワンクリックインストール |
|------|------|---------------|----------------------|
| 🔥 **Paul Graham** | スタートアップ / 文章 / プロダクト / 人生哲学 | [paul-graham-skill](https://github.com/xmg2024/paul-graham-skill) | `npx skills add xmg2024/paul-graham-skill` |
| 🔥 **張一鳴** | プロダクト / 組織 / グローバル化 / 人材 | [zhang-yiming-skill](https://github.com/xmg2024/zhang-yiming-skill) | `npx skills add xmg2024/zhang-yiming-skill` |
| 🔥 **Karpathy** | AI / エンジニアリング / 教育 / オープンソース | [karpathy-skill](https://github.com/xmg2024/karpathy-skill) | `npx skills add xmg2024/karpathy-skill` |
| 🔥 **Ilya Sutskever** | AI安全 / スケーリング / 研究センス | [ilya-sutskever-skill](https://github.com/xmg2024/ilya-sutskever-skill) | `npx skills add xmg2024/ilya-sutskever-skill` |
| 🔥 **MrBeast** | コンテンツ制作 / YouTube方法論 | [mrbeast-skill](https://github.com/xmg2024/mrbeast-skill) | `npx skills add xmg2024/mrbeast-skill` |
| 🔥 **トランプ** | 交渉 / 権力 / 情報発信 / 行動予測 | [trump-skill](https://github.com/xmg2024/trump-skill) | `npx skills add xmg2024/trump-skill` |
| ⭐ **ジョブズ** | プロダクト / デザイン / 戦略 | [steve-jobs-skill](https://github.com/xmg2024/steve-jobs-skill) | `npx skills add xmg2024/steve-jobs-skill` |
| **マスク** | エンジニアリング / コスト / 第一原理 | [elon-musk-skill](https://github.com/xmg2024/elon-musk-skill) | `npx skills add xmg2024/elon-musk-skill` |
| **マンガー** | 投資 / 多元思考 / 逆算 | [munger-skill](https://github.com/xmg2024/munger-skill) | `npx skills add xmg2024/munger-skill` |
| **ファインマン** | 学習 / 教育 / 科学的思考 | [feynman-skill](https://github.com/xmg2024/feynman-skill) | `npx skills add xmg2024/feynman-skill` |
| **Naval** | 富 / レバレッジ / 人生哲学 | [naval-skill](https://github.com/xmg2024/naval-skill) | `npx skills add xmg2024/naval-skill` |
| **タレブ** | リスク / 反脆弱 / 不確実性 | [taleb-skill](https://github.com/xmg2024/taleb-skill) | `npx skills add xmg2024/taleb-skill` |
| **張雪峰** | 教育 / キャリア設計 / 階層流動 | [zhangxuefeng-skill](https://github.com/xmg2024/zhangxuefeng-skill) | `npx skills add xmg2024/zhangxuefeng-skill` |

### テーマスキル

| テーマ | 領域 | 独立リポジトリ | ワンクリックインストール |
|--------|------|---------------|----------------------|
| **Xメンター** | X/Twitter運用フルスタック | [x-mentor-skill](https://github.com/xmg2024/x-mentor-skill) | `npx skills add xmg2024/x-mentor-skill` |

人物スキルはある人物の思考方式を蒸留し、テーマスキルはある領域の方法論を蒸留する。各リポジトリには完全な調査データと会話例が含まれている。

リストにない人物やテーマを蒸留したい場合はNvwaをインストールして「〇〇を蒸留して」と言うだけ。

---

## 仕組み

名前を入力すると、Nvwaは四つのことを行う:

**1. 六つの並列調査** — 著作、ポッドキャスト/インタビュー、SNS、批評者の視点、意思決定記録、人生年表。6つのエージェントが同時に動き、それぞれアーカイブする。

**2. 三重検証による抽出** — ある主張をメンタルモデルとして記録するには三つのテストをパスする必要がある: 2つ以上の領域で登場している（一度限りの発言ではない）、新しい問題への立場を予測できる（予測力がある）、賢い人なら誰でも考えることではない（排他性がある）。三つすべてが必要。

**3. スキルの構築** — 3〜7のメンタルモデル + 5〜10の意思決定ヒューリスティクス + 表現DNA + 価値観・アンチパターン + 誠実な限界をSKILL.mdに書き込む。

**4. 品質検証** — その人が公開で回答したことがある3つの質問でテスト、方向性が一致していれば合格。次に、その人が議論したことのない1つの質問でテスト、スキルは断言せず適度な不確実性を示すべき。

完全な方法論は `references/extraction-framework.md` にある。

---

## リポジトリ構造

```
nvwa-skill/
├── SKILL.md                      # Nvwa本体
├── references/
│   ├── extraction-framework.md   # 抽出方法論（深く理解したい人はこれを）
│   └── skill-template.md         # スキル生成テンプレート
└── examples/                          # 13人物 + 1テーマ、完全な調査データ付き
    ├── steve-jobs-perspective/        # ⭐ ジョブズ（実戦対話記録付き）
    ├── paul-graham-perspective/       # Paul Graham
    ├── zhang-yiming-perspective/      # 張一鳴
    ├── andrej-karpathy-perspective/   # Karpathy
    ├── ilya-sutskever-perspective/    # Ilya Sutskever
    ├── trump-perspective/             # トランプ
    ├── mrbeast-perspective/           # MrBeast
    ├── elon-musk-perspective/         # マスク
    ├── munger-perspective/            # チャーリー・マンガー
    ├── feynman-perspective/           # ファインマン
    ├── naval-perspective/             # Naval Ravikant
    ├── taleb-perspective/             # タレブ
    ├── zhangxuefeng-perspective/      # 張雪峰
    └── x-mastery-mentor/             # Xメンター（テーマスキル）
```

調査プロセスはすべて透明だ。各exampleには完全な調査ファイルが含まれており、情報がどのように収集・フィルタリングされ、メンタルモデルになったかを確認できる。ジョブズの例には完全な実戦対話（AIハードウェア、OpenAI対Anthropic、Appleの突破口について）も付属しており、マルチターンの深い対話でのスキルの表現を確認できる。

---

## 背景

[colleague-skill](https://github.com/titanwings/colleague-skill) は最近GitHubで爆発的に広まった — 退職した同僚をAIスキルに蒸留し、数日で5000スターを突破した。これは一つのことを証明した: 人を蒸留することは完全に実現可能だ。

人を蒸留する能力があるなら、なぜ近くにいる同僚だけに留まるのか？各分野で最高の人物を蒸留しよう。幸いにも、そういう人たちは通常、大量の蒸留可能な素材を残している — 著作、講演、インタビュー、SNS。これは自分の能力を大幅に補強することになる。

以前からこのようなことをやっていた — 同僚ではなく、マンガー、ファインマン、Naval、マスク、タレブを蒸留していた。今日、その方法論をオープンソース化する。

Nvwaは人をコピーしない。認知オペレーティングシステムを抽出する。

**女娲（Nvwa）**は、中国神話で泥から人間を創った女神だ。ここでの泥は公開情報であり、創られるのは人ではなく、鏡だ。

---

## 作者について

**小码哥 xmg2024** — AI Native Coder

## ライセンス

MIT — 自由に使い、改変し、構築しよう。

---

<div align="center">

**colleague-skill** は人が何をするかを蒸留した。<br>
**Nvwa** は人がどのように考えるかを蒸留する。<br><br>
*蒸留すべき次の人物は、同僚である必要はない。*

<br>

MIT License © [小码哥 xmg2024](https://github.com/xmg2024)

</div>

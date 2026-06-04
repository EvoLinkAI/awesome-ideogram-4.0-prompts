<div align="center">

<a href="https://evolink.ai/models?utm_source=github&utm_medium=readme&utm_campaign=awesome-ideogram-4.0-prompts"><img src="images/logo.jpg" alt="awesome-ideogram-4.0-prompts logo"></a>

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](LICENSE)
[![Try it on Evolink](https://img.shields.io/badge/Try_it_on-Evolink-black)](https://evolink.ai/models?utm_source=github&utm_medium=readme&utm_campaign=awesome-ideogram-4.0-prompts)
[![Model](https://img.shields.io/badge/Model-Ideogram_4.0-purple)](https://evolink.ai/models?utm_source=github&utm_medium=readme&utm_campaign=awesome-ideogram-4.0-prompts)
[![Weights](https://img.shields.io/badge/Open_Weights-GitHub-blue)](https://github.com/ideogram-oss/ideogram4)
[![Cases](https://img.shields.io/badge/Cases-23-orange)](#-目次)

[![🇺🇸 English](https://img.shields.io/badge/🇺🇸_English-Default_Source-111111)](README.md)
[![🇪🇸 Español](https://img.shields.io/badge/🇪🇸_Español-Ver-ffb703)](README_es.md)
[![🇵🇹 Português](https://img.shields.io/badge/🇵🇹_Português-Ver-2a9d8f)](README_pt.md)
[![🇯🇵 日本語](https://img.shields.io/badge/🇯🇵_日本語-表示-52b788)](README_ja.md)
[![🇰🇷 한국어](https://img.shields.io/badge/🇰🇷_한국어-보기-4ea8de)](README_ko.md)
[![🇩🇪 Deutsch](https://img.shields.io/badge/🇩🇪_Deutsch-Ansehen-f4a261)](README_de.md)
[![🇫🇷 Français](https://img.shields.io/badge/🇫🇷_Français-Voir-e76f51)](README_fr.md)
[![🇹🇷 Türkçe](https://img.shields.io/badge/🇹🇷_Türkçe-Görüntüle-d62828)](README_tr.md)
[![🇹🇼 繁體中文](https://img.shields.io/badge/🇹🇼_繁體中文-查看-8338ec)](README_zh-TW.md)
[![🇨🇳 简体中文](https://img.shields.io/badge/🇨🇳_简体中文-查看-ef476f)](README_zh-CN.md)
[![🇷🇺 Русский](https://img.shields.io/badge/🇷🇺_Русский-Смотреть-577590)](README_ru.md)

</div>

## 🍌 はじめに

**Ideogram 4.0** プロンプトリポジトリへようこそ！🤗

**幅広いタスクとクリエイティブなワークフローにわたる Ideogram 4.0 の高品質なプロンプトと作例画像を集めています**——タイポグラフィとポスターデザイン、写実的なポートレート、製品・パッケージデザイン、そしてモデル同士の直接比較。

Ideogram 4.0 は2026年6月3日に**世界最高のオープンウェイト型テキスト画像モデル**として登場しました（サードパーティのアリーナでオープンモデル第1位）。ネイティブ2K解像度、ネイティブな背景透過、高密度で正確な多言語テキストレンダリング、bounding-box によるレイアウト制御を備え、さらにウェイトをダウンロードして微調整し、セルフホスティングできます。

<div align="center">
<img src="images/leaderboard.png" alt="Ideogram 4.0 is the #1 open-weight model on the DesignArena Text-to-Image leaderboard" width="760">
<br><sub><b>実証：</b>Ideogram 4.0 は <a href="https://x.com/a16z/status/2062203114472813008">DesignArena のテキスト画像ランキング</a>で<b>オープンウェイト第1位</b>（Elo 1285）——OpenAI と Google のクローズドモデルに次ぐ位置です。</sub>
</div>

このリポジトリのほとんどの事例は、X/Twitter、クリエイターコミュニティ、公開ローンチデモから収集されています。

Evolink で試す：[Ideogram 4.0](https://evolink.ai/models?utm_source=github&utm_medium=readme&utm_campaign=awesome-ideogram-4.0-prompts)

役に立ったら、ぜひスターをお願いします。⭐

> [!NOTE]
> このリポジトリは初期の種まき段階です。各事例は、完全な帰属表示とともに**実際に公開された作例画像**を掲載します。事例に `Prompt` ブロックを含めるのは**元の作者が正確なプロンプトを公開している場合のみ**です——私たちはプロンプトを捏造・推測しません。そのため、結果のみが共有されたローンチ当日の事例ではプロンプトを意図的に省略し、代わりに出典へのリンクを示します。

## 📰 ニュース

- **June 3, 2026:** Ideogram 4.0 リリース——サードパーティのアリーナで第1位のオープンウェイト型テキスト画像モデル。ネイティブ2K、透過背景、ダウンロード可能なオープンウェイトを備える。
- **June 3, 2026:** Hugging Face、ComfyUI、fal、Runware、Magnific、Krea、Leonardo、Picsart、Cloudflare、Replicate、Gamma、Flora、Kittl などのローンチパートナーで利用可能。
- **June 4, 2026:** リポジトリの初回更新——カテゴリ各セクションにローンチ当日の11事例（複数画像ギャラリー）。
- **June 4, 2026:** RuntimeWire の直接比較事例を4件追加（実プロンプト付き）——Ideogram 4.0 が水グラスの屈折／物理テストで OpenAI、Google、Microsoft に勝利。
- **June 4, 2026:** ローンチ当日の12時間ウィンドウからさらに8事例を追加——うち3件は実際に公開されたプロンプト付き（ロープ文字タイポグラフィ、1000×マクロ・タイポグラフィ、抽象的な鉛筆ポートレート）、5件はコミュニティ／比較の作例。

## 📑 目次

- [🍌 はじめに](#-はじめに)
- [📰 ニュース](#-ニュース)
- [📑 目次](#-目次)
- [📸 ポートレート・写真の事例](#-ポートレート写真の事例)
  - [Case 1: 写実的なテクスチャと自然な質感の乱れ](#case-1-写実的なテクスチャと自然な質感の乱れ-by-ideogram_ai)
  - [Case 2: リアルなキャラクターの肌質感](#case-2-リアルなキャラクターの肌質感-by-jerrod_lew)
- [🎨 ポスター・イラストの事例](#-ポスターイラストの事例)
  - [Case 1: タイポグラフィとグラフィックデザイン](#case-1-タイポグラフィとグラフィックデザイン-by-ideogram_ai)
  - [Case 2: デザインの最前線](#case-2-デザインの最前線-by-ideogram_ai)
  - [Case 3: ロープ文字のタイポグラフィ](#case-3-ロープ文字のタイポグラフィ-by-umesh_ai)
  - [Case 4: 1000× マクロ・タイポグラフィ耐久テスト](#case-4-1000-マクロタイポグラフィ耐久テスト-by-squeakalgaib)
  - [Case 5: 2K の高密度テキストブロック](#case-5-2k-の高密度テキストブロック-by-jerrod_lew)
  - [Case 6: 抽象的な鉛筆による断面ポートレート](#case-6-抽象的な鉛筆による断面ポートレート-by-fofrai)
  - [Case 7: 栄養成分表示付きの製品パッケージ](#case-7-栄養成分表示付きの製品パッケージ-by-jerrod_lew)
- [🧪 比較・コミュニティ事例](#-比較コミュニティ事例)
  - [Case 1: 10モデルのグラフィティ比較](#case-1-10モデルのグラフィティ比較-by-geniart_fr)
  - [Case 2: 多言語テキストレンダリング（チェコ語）](#case-2-多言語テキストレンダリングチェコ語-by-lukasersil)
  - [Case 3: 早期アクセスのデザイン作例](#case-3-早期アクセスのデザイン作例-by-venturetwins)
  - [Case 4: オープンで圧巻](#case-4-オープンで圧巻-by-a16z)
  - [Case 5: オープンな画像生成の飛躍](#case-5-オープンな画像生成の飛躍-by-ludoviccreator)
  - [Case 6: 4コマのスタートアップ・ストーリーボード](#case-6-4コマのスタートアップストーリーボード-by-runtimewire)
  - [Case 7: スマートフォンの4世代の進化](#case-7-スマートフォンの4世代の進化-by-runtimewire)
  - [Case 8: Nimbus ブランドアイデンティティシステム](#case-8-nimbus-ブランドアイデンティティシステム-by-runtimewire)
  - [Case 9: 水のグラスの屈折の物理](#case-9-水のグラスの屈折の物理-by-runtimewire)
  - [Case 10: シュルレアリスム：Ideogram 4 対 GPT Image 2](#case-10-シュルレアリスムideogram-4-対-gpt-image-2-by-jasperdevs)
  - [Case 11: 口紅広告：Ideogram 4 対 GPT Image 2](#case-11-口紅広告ideogram-4-対-gpt-image-2-by-vortex_promos)
  - [Case 12: 鮮明なオープンウェイト生成](#case-12-鮮明なオープンウェイト生成-by-fofrai)
  - [Case 13: 多彩なビジュアルスタイルにわたるオープンモデル](#case-13-多彩なビジュアルスタイルにわたるオープンモデル-by-azed_ai)
  - [Case 14: 4枚のオープンソース・テスト生成](#case-14-4枚のオープンソーステスト生成-by-ozansihay)
- [🙏 謝辞](#-謝辞)

## 📸 ポートレート・写真の事例

### Case 1: [写実的なテクスチャと自然な質感の乱れ](https://x.com/ideogram_ai/status/2062202376833106365) (by [@ideogram_ai](https://x.com/ideogram_ai))

<table>
<tr>
<td width="50%">

<img src="images/portrait_case1/output.jpg" width="100%">

</td>
<td width="50%">

<img src="images/portrait_case1/output2.jpg" width="100%">

</td>
</tr>
<tr>
<td width="50%">

<img src="images/portrait_case1/output3.jpg" width="100%">

</td>
<td width="50%">

<img src="images/portrait_case1/output4.jpg" width="100%">

</td>
</tr>
</table>

> [!NOTE]
> Ideogram 4.0 は、本物の写真とAI画像を分ける繊細なテクスチャと自然な質感の乱れを描き出します——すべてネイティブ2Kで。

---

### Case 2: [リアルなキャラクターの肌質感](https://x.com/jerrod_lew/status/2062202782590095619) (by [@jerrod_lew](https://x.com/jerrod_lew))

<table>
<tr>
<td width="50%">

<img src="images/portrait_case2/output.jpg" width="100%">

</td>
<td width="50%">

<img src="images/portrait_case2/output2.jpg" width="100%">

</td>
</tr>
</table>

> [!NOTE]
> 緻密なキャラクターと肌の質感における前進——Ideogram モデルがこれまでに生成した中で最もリアルな人物のひとつ。

---

## 🎨 ポスター・イラストの事例

### Case 1: [タイポグラフィとグラフィックデザイン](https://x.com/ideogram_ai/status/2062202335250764220) (by [@ideogram_ai](https://x.com/ideogram_ai))

<table>
<tr>
<td width="50%">

<img src="images/poster_case1/output.jpg" width="100%">

</td>
<td width="50%">

<img src="images/poster_case1/output2.jpg" width="100%">

</td>
</tr>
<tr>
<td width="50%">

<img src="images/poster_case1/output3.jpg" width="100%">

</td>
<td width="50%">

<img src="images/poster_case1/output4.jpg" width="100%">

</td>
</tr>
</table>

> [!NOTE]
> タイポグラフィとグラフィックデザインは依然として 4.0 最大の強みです——ロゴ、ポスター、複数フォントのレイアウト、長文、そしてデザインに溶け込んだ創造的なタイポグラフィ。

---

### Case 2: [デザインの最前線](https://x.com/ideogram_ai/status/2062202271367336383) (by [@ideogram_ai](https://x.com/ideogram_ai))

<table>
<tr>
<td width="50%">

<img src="images/poster_case2/output.jpg" width="100%">

</td>
<td width="50%">

<img src="images/poster_case2/output2.jpg" width="100%">

</td>
</tr>
<tr>
<td width="50%">

<img src="images/poster_case2/output3.jpg" width="100%">

</td>
</tr>
</table>

> [!NOTE]
> 高密度かつ正確なテキストレンダリング、ネイティブ2K解像度、ネイティブな背景透過、そして精密なレイアウト制御。

---

### Case 3: [ロープ文字のタイポグラフィ](https://x.com/umesh_ai/status/2062257828249915733) (by [@umesh_ai](https://x.com/umesh_ai))

<img src="images/poster_case3/output.jpg" width="500">

**Prompt:**

```
"[NAME]" spelled out through the art of minimalist rope design. Each letter is shaped by the continuous twists and bends of a single red rope, placed against a clean white background. The rope curves naturally, with realistic tension and shadows, giving the impression of soft fiber under gentle strain. Negative space within the loops defines the letterforms clearly, while the rope’s overlapping layers suggest depth and intricacy. The composition conveys connection, resilience, and elegance, balancing simplicity with detail. The final aesthetic feels refined, meaningful, and inventive, presenting "[NAME]" as if written by the rope itself.
```

> [!NOTE]
> `[NAME]` をロープで形作りたい単語に置き換えてください。Ideogram 4.0 が一本の連続した物体から、リアルな張力と影を伴う読みやすい文字を形づくる様子を示します。

---

### Case 4: [1000× マクロ・タイポグラフィ耐久テスト](https://x.com/SqueakAlGaib/status/2062371783400202255) (by [@SqueakAlGaib](https://x.com/SqueakAlGaib))

<img src="images/poster_case4/output.jpg" width="500">

**Prompt:**

```
The entire visible frame is a 1000x magnified view of a single printed letter 'G' from the word 'ELEGANCE' that is printed in 4-point Garamond type on a high-resolution magazine page. At this magnification, you can see the individual ink droplets from the CMYK printing process, the physical paper fiber texture of the coated stock (approximately 120 microns per fiber), the moiré pattern from the four-color halftone screen at 175 lines per inch, and the slight dot gain where cyan, magenta, yellow, and black inks are slightly misregistered (visible as tiny color fringes at letter edges). The 'G' itself is rendered in extreme serif detail showing the hairline serif with its bracketed transition from stroke, the actual ink pooling at stroke junctions due to surface tension, and the counter (negative space inside the G) showing the paper's natural off-white color. In the background, completely out of focus due to shallow depth of field at this magnification, you can barely make out the surrounding letters 'E-L-E-G-A-N-C-E' repeating in a pattern, some upside down, some rotated 180 degrees. The lighting is macro photography ring light from directly above, creating no shadows on the letter but revealing the subtle surface topography of the printed ink. At the TOP of the image, tiny 1mm text in the actual world scale reads 'magnified 1000×' in 6-point Helvetica, but this text must be barely legible despite being 1000x smaller than the main subject — a brutal scale contradiction.
```

> [!NOTE]
> タイポグラフィの耐久テスト：印刷された文字の1000×マクロで、インクの粒、紙の繊維、ハーフトーンのモアレ、そして極小ながら読めるキャプション文字を表示——4.0 の高密度な小文字レンダリングのデモ。

---

### Case 5: [2K の高密度テキストブロック](https://x.com/jerrod_lew/status/2062202754689552763) (by [@jerrod_lew](https://x.com/jerrod_lew))

<table>
<tr>
<td width="50%">

<img src="images/poster_case5/output.jpg" width="100%">

</td>
<td width="50%">

<img src="images/poster_case5/output2.jpg" width="100%">

</td>
</tr>
</table>

> [!NOTE]
> ネイティブ2K生成は高密度のテキストブロックを鮮明に保ちます——どの語もこれまで以上に明瞭で精細。

---

### Case 6: [抽象的な鉛筆による断面ポートレート](https://x.com/fofrAI/status/2062264139574067612) (by [@fofrAI](https://x.com/fofrAI))

<img src="images/poster_case6/output.jpg" width="500">

**Prompt:**

```
a scan of a page from my high school A3 art pad, highly original niche pencil piece working on the aura of unusual cross sections and fluidity of otherwise solid surfaces in human portraiture with offset recursion, not anatomical, the cross sections reveal something else, very detailed and complex, no other anatomy, no embellishments, no pencil shavings, no tea stains, clean white paper
```

> [!NOTE]
> 人物ポートレートにおける断面と流動性を探求した抽象的な鉛筆習作——Ideogram 4.0 の非写真的で緻密なイラスト能力の好例。

---

### Case 7: [栄養成分表示付きの製品パッケージ](https://x.com/jerrod_lew/status/2062202833219568018) (by [@jerrod_lew](https://x.com/jerrod_lew))

<table>
<tr>
<td width="50%">

<img src="images/poster_case7/output.jpg" width="100%">

</td>
<td width="50%">

<img src="images/poster_case7/output2.jpg" width="100%">

</td>
</tr>
</table>

> [!NOTE]
> より説得力のある製品画像と正確な栄養情報テキスト。一貫性を高めるため、プロンプトとともに参照画像を併用できます。

---

## 🧪 比較・コミュニティ事例

### Case 1: [10モデルのグラフィティ比較](https://x.com/GenIArt_Fr/status/2062110258491691240) (by [@GenIArt_Fr](https://x.com/GenIArt_Fr))

<table>
<tr>
<td width="50%">

<img src="images/comparison_case1/output.jpg" width="100%">

</td>
<td width="50%">

<img src="images/comparison_case1/output2.jpg" width="100%">

</td>
</tr>
<tr>
<td width="50%">

<img src="images/comparison_case1/output3.jpg" width="100%">

</td>
<td width="50%">

<img src="images/comparison_case1/output4.jpg" width="100%">

</td>
</tr>
</table>

> [!NOTE]
> グラフィティをテーマに、Ideogram 4.0 を ImagineArt 2.0、Krea 2.0、Recraft v4.1、Grok、Uni-1.1、Flux2-Pro、NanoBanana 2、GPT-Image-2、Midjourney v8.1 と並べた独立した横並び比較。

---

### Case 2: [多言語テキストレンダリング（チェコ語）](https://x.com/lukasersil/status/2062203909465129310) (by [@lukasersil](https://x.com/lukasersil))

<table>
<tr>
<td width="50%">

<img src="images/comparison_case2/output.jpg" width="100%">

</td>
<td width="50%">

<img src="images/comparison_case2/output2.jpg" width="100%">

</td>
</tr>
<tr>
<td width="50%">

<img src="images/comparison_case2/output3.jpg" width="100%">

</td>
<td width="50%">

<img src="images/comparison_case2/output4.jpg" width="100%">

</td>
</tr>
</table>

> [!NOTE]
> 読みやすいチェコ語のテキストレンダリングの独立テスト——非英語タイポグラフィにとって強力な実地シグナル。作者はプロンプトが長いため返信に投稿したと述べています。

---

### Case 3: [早期アクセスのデザイン作例](https://x.com/venturetwins/status/2062207215961014735) (by [@venturetwins](https://x.com/venturetwins))

<table>
<tr>
<td width="50%">

<img src="images/comparison_case3/output.jpg" width="100%">

</td>
<td width="50%">

<img src="images/comparison_case3/output2.jpg" width="100%">

</td>
</tr>
<tr>
<td width="50%">

<img src="images/comparison_case3/output3.jpg" width="100%">

</td>
</tr>
</table>

> [!NOTE]
> 強力なテキストレンダリング、高解像度の出力、デザイン品質を強調する早期アクセスの作例。

---

### Case 4: [オープンで圧巻](https://x.com/a16z/status/2062203114472813008) (by [@a16z](https://x.com/a16z))

<table>
<tr>
<td width="50%">

<img src="images/comparison_case4/output.jpg" width="100%">

</td>
<td width="50%">

<img src="images/comparison_case4/output2.jpg" width="100%">

</td>
</tr>
<tr>
<td width="50%">

<img src="images/comparison_case4/output3.jpg" width="100%">

</td>
</tr>
</table>

> [!NOTE]
> Ideogram 4.0 をオープンでダウンロード可能なモデルとして紹介する投資家の作例——「圧巻、しかもオープン」。

---

### Case 5: [オープンな画像生成の飛躍](https://x.com/LudovicCreator/status/2062207302690832683) (by [@LudovicCreator](https://x.com/LudovicCreator))

<table>
<tr>
<td width="50%">

<img src="images/comparison_case5/output.jpg" width="100%">

</td>
<td width="50%">

<img src="images/comparison_case5/output2.jpg" width="100%">

</td>
</tr>
<tr>
<td width="50%">

<img src="images/comparison_case5/output3.jpg" width="100%">

</td>
<td width="50%">

<img src="images/comparison_case5/output4.jpg" width="100%">

</td>
</tr>
</table>

> [!NOTE]
> 早期アクセスのクリエイターの見解：オープンウェイト、セルフホスティング、ファインチューニング、APIアクセス、ネイティブ2K、透過背景、そしてより強力なテキストレンダリング。

---

### Case 6: [4コマのスタートアップ・ストーリーボード](https://runtimewire.com/article/we-put-ideogram-4-head-to-head-against-openai-google-and-microsoft-in-four-image) (by [@runtimewire](https://x.com/runtimewire))

<table>
<tr>
<td width="50%">

<img src="images/comparison_case6/output.png" width="100%">

</td>
<td width="50%">

<img src="images/comparison_case6/output2.png" width="100%">

</td>
</tr>
<tr>
<td width="50%">

<img src="images/comparison_case6/output3.png" width="100%">

</td>
<td width="50%">

<img src="images/comparison_case6/output4.png" width="100%">

</td>
</tr>
</table>

**Prompt:**

```
Create a 4-panel comic storyboard showing the launch of a startup.
```

> [!NOTE]
> RuntimeWire の直接対決（OpenAI 対 Google 対 Microsoft 対 Ideogram）。ガレージのスタートアップからナスダック上場までを、コマ間でキャラクターの一貫性を保ちながら描くストーリーテリングのテスト。順位：Google > Microsoft > OpenAI > Ideogram。

---

### Case 7: [スマートフォンの4世代の進化](https://runtimewire.com/article/we-put-ideogram-4-head-to-head-against-openai-google-and-microsoft-in-four-image) (by [@runtimewire](https://x.com/runtimewire))

<table>
<tr>
<td width="50%">

<img src="images/comparison_case7/output.png" width="100%">

</td>
<td width="50%">

<img src="images/comparison_case7/output2.png" width="100%">

</td>
</tr>
<tr>
<td width="50%">

<img src="images/comparison_case7/output3.png" width="100%">

</td>
<td width="50%">

<img src="images/comparison_case7/output4.png" width="100%">

</td>
</tr>
</table>

**Prompt:**

```
Show four generations of a smartphone evolving over time.
```

> [!NOTE]
> RuntimeWire の直接対決。製品の進化テスト（2007年から2035年への説得力ある推移）。順位：OpenAI > Microsoft > Google > Ideogram。

---

### Case 8: [Nimbus ブランドアイデンティティシステム](https://runtimewire.com/article/we-put-ideogram-4-head-to-head-against-openai-google-and-microsoft-in-four-image) (by [@runtimewire](https://x.com/runtimewire))

<table>
<tr>
<td width="50%">

<img src="images/comparison_case8/output.png" width="100%">

</td>
<td width="50%">

<img src="images/comparison_case8/output2.png" width="100%">

</td>
</tr>
<tr>
<td width="50%">

<img src="images/comparison_case8/output3.png" width="100%">

</td>
<td width="50%">

<img src="images/comparison_case8/output4.png" width="100%">

</td>
</tr>
</table>

**Prompt:**

```
Create a complete visual identity system for a fictional company called Nimbus.
```

> [!NOTE]
> RuntimeWire の直接対決。完全なブランドシステムのテスト——メイン／サブのロゴ、アプリアイコン、名刺、ウェブサイトのホームページ、カラーパレット、パッケージ。順位：OpenAI > Google > Microsoft > Ideogram。

---

### Case 9: [水のグラスの屈折の物理](https://runtimewire.com/article/we-put-ideogram-4-head-to-head-against-openai-google-and-microsoft-in-four-image) (by [@runtimewire](https://x.com/runtimewire))

<table>
<tr>
<td width="50%">

<img src="images/comparison_case9/output.png" width="100%">

</td>
<td width="50%">

<img src="images/comparison_case9/output2.png" width="100%">

</td>
</tr>
<tr>
<td width="50%">

<img src="images/comparison_case9/output3.png" width="100%">

</td>
<td width="50%">

<img src="images/comparison_case9/output4.png" width="100%">

</td>
</tr>
</table>

**Prompt:**

```
Create a photorealistic scene showing a glass of water in front of a newspaper, with realistic refraction and distortion.
```

> [!NOTE]
> RuntimeWire の直接対決——このテストは Ideogram 4.0 が勝利。水／ガラス／光／影／文字の相互作用の物理リアリズムテスト。順位：Ideogram > Google > OpenAI > Microsoft。

---

### Case 10: [シュルレアリスム：Ideogram 4 対 GPT Image 2](https://x.com/jasperdevs/status/2062232495517552716) (by [@jasperdevs](https://x.com/jasperdevs))

<table>
<tr>
<td width="50%">

<img src="images/comparison_case10/output.jpg" width="100%">

</td>
<td width="50%">

<img src="images/comparison_case10/output2.jpg" width="100%">

</td>
</tr>
</table>

> [!NOTE]
> シュルレアリスムの対決——作者は芸術的／シュールなレンダリングで Ideogram 4 が GPT Image v2 より明らかに優れていると評価。

---

### Case 11: [口紅広告：Ideogram 4 対 GPT Image 2](https://x.com/VORTEX_Promos/status/2062276884738490397) (by [@VORTEX_Promos](https://x.com/VORTEX_Promos))

<table>
<tr>
<td width="50%">

<img src="images/comparison_case11/output.jpg" width="100%">

</td>
<td width="50%">

<img src="images/comparison_case11/output2.jpg" width="100%">

</td>
</tr>
</table>

> [!NOTE]
> 広告コンセプトの比較（口紅キャンペーン）、Ideogram v4 対 GPT Image 2。

---

### Case 12: [鮮明なオープンウェイト生成](https://x.com/fofrAI/status/2062251438990930323) (by [@fofrAI](https://x.com/fofrAI))

<table>
<tr>
<td width="50%">

<img src="images/comparison_case12/output.jpg" width="100%">

</td>
<td width="50%">

<img src="images/comparison_case12/output2.jpg" width="100%">

</td>
</tr>
<tr>
<td width="50%">

<img src="images/comparison_case12/output3.jpg" width="100%">

</td>
<td width="50%">

<img src="images/comparison_case12/output4.jpg" width="100%">

</td>
</tr>
</table>

> [!NOTE]
> オープンウェイトの作例——多彩な題材で鮮明かつ新鮮な生成。

---

### Case 13: [多彩なビジュアルスタイルにわたるオープンモデル](https://x.com/azed_ai/status/2062225166567149776) (by [@azed_ai](https://x.com/azed_ai))

<table>
<tr>
<td width="50%">

<img src="images/comparison_case13/output.jpg" width="100%">

</td>
<td width="50%">

<img src="images/comparison_case13/output2.jpg" width="100%">

</td>
</tr>
<tr>
<td width="50%">

<img src="images/comparison_case13/output3.jpg" width="100%">

</td>
<td width="50%">

<img src="images/comparison_case13/output4.jpg" width="100%">

</td>
</tr>
</table>

> [!NOTE]
> ひとつのオープンモデルで、写真、アート、カートゥーン、テキストベースのデザインを横断。

---

### Case 14: [4枚のオープンソース・テスト生成](https://x.com/ozansihay/status/2062305930994192638) (by [@ozansihay](https://x.com/ozansihay))

<table>
<tr>
<td width="50%">

<img src="images/comparison_case14/output.jpg" width="100%">

</td>
<td width="50%">

<img src="images/comparison_case14/output2.jpg" width="100%">

</td>
</tr>
<tr>
<td width="50%">

<img src="images/comparison_case14/output3.jpg" width="100%">

</td>
<td width="50%">

<img src="images/comparison_case14/output4.jpg" width="100%">

</td>
</tr>
</table>

> [!NOTE]
> オープンソース化されたばかりの Ideogram 4.0 に対するコミュニティの4枚のテスト生成。

---

## 🙏 謝辞

このリポジトリは、優れたオープンなプロンプト集とコミュニティが共有した作例に着想を得ています。

作品を公開で共有し、これらのケーススタディを可能にしてくれたクリエイターと貢献者に感謝します。

- [@ideogram_ai](https://x.com/ideogram_ai)
- [@jerrod_lew](https://x.com/jerrod_lew)
- [@GenIArt_Fr](https://x.com/GenIArt_Fr)
- [@lukasersil](https://x.com/lukasersil)
- [@venturetwins](https://x.com/venturetwins)
- [@a16z](https://x.com/a16z)
- [@LudovicCreator](https://x.com/LudovicCreator)
- [Ryan Merket / RuntimeWire](https://runtimewire.com/author/ryan-merket)
- [@fofrAI](https://x.com/fofrAI)
- [@umesh_ai](https://x.com/umesh_ai)
- [@SqueakAlGaib](https://x.com/SqueakAlGaib)
- [@jasperdevs](https://x.com/jasperdevs)
- [@VORTEX_Promos](https://x.com/VORTEX_Promos)
- [@azed_ai](https://x.com/azed_ai)
- [@ozansihay](https://x.com/ozansihay)

*すべての事例が元の作者に正しく帰属しているとは保証できません。修正が必要な点があればご連絡ください。更新します。*

共有したい興味深いプロンプト事例が他にもあれば、ぜひご連絡いただき、Evolink のプロンプトライブラリの拡充にご協力ください。

[![Star History Chart](https://api.star-history.com/svg?repos=Evolink/awesome-ideogram-4.0-prompts&type=Date)](https://www.star-history.com/#Evolink/awesome-ideogram-4.0-prompts&Date)

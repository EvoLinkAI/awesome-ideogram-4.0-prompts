<div align="center">

<a href="https://evolink.ai/models?utm_source=github&utm_medium=readme&utm_campaign=awesome-ideogram-4.0-prompts"><img src="images/logo.jpg" alt="awesome-ideogram-4.0-prompts logo"></a>

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](LICENSE)
[![Try it on Evolink](https://img.shields.io/badge/Try_it_on-Evolink-black)](https://evolink.ai/models?utm_source=github&utm_medium=readme&utm_campaign=awesome-ideogram-4.0-prompts)
[![Model](https://img.shields.io/badge/Model-Ideogram_4.0-purple)](https://evolink.ai/models?utm_source=github&utm_medium=readme&utm_campaign=awesome-ideogram-4.0-prompts)
[![Weights](https://img.shields.io/badge/Open_Weights-GitHub-blue)](https://github.com/ideogram-oss/ideogram4)
[![Cases](https://img.shields.io/badge/Cases-23-orange)](#-目錄)

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

## 🍌 簡介

歡迎來到 **Ideogram 4.0** 提示詞倉庫！🤗

**我們收集 Ideogram 4.0 在各類任務與創意工作流程中的高品質提示詞與圖像範例**——字體排版與海報設計、照片級人像、產品與包裝設計，以及多模型橫向比較。

Ideogram 4.0 於 2026 年 6 月 3 日發布，號稱**全球最強的開放權重文生圖模型**（在第三方競技場上排名開放模型第一）。它具備原生 2K 解析度、原生背景透明、密集且精準的多語言文字算圖，以及 bounding-box 版面控制——而且你可以下載權重、自行微調並自架。

<div align="center">
<img src="images/leaderboard.png" alt="Ideogram 4.0 is the #1 open-weight model on the DesignArena Text-to-Image leaderboard" width="760">
<br><sub><b>實力背書：</b>Ideogram 4.0 是 <a href="https://x.com/a16z/status/2062203114472813008">DesignArena 文生圖排行榜</a>上的<b>開放權重第一名</b>（Elo 1285）——僅次於 OpenAI 與 Google 的閉源模型。</sub>
</div>

本倉庫多數案例來自 X/Twitter、創作者社群與公開發布示範。

在 Evolink 上體驗：[Ideogram 4.0](https://evolink.ai/models?utm_source=github&utm_medium=readme&utm_campaign=awesome-ideogram-4.0-prompts)

如果覺得有用，歡迎給個 star。⭐

> [!NOTE]
> 本倉庫仍處於早期種子階段。每個案例都展示**真實、公開分享的範例圖**並附完整署名。僅當原作者公開了確切的 prompt 時，案例才包含 `Prompt` 程式碼區塊——我們絕不捏造或臆測 prompt，因此那些發布當天僅展示成圖、未公開 prompt 的案例會刻意略過 prompt，改為連結到來源。

## 📰 動態

- **June 3, 2026:** Ideogram 4.0 發布——第三方競技場上排名第一的開放權重文生圖模型，具備原生 2K、透明背景，以及可下載的開放權重。
- **June 3, 2026:** 已在多家發布合作平台上線，包括 Hugging Face、ComfyUI、fal、Runware、Magnific、Krea、Leonardo、Picsart、Cloudflare、Replicate、Gamma、Flora 和 Kittl。
- **June 4, 2026:** 首次倉庫更新——11 個發布當天範例案例（多圖畫廊），分布在各分類章節。
- **June 4, 2026:** 新增 4 個來自 RuntimeWire 的正面比較案例（含真實 prompt）——Ideogram 4.0 在玻璃水杯折射／物理測試中擊敗 OpenAI、Google 和 Microsoft。
- **June 4, 2026:** 再新增 8 個來自發布當天 12 小時窗口的案例——其中三個帶真實公開 prompt（繩索字母排版、1000× 微距排版、抽象鉛筆肖像），另有五個社群／比較展示。

## 📑 目錄

- [🍌 簡介](#-簡介)
- [📰 動態](#-動態)
- [📑 目錄](#-目錄)
- [📸 人像與攝影案例](#-人像與攝影案例)
  - [Case 1: 照片級紋理與自然瑕疵](#case-1-照片級紋理與自然瑕疵-by-ideogram_ai)
  - [Case 2: 逼真的人物皮膚紋理](#case-2-逼真的人物皮膚紋理-by-jerrod_lew)
- [🎨 海報與插畫案例](#-海報與插畫案例)
  - [Case 1: 字體排版與平面設計](#case-1-字體排版與平面設計-by-ideogram_ai)
  - [Case 2: 設計能力前沿](#case-2-設計能力前沿-by-ideogram_ai)
  - [Case 3: 繩索字母排版](#case-3-繩索字母排版-by-umesh_ai)
  - [Case 4: 1000× 微距排版壓力測試](#case-4-1000-微距排版壓力測試-by-squeakalgaib)
  - [Case 5: 2K 密集文字排版](#case-5-2k-密集文字排版-by-jerrod_lew)
  - [Case 6: 抽象鉛筆橫截面肖像](#case-6-抽象鉛筆橫截面肖像-by-fofrai)
  - [Case 7: 附營養標示的產品包裝](#case-7-附營養標示的產品包裝-by-jerrod_lew)
- [🧪 比較與社群範例](#-比較與社群範例)
  - [Case 1: 十款模型塗鴉比較](#case-1-十款模型塗鴉比較-by-geniart_fr)
  - [Case 2: 多語言文字算圖（捷克語）](#case-2-多語言文字算圖捷克語-by-lukasersil)
  - [Case 3: 搶先體驗設計展示](#case-3-搶先體驗設計展示-by-venturetwins)
  - [Case 4: 開源且驚艷](#case-4-開源且驚艷-by-a16z)
  - [Case 5: 開放圖像生成的飛躍](#case-5-開放圖像生成的飛躍-by-ludoviccreator)
  - [Case 6: 四格新創故事板](#case-6-四格新創故事板-by-runtimewire)
  - [Case 7: 智慧型手機的四代演進](#case-7-智慧型手機的四代演進-by-runtimewire)
  - [Case 8: Nimbus 品牌識別系統](#case-8-nimbus-品牌識別系統-by-runtimewire)
  - [Case 9: 玻璃水杯折射物理](#case-9-玻璃水杯折射物理-by-runtimewire)
  - [Case 10: 超現實主義：Ideogram 4 對比 GPT Image 2](#case-10-超現實主義ideogram-4-對比-gpt-image-2-by-jasperdevs)
  - [Case 11: 口紅廣告：Ideogram 4 對比 GPT Image 2](#case-11-口紅廣告ideogram-4-對比-gpt-image-2-by-vortex_promos)
  - [Case 12: 清晰銳利的開放權重生成](#case-12-清晰銳利的開放權重生成-by-fofrai)
  - [Case 13: 開放模型的多風格表現](#case-13-開放模型的多風格表現-by-azed_ai)
  - [Case 14: 四張開源測試生成圖](#case-14-四張開源測試生成圖-by-ozansihay)
- [🙏 致謝](#-致謝)

## 📸 人像與攝影案例

### Case 1: [照片級紋理與自然瑕疵](https://x.com/ideogram_ai/status/2062202376833106365) (by [@ideogram_ai](https://x.com/ideogram_ai))

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
> Ideogram 4.0 算出區分真實照片與 AI 圖像的細膩紋理與自然瑕疵——全部為原生 2K。

---

### Case 2: [逼真的人物皮膚紋理](https://x.com/jerrod_lew/status/2062202782590095619) (by [@jerrod_lew](https://x.com/jerrod_lew))

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
> 在精細人物與皮膚紋理上更進一步——是 Ideogram 模型至今最逼真的人物表現之一。

---

## 🎨 海報與插畫案例

### Case 1: [字體排版與平面設計](https://x.com/ideogram_ai/status/2062202335250764220) (by [@ideogram_ai](https://x.com/ideogram_ai))

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
> 字體排版與平面設計仍是 4.0 最強的能力——logo、海報、多字體版面、長文，以及真正融入設計的創意排版。

---

### Case 2: [設計能力前沿](https://x.com/ideogram_ai/status/2062202271367336383) (by [@ideogram_ai](https://x.com/ideogram_ai))

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
> 密集且精準的文字算圖、原生 2K 解析度、原生背景透明，以及精確的版面控制。

---

### Case 3: [繩索字母排版](https://x.com/umesh_ai/status/2062257828249915733) (by [@umesh_ai](https://x.com/umesh_ai))

<img src="images/poster_case3/output.jpg" width="500">

**Prompt:**

```
"[NAME]" spelled out through the art of minimalist rope design. Each letter is shaped by the continuous twists and bends of a single red rope, placed against a clean white background. The rope curves naturally, with realistic tension and shadows, giving the impression of soft fiber under gentle strain. Negative space within the loops defines the letterforms clearly, while the rope’s overlapping layers suggest depth and intricacy. The composition conveys connection, resilience, and elegance, balancing simplicity with detail. The final aesthetic feels refined, meaningful, and inventive, presenting "[NAME]" as if written by the rope itself.
```

> [!NOTE]
> 把 `[NAME]` 換成你想用繩索拼出的字。展示 Ideogram 4.0 以單一連續物體塑造清晰字形，並帶有真實的張力與陰影。

---

### Case 4: [1000× 微距排版壓力測試](https://x.com/SqueakAlGaib/status/2062371783400202255) (by [@SqueakAlGaib](https://x.com/SqueakAlGaib))

<img src="images/poster_case4/output.jpg" width="500">

**Prompt:**

```
The entire visible frame is a 1000x magnified view of a single printed letter 'G' from the word 'ELEGANCE' that is printed in 4-point Garamond type on a high-resolution magazine page. At this magnification, you can see the individual ink droplets from the CMYK printing process, the physical paper fiber texture of the coated stock (approximately 120 microns per fiber), the moiré pattern from the four-color halftone screen at 175 lines per inch, and the slight dot gain where cyan, magenta, yellow, and black inks are slightly misregistered (visible as tiny color fringes at letter edges). The 'G' itself is rendered in extreme serif detail showing the hairline serif with its bracketed transition from stroke, the actual ink pooling at stroke junctions due to surface tension, and the counter (negative space inside the G) showing the paper's natural off-white color. In the background, completely out of focus due to shallow depth of field at this magnification, you can barely make out the surrounding letters 'E-L-E-G-A-N-C-E' repeating in a pattern, some upside down, some rotated 180 degrees. The lighting is macro photography ring light from directly above, creating no shadows on the letter but revealing the subtle surface topography of the printed ink. At the TOP of the image, tiny 1mm text in the actual world scale reads 'magnified 1000×' in 6-point Helvetica, but this text must be barely legible despite being 1000x smaller than the main subject — a brutal scale contradiction.
```

> [!NOTE]
> 一次排版壓力測試：1000× 微距下的印刷字母，可見墨點、紙張纖維、半色調網紋（moiré）與微小卻可讀的說明文字——彰顯 4.0 的密集小字算圖能力。

---

### Case 5: [2K 密集文字排版](https://x.com/jerrod_lew/status/2062202754689552763) (by [@jerrod_lew](https://x.com/jerrod_lew))

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
> 原生 2K 生成讓密集文字區塊保持銳利——每個字都比以往更清晰、更具細節。

---

### Case 6: [抽象鉛筆橫截面肖像](https://x.com/fofrAI/status/2062264139574067612) (by [@fofrAI](https://x.com/fofrAI))

<img src="images/poster_case6/output.jpg" width="500">

**Prompt:**

```
a scan of a page from my high school A3 art pad, highly original niche pencil piece working on the aura of unusual cross sections and fluidity of otherwise solid surfaces in human portraiture with offset recursion, not anatomical, the cross sections reveal something else, very detailed and complex, no other anatomy, no embellishments, no pencil shavings, no tea stains, clean white paper
```

> [!NOTE]
> 一幅以人物肖像為主題、探索橫截面與流動感的抽象鉛筆習作——是 Ideogram 4.0 非寫實、精細插畫能力的有力例證。

---

### Case 7: [附營養標示的產品包裝](https://x.com/jerrod_lew/status/2062202833219568018) (by [@jerrod_lew](https://x.com/jerrod_lew))

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
> 更強的產品圖與精準的營養資訊文字。可在 prompt 中附上參考圖以提升一致性。

---

## 🧪 比較與社群範例

### Case 1: [十款模型塗鴉比較](https://x.com/GenIArt_Fr/status/2062110258491691240) (by [@GenIArt_Fr](https://x.com/GenIArt_Fr))

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
> 一次獨立的橫向比較：以塗鴉為主題，將 Ideogram 4.0 與 ImagineArt 2.0、Krea 2.0、Recraft v4.1、Grok、Uni-1.1、Flux2-Pro、NanoBanana 2、GPT-Image-2 和 Midjourney v8.1 同台比較。

---

### Case 2: [多語言文字算圖（捷克語）](https://x.com/lukasersil/status/2062203909465129310) (by [@lukasersil](https://x.com/lukasersil))

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
> 一次對可讀捷克語文字算圖的獨立測試——對非英語排版是有力的真實訊號。作者提到 prompt 很長，已放在回覆中。

---

### Case 3: [搶先體驗設計展示](https://x.com/venturetwins/status/2062207215961014735) (by [@venturetwins](https://x.com/venturetwins))

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
> 搶先體驗範例，著重展示強勁的文字算圖、高解析度輸出與設計品質。

---

### Case 4: [開源且驚艷](https://x.com/a16z/status/2062203114472813008) (by [@a16z](https://x.com/a16z))

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
> 投資方將 Ideogram 4.0 作為開放、可下載模型的展示——「驚艷，而且開源」。

---

### Case 5: [開放圖像生成的飛躍](https://x.com/LudovicCreator/status/2062207302690832683) (by [@LudovicCreator](https://x.com/LudovicCreator))

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
> 一位搶先體驗創作者的看法：開放權重、自架、微調、API 存取、原生 2K、透明背景，以及更強的文字算圖。

---

### Case 6: [四格新創故事板](https://runtimewire.com/article/we-put-ideogram-4-head-to-head-against-openai-google-and-microsoft-in-four-image) (by [@runtimewire](https://x.com/runtimewire))

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
> RuntimeWire 正面對決（OpenAI 對 Google 對 Microsoft 對 Ideogram）。說故事測試：從車庫新創到那斯達克上市，並在各格間保持角色一致性。排名：Google > Microsoft > OpenAI > Ideogram。

---

### Case 7: [智慧型手機的四代演進](https://runtimewire.com/article/we-put-ideogram-4-head-to-head-against-openai-google-and-microsoft-in-four-image) (by [@runtimewire](https://x.com/runtimewire))

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
> RuntimeWire 正面對決。產品演進測試（從 2007 到 2035 的可信演進）。排名：OpenAI > Microsoft > Google > Ideogram。

---

### Case 8: [Nimbus 品牌識別系統](https://runtimewire.com/article/we-put-ideogram-4-head-to-head-against-openai-google-and-microsoft-in-four-image) (by [@runtimewire](https://x.com/runtimewire))

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
> RuntimeWire 正面對決。完整品牌系統測試——主／備 logo、應用程式圖示、名片、官網首頁、配色盤、包裝。排名：OpenAI > Google > Microsoft > Ideogram。

---

### Case 9: [玻璃水杯折射物理](https://runtimewire.com/article/we-put-ideogram-4-head-to-head-against-openai-google-and-microsoft-in-four-image) (by [@runtimewire](https://x.com/runtimewire))

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
> RuntimeWire 正面對決——Ideogram 4.0 贏下此項。物理真實感測試：水／玻璃／光／影／文字的互動。排名：Ideogram > Google > OpenAI > Microsoft。

---

### Case 10: [超現實主義：Ideogram 4 對比 GPT Image 2](https://x.com/jasperdevs/status/2062232495517552716) (by [@jasperdevs](https://x.com/jasperdevs))

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
> 超現實主義對決——作者認為在藝術／超現實算圖上 Ideogram 4 明顯強於 GPT Image v2。

---

### Case 11: [口紅廣告：Ideogram 4 對比 GPT Image 2](https://x.com/VORTEX_Promos/status/2062276884738490397) (by [@VORTEX_Promos](https://x.com/VORTEX_Promos))

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
> 一次廣告創意比較（口紅廣告），在 Ideogram v4 與 GPT Image 2 之間比較。

---

### Case 12: [清晰銳利的開放權重生成](https://x.com/fofrAI/status/2062251438990930323) (by [@fofrAI](https://x.com/fofrAI))

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
> 開放權重展示——多種題材下清晰、新鮮的生成。

---

### Case 13: [開放模型的多風格表現](https://x.com/azed_ai/status/2062225166567149776) (by [@azed_ai](https://x.com/azed_ai))

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
> 同一個開放模型橫跨攝影、藝術、卡通與文字類設計。

---

### Case 14: [四張開源測試生成圖](https://x.com/ozansihay/status/2062305930994192638) (by [@ozansihay](https://x.com/ozansihay))

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
> 社群對剛開源的 Ideogram 4.0 的四張測試生成圖。

---

## 🙏 致謝

本倉庫受到優秀的開放提示詞合集與社群分享範例的啟發。

感謝所有公開分享作品、讓這些案例研究得以成立的創作者與貢獻者。

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

*我們無法保證每個案例都已正確歸屬到原始創作者。如有需要更正之處，請聯絡我們，我們會即時更新。*

如果你有更多有趣的提示詞案例想分享，歡迎聯絡我們，一起擴充 Evolink 提示詞庫。

[![Star History Chart](https://api.star-history.com/svg?repos=Evolink/awesome-ideogram-4.0-prompts&type=Date)](https://www.star-history.com/#Evolink/awesome-ideogram-4.0-prompts&Date)

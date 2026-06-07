<div align="center">

<a href="https://evolink.ai/models?utm_source=github&utm_medium=readme&utm_campaign=awesome-ideogram-4.0-prompts"><img src="images/logo.jpg" alt="awesome-ideogram-4.0-prompts logo"></a>

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](LICENSE)
[![Try it on Evolink](https://img.shields.io/badge/Try_it_on-Evolink-black)](https://evolink.ai/models?utm_source=github&utm_medium=readme&utm_campaign=awesome-ideogram-4.0-prompts)
[![Model](https://img.shields.io/badge/Model-Ideogram_4.0-purple)](https://evolink.ai/models?utm_source=github&utm_medium=readme&utm_campaign=awesome-ideogram-4.0-prompts)
[![Weights](https://img.shields.io/badge/Open_Weights-GitHub-blue)](https://github.com/ideogram-oss/ideogram4)
[![Cases](https://img.shields.io/badge/Cases-25-orange)](#-содержание)

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

## 🍌 Введение

Добро пожаловать в репозиторий промптов **Ideogram 4.0**! 🤗

**Мы собираем качественные промпты и примеры изображений для Ideogram 4.0 для широкого спектра задач и творческих рабочих процессов** — типографика и дизайн постеров, фотореалистичные портреты, дизайн продукта и упаковки, а также прямые сравнения моделей.

Ideogram 4.0 вышел 3 июня 2026 года как **лучшая в мире текстово-визуальная модель с открытыми весами** (№1 среди открытых моделей на сторонних аренах). Она предлагает нативное разрешение 2K, нативную прозрачность фона, плотный и точный многоязычный рендеринг текста и контроль макета через bounding-box — а ещё вы можете скачать веса, дообучить их и разместить у себя.

<div align="center">
<img src="images/leaderboard.png" alt="Ideogram 4.0 is the #1 open-weight model on the DesignArena Text-to-Image leaderboard" width="760">
<br><sub><b>Доказательство:</b> Ideogram 4.0 — модель <b>№1 с открытыми весами</b> в <a href="https://x.com/a16z/status/2062203114472813008">рейтинге DesignArena Text-to-Image</a> (Elo 1285) — уступает только закрытым моделям OpenAI и Google.</sub>
</div>

Большинство случаев в этом репозитории отобраны из X/Twitter, сообществ авторов и публичных демонстраций запуска.

Попробуйте на Evolink: [Ideogram 4.0](https://evolink.ai/models?utm_source=github&utm_medium=readme&utm_campaign=awesome-ideogram-4.0-prompts)

Если это полезно, поставьте звёздочку. ⭐

> [!NOTE]
> Этот репозиторий находится на ранней начальной стадии. Каждый случай показывает **реальное, публично опубликованное примерное изображение** с полным указанием авторства. Случаи включают блок `Prompt` **только если оригинальный автор опубликовал точный промпт** — мы никогда не выдумываем и не угадываем промпты, поэтому случаи дня запуска (где были показаны только результаты) намеренно опускают промпт и ссылаются на источник.

## 📰 Новости

- **June 3, 2026:** Вышел Ideogram 4.0 — текстово-визуальная модель №1 с открытыми весами на сторонних аренах, с нативным 2K, прозрачным фоном и загружаемыми открытыми весами.
- **June 3, 2026:** Доступно на партнёрских платформах запуска, включая Hugging Face, ComfyUI, fal, Runware, Magnific, Krea, Leonardo, Picsart, Cloudflare, Replicate, Gamma, Flora и Kittl.
- **June 4, 2026:** Первое обновление репозитория — 11 примеров дня запуска (галереи из нескольких изображений) в разделах категорий.
- **June 4, 2026:** Добавлены 4 случая прямого сравнения от RuntimeWire (с реальными промптами) — Ideogram 4.0 выигрывает тест преломления/физики стакана воды у OpenAI, Google и Microsoft.
- **June 4, 2026:** Добавлены ещё 8 случаев из 12-часового окна дня запуска — включая три с реальными опубликованными промптами (верёвочная типографика, макротипографика 1000×, абстрактный карандашный портрет) и пять витрин сообщества/сравнений.

- **7 июня 2026 г.:** Добавлены 2 кейса сообщества из первой волны выходных — японский фэнтези-промпт про школьницу-воительницу и продвинутый workflow-промпт для Ideogram 4 JSON caption generator.
## 📑 Содержание

- [🍌 Введение](#-введение)
- [📰 Новости](#-новости)
- [📑 Содержание](#-содержание)
- [📸 Примеры портрета и фотографии](#-примеры-портрета-и-фотографии)
  - [Case 1: Фотореалистичная текстура и несовершенства](#case-1-фотореалистичная-текстура-и-несовершенства-by-ideogram_ai)
  - [Case 2: Реалистичная текстура кожи персонажа](#case-2-реалистичная-текстура-кожи-персонажа-by-jerrod_lew)
- [🎨 Примеры постеров и иллюстраций](#-примеры-постеров-и-иллюстраций)
  - [Case 1: Типографика и графический дизайн](#case-1-типографика-и-графический-дизайн-by-ideogram_ai)
  - [Case 2: Граница дизайна](#case-2-граница-дизайна-by-ideogram_ai)
  - [Case 3: Типографика из верёвочных букв](#case-3-типографика-из-верёвочных-букв-by-umesh_ai)
  - [Case 4: Стресс-тест макротипографики 1000×](#case-4-стресс-тест-макротипографики-1000-by-squeakalgaib)
  - [Case 5: Плотные блоки текста в 2K](#case-5-плотные-блоки-текста-в-2k-by-jerrod_lew)
  - [Case 6: Абстрактный карандашный портрет в разрезах](#case-6-абстрактный-карандашный-портрет-в-разрезах-by-fofrai)
  - [Case 7: Упаковка продукта с пищевыми этикетками](#case-7-упаковка-продукта-с-пищевыми-этикетками-by-jerrod_lew)
  - [Case 8: Школьница-воительница исекая](#case-8-школьница-воительница-исекая-by-fet_shizaibu)
- [🧪 Сравнения и примеры сообщества](#-сравнения-и-примеры-сообщества)
  - [Case 1: Сравнение граффити на 10 моделях](#case-1-сравнение-граффити-на-10-моделях-by-geniart_fr)
  - [Case 2: Многоязычный рендеринг текста (чешский)](#case-2-многоязычный-рендеринг-текста-чешский-by-lukasersil)
  - [Case 3: Витрина дизайна раннего доступа](#case-3-витрина-дизайна-раннего-доступа-by-venturetwins)
  - [Case 4: Открыто и впечатляюще](#case-4-открыто-и-впечатляюще-by-a16z)
  - [Case 5: Скачок для открытой генерации изображений](#case-5-скачок-для-открытой-генерации-изображений-by-ludoviccreator)
  - [Case 6: Раскадровка стартапа из 4 панелей](#case-6-раскадровка-стартапа-из-4-панелей-by-runtimewire)
  - [Case 7: Четыре поколения смартфона](#case-7-четыре-поколения-смартфона-by-runtimewire)
  - [Case 8: Система фирменного стиля Nimbus](#case-8-система-фирменного-стиля-nimbus-by-runtimewire)
  - [Case 9: Физика преломления в стакане воды](#case-9-физика-преломления-в-стакане-воды-by-runtimewire)
  - [Case 10: Сюрреализм: Ideogram 4 против GPT Image 2](#case-10-сюрреализм-ideogram-4-против-gpt-image-2-by-jasperdevs)
  - [Case 11: Реклама помады: Ideogram 4 против GPT Image 2](#case-11-реклама-помады-ideogram-4-против-gpt-image-2-by-vortex_promos)
  - [Case 12: Чёткие генерации с открытыми весами](#case-12-чёткие-генерации-с-открытыми-весами-by-fofrai)
  - [Case 13: Открытая модель в разных визуальных стилях](#case-13-открытая-модель-в-разных-визуальных-стилях-by-azed_ai)
  - [Case 14: Четыре тестовые генерации с открытым кодом](#case-14-четыре-тестовые-генерации-с-открытым-кодом-by-ozansihay)
  - [Case 15: Ideogram 4 JSON Caption Generator](#case-15-ideogram-4-json-caption-generator-by-photogenicweeke)
- [🙏 Благодарности](#-благодарности)

## 📸 Примеры портрета и фотографии

### Case 1: [Фотореалистичная текстура и несовершенства](https://x.com/ideogram_ai/status/2062202376833106365) (by [@ideogram_ai](https://x.com/ideogram_ai))

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
> Ideogram 4.0 передаёт тонкую текстуру и естественные несовершенства, отличающие настоящую фотографию от ИИ-изображения, — всё в нативном 2K.

---

### Case 2: [Реалистичная текстура кожи персонажа](https://x.com/jerrod_lew/status/2062202782590095619) (by [@jerrod_lew](https://x.com/jerrod_lew))

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
> Шаг вперёд в детализации персонажей и текстуре кожи — одни из самых реалистичных людей, созданных моделью Ideogram на сегодня.

---

## 🎨 Примеры постеров и иллюстраций

### Case 1: [Типографика и графический дизайн](https://x.com/ideogram_ai/status/2062202335250764220) (by [@ideogram_ai](https://x.com/ideogram_ai))

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
> Типографика и графический дизайн остаются сильнейшими сторонами 4.0 — логотипы, постеры, многошрифтовые макеты, длинные тексты и креативная типографика, встроенная в дизайн.

---

### Case 2: [Граница дизайна](https://x.com/ideogram_ai/status/2062202271367336383) (by [@ideogram_ai](https://x.com/ideogram_ai))

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
> Плотный и точный рендеринг текста, нативное разрешение 2K, нативная прозрачность фона и точный контроль макета.

---

### Case 3: [Типографика из верёвочных букв](https://x.com/umesh_ai/status/2062257828249915733) (by [@umesh_ai](https://x.com/umesh_ai))

<img src="images/poster_case3/output.jpg" width="500">

**Prompt:**

```
"[NAME]" spelled out through the art of minimalist rope design. Each letter is shaped by the continuous twists and bends of a single red rope, placed against a clean white background. The rope curves naturally, with realistic tension and shadows, giving the impression of soft fiber under gentle strain. Negative space within the loops defines the letterforms clearly, while the rope’s overlapping layers suggest depth and intricacy. The composition conveys connection, resilience, and elegance, balancing simplicity with detail. The final aesthetic feels refined, meaningful, and inventive, presenting "[NAME]" as if written by the rope itself.
```

> [!NOTE]
> Замените `[NAME]` на слово, которое хотите выложить верёвкой. Показывает, как Ideogram 4.0 формирует читаемые буквы из единого непрерывного объекта с реалистичным натяжением и тенью.

---

### Case 4: [Стресс-тест макротипографики 1000×](https://x.com/SqueakAlGaib/status/2062371783400202255) (by [@SqueakAlGaib](https://x.com/SqueakAlGaib))

<img src="images/poster_case4/output.jpg" width="500">

**Prompt:**

```
The entire visible frame is a 1000x magnified view of a single printed letter 'G' from the word 'ELEGANCE' that is printed in 4-point Garamond type on a high-resolution magazine page. At this magnification, you can see the individual ink droplets from the CMYK printing process, the physical paper fiber texture of the coated stock (approximately 120 microns per fiber), the moiré pattern from the four-color halftone screen at 175 lines per inch, and the slight dot gain where cyan, magenta, yellow, and black inks are slightly misregistered (visible as tiny color fringes at letter edges). The 'G' itself is rendered in extreme serif detail showing the hairline serif with its bracketed transition from stroke, the actual ink pooling at stroke junctions due to surface tension, and the counter (negative space inside the G) showing the paper's natural off-white color. In the background, completely out of focus due to shallow depth of field at this magnification, you can barely make out the surrounding letters 'E-L-E-G-A-N-C-E' repeating in a pattern, some upside down, some rotated 180 degrees. The lighting is macro photography ring light from directly above, creating no shadows on the letter but revealing the subtle surface topography of the printed ink. At the TOP of the image, tiny 1mm text in the actual world scale reads 'magnified 1000×' in 6-point Helvetica, but this text must be barely legible despite being 1000x smaller than the main subject — a brutal scale contradiction.
```

> [!NOTE]
> Стресс-тест типографики: макроснимок печатной буквы при увеличении 1000×, на котором видны капли чернил, волокна бумаги, муар полутонов и крошечный, но читаемый текст подписи — демонстрация плотного рендеринга мелкого текста в 4.0.

---

### Case 5: [Плотные блоки текста в 2K](https://x.com/jerrod_lew/status/2062202754689552763) (by [@jerrod_lew](https://x.com/jerrod_lew))

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
> Нативная генерация 2K сохраняет плотные блоки текста чёткими — каждое слово яснее и детальнее, чем раньше.

---

### Case 6: [Абстрактный карандашный портрет в разрезах](https://x.com/fofrAI/status/2062264139574067612) (by [@fofrAI](https://x.com/fofrAI))

<img src="images/poster_case6/output.jpg" width="500">

**Prompt:**

```
a scan of a page from my high school A3 art pad, highly original niche pencil piece working on the aura of unusual cross sections and fluidity of otherwise solid surfaces in human portraiture with offset recursion, not anatomical, the cross sections reveal something else, very detailed and complex, no other anatomy, no embellishments, no pencil shavings, no tea stains, clean white paper
```

> [!NOTE]
> Абстрактный карандашный этюд разрезов и текучести в портрете человека — хороший пример нефотографической, тонко детализированной иллюстрации Ideogram 4.0.

---

### Case 7: [Упаковка продукта с пищевыми этикетками](https://x.com/jerrod_lew/status/2062202833219568018) (by [@jerrod_lew](https://x.com/jerrod_lew))

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
> Более сильные изображения продукта с точным текстом пищевой ценности. Для согласованности вместе с промптом можно передавать референсные изображения.

---


### Case 8: [Школьница-воительница исекая](https://x.com/FET_SHIZAIBU/status/2063462042221310257) (by [@FET_SHIZAIBU](https://x.com/FET_SHIZAIBU))

<img src="images/poster_case8/output.jpg" width="500">

**Prompt:**

```
異世界に転移した女子高生が、学生服（Yシャツにネクタイ、プリーツスカート）に肩当・胸当て・手甲を付けた戦士スタイルで、ショートソードを右手に、ラウンドシールドを左手に構え、真剣な表情で隙のない構えをとっている。アイレベルの全身ショット。アクションシーン。女子高生はやや画面右に位置したオフセット構図。画像解像度: 幅:1024 高さ:1024
```

> [!NOTE]
> Компактный японский фэнтези-экшен-промпт: школьная форма, лёгкая броня и стойка с мечом и щитом в чистом полнофигурном кадре.

---

## 🧪 Сравнения и примеры сообщества

### Case 1: [Сравнение граффити на 10 моделях](https://x.com/GenIArt_Fr/status/2062110258491691240) (by [@GenIArt_Fr](https://x.com/GenIArt_Fr))

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
> Независимое сравнение Ideogram 4.0 с ImagineArt 2.0, Krea 2.0, Recraft v4.1, Grok, Uni-1.1, Flux2-Pro, NanoBanana 2, GPT-Image-2 и Midjourney v8.1 на тему граффити.

---

### Case 2: [Многоязычный рендеринг текста (чешский)](https://x.com/lukasersil/status/2062203909465129310) (by [@lukasersil](https://x.com/lukasersil))

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
> Независимый тест читаемого рендеринга чешского текста — сильный реальный сигнал для неанглийской типографики. Автор отметил, что промпты длинные, и опубликовал их в ответах.

---

### Case 3: [Витрина дизайна раннего доступа](https://x.com/venturetwins/status/2062207215961014735) (by [@venturetwins](https://x.com/venturetwins))

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
> Примеры раннего доступа, подчёркивающие сильный рендеринг текста, вывод высокого разрешения и качество дизайна.

---

### Case 4: [Открыто и впечатляюще](https://x.com/a16z/status/2062203114472813008) (by [@a16z](https://x.com/a16z))

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
> Витрина инвестора, представляющая Ideogram 4.0 как открытую, загружаемую модель — «потрясающе, и это открыто».

---

### Case 5: [Скачок для открытой генерации изображений](https://x.com/LudovicCreator/status/2062207302690832683) (by [@LudovicCreator](https://x.com/LudovicCreator))

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
> Мнение создателя из раннего доступа: открытые веса, самостоятельный хостинг, дообучение, доступ по API, нативный 2K, прозрачный фон и более сильный рендеринг текста.

---

### Case 6: [Раскадровка стартапа из 4 панелей](https://runtimewire.com/article/we-put-ideogram-4-head-to-head-against-openai-google-and-microsoft-in-four-image) (by [@runtimewire](https://x.com/runtimewire))

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
> Очная дуэль RuntimeWire (OpenAI против Google против Microsoft против Ideogram). Сюжетный тест от гаражного стартапа до листинга на Nasdaq с сохранением согласованности персонажей между панелями. Рейтинг: Google > Microsoft > OpenAI > Ideogram.

---

### Case 7: [Четыре поколения смартфона](https://runtimewire.com/article/we-put-ideogram-4-head-to-head-against-openai-google-and-microsoft-in-four-image) (by [@runtimewire](https://x.com/runtimewire))

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
> Очная дуэль RuntimeWire. Тест эволюции продукта (правдоподобное развитие с 2007 по 2035 год). Рейтинг: OpenAI > Microsoft > Google > Ideogram.

---

### Case 8: [Система фирменного стиля Nimbus](https://runtimewire.com/article/we-put-ideogram-4-head-to-head-against-openai-google-and-microsoft-in-four-image) (by [@runtimewire](https://x.com/runtimewire))

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
> Очная дуэль RuntimeWire. Полный тест фирменного стиля — основной и альтернативный логотип, иконка приложения, визитка, главная страница сайта, цветовая палитра и упаковка. Рейтинг: OpenAI > Google > Microsoft > Ideogram.

---

### Case 9: [Физика преломления в стакане воды](https://runtimewire.com/article/we-put-ideogram-4-head-to-head-against-openai-google-and-microsoft-in-four-image) (by [@runtimewire](https://x.com/runtimewire))

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
> Очная дуэль RuntimeWire — Ideogram 4.0 ВЫИГРАЛ этот тест. Тест физической достоверности взаимодействия воды/стекла/света/тени/текста. Рейтинг: Ideogram > Google > OpenAI > Microsoft.

---

### Case 10: [Сюрреализм: Ideogram 4 против GPT Image 2](https://x.com/jasperdevs/status/2062232495517552716) (by [@jasperdevs](https://x.com/jasperdevs))

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
> Дуэль сюрреализма — автор счёл Ideogram 4 заметно сильнее GPT Image v2 в художественных/сюрреалистичных рендерах.

---

### Case 11: [Реклама помады: Ideogram 4 против GPT Image 2](https://x.com/VORTEX_Promos/status/2062276884738490397) (by [@VORTEX_Promos](https://x.com/VORTEX_Promos))

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
> Сравнение рекламной концепции (кампания помады) между Ideogram v4 и GPT Image 2.

---

### Case 12: [Чёткие генерации с открытыми весами](https://x.com/fofrAI/status/2062251438990930323) (by [@fofrAI](https://x.com/fofrAI))

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
> Витрина открытых весов — чёткие, свежие генерации на разные темы.

---

### Case 13: [Открытая модель в разных визуальных стилях](https://x.com/azed_ai/status/2062225166567149776) (by [@azed_ai](https://x.com/azed_ai))

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
> Одна открытая модель в фотографии, искусстве, мультфильмах и текстовом дизайне.

---

### Case 14: [Четыре тестовые генерации с открытым кодом](https://x.com/ozansihay/status/2062305930994192638) (by [@ozansihay](https://x.com/ozansihay))

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
> Четыре тестовые генерации сообщества для только что открытого Ideogram 4.0.

---


### Case 15: [Ideogram 4 JSON Caption Generator](https://x.com/PhotogenicWeekE/status/2063453896337715389) (by [@PhotogenicWeekE](https://x.com/PhotogenicWeekE))

<table>
<tr>
<td width="50%">

<img src="images/comparison_case15/output.jpg" width="100%">

</td>
<td width="50%">

<img src="images/comparison_case15/output2.jpg" width="100%">

</td>
</tr>
<tr>
<td width="50%">

<img src="images/comparison_case15/output3.jpg" width="100%">

</td>
</tr>
</table>

**Prompt:**

```
    You are an Ideogram 4 JSON caption generator.

    The user will specify the aspect ratio, resolution, and image content. Use both the aspect ratio and pixel dimensions to calculate appropriate bbox coordinates on the 0-1000 scale.

    When the user describes an image, output ONLY a valid JSON object. No explanation, no markdown, no code blocks — raw JSON only.

    ## Aspect ratio, resolution and bbox relationship

    bbox is [ymin, xmin, ymax, xmax] on a 0-1000 normalized scale.
    The 0-1000 grid maps to actual pixel dimensions according to the resolution.
    You MUST use both aspect ratio AND pixel dimensions when placing elements.

    For example:
    - At 1024x1536: (ymax - ymin) / 1000 × 1536px = actual vertical pixels for the element
    - At 2048x3072: (ymax - ymin) / 1000 × 3072px = actual vertical pixels for the element
    - At 1024x1024: (ymax - ymin) / 1000 × 1024px = actual vertical pixels for the element
    - At 1680x944: (ymax - ymin) / 1000 × 944px = actual vertical pixels for the element
    - Always verify that bbox gives enough pixel space for the described subject

    ### Vertical landmark guide by aspect ratio

    For a full standing figure, use these approximate ymin/ymax landmarks:

    | Body part   | 2:3 (portrait) | 1:1 (square) | 3:2 (landscape) | 16:9 (landscape) |
    |-------------|----------------|--------------|-----------------|------------------|
    | Top of head | 30             | 30           | 50              | 80               |
    | Chin        | 150            | 200          | 250             | 280              |
    | Shoulders   | 200            | 250          | 300             | 330              |
    | Chest       | 250            | 320          | 370             | 400              |
    | Waist       | 450            | 520          | 560             | 580              |
    | Hips        | 550            | 600          | 630             | 650              |
    | Knees       | 750            | 780          | 800             | 820              |
    | Ankles      | 900            | 920          | 930             | 940              |
    | Bottom edge | 970            | 970          | 970             | 970              |

    ### Pixel verification examples

    At 1024x1536 (2:3):
    - Full body ymin=30, ymax=950 → (950-30)/1000 × 1536 = 1413px ✓ sufficient
    - Wrong: ymin=100, ymax=800 → (800-100)/1000 × 1536 = 1075px ✗ too tight, will crop

    At 2048x3072 (2:3):
    - Full body ymin=30, ymax=950 → (950-30)/1000 × 3072 = 2826px ✓ sufficient

    At 2048x2048 (1:1):
    - Full body ymin=30, ymax=970 → (970-30)/1000 × 2048 = 1925px ✓ sufficient

    At 1024x1024 (1:1):
    - Full body ymin=30, ymax=970 → (970-30)/1000 × 1024 = 962px ✓ sufficient

    At 1680x944 (16:9):
    - Waist-up ymin=80, ymax=700 → (700-80)/1000 × 944 = 585px ✓ sufficient
    - Full body is not recommended for 16:9 — vertical space (944px) is too limited for a standing figure
    - Prefer waist-up, bust-up, or scene/group compositions for 16:9

    Always perform this verification before finalizing bbox values.

    ### Framing rules

    - Full body (head to ankle): ymin ~30, ymax ~950 (portrait only — avoid for 16:9)
    - Knee-up crop: ymin ~30, ymax ~800
    - Waist-up crop: ymin ~30, ymax ~600 (portrait) / ymin ~80, ymax ~700 (16:9)
    - Bust-up crop: ymin ~30, ymax ~450 (portrait) / ymin ~80, ymax ~600 (16:9)
    - Face close-up: ymin ~30, ymax ~300 (portrait) / ymin ~100, ymax ~700 (16:9)
    - Scene/cinematic: multiple subjects or environment — distribute horizontally for 16:9

    For portrait 2:3, a subject filling the frame vertically should use:
      ymin: 20–50, ymax: 930–970
    Never place a full standing figure with ymin > 100 or ymax < 850 in 2:3 portrait.

    ### Horizontal placement guide

    - Center: xmin ~200, xmax ~800
    - Slight left offset: xmin ~100, xmax ~650
    - Slight right offset: xmin ~350, xmax ~900
    - Full width: xmin ~50, xmax ~950
    - For 16:9 multi-subject: distribute across xmin ~50–950 with subjects at ~150–400, ~400–650, ~600–900

    ## Framing rules for full-body shots

    When the subject is a standing or full-body figure (portrait orientations only):
    - Always include in high_level_description: "full body visible from head to feet, no cropping, entire figure within frame"
    - Always include in the primary subject element desc: "full body visible, head to feet entirely within frame, no cropping at top or bottom"
    - Set subject bbox with sufficient vertical margin: ymin 20–50, ymax 930–970
    - Never let the subject bbox touch or exceed the frame edges vertically

    When the user specifies a crop (knee-up, waist-up, bust-up):
    - Apply the framing guide table above
    - Do NOT add full-body language to desc

    For 16:9 landscape:
    - Do NOT attempt full-body standing figure unless explicitly requested
    - Default to waist-up or scene composition
    - Distribute elements horizontally to use the wide frame effectively

    ## bbox verification rule

    Before outputting, explicitly calculate:
    - vertical pixels = (ymax - ymin) / 1000 × height_px
    - horizontal pixels = (xmax - xmin) / 1000 × width_px
    - If the user requested full body or knee-up, vertical pixels must be at least:
      - full body: height_px × 0.85 or more
      - knee-up: height_px × 0.70 or more
    - If the calculation fails, expand ymin toward 20 and ymax toward 950 and recalculate
    - For portrait orientation (height_px > width_px): the subject's bbox height (ymax - ymin) must always be greater than its bbox width (xmax - xmin). Never output a bbox where xmax - xmin > ymax - ymin for a portrait image.
    - For landscape orientation (width_px > height_px): the subject's bbox width (xmax - xmin) is naturally larger than height — this is expected and correct.

    ## Output format

    {
      "high_level_description": "...",
      "style_description": {
        "aesthetics": "...",
        "lighting": "...",
        "photo": "...",
        "medium": "...",
        "color_palette": ["#RRGGBB", ...]
      },
      "compositional_deconstruction": {
        "background": "...",
        "elements": [
          {
            "type": "obj",
            "bbox": [ymin, xmin, ymax, xmax],
            "desc": "...",
            "color_palette": ["#RRGGBB", ...]
          }
        ]
      }
    }

    ## Rules

    - Key order must be exactly as shown above
    - bbox: [ymin, xmin, ymax, xmax] on 0-1000 scale
    - color_palette: uppercase #RRGGBB only, max 16 for style_description, max 5 per element
    - style uses either "photo" key (photographic) or "art_style" key (illustration/painting) — never both
    - If art_style: key order is aesthetics, lighting, medium, art_style, color_palette
    - type "text" requires a "text" field inserted between "bbox" and "desc"
    - elements listed background-to-foreground
    - The primary subject must always be fully contained within the 0-1000 grid — never let head or feet exceed the frame
    - Output raw JSON only, nothing else

    ## Input format

    The user will provide:
    - Aspect ratio and resolution (e.g. "2:3 1024x1536", "2:3 2048x3072", "1:1 1024x1024", "1:1 2048x2048", "16:9 1680x944", "16:9 1920x1080", "9:16 1080x1920")
    - Image description in natural language

    Use both the aspect ratio AND the pixel dimensions to calculate bbox coordinates.
    Always verify that (ymax - ymin) / 1000 × height_px gives sufficient vertical pixels for the subject before finalizing bbox values.
```

> [!NOTE]
> Основной пост показывает результаты workflow; полный system prompt был опубликован в ответе самого автора и сохранён здесь как переиспользуемый power-user шаблон для структурированного layout-prompting в Ideogram 4.

---

## 🙏 Благодарности

Этот репозиторий вдохновлён превосходными открытыми коллекциями промптов и примерами, которыми поделилось сообщество.

Спасибо авторам и участникам, которые публично поделились своей работой и сделали эти примеры возможными.

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

*Мы не можем гарантировать, что каждый случай атрибутирован оригинальному автору. Если что-то нужно исправить, свяжитесь с нами, и мы обновим.*

Если у вас есть ещё интересные примеры промптов, пишите нам и помогите расширить библиотеку промптов Evolink.

[![Star History Chart](https://api.star-history.com/svg?repos=Evolink/awesome-ideogram-4.0-prompts&type=Date)](https://www.star-history.com/#Evolink/awesome-ideogram-4.0-prompts&Date)

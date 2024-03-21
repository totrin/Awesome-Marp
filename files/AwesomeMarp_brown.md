---
marp: true
size: 16:9
theme: am_brown
paginate: true
headingDivider: [2,3]
footer: \ *Chuhong (Rainbow Goose Manor)* *Awesome Marp: Replace LaTeX Beamer!* *January 13, 2024 (v1.3)*
---

<!-- _class: cover_a 
<!-- _header: "" --> 
<!-- _footer: "" --> 
<!-- _paginate: "" --> 

# Awesome Marp: Replace LaTeX Beamer!

###### "Simple to use, fully-featured personalized PPT template"

@Chuhong
WeChat: Rainbow Goose Manor
Release Date: January 13, 2024 (v1.3)
<ch2099058972@163.com>
Awesome-Marp Address: [GitHub Repository](https://github.com/favourhong/Awesome-Marp)/[Gitee Repository](https://gitee.com/favourhong/Awesome-Marp)

## What is Awesome Marp?

<!-- _class: cols2_ol_ci fglass toc_a  -->
<!-- _footer: "" -->
<!-- _header: "CONTENTS" -->
<!-- _paginate: "" -->

- [About the Template](#3)
- [Cover Page](#10) 
- [Table of Contents](#16)
- [Column and List Splitting](#20)
- [Quotes, Links, and Callout Boxes](#38)
- [Navigation Bar](#45)
- [Other Custom Styles](#48)
- [Basic Knowledge You Need to Know](#56)
- [Last Page](#59)

## 1. About the Template

<!-- _class: trans -->
<!-- _footer: "" -->
<!-- _paginate: "" -->

## 1. About the Template

- **Before you start:** You need to know about these tools, Markdown, Markdown editor (VS Code or Obsidian), and Marp. I won't go into detail about what these are, but there will be some concise content for your reference on [pages 55](#55) to [58](#58), along with several links for you to check out.
- **Why develop Awesome Marp?** 
  - Marp natively only offers 3 themes (`default` / `gaia` / `uncover`), with average presentation effects. So, based on my usage, I gradually polished this entire set of templates while using and modifying them.
- **Features of Awesome Marp:**
  - Supports column presentation, Callouts (similar to Beamer's theorem boxes), provides various types of cover and table of contents pages, can implement navigation progress bars, supports custom alignment of images (center/left/right), etc.

- Following the principle of "ready to use," I have uploaded the project folder to [GitHub](https://github.com/favourhong/Awesome-Marp) and [Gitee](https://gitee.com/favourhong/Awesome-Marp).
- Tools used: Software [Visual Studio Code](https://code.visualstudio.com) or [Obsidian](https://obsidian.md/), [Marp for VScode (plugin)](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode)

## 1. About the Template

- Awesome Marp supports 38 custom styles, which need to be specified on the page (e.g., `<!-- _class: trans -->`):

| Cover Page | Table of Contents | Columns       | Callout Boxes | Other 1                      | Other 2                                                        |
| ---------- | ----------------- | ------------- | ------------- | --------------------------- | ------------------------------------------------------------- |
| `cover_a`  | `toc_a`           | `cols-2`      | `bq-black`    | Transition page `trans`     | Title for figures, etc. `caption`                              |
| `cover_b`  | `toc_b`           | `cols-2-64`   | `bq-purple`   | Last page `lastpage`        | Frosted glass effect for non-nested unordered lists `fglass`   |
| `cover_c`  |                   | `cols-2-73`   | `bq-red`      | Navigation bar `navbar`     | Footnote: `footnote`                                           |
| `cover_d`  |                   | `cols-3`      | `bq-blue`     | Fixed title + no background `fixedtitleA` | Adjust font size: `tinytext`/`smalltext`/<br>`largetext`/`hugetext` |
| `cover_e`  |                   | `cols-2-46`   | `bq-green`    | Fixed title + background `fixedtitleB` |                                                               |
|            |                   | `cols-2-37`   |               | Two-column ordered list `cols2_ol_sq/ci` |                                                               |
|            |                   | `rows-2`      |               | Two-column unordered list `cols_ul_sq/ci` |                                                               |
|            |                   | `pin-3`       |               | Single-column ordered list `col1_ul_sq/ci` |                                                               |

## 1. About the Template

- Awesome Marp's theme colors (6 types), can switch Theme in the YAML section, like `theme: am_dark`:

| Dark      | Green      | Red    | Blue     | Brown      | Purple |
|-----------|------------|--------|----------|------------|--------|
| `am_dark` | `am_green` | `am_red` | `am_blue` | `am_brown` |`am_purple`|

## 1. About the Template

- How to use:
  - **With VS Code**: Simply open the `Awesome-Marp` folder with VS Code.
    - If you want to "use it right away," just modify according to the shared Markdown source code.
    - If you are not satisfied with some effects and expect simple adjustments, currently there are 6 CSS files under `Awesome-Marp/themes`, which determine the final rendering effect of the Markdown source code, you can try to modify them.
    - If you can customize your personalized CSS file, don't forget to add your CSS file path in `Awesome-Marp/.vscode/settings.json` before rendering.

- Fonts: Fonts used in Awesome Marp include:
  - Body font: `Latin Modern Math`, if not installed, the default will be `Calibri` and `KaiTi`.
  - Title font: `Optima LT Medium`, if not installed, the default will be `Arial` and `SimHei`.
  - Footnote font: `Charm`, if not installed, the default will be `Calibri` and `KaiTi`.
  - Code font: `Fira Code`, if not installed, the default will be `Consolas` and `STZhongsong`.

## 1. About the Template: Update Log

- [Awesome Marp: I developed a whole set of Marp themes, Markdown converted PPT can also look good!](https://mp.weixin.qq.com/s?__biz=MzkwOTE3NDExOQ==&mid=2247486787&idx=1&sn=2652ddae81f50240844cb652780912e1&chksm=c13ff94bf648705da1ba986b91265e3ff018acaffcfa60d7807a81be22176005e7a2b4483627&scene=178&cur_album_id=3132459596339757070#rd)
- [Awesome Marp v1.1: The title row does not float with the text, now it's more like Beamer!](https://mp.weixin.qq.com/s?__biz=MzkwOTE3NDExOQ==&mid=2247486800&idx=1&sn=527348e242576079e4bd6cd1823c823a&chksm=c13ff958f648704e40a202db6ad5fa215ef4c189d66403e161d6ace9828406a8747ac755684f&scene=178&cur_album_id=3132459596339757070#rd)
- [Awesome Marp v1.2: Added footnotes, adjust font size and other styles~](https://mp.weixin.qq.com/s?__biz=MzkwOTE3NDExOQ==&mid=2247486825&idx=1&sn=56d632ce164831438ec87c1b20ed4c4c&chksm=c13ff961f64870774f069ab816340783d8f54fd6b89363b8d9412c593efc640851ce9edd8833&scene=178&cur_album_id=3132459596339757070#rd) 

## Let's take a look at the effects ~  

<!-- _class: trans -->
<!-- _footer: "" -->
<!-- _paginate: "" -->

## 2. Cover Page

<!-- _class: trans -->
<!-- _footer: "" -->
<!-- _paginate: "" -->

## 2. Cover Page

- Large title: Use a level 1 heading `# ` (e.g., `# Awesome Marp: Custom Marp Theme`)
- Subtitle: Use a level 6 heading `###### ` (e.g., `###### Crafting a Simple Yet Distinctive Presentation`)
- This template provides 5 types of cover page styles, which need to be set in the page using local directives, like: `<!-- _class: cover_a -->` 
  - `cover_a`: [1st type](#1)
  - `cover_b`: [2nd type](#12)
  - `cover_c`: Reserved header for school logo, footer for motto [3rd type](#13)
  - `cover_d`: Only reserved footer for motto [4th type](#14)
  - `cover_e`: Reserved header for school logo, footer for school logo and name [5th type](#15)

- If a global footer, header, or pagination has already been set but is not desired on the cover page, you can use `<!-- _footer: "" -->` / `<!-- _header: "" -->` / `<!-- _paginate: "" -->` to hide them locally.
- When the title text exceeds the page width, it will overflow and wrap. Here, you can use `<!-- fit -->` to automatically adjust the text size based on the page width.

---

<!-- _class: cover_b -->
<!-- _header: "" -->
<!-- _footer: "" -->
<!-- _paginate: "" -->

# Awesome Marp: Replace LaTeX Beamer!

###### "Simple to use, fully-featured personalized PPT template"

@Chuhong
WeChat: Rainbow Goose Manor
Release Date: January 13, 2024 (v1.3)
<ch2099058972@163.com>
Awesome-Marp Address: [GitHub Repository](https://github.com/favourhong/Awesome-Marp)/[Gitee Repository](https://gitee.com/favourhong/Awesome-Marp)

---

<!-- _class: cover_c -->
<!-- _paginate: "" -->

# <!-- fit -->Awesome Marp: Replace LaTeX Beamer!

###### "Simple to use, fully-featured personalized PPT template"

---

<!-- _class: cover_d -->
<!-- _paginate: "" -->
<!-- _footer: "Climb high, seek knowledge" -->

# <!-- fit -->Awesome Marp: Easily Replace LaTeX Beamer!

###### "Simple to use, fully-featured personalized PPT template"

@Chuhong
WeChat Public Account: Honghu Villa
Release Date: January 13, 2024 (v1.3)
<ch2099058972@163.com>
Awesome-Marp Address: [GitHub Repository](https://github.com/favourhong/Awesome-Marp)/[Gitee Repository](https://gitee.com/favourhong/Awesome-Marp)

---

<!-- _class: cover_e -->
<!-- _paginate: "" -->
<!-- _footer: ![](https://mytuchuang-1303248785.cos.ap-beijing.myqcloud.com/picgo/202309231557236.png) -->
<!-- _header: ![](https://mytuchuang-1303248785.cos.ap-beijing.myqcloud.com/picgo/202309231558983.png) -->

# <!-- fit -->Awesome Marp: Easily Replace LaTeX Beamer!

###### "Simple to use, fully-featured personalized PPT template"

@Chuhong
WeChat Public Account: Honghu Villa
Release Date: January 13, 2024 (v1.3)
<ch2099058972@163.com>
Awesome-Marp Address: [GitHub Repository](https://github.com/favourhong/Awesome-Marp)/[Gitee Repository](https://gitee.com/favourhong/Awesome-Marp)

## 3. Table of Contents

<!-- _class: trans -->
<!-- _footer: "" -->
<!-- _paginate: "" -->

## 3. Table of Contents

- Awesome Marp provides at least two styles of table of contents pages, which require setting local styles when used.
  - `toc_a`: The content of the header needs to be set to `CONTENTS`, i.e., `<!-- _header: "CONTENTS" -->`.
  - `toc_b`: The content of the header needs to be set to `Table of Contents<br>CONTENTS<br>Your LOGO address`, i.e., `<!-- _header: Table of Contents<br>CONTENTS<br>![](./logo.png)-->`.
  - The various columnar list styles provided can also be used as table of contents pages, such as `<!-- _class: cols2_ol_ci fglass -->` (see the effect [here](#32)).

- Similarly, if a global footer or page number has already been defined, you can use `<!-- _footer: "" -->` / `<!-- _paginate: "" -->` to hide them locally.
- Table of contents styles: [First kind](#2), [Second kind](#18), and [Third kind](#19).

---

<!-- _class: toc_a -->
<!-- _header: "CONTENTS" -->
<!-- _footer: "" -->
<!-- _paginate: "" -->

- [About the Template](#3)
- [Cover Page](#10) 
- [Table of Contents](#16)
- [Page Columns and List Columns](#20)
- [Quotes, Links, and Callouts](#38)
- [Navigation Bar](#45)
- [Other Custom Styles](#48)
- [Basic Knowledge You Need to Know](#56)
- [Last Page](#59)

---

<!-- _header: Table of Contents<br>CONTENTS<br>![](https://mytuchuang-1303248785.cos.ap-beijing.myqcloud.com/picgo/202309231558983.png)-->
<!-- _class: toc_b -->
<!-- _footer: "" -->
<!-- _paginate: "" -->

- [About the Template](#3)
- [Cover Page](#10) 
- [Table of Contents](#16)
- [Page Columns and List Columns](#20)
- [Quotes, Links, and Callouts](#38)
- [Navigation Bar](#45)
- [Other Custom Styles](#48)
- [Basic Knowledge You Need to Know](#56)
- [Last Page](#59)

## 4. Page breaks vs. list breaks

<!-- _class: trans -->
<!-- _footer: "" -->
<!-- _paginate: "" -->

## 4.1 Page Splits and List Splits: Page Splits

- Awesome Marp provides 8 types of page splits, they are:
 - `cols-2`: [two columns, split 50/50](#23)
 - `cols-2-64`: [two columns, split 60/40] (#24)
 - `cols-2-73`: [two columns split, seventy-three] (#25)
 - `cols-2-46`: [two columns divided into columns, four-sixths] (#26)
 - `cols-2-37`: [two columns split, three-seven] (#27) 
- `cols-3`: [three columns divided equally] (#28)
 - `rows-2`: [two rows divided into columns] (#29)
 - `pin-3`: [pinned column](#30)

- If a column is an image, you can replace `class=ldiv` with `class=limg` to achieve vertical center alignment of the image (`class=ldiv` is top aligned).


## 4.1 Page breaks and list breaks: page breaks

- The `<!-- _class: cols-2 -->` As an example, the Markdown source code is:

```markdown
<!-- _class: cols-2 -->'. 
<div class=ldiv> 

The content of the first column (left sidebar) is here

The content can be plain plain text, a list, a quote block, a link, an image, etc.
</div>

<div class=rdiv>

The content of the second column (right-hand column) is here
</div
```

- If it's in three columns (`<! -- _class: cols-3 -->`), another `<div class="mdiv"></div>` tag would be required


## The Lotus Pond (two columns in fifty-fifty)

<!-- _class: cols-2 -->

<div class=ldiv>

Above the curving lotus pond, mesmerized by fields of leaves. The leaves are very high out of the water, like the skirts of the dancers in the pavilion.

Layers of leaves in the middle, sporadically dotted with some white flowers, there are curly open, there are shyly dozen; as a grain of pearl, such as the stars in the blue sky, and as just out of the bath of the beauty.

Breeze, send a wisp of fragrance, as if the distant high building faint song. At this time the leaves and flowers also have a tremor, like lightning, all of a sudden spread across the lotus pond over there.

The leaves are shoulder to shoulder and close together, which is like a condensed blue wave mark. Underneath the leaves is a vein of flowing water, covered, can not see some color; but the leaves are more to see the style.

-- Zhu Ziqing, Moonlight in a Lotus Pond [Back](#21)
</div>

<div class=rimg>

<!-- ! [#c](https://mytuchuang-1303248785.cos.ap-beijing.myqcloud.com/picgo/202309221014499.png) -->
![#c](https://mytuchuang-1303248785.cos.ap-beijing.myqcloud.com/picgo/202309221630151.png)
</div>

## "Spring" (two columns of sixty-four cents)

<!-- _class: cols-2-64 -->

<div class=limg>

![#c](https://mytuchuang-1303248785.cos.ap-beijing.myqcloud.com/picgo/202309201217248.png)
</div>

<div class=rdiv>

Hopefully, hopefully, the east wind came, the footsteps of spring is close.

Everything is like just waking up like, gladly opened his eyes. The mountains are moist, the water rises, the sun's face red.

The grass sneaks out of the earth, tender and green. In the garden, in the field, look, a large area full of a large area. Sitting, lying, playing two rolls, kicking a few feet ball, race a few times running, catch a few times hide and seek. The wind is gentle and the grass is soft.

-- Zhu Ziqing's Spring

[Back](#21)
</div

## Classic Prose Verses (Two Columns, Seven Thirds)

<!-- _class: cols-2-73 -->

<div class=limg>

![#c](https://mytuchuang-1303248785.cos.ap-beijing.myqcloud.com/picgo/202309221010523.png)

</div>

<div class=rdiv>

Classic prose verses are:

- Zhu Ziqing: Moonlight in a Lotus Pond
- Lin Qingxuan: Moon to the Center of the Sky
- Yu Dafu: "Autumn in the Ancient Capital".
- Eileen Chang: The Sound of Falling Flowers
- Yu Guangzhong: "Listen to the Cold Rain".
- ZHANG Nanzhang: "The Rejection of Peony".
- Feng Zikai: The Willow
- ZHOU Zuoren: The Black-topped Boat
- ZHENG Zhenduo: The Stone Lake
- Liang Shiqiu: The House of Grace

[Back](#21)
</div>

## "Spring" (2 columns, 46 cents)

<!-- _class: cols-2-46 -->

<div class=ldiv>


Hopefully, hopefully, the east wind has come, and the footsteps of spring are near.

Everything looks like it has just woken up and opened its eyes gladly. The mountains are moist, the water rises, the sun's face is red.

The grass sneaks out of the earth, tender and green. In the garden, in the field, look, a large area full of a large area. Sitting, lying, playing two rolls, kicking a few feet ball, race a few times running, catch a few times hide and seek. The wind is gentle and the grass is soft.

-- Zhu Ziqing's Spring

[Back](#21)
</div>

<div class=rimg>

![#c](https://mytuchuang-1303248785.cos.ap-beijing.myqcloud.com/picgo/202309201217248.png)
</div>

## Classic Prose Verses (Two Columns and Three Sevens)

<!-- _class: cols-2-37 -->

<div class=ldiv>


The classic prose poems are:

- Zhu Ziqing: Moonlight in a Lotus Pond
- Lin Qingxuan: The Moon to the Center of the Sky
- Yu Dafu: "Autumn in the Ancient Capital".
- Eileen Chang: The Sound of Falling Flowers
- Yu Guangzhong: "Listen to the Cold Rain".
- ZHANG Nanzhang: "The Rejection of Peony".
- Feng Zikai: The Willow
- ZHOU Zuoren: The Black-topped Boat
- ZHENG Zhenduo: The Stone Lake
- Liang Shiqiu: The House of Grace

[Back](#21)
</div>

<div class=rimg>

![#c](https://mytuchuang-1303248785.cos.ap-beijing.myqcloud.com/picgo/202309221010523.png)
</div>

## Summer and Fall (three columns and three equal parts)

<!-- _class: cols-3 -->

<div class=ldiv>

![#center](https://mytuchuang-1303248785.cos.ap-beijing.myqcloud.com/picgo/202309201206630.png)

</div>

<div class=mdiv>

![#center](https://mytuchuang-1303248785.cos.ap-beijing.myqcloud.com/picgo/202309201151809.png)

![#center](https://mytuchuang-1303248785.cos.ap-beijing.myqcloud.com/picgo/202309201158036.png)
</div>

<div class=rdiv>

![#center](https://mytuchuang-1303248785.cos.ap-beijing.myqcloud.com/picgo/202309201154535.png)

[return](#21)
</div>


## High mountains and deserts (two-line split column)

<!-- _class: rows-2 -->

<div class="timg">

![#c h:250](https://mytuchuang-1303248785.cos.ap-beijing.myqcloud.com/picgo/202401131736186.png)
</div>

<div class="bimg">

![#c h:260](https://mytuchuang-1303248785.cos.ap-beijing.myqcloud.com/picgo/202401131737821.png)
</div>

## The Mystery of the Universe (pint-sized columns)

<!-- _class: pin-3 -->

<div class="tdiv">

> Four hundred years ago, two very different scientists pushed the boundaries of the then-known world. in Venice in 1609, Galileo Galilei looked at the stars through a telescope, built instruments, and conducted experiments. In Prague, the theologian Johannes Kepler discovered the laws of planetary motion, laying the foundations of modern astrophysics and contemplating the grand structure of the universe. Drawing on a hitherto little-noticed but heart-wrenching exchange of correspondence, 
</div>

<div class="limg">

![#c](https://mytuchuang-1303248785.cos.ap-beijing.myqcloud.com/picgo/202401131712626.png)
</div>

<div class="rimg">

![#c h:260](https://mytuchuang-1303248785.cos.ap-beijing.myqcloud.com/picgo/202401131713779.png)
</div


## 4.2 Page Split and List Split: List Split

Awesome Marp v1.3 provides 6 ways of list breakdown, they are:

- `cols2_ol_sq`: render as [ordered list + square number](#32)
- `cols2_ol_ci`: rendering as [ordered list + round number](#33)
- `cols2_ul_sq`: render as [unordered list + square number](#34)
- `cols2_ul_ci`: rendered as [unordered list + circle number](#35)
- `col1_ul_sq`: render as [ordered list + square number](#36)
- `col1_ul_ci`: rendering effect as [ordered list + circular serial number](#37)


## Microeconomics: A Modern Perspective

<!-- _class: cols2_ol_sq fglass -->

Rendering is **ordered list + square serial number**
Custom styles are `<!-- _class: cols2_ol_sq fglass -->`

- Preferences and utility
- Budget constraints and consumer optimality
- Demand functions
- Supply functions for labor and savings
- Welfare economics: single and multi-input models
- Theory of the firm: single and multiple input goods models
- Perfectly competitive markets
- Perfect monopoly, monopolistic competition and duopoly
- Game theory
- Exchange and production economies


[Back](#28)


## Microeconomics: A Modern Perspective

<!-- _class: cols2_ol_ci fglass -->

Rendering is **ordered list + rounded serial number**
Custom styles are: `<!-- _class: cols2_ol_ci fglass -->`

- Preferences and utility
- Budget constraints and consumer optimality
- Demand functions
- Supply functions for labor and savings
- Welfare economics: single and multi-input models
- Theory of the firm: single and multiple input goods models
- Perfectly competitive markets
- Perfect monopoly, monopolistic competition and duopoly
- Game theory
- Exchange and production economies

[Back](#28)

## Staying Out of the Way

<!-- _class: cols2_ul_sq fglass -->

Rendering is **unordered list + square ordinal numbers**
Custom styles are: `<!-- _class: cols2_ul_sq fglass -->`

- Chapter 1: The Powers and Affairs of Local Government 
- Chapter 2: Finance, Taxation, and Government Behavior 
- Chapter 3: Government Investment and Debt 
- Chapter 4: The Role of Government in Industrialization 
- Chapter 5: Urbanization and Imbalance 
- Chapter 6: Debt and Risk 
- Chapter 7: Domestic and International Imbalances 
- Chapter 8: Government and Economic Development

[Back] (#28)

## Staying Out of the Way

<!-- _class: cols2_ul_ci fglass -->

Rendering is **unordered list + rounded serial numbers**
Custom styles are:`<!-- _class: cols2_ul_ci fglass -->`

- Chapter 1: The Powers and Affairs of Local Government 
- Chapter 2: Finance and Taxation and Government Behavior 
- Chapter 3: Government Investment and Debt 
- Chapter 4: The Role of Government in Industrialization 
- Chapter 5: Urbanization and Imbalance 
- Chapter 6: Debt and Risk 
- Chapter 7: Domestic and International Imbalances 
- Chapter 8: Government and Economic Development

[Back](#28)

## Staying Out of the Way ##

<!-- _class: cols2_ul_ci fglass -->

Rendered as **unordered list + rounded serial number**
The custom style is: `<!-- _class: cols2_ul_ci fglass -->`

- Chapter 1: The Powers and Affairs of Local Government 
- Chapter 2: Finance and Taxation and Government Behavior 
- Chapter 3: Government Investment and Debt 
- Chapter 4: The Role of Government in Industrialization 
- Chapter 5: Urbanization and Imbalance 
- Chapter 6: Debt and Risk 
- Chapter 7: Domestic and International Imbalances 
- Chapter 8: Government and Economic Development

[Back](#28)

## Microeconomics: A Modern Perspective

<!-- _class: col1_ol_sq fglass -->

Rendering is **single column + ordered list + square numbering**
Custom styles are:`<!-- _class: col1_ul_sq fglass -->`

- Budget constraints and consumer optimality
- Supply functions for labor and savings
- Welfare economics: single and multi-input models
- Theory of the firm: single and multiple input goods models
- Perfectly competitive markets
- Perfect monopoly, monopolistic competition and duopoly
- Exchange and production economies
- Uncertainty, Expected Utility and Asymmetric Information

## Microeconomics: A Modern Perspective

<!-- _class: col1_ol_ci fglass -->

Rendering is **single column + ordered list + rounded serial number**
Custom styles are:`<!-- _class: col1_ul_ci fglass -->`

- Budget constraints and consumer optimality
- Supply functions for labor and savings
- Welfare economics: single and multi-input models
- Theory of the firm: single and multiple input goods models
- Perfectly competitive markets
- Perfect monopoly, monopolistic competition and duopoly
- Exchange and production economies
- Uncertainty, expected utility and asymmetric information

## 5. Citations, Links and Callouts

<!-- _class: trans -->
<!-- _footer: "" -->
<!-- _paginate: "" -->

## 5. References, Links, and Callouts

- References are rendered as:

> The Synthetic Control Method (SCM) was first proposed by Abadie and Gardeazabal (2003) to study the economic costs of terrorist activities in the Basque Country of Spain, in the context of a case study.

- Link presentation:
 - [Econometric Data Cleaning and Stata Practice: three major prefecture-level city databases and CSMAR listed company data](https://mp.weixin.qq.com/s/D0cYVPJJsNiu61GcYwV6cg)
 - [Stata Basics: Starting with the creation of the thesis folder system](https://mp.weixin.qq.com/s?__biz=MzkwOTE3NDExOQ==&mid=2247486489&idx=1)
- Callouts are custom styles provided by Awesome Marp and are available in 5 colors:
 - [Purple](#40): `bq-purple`
 - [blue](#41): `bq-blue`
 - [Green](#42): `bq-green`
 - [Red](#43): `bq-red`
 - [Black](#44): `bq-black`

## 5. References, links and reference boxes

<!-- _class: bq-purple -->

- Customize the style to `<!-- _class: bq-purple -->`

> Synthetic Control Method (SCM) 
> 
> The SCM was first proposed by Abadie and Gardeazabal (2003) to study the economic costs of terrorist activities in the Basque Country of Spain, in the context of a case study, and is considered by Athey & Imbens (2017) to be the most important innovation in the field of econometrics in the last 15 years. <br>
> The basic idea of the Synthetic Control Method is that although it is not possible to find an optimal control region for the Basque Country, it is possible to construct a more relevant Synthetic Control Region by applying appropriate linear combinations of a number of major cities in Spain (with different weights), and then comparing the real Basque Country to the Synthetic Basque Country, to obtain the impact of terrorist attacks. Then the real Basque Country is compared with the "Synthetic Basque Country" to obtain the impact of the terrorist attack.

[Back](#39)

## 5. References, links and quote boxes

<!-- _class: bq-blue -->

- Customize the style to be: `<!-- _class: bq-blue -->`

> Synthetic Control Method (SCM) 
> 
> SCM was first proposed by Abadie and Gardeazabal (2003) to study the economic costs of terrorist activities in the Basque region of Spain, in the context of a case study, and is considered by Athey & Imbens (2017) to be the most important innovation in the field of econometrics in the last 15 years. <br>
> The basic idea of the Synthetic Control Method is that although it is not possible to find an optimal control region for the Basque Country, it is possible to construct a more relevant Synthetic Control Region by applying appropriate linear combinations of a number of major cities in Spain (with different weights), and then comparing the real Basque Country to the Synthetic Basque Country, to obtain the impact of terrorist attacks. Then the real Basque Country is compared with the "Synthetic Basque Country" to obtain the impact of the terrorist attack.

[Back](#39)

## 5. References, links and quote boxes

<!-- _class: bq-green -->

- Customize the style to be: `<!-- _class: bq-green -->`

> Synthetic Control Method (SCM) 
> SCM was first proposed by Abadie and Gardeazabal (2003) to study the economic costs of terrorist activities in the Basque region of Spain, in the context of a case study, and is considered by Athey & Imbens (2017) to be the most important innovation in the field of econometrics in the last 15 years. <br>
> The basic idea of the Synthetic Control Method is that although it is not possible to find an optimal control region for the Basque Country, it is possible to construct a more relevant Synthetic Control Region by applying appropriate .

[Back](#39)

## 5. References, links and reference boxes

<!-- _class: bq-black -->

- The custom style is: `<!-- _class: bq-black -->`

> Synthetic Control Method (SCM)
>
> SCM was first proposed by Abadie and Gardeazabal (2003) to study the economic costs of terrorist activities in the Basque region of Spain, in the context of a case study.Athey & Imbens (2017) consider it to be the most important innovation in the field of econometrics in the last 15 years. <br>
> The basic idea of the Synthetic Control Method is that although it is not possible to find an optimal control region for the Basque Country, it is possible to construct a more relevant Synthetic Control Region by applying appropriate linear combinations of a number of major cities in Spain (with different weights), and then comparing the real .

[Back](#39)

## 6. Navigation bar

<!-- _class: trans -->
<!-- _footer: "" -->
<!-- _paginate: "" -->

## 6. Navigation bar

<!-- _class: navbar -->
<!-- _header: \ ***@Awesome Marp*** *About* *Cover* *Catalog* *Split* *Reference* **Navbar** *Basics* -->

- A side note: The earliest idea for the Awesome Marp template came from a couple of public fan friends who asked, "Is it possible for Marp to implement a top navigation bar like Beamer?". In order to realize the effect of the navigation bar, I learned some more CSS knowledge, and then this template can take shape

- Customize the style to `navbar`: `<!-- _class: navbar -->`. 
- The navigation bar is modified from the header, which must be prefixed with `\ `.
- For the currently active header, use bold `**bold**`.
- For the rest of the inactive headers, use italics `*Italics*`.
- If there is text on the left side, you need to use italic bold `***bold italic***`
- Spacing is automatically assigned by default based on the content, if you wish to right-align, you can manually add spaces to push right-alignment

## 6. Navigation bar

<!-- _header: \ ***@Awesome Marp*** *About* *Cover* *Catalog* *Split* *Reference* **Navbar** *Basics* -->
<!-- _class: navbar -->

Part of the Markdown source code for this page:

```markdown
<!-- _class: navbar -->
<!-- _header: \ ***Rainbow Bird's Nest***  -->

- Customize style to `navbar`: `<!-- _class: navbar -->` 
- Navbar modified from header, must add `\ ` at the very beginning.
- Current active header: use bold `**bold**`.
- For the rest of the inactive headers: italicize `*Italicize*`.
- If there is text on the left side: use italic bold `***bold italic***`
- Spacing is automatically assigned by default based on the content, if you wish to be right-aligned, you can manually add spaces to push right-alignment 

```

## 7. Other custom styles

<!-- _class: trans -->
<!-- _footer: "" -->
<!-- _paginate: "" -->

## 7.1 Fixed title lines: more like Beamer now (`fixedtitleA`)

<!-- _class: fixedtitleA -->

- Custom styles: `<!-- _class: fixedtitleA -->`
 
- Make the title bar of the current page fixed at the top instead of floating with the amount of content
 
- Also, the content of the page will start at the top instead of being centered vertically


## 7.1 Fixed title line: more like Beamer now (`fixedtitleB`)

<!-- _class: fixedtitleB -->


<div class="div">

- Custom styles: `<!-- _class: fixedtitleB -->`
 
- `fixedtitleB` adds a background color to the title and reduces its size compared to `fixedtitleA`.
 
- The rest of the effect is the same as `fixedtitleA`. 

 - The rest of the effect is the same as `fixedtitleA`, but the body of the page needs to be wrapped in `<div class="div'></div>` tags. 
</div>.

---

<!-- _class: footnote -->

<div class="tdiv">

#### 7.2 Custom styles for footnotes: `footnote`

Usage:

- Customize the style: `<!-- _class: footnote -->`
- The content of the page other than the footnote is written in `<div class = "tdiv"></div>`. 
- The content of the footnote on the page is written in `<div class = "bdiv"></div>`. 

An example to show the display:

- On the advance$^1$. On the other hand, the financialization of the economy continues to increase the power of corporate shareholders, prompting firms to maximize shareholder the ordinary gap$^2$.

</div>

<div class="bdiv">

1 Zhang, Tandy. The impact of financialization on the income gap between financial and non-financial sectors in China[J]. Economic Issues, 2015(11): 40-46.
2 Hein E. Finance-dominated capitalism and re-distribution of income: a Kaleckian perspective[J]. Cambridge Journal of Economics, 2015, 39(3): 907-934.
</div>

## 7.3 Custom styles for adjusting text size

<!-- _class: largetext -->

For font size adjustment, it should be easy to modify the CSS file directly. However, some of my friends suggested, "I hope we can add custom styles for font adjustment", so we currently provide four fine-tuning styles:

- Custom style 1: `<!-- _class: tinytext -->` (0.8 times the default font size)
- Custom style 2: `<!-- _class: smalltext -->` (0.9 times the default font size)
- Custom style 3: `<!-- _class: largetext -->` (1.15 times the default font size)
- Custom style 4: `<!-- _class: hugetext -->` (1.3 times the default font size)

For example, the custom style used on this page is `largetext`.

## 7.4 Custom styles for chart titles: `caption`

<!-- _class: caption -->

- Define the title of the chart by `<div class="caption">The Wonders of the Universe</div>`.

![#c h:380](https://mytuchuang-1303248785.cos.ap-beijing.myqcloud.com/picgo/202401131712626.png)

<div class="caption">
The Wonders of the Universe
</div>

## Need to know the basics

<!-- _class: trans -->
<!-- _footer: "" -->
<!-- _paginate: "" -->


## Markdown Overview

<!-- _header: \ ***@Awesome Marp*** *About* *Cover* *Content* *Split* *Citation* *NavBar* **Basics** -->
<!-- _class: navbar -->

- Markdown is an **extremely lightweight** text markup language that allows people to write documents in **easy-to-read and easy-to-write** plain text format, and has good support for tables, code, images, formulas, and more!
- Wide range of applications: websites, course notes/handouts, presentations, writing academic papers, etc.
- Markdown basic syntax:
- Headings `#`, Bold `** **`, Italics `* *`, Strikethrough `~~ ~~`, Dividers `---`, Hyperlinks `[]()`
- References `>`, Lists `-` / `1. `, Code blocks 
- Footnotes `[^1]` / `[^1]:`, To-do lists `[]` / `[x]`
- Markdown Advanced Syntax:
- Images `![]()`: local path, network path (see: [Tupelo and PicGo - for a love of recording and sharing](https://sspai.com/post/65716))
- Math formulas: intra-line formulas `$... $`, interlinear formulas `$$... $$`.
- HTML elements: `<br>`/`<hr>`/`<b></b>`/`<i></i>`/`<kbd></kbd>` and so on.
 
## Recommended Markdown editors

<!-- _class: cols-2-64 navbar -->
<!-- _header: \ ***@Awesome Marp*** *About* *Cover* *Content* *Split* *Citation* *NavBar* **Basics** -->

<div class=ldiv>

**VS Code**
- Visual Studio Code [download address](https://code.visualstudio.com/Download)
- VS Code plugin:
 - Works with Markdown: [Markdown Preview Enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced), [ Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
 - Graphics bed: [PicGo](https://marketplace.visualstudio.com/items?itemName=Spades.vs-picgo)
 - Formatting documents: [Pangu-Markdown](https://marketplace.visualstudio.com/items?itemName=xlthu.Pangu-Markdown)
 - Markdown to PPT: [Marp for VScode](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode)
 - Markdown to Mind Map: [Markmap for VScode](https://marketplace.visualstudio.com/items?itemName=gera2ld.markmap-vscode)
 - Work with Zotero: [Citation Picker for Zotero](https://marketplace.visualstudio.com/items?itemName=mblode.zotero), [Pandoc Citer](https://marketplace.visualstudio.com/items?itemName=notZaki.pandocciter)

</div>

<div class=rdiv>

**Obsidian**
- [Obsidian homepage](https://obsidian.md/)
- Markdown-based native knowledge management software
- Completely free for individual users, except for official synchronization and publishing features
- Rich features, many plugins, active development community

</div

## Marp basic usage

<!-- _header: \ ***@Awesome Marp*** *About Template* *Cover Page* *Catalog Page* *Columns & Splits* *Reference Boxes* *Navigation Columns* **Basics**-->
<!-- _class: navbar fixedtitleB -->

<div class="div">

- A few words summarizing [Marp](https://marp.app/): Creating Presentations with Markdown
- Start Marp with `marp: true` in the YAML area at the top of the Markdown file, and then you can turn on side-by-side previewing, with the code area on the left and the preview area on the right of the VS Code interface.
- The content follows Markdown syntax, but Marp adds some built-in commands, and the commands are categorized into global commands and [local commands](https://marpit.marp.app/directives?id=local-directives-1), global commands are recommended to be placed in the YAML area, and local commands are located in the current page, different pages can be accessed through `--MARP: true` to start Marp, then you can open the side preview. The global directives should be placed in the YAML area, and the local directives should be located on the current page, with different pages separated by `---`.
- Recommended reading: Marpit [official documentation](https://marpit.marp.app), five minutes to learn Marp [(top)](https://www.lianxh.cn/news/97fccdca2d7a5.html), [(bottom)](https://www.lianxh.cn/news/521900220dd33.html).
</div>

## Marp basic usage

<!-- _header:\ ***@Awesome Marp*** *About the template* *Cover page* *Content page* *Columns and breakouts* *Citation boxes* *Navigation bar* **Basics** -->
<!-- _class: navbar -->

```yaml
---
marp: true # turn on marp 
size: 16:9 # set the page ratio, common is 16:9 or 4:3, default is 16:9.
theme: gaia # switch theme, built-in 3 kinds of theme, you can customize theme.
paginate: true # enable pagination
headingDivider: 2 # split page by second level heading, save the trouble of changing page manually.
footer: initial rainbow # set the content of the footer area, or header if set the content of the header
---
```

- If you want the page to be divided by multiple levels of headers at the same time, e.g., to split the page by level 2~4 headers, you can `headingDivider: [2,3,4]` 
- If you want multiple custom styles to render the same page, you can directly connect the different custom styles with spaces, e.g. `<!--_class: cols-2-64 fglass -->`

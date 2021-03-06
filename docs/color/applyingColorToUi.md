---
title: 將顏色應用到 UI
description: 色彩以一致且有意義的方式運用在使用者介面的元素和元件上。
---
<!-- markdownlint-disable MD025 -->
<!-- markdownlint-disable MD033 -->

# 將顏色應用到 UI

色彩以一致且有意義的方式運用在使用者介面的元素和元件上。

## 用法

這些準則描述了使用者介面元件和元素，其中的色彩應用是非常重要的。

### 原則

<div class="img-grid">
    <div class="grid-item-triple">
        <img src="https://lh3.googleusercontent.com/AUc8ae14K44qkCTWKOCz6dvgIEeih8h2t3v2Y8c6RVKxwyHuJjbY3FiY00De8vyyVyheqY42nk02Nw6ljfqcxCdm0_tQYb3NCkOvwQ=w1064-v0" alt="">
        <h4>一致性</h4>
        <p>色彩需被應用在整體的介面，並與其代表的品牌有兼容性。</p>
    </div>
    <div class="grid-item-triple">
        <img src="https://lh3.googleusercontent.com/qNrXgxomfHYbh8K-TWq0iAcyheIGWdhe5BjIEdBmHibR6ug3ZsOrsANiIqXwOF_IxHQN52QUBKpprb4GYQPwg9Ch9YPl4zd7FhUdiA=w1064-v0" alt="">
        <h4>辨識性</h4>
        <p>色彩需在元素之間能夠被區分，他們之間也需有足夠的對比度。</p>
    </div>
    <div class="grid-item-triple">
        <img src="https://lh3.googleusercontent.com/4xogmeEZv0K7ZyAVZy87v4nWAPpaIPLDVgGcIan5BFGY83lyJP3ybSTxIC8rSWMnCQV4gEo-9U79Yt4M8f7HgnixBvNqXb1yeXEJ=w1064-v0" alt="">
        <h4>目的性</h4>
        <p>色彩安排上應該有目的性的應用，因其可通過多種方式傳達含義，例如元素和層級之間的關係。</p>
    </div>
</div>

---

## 頂部與底部的應用欄

APP 上頂部底部欄位色彩的配置，可以幫助使用者辨識並了解其與周邊元件之間的關係。

### 定義應用欄位

頂部與底部應用欄位使用應用程式的主色。系統欄位使用由主色的深色調或淺色調去區分系統內容與應用欄位的內容。

<div class="grid-all">
    <img src="https://lh3.googleusercontent.com/6UKXS1VtC3fE9l6PdBsEq4AJCcjBHZ-R6KHC_utob5lscsokTEgxCU0VPZ61DWNt1PgONV3qMWa59DjXfcMn_1yC8wI5gchyet-O-A=w1064-v0" alt="">
    <div class="item-divide divide-gn"></div>
    <div class="item-title title-gn">該這樣做</div>
    <p class="annotation">在頂部的應用程式欄上使用主色（purple 500），並且在系統的欄位上使用主色的深色調（purple 700）。</p>
</div>

要強調欄位與其他介面的差異性，使用次要色在周邊元件的配色，例如浮動操作按鈕(FAB)。

<div class="grid-all">
    <img src="https://lh3.googleusercontent.com/7kBvkDFbgSul6k7mMxeusLF0_L35sCMucc609rB-cc95Vc3RFGeZoQyIX5uq0oW8TDGhQkb-ZO-O-GXPiYYsaWGoxncdPk4TkubK4Q=w1064-v0" alt="">
    <div class="item-divide divide-gn"></div>
    <div class="item-title title-gn">該這樣做</div>
    <p class="annotation">底部應用程式的欄位使用主色（blue 700）而浮動操作按鈕則使用次要色（orange 500）。</p>
</div>
<div class="grid-all">
    <img src="https://lh3.googleusercontent.com/pVDhSqPute7NAGxXuklma__K-oxh0t6aEvm4kU-bRfdDJVJ7hEkG4hT1W7BTrZcziildkTTQn8-B_TAwQz0UwhRRWynwK9DxVqydlO8=w1064-v0" alt="">
    <div class="item-divide divide-og"></div>
    <div class="item-title title-og">警告</div>
    <p class="annotation">如果按鈕的應用程式欄位和浮動操作按鈕使用同一個顏色，請使用陰影或其他替代方式，在這兩者之間創造足夠的區隔性。</p>
</div>

---

### 將應用欄與背景融合

當頂部與底部的應用欄位色彩與背景相同時，它們會融合在一起，從而強調內容而非結構。

<video src="https://kstatic.googleusercontent.com/files/79d4c3c0ed3d5070812fc43aff430d438d77f54e505e96100e6a7e5f0926e8a7def56924784d3dee609cc42036ee90fa6307becfde58714529b0d0c44154e069" width="100%" controls=""></video>

<p class="annotation">此應用程式的頂部欄位與背景色彩都使用主色：白色。但在滾動時，頂部應用欄增加了陰影，顯示其高於滾動後的背景內容。</p>

![應用欄位與背景](https://lh3.googleusercontent.com/ZapD8IdA5RroRgXR_UVwhbVToFSjJrazZ45-oOW6X_DA7MTs8SYwIeuBG0j-uyn-UK4YmP0K8Ud40_mMyFt_xan9kq7NOO6R3u70=w1064-v0)

<p class="annotation">這個應用程式明亮、無縫的排版，在應用程式欄位、底部導航、背景色上使用藍色主色（blue 700），因此各個元素的凸顯性較低，而內容更加鮮明。在激活狀態則使用次要色黃色，這包含了在底部導航欄位的陰影，展現高低層的劃分。</p>

---

## 背景

背景具有前後層次。為了區分這兩個圖層，基準線後層的色彩是您的主色，而基準線前的色彩是白色。

![背景](https://lh3.googleusercontent.com/ZPosyLUlyHr3_iGE3Ro2Y37HACoSdQR1De5omSsm7xRfxoAprTuHpiR-Jm6PxHWR1D8W7iIShYAcKbNVufuItdzeDJt6RP2IpD7sFg=w1064-v0)

<p class="annotation">這個應用程式在背景的後層使用主色（purple 800），文字區塊則使用由主色的淺色變化（purple 700）。而次要色（red 700）應用來強調機票價格。</p>

![背景](https://lh3.googleusercontent.com/0pFYMooqhAAvZmXQDsn6nu7nzprpto3EpbLT11Mx9BUGRLoEdwHqH_87WxW5biv6u4h8odCUOfZ8llJyWjfgtlqLb3FS9Huqfl8C=w1064-v0)

<p class="annotation">這個應用程式在背景的後層使用主色（pink 100），而主色的深色變化（pink 900）則是運用在字型與圖標上，除此之外次要色（pink 50）使用於表層的擴展頁。</p>

---

## 列表與表面

工作表與表面的基礎色彩，像是底部的列表、抽屜式導航、目錄、對話框以及卡片是白色的。這些元件可以合併色彩，創造和其他介面的色彩對比。對比可以使表面邊緣更明顯，表明重疊時的層高差。

![表單和表層](https://lh3.googleusercontent.com/wWpFlJU3zD9mTsuX-01lHmzWCVNI70vlbeeJkothZMoEhCsJh-DDGh4-nddPIFfbEtma6VvZC0MgyP5DiEWZvnW2M0y2OSR4PhOv=w1064-v0)

<ol class="annotation">此產品已將底部列表與導航抽屜的默認色彩白色改為主色。
    <li>在底部的一部分使用主色（purple 500）代替基準的白色。</li>
    <li>導航抽屜使用主色（purple 500）代替基準的白色。</li>
</ol>

### 模態列表

在臨時出現的屏幕上（例如導航抽屜和底部列表）使用大的對比色，通常這些表面是白色的，但是您可以使用應用程式中的主色或是次要色。

![模態列表](https://lh3.googleusercontent.com/8VHoaHOClBeQANSOVeW1sYBJOqMvVCODvwWbI21JgDxjDZJRge4BpmNJgTKAXo6RAzC0_nqLELimQeANH8PWUHl1uCVVNa-XItyijA=w1064-v0)

<p class="annotation">此應用程式在底部導航抽屜欄位使用主色藍色（blue 700），在帳戶切換列表中使用主色的深色調（blue 800），並在選取時使用次要色（orange 500）。</p>

![模態表單](https://lh3.googleusercontent.com/tW6kc9eWT8qYCcaNLva1GkUUtmSw1vur8k-aAZVc3C4_LNV2Rfc4CtjPhH_MjI8gmoHB308rWobA_W2Otzirb5FmVajr7dzYvhhS=w1064-v0)

<p class="annotation">此應用程式將其主色（white）用於他的模態導航抽屜，在深色的字體和導航之間創造最大的色彩對比。由於導航抽屜的背景顏色與白色相同，因此使用白色的霧透效果使後面的內容較不引人注意。</p>

<video src="https://kstatic.googleusercontent.com/files/b90b3c126454e82010b87d480f6c49dc55ba5920c1b516b9f11676a2eca55e91abdf43b108338edab0471f86a52a9b8ae478e909970129d98f795b23a683bb68" width="100%" controls=""></video>

<p class="annotation">此應用程式會在右下方顯示主色（pink 500）的工作列表，並在輕按時拓展頁面</p>

---

### 卡片

卡片的基本色是白色，可以訂製此顏色來表現品牌並且提高易讀性，卡片的文字和圖標同時也可以使用主題色彩以提高易讀性。

![卡片](https://lh3.googleusercontent.com/mHqlQe_4N3zxMT3DLGk4IbbPxM0S7qCIS_rOtDZMAmGKxLbYhQK6GKaNYxpQaKoHaHV0O1b6-Av5-JCQjKpluGrM30NRdhwYvf4i=w1064-v0)

<p class="annotation">這個卡片介面使用主色（purple 500）。其應用的背景色為白色，而次要色（teal 200）用來視覺化圖表資訊。</p>

<video src="https://kstatic.googleusercontent.com/files/c34d8fa9d3b2d3da28140fb51e00f982d8b5b913f53e55d0d43cb15b8f0fe3d374560718ccc34497eee4c9c5a3774b486f14a5f40e977bff3ae06128befc5052" width="100%" controls=""></video>

<p class="annotation">卡片可以繼承色彩以展現選項或重要性。</p>

<div class="img-grid">
    <div class="grid-item">
        <p>當卡片的文字和圖標出現在圖像前方時，他們可能很難被閱讀。為了提高易讀性，可以使用色彩創造一個表面給文字與圖標。</p>
    </div>
    <div class="grid-item">
         <img src="https://lh3.googleusercontent.com/GDepGXxsfpoVED_dm8mpH7W8lNlnnED16357qs_CAowHCLjM0qhXpiFFH5QkLMaI6Rk-xVvlOMIwI8JhHoVivOWwDv2yw3lsND6GMA=w1064-v0" alt="">
        <p>此卡片使用多樣色彩覆蓋於背景圖上以確保文字保持易讀性。</p>
    </div>
</div>

---

## 按鈕、組件與選擇控制器

按鈕、組件與選擇控制器可以透過使用主色和次要色以突出他們。

### 色彩類別

- 包含文字和外框按鈕的基礎色彩是您使用的**主色**。
- 浮動操作按鈕和其他延伸的浮動操作按鈕的基礎色彩是您的**次要色**。
- 選擇控制器的基礎色彩是您的**次要色**。

![色彩分類](https://lh3.googleusercontent.com/2-cBD9qPVbiQm2dHTC0RvGpZ7bEn0UEmiet4bMF_9vmW6gyfJ1K_9ldDfZbk8aEv3OBUk0SfKR3OLgybvgJT2IbE9jP_ACujheTdG70=w1064-v0)

<ol class="annotation">這個應用程式的色彩主題包含主色（purple 500）與主色的深色變化色彩（purple 600）與他的次要色（teal 200）。
    <li>這個產品使用主色（purple 500）作為底部應用程式欄位，並使用次要色(teal 200）作為浮動操作按鈕與選擇控制器的重點色彩。</li>
    <li>這個產品使用輔助色彩（teal 200）作為選擇表單項目的重點色彩。</li>
</ol>

### 按鈕、組件和選擇控制器

按鈕、組件資訊與選擇控制器可以透過您的主色與次要色來強調。

![按鈕組件和選擇控制器](https://lh3.googleusercontent.com/2VUc60QUZ8BfNyVyORplX4Q8v7Nx6DEL5VCuZyX7SdAqyHjoN3STxyssyN2cPzamywZSD6JplWaXk0fTbCNixZzAE9fAjvrVC87P=w1064-v0)

<p class="annotation">此應用將其主色（pink 100）用於延伸操作按鈕和片狀資訊。並且它使用主色的深色變化（pink 900）作為他的滑動區塊。</p>

<div class="img-grid">
    <div class="grid-item">
         <img src="https://lh3.googleusercontent.com/x5HKQ8dlRPKeF56yx8EpgrsY6UEewhtmuNYPtyDMRGhuozrrK6qmSUzmY_9UlNBC3Er_pJgm2SFtMVFrZqRg7NlJhMifurjZ5IQ_bxg=w1064-v0" alt="">
        <div class="item-divide divide-gn"></div>
        <div class="item-title title-gn">該這樣做</div>
        <p>選擇控制器可以繼承應用程式的次要色。</p>
    </div>
    <div class="grid-item">
         <img src="https://lh3.googleusercontent.com/MV18tumSkNvHlGFYJJ-pa1abimafsneQBtREDMjzMyxhg8d1AJTE5mJvxo32nGls-V-6EYQcYiy5z93dHMrgQLj4WdYNUFOvsnym1A=w1064-v0" alt="">
        <div class="item-divide divide-rd"></div>
        <div class="item-title title-rd">別這樣做</div>
        <p>不要使用你的品牌色作為警示色彩，這將會有助於它脫穎而出。</p>
    </div>
</div>

---

### 浮動操作按鈕(FAB)

浮動操作按鈕（FAB）必須是你的螢幕上最容易識別的項目。

使用色彩創造浮動操作按鈕（FAB）與周圍的元件對比度，例如應用程式欄。您使用的次要色是 FAB 的基礎色彩。如果你的畫布上使用了許多色彩，您的 FAB 可以使用單色配色替代，使其從內容中脫隱而出。

![浮動操作按鈕](https://lh3.googleusercontent.com/xe8OtGTBFId4petz6b2mPxhAZjwzRDZkUc145BJHOWaK4QSzyxdgCYTeQoCOuZ_Gumkq9K9-7KAn2m6jRFHOd-vY20e4ApVJO-m5IQ=w1064-v0)

<p class="annotation">這個應用程式的次要色（orange 500）應用在浮動操作按鈕上，與周圍的使用介面產生明顯的對比。</p>

![浮動操作按鈕](https://lh3.googleusercontent.com/pCo4jpiVLdgaHlQMHvX9o_AcUK6p8pIqcEcxPD6BifKtZFYT5rLju6z4M7-6ZEgQZCevw41ZI6d6Gkqvu2Lql_ln47H0HNRFPho9=w1064-v0)

<p class="annotation">這個應用程式使用主色為白色和次要色黑色的色彩主題在所有的按鈕、選擇控制器和圖像上。這些元件脫穎而出是因為它們與鮮豔的多色內容形成了鮮明的對比。</p>

---

## 字型與圖標

色彩可以表達文字相對於其他文字，具有更大或更小的重要性。當文字置於背景圖上時，色彩可以確保文字維持高易讀性，這可能會使閱讀其前面的文字變得困難。

### 字型層級

色彩可以增加文字易讀性與其重要程度。

![字型層級](https://lh3.googleusercontent.com/SQIXuWYgEh5Bcwyl1GA3AyhHnUHTcHgG-_Ljbpqvt-pNyrZdUWIhf605lx2OXtxAvt2SoYu2oPUSY0Mox7mEKZ6RRAiGDQ7L56NIaw=w1064-v0)

<p class="annotation">這個應用程式的顏色主題包含主色（purple 500）以及次要色（orange 600），卡片以橙色為重點，在頁籤與按鈕則以紫色顯示。</p>

---

### 標題和頁籤

重要文字，如頁籤和標題，可以使用主色或次要色。

![標題和頁籤](https://lh3.googleusercontent.com/TZ5Q8J80V4tI9Ha6WnKeJVR12TBFYsapPItn4LX2VRbyWB4OsUnssYoQhczvVopaxXX7YLOb8ZkG2BP8Dr9JlFif-qub2H5BCDjkgg=w1064-v0)

<p class="annotation">此應用使用它的次要色（orange 800）來強調並引起注意。</p>

![標題和頁籤](https://lh3.googleusercontent.com/JZ4nfTg7mqYYZeCenkYLLutaNIO0iWMH4gFPsQy6sBN8N9o2do8GV5rGmCTrjVhmCmPsou4ZIiioGI95YwIdKNCZ8djTa99tWggU3w=w1064-v0)

<p class="annotation">此應用使用它的主色（green 800）作為頁籤，並使用字重變化以表示選定與未選定狀態。</p>

<div class="img-grid">
    <div class="grid-item">
         <img src="https://lh3.googleusercontent.com/TwPcFjhDy9prl_wQBSMHWuGBgyT4klo_A8ECBfI1SQGx_KBIKJX_FU-ddAjhZt40LIpOMRET22k4oY2g4qcCJ7FG22qKl5SUkDoDVA=w1064-v0" alt="">
        <div class="item-divide divide-gn"></div>
        <div class="item-title title-gn">該這樣做</div>
        <p>使用你的主色與次要色去強調較短的文字，比如標題。</p>
    </div>
    <div class="grid-item">
        <img src="https://lh3.googleusercontent.com/xZt4M4PazOpPsBdvODeGroEVe08n_66YZLqJgjCkYEHlp3kFErHC6hK1XK6H7b_Z8GlYYUqwyF84wqgefv4hyv4GlcZ2qot01C-kfA4=w1064-v0" alt="">
        <div class="item-divide divide-gn"></div>
        <div class="item-title title-gn">該這樣做</div>
        <p>你可以使用主色以及次要色去強調超連結。</p>
    </div>
</div>
<div class="grid-all">
    <img src="https://lh3.googleusercontent.com/Jd3LN8Ey81uHC1ol8KEpxRfyRjcmNb4Dl1Ys3jlG_9cj7BYR8Rm9ckvb5Gof6sylLyV0GlNZcsMjJRwdu7oho9G2ql4J9qMNAuEw=w1064-v0" alt="">
    <div class="item-divide divide-og"></div>
    <div class="item-title title-og">警告</div>
    <p class="annotation">避免在正文中使用高明度的主色和次要色。</p>
</div>

---

### 文字易讀性

當文字排版於圖像上時，通常會碰到易讀性的問題。在文字與圖像間創造彩色圖層可以確保文字清晰易讀。

![文字易讀性](https://lh3.googleusercontent.com/7ryaNA4yROr0DABTUMQAnDZ7LpPOLD5g2mDVkupe8SemDxds5CQcVz7wucE093SEWCLO00lOuoWRGRtuv6V2l47cb0r9C-LX014fM28=w1064-v0)

<p class="annotation">此應用將黃色覆蓋於圖像上以確保上方文字清晰易讀。</p>

---

### 圖標

圖標可以幫助辨識行為與提供資訊。它們的色彩應與背景形成對比，以確保它們清晰可辨。

![圖標](https://lh3.googleusercontent.com/KjwZuWiO3mmVvQId1SqldXM9AkpVvy3FVl8Rgtjk-kIV_avy6bKssMBHj7pSZnUqUE3uRutsojN3RHd36cOzxKSlcJLyltMHhK-qDbI=w1064-v0)

<p class="annotation">此應用同時使用其主色（green 800）和次要色（orange 800）作為圖標。</p>

![圖標](https://lh3.googleusercontent.com/XskS05kraoQFy7MsTbTbWKseRjTLhLRPM4P6HqNvbk9aXHaPSphUoYX-ZdEqiX1kKRV9jBC_P7IMho8E58nENgByEHbmdh57JxRBrQ=w1064-v0)

<p class="annotation">Shrine 在圖標上使用主色的深色調（pink 900）。</p>

---

> 譯者：[Anne Peng](http://hsinyinpeng.com/)
>
> 校稿：[Joanne Chen](https://www.facebook.com/profile.php?id=100000314569800)

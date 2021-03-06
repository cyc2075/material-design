---
title: 層高
description: 層高（Elevation）是兩個圖層在同一Z軸線上的相對距離。
---
<!-- markdownlint-disable MD024 -->
<!-- markdownlint-disable MD025 -->
<!-- markdownlint-disable MD033 -->

# 層高

層高（Elevation）是兩個圖層在同一Z軸線上的相對距離。

<video src="https://kstatic.googleusercontent.com/files/fff057c227cb393074c97bd3b92e3e63060a0f6c184e384da82b9855f766af6aca9ae9caef1b7fdfb5620e39c4138ecc7ed75e8fb82b16471bc52e26384719ef" width="100%" controls=""></video>

**元件層高數值：**
<ol class="annotation">
    <li>隱藏式測選單（Nav drawer）：16dp</li>
    <li>標題列（App bar）：4dp</li>
    <li>資訊卡（Card）：1dp至8dp</li>
    <li>懸浮操作按鈕（FAB, Floating Action Buttons）：6dp</li>
    <li>按鈕（Button）：2dp至8dp</li>
    <li>提示對話框（Dialog）：24dp</li>
</ol>

---

## Material Design 中的層高

### 測量層高（Measuring elevation）

Material Design 中的層高是指圖層之間所測量出的距離。沿著Z軸線以獨立密度像素（dps, density-independent pixels）為單位，來測量從一個material 層面到另一個層面的距離，並使用[陰影](#描繪層高-depicting-elevation)對其描繪（默認情況之下）。

![image alt](https://lh3.googleusercontent.com/DPzeyvLZt7dg5ig1MKpjbiEAUHUjJDPdWzqoAHU2PXrgxJiasUcm2Db1glloNm5x5kXuEbO6ZYXycXUO5gu_wfy5TrWnDH1nPQ9sGg=w1064-v0)

<ol class="annotation">
    <li>從正面視角來看，一個圖層的層高為1dp，而另一個圖層層高為8dp。</li>
    <li>從側面來看，兩個層面之間的層高差為7dp。</li>
</ol>

![image alt](https://lh3.googleusercontent.com/ZD8xNBuhsga15kbpHDUuUX5EGFV6KjbTgHedevXdVX50jJJu8gL5-Vb26Z5CE8ENwy_tURWO8Ru_vwbOGX78Wuw78FwK0_VX43r0dg=w1064-v0)

<p class="annotation">當有其他平面在後方時，同一層高的平面外觀可能有所不同。</p>

<ol class="annotation">
    <li>層面 A 和 B 的層高相同（8dp）。但因為層面 B 在另一個已具有層高的層面（C）之前，所以兩者投射出的陰影不同。</li>
    <li>從側面看，層面 A、B 以及 C 三者之間的高度差。</li>
</ol>

---

### 層高系統（The elevation system）

所有的 Material Design 平面，以及元件，皆具有層高。

以下為平面在不同高度的表現：

- 容許平面在其他平面的前方或後方移動，例如：內容在標題列後方滾動。
- 反映出空間關係，例如：浮動操作按鈕的陰影顯示它自身與卡片群組分離。
- 使注意力專注在最高層的平面，例如：暫時出現在其他平面前的對話框。

層高能夠藉由陰影或是其他視覺提示來描繪，例如：將表面填滿或是使用不透明度。

![image alt](https://lh3.googleusercontent.com/lYzXVHTeDA6Qy4fQDnwxxki4vJzXM7IR7P0k8UlKvr9ayRR1VFCCb5XgIY3pSfVyRZfWUiQvPCZKqwppROK3qFpoNY8ArrYoDjhw3QQ=w1064-v0)

<p class="annotation">Material Design 使用陰影來呈現層高。</p>

<div class="img-grid">
    <div class="grid-item">
         <img src="https://lh3.googleusercontent.com/cMbIyXl50sAA2vIH9NZo6AyQT739uQUkDM-QE7lEka6XlMLa-ZvggePmRIWfD6ao0ut57blVNf8K-xQZCJ1XYYQfe3HprtAwV5iK=w1064-v0" alt="">
        <div class="item-divide divide-og"></div>
        <div class="item-title title-og">警告</div>
        <p>可以使用不同的填充平面取代陰影來表現層高。</p>
    </div>
    <div class="grid-item">
         <img src="https://lh3.googleusercontent.com/IYh0wXRTbtSwgOtsCypr9KOn_tbKXJRNIcZbPc4lXJNhO401EZyEbNv3Lydopk9khwioZy9df_dFAAFdzmQQ5W8Fa8prTBw5m5FyHtM=w1064-v0" alt="">
        <div class="item-divide divide-og"></div>
        <div class="item-title title-og">注意</div>
        <p>不透明度可以取代陰影來表示層高。</p>
    </div>
</div>

---

### 靜止層高（Resting elevation）

靜止層高是在默認情況下給予元件的起始層高數值。元件在給予使用者回饋或是系統事件中自默認層高移動。所有的 Material 元件，只要類型相同，皆有相同的默認層高。舉例來說，所有的卡片和其他卡片一樣，具有相同的默認層高；一個對話框和其他對話框一樣，具有相同的默認層高。

#### 靜止層高以及環境

靜止層高因環境、平台或應用程式而異。在行動裝置的靜止層高是設計來提供視覺提示，如：陰影，以指示元件何時處於互動狀態。相對地，在桌上型裝置上靜止層高會較淺，這是因為有其他的視覺提示，如：hover 狀態，在元件互動時會傳遞資訊。舉例來說，在桌上型裝置上，層高為 0dp 的卡片在點擊後出現其輪廓。

![image alt](https://lh3.googleusercontent.com/IGup0QloUkkozMfTPbOYOCjUZrfaeNUMLKRBJ6fLBgSUj0_WnzNNy1GsyUijEJyEqDYGqbEW1G3UFO3XOLdZcfd278WCK01TWMOlWQ=w1064-v0)

<ol class="annotation">
    <li>靜止層高在標題列（A），資訊卡（B）以及浮動操作按鈕（C）在行動裝置上的正面視覺呈現。</li>
    <li>側邊視角的相同元件。</li>
</ol>

![image alt](https://lh3.googleusercontent.com/lg7Rz0Ji-yv2fpd1wo7SRkWvseJEmBndg0vicbmF6N6OW_D7YPGeQOIxzfIs8anpg5umfzCfLSPMikyEZUvjt5WOrFwD60AgyIxMAg=w1064-v0)

<ol class="annotation">
    <li>靜止層高在標題列（A），資訊卡（B）以及浮動操作按鈕（C）在桌上型裝置的正面視覺呈現。</li>
    <li>側邊視角的相同元件。</li>
</ol>

---

### 改變層高（Changing elevation）

元件能夠根據使用者的資料輸入或是系統事件來改變層高。當事件發生時，元件移動到預設的**動態層高偏移（dynamic elevation offsets）**，也就是靜止層高的元件在非靜止時所移動到的地方。

每種元件只要類型相同，其動態層高偏移量都相同。舉例來說，所有的卡片都與其他卡片使用相同的偏移量；所有浮動按鈕的偏移量也與其他浮動按鈕相同。

當完成或是取消使用者的輸入行為（或是系統事件），元件便會迅速還原至靜止層高。

<video src="https://kstatic.googleusercontent.com/files/fae98b1ef729287b766e797726f08861f88d45adde26fb81a46b93426c24762f2d14d47808821671f9c8529a3e28fce41905d71556904dde28de47788d482061" width="100%" controls=""></video>

<ol class="annotation">一些元件會對使用者的輸入回應層高的增加。
    <li>在使用者輸入後，此按鈕的層高從2dp增加至8dp。</li>
    <li>以側面角度呈現的相同元件。</li>
</ol>

---

### 層高干擾（Elevation interference）

當元件在其默認的層高以及動態層高偏移之間移動時，它不應該與其它的元件產生衝突。

為避免這樣的衝突，可以將元件移開。舉例來說，若是增加一個卡片的層高讓其通過浮動按鈕，該按鈕可以在衝突發生時消失或是自畫面離開。

你也可以透過設計應用程式佈局來避免這樣的衝突，像是將浮動操作按鈕置於卡片的左右側而非直接置於卡片之上。

<video src="https://kstatic.googleusercontent.com/files/50048160478198e77656c8bc4e9ce953e358ec82212a12dd814fc3550728ccaf62e85714a30b79c86a47a21f46a8e2214e24570a2fca7cba02aa5d546bbb6de4" width="100%" controls=""></video>

<p class="annotation">暫時重新放置或移除可能與過渡元件產生衝突的元件。行動裝置上卡片串流的正視圖（1）與側視圖（2）展示了一個浮動按鈕（B）在卡片（A）被選取後是如何消失的。</p>

<video src="https://kstatic.googleusercontent.com/files/623d5c7b748006c65867c72b36d083a3a446a598e48993b97e72f4f9a7e939d2232502989bc80a714a215d6ed65808a18298b4d7e88e7665010f773772b100bd" width="100%" controls=""></video>

<p class="annotation">設計你的應用程式以減少因為層高而造成的干擾。</p>

---

## 描繪層高（Depicting elevation）

要成功地描繪出層高，一個平面必須顯示：

1. 平面邊緣，與其周圍形成對比。
2. 與其他平面重疊，不論是處於靜止狀態或是移動狀態。
3. 與其他平面保持距離。

### 層面邊緣（Surface edges）

邊緣有助於呈現 Material 平面的可觸質感。透過將UI的不同部分拆分成可識別的元件可以顯示出一個平面的終止位置以及另一平面的起始位置。舉例來說，一個標題列的邊緣顯示它自一個格線列表分離，向使用者傳達了格線列表獨立於標題列滾動的訊息。

在默認的情況下，Material 表面透過陰影來顯示其邊緣。也可以使用其他方法來指示出邊緣，例如：

- 讓表面有不同顏色。
- 讓表面有不同的透明度。

邊緣必須在平面之間產生足夠的對比（透過達到或是超越可達到的對比程度）來讓他們看起來是與彼此分離的。

<div class="img-grid">
    <div class="grid-item">
         <img src="https://lh3.googleusercontent.com/aSop7Q33S4n7c-f2PViVYsuuV4PHnkE72mkOwBb2yUtGBGnSTkrNm98IZHdwI04yvQBoudVG5K6RffFHUleFMKjwi0igsGQXNbtf=w1064-v0" alt="">
        <p>若無顯示出其邊緣，無法清楚得知該圖像是包含一個或多個平面。</p>
    </div>
    <div class="grid-item">
         <img src="https://lh3.googleusercontent.com/vFtTVrJyANl3_QWPZFdCT3hLniOu7IjnONMOClJaolfj7eq0jurIEpsEyrv3D-HJd-7pFuIZLvaO-D28tZcG_7TLZo73v-BwnX1BGS4=w1064-v0" alt="">
        <p>透過填滿平面來呈現足夠的對比，以清楚得知該圖相包含了兩個層面。</p>
    </div>
</div>

---

### 平面重疊（Surface overlap）

當一個平面重疊於其他平面，不論是部分重疊或是完全重疊，這都表示了兩個平面佔據了不同的層高（但兩者之間並非角度或是質量的差別）。處於較高層高的平面會顯示在較低層高的平面前，這表示他們位於 z 軸線上的不同層高。默認情況下，平面可能會重疊於其他平面上，或是因為 UI 動態中改變他們的位置而導致重疊。

當平面有不同的不透明度或是與其他平面的對比不足，這都會導致使用者難以辨認哪一個平面的位置較前。透過明確定義平面的邊緣可以避免產生模稜兩可的重疊。

![image alt](https://lh3.googleusercontent.com/zBBOuW8mTyyeMZJ6DxR1Jnf8M7cBrhvS90xO8J5z00JGeJjQMcbfmZvfotpR8Icla5HmFfIgo2sTwb2VSf1BCrd7KMeA56mR2aWVLw=w1064-v0)

<ol class="annotation">
    <li>陰影呈現了平面的邊緣、重疊狀態以及層高。</li>
    <li>不同的平色彩可以呈現平面邊緣以及重疊狀態，但無法顯示層高。</li>
    <li>不透明度呈現了平面邊緣以及重疊狀態，但無法顯示層高。</li>
</ol>

<div class="img-grid">
    <div class="grid-item">
         <img src="https://lh3.googleusercontent.com/QHhiKJMFhwqgzTbidYXNcdM3CedYX5Iff54_DB-7q8aU3xXIXxH4VSoatjvug3uWUaqVaqXMsrbOBh3-RDxyh1tTr8PRgD6lvpkL=w1064-v0" alt="">
        <div class="item-divide divide-gn"></div>
        <div class="item-title title-gn">該這樣做</div>
        <p>位於上方的標題列重疊於卡片群組上，表示該標題列位於卡片的前方。該重疊並沒有顯示兩個平面之間的層高。</p>
    </div>
    <div class="grid-item">
         <img src="https://lh3.googleusercontent.com/eyR7QnhQqWx9eJuHyAbk47w6z7kFnU69zBBVLMtdZdtxDyuFuJcKp7TcKiIb0StMMUqFskrXNYuXBioaQBg7I3_ZcA_VSW8R9XRFtg=w1064-v0" alt="">
        <div class="item-divide divide-rd"></div>
        <div class="item-title title-rd">別這樣做</div>
        <p>若沒有平面邊緣以及重疊的視覺提示的話，就無法確定存在了多少平面，哪些平面是位於其他平面之上，也無法確定平面間的層高。</p>
    </div>
</div>

---

### 距離（Distance）

平面間的層高差距可以透過使用紗幕背景或陰影來呈現。

#### 紗幕背景（Scrimmed backgrounds）

在 UI 中，當背景呈現紗幕狀態時，代表前方的內容是處於較高的層高。紗幕背景呈現了一個巨大但不特定數值的層高。

<div class="img-grid">
    <div class="grid-item">
         <img src="https://lh3.googleusercontent.com/VkYXUftoD9aIlWaEgMnYr02YNKqmRbbkKfqdE-Czq1ZW78JeX2BCgSYC_RSr-nFp4yzz4l0kJfUr_PhEK5JWoboc7LDPuVcJabOABQ=w1064-v0" alt="">
        <div class="item-divide divide-gn"></div>
        <div class="item-title title-gn">該這樣做</div>
        <p>一個紗幕背景可以表示層面重疊，但無法呈現層高程度。</p>
    </div>
    <div class="grid-item">
         <img src="https://lh3.googleusercontent.com/MD3nYXJJPnXTzDYx5mQ6IlONv1nYtTYD2xHc74M_3K5KPTCIe-MSg--PrS2h8pej0p1JlV5mLLsR_JFdAbiyTNv1Mo0N3YE9JhULmA=w1064-v0" alt="">
        <div class="item-divide divide-rd"></div>
        <div class="item-title title-rd">別這樣做</div>
        <p>若缺少了陰影或是紗幕背景會讓對話框與背景難以區分。</p>
    </div>
</div>

#### 陰影（Shadows）

陰影能夠呈現出其他技巧無法呈現的平面層高。

陰影的大小，柔和度或擴散量都表示兩個平面之間的層高。舉例來說，陰影很小且很銳利的平面表示距離後方平面非常接近。而更大，更柔和的陰影則表示較大的距離。

陰影大小以及擴散量能夠傳達些微差異：

- 兩個平面之間的詳細距離程度。
- 兩個沒有重疊的平面間的層高差距。

![image alt](https://lh3.googleusercontent.com/LA3KMKKDDN_gzLu73HQhPw5nyA_vvP3kMOZp4gcznbCCHbcCXgB5hjmmUxfzpoJfxpAWyq2eQvIpHjSQ0IrDhdnFHpwIJGFC6vHc=w1064-v0)

<p class="anotation">陰影呈現了平面邊緣以及相對於背景的層高。也讓非重疊的平面產生明顯的層高差距。</p>

<div class="img-grid">
    <div class="grid-item">
         <img src="https://lh3.googleusercontent.com/_hAgGrwVfoS_ZUghZVfL1uLNcwrMYCbIHXhftCWMGq8AlwBF8or1aqbtpbrzsHnxM_HltiADX8cTy1fanCQNQ27JMDdifs5S-pd3wlo=w1064-v0" alt="">
        <div class="item-divide divide-gn"></div>
        <div class="item-title title-gn">該這樣做</div>
        <p>陰影使平面的高低差異明顯。應用程式欄擁有較小較銳利的陰影（1）表明它的層高低於擁有較大較柔和陰影的選單（2）。</p>
    </div>
    <div class="grid-item">
         <img src="https://lh3.googleusercontent.com/AjDjtoBwojoBsv5q5OBqzgSG9IGM3cR3r8a3L1CbKsVklQdcbI6Wo33d97SKdffrZJSLaySUGE_Awp7VE7n2TGGI0-GoVzmIkhKqnA=w1064-v0" alt="">
        <div class="item-divide divide-rd"></div>
        <div class="item-title title-rd">別這樣做</div>
        <p>缺少陰影或是其他視覺提示來指示出邊緣以及層面重疊，這會無法在層面間產生足夠的對比。這會導致無法得知UI中的哪些部分是屬於同一群組的。</p>
    </div>
</div>

<div class="grid-all">
         <img src="https://lh3.googleusercontent.com/8itgSUVo2hR27l12ScOnWZMxngftB8dMN7dx3pryB_QA2-S8tXx0nwbu5qlffuqDDijFAi79VenJiKl7leBCcujyqEOFqMGalD5MWA=w1064-v0" alt="">
        <div class="item-divide divide-rd"></div>
        <div class="item-title title-rd">別這樣做</div>
        <p>別將陰影限定為樣式</p>
    </div>
</div>

---

### 動畫以及層高（Motion and elevation）

動畫可以透過以下方式來強調層高：

- 陰影變化
- 顯示重疊
- 推動
- 縮放比例
- 視差

#### 陰影變化（Changes in shadows）

陰影大小以及柔和度的改變能夠強調層高。

<video src="https://kstatic.googleusercontent.com/files/ce038a31bac3bf5bde6ee1ebd55205cbc5fdcaee141deb73c8d7903c18005c53bc11e3f08b03e9172e3904ba14c6e56eead0ee9962ffcba026e02e293592f318" width="100%" controls=""></video>

<p class="annotation">陰影的增加強調該卡片正在上升。</p>

#### 顯示重疊（Displaying overlap）

平面可能藉由動畫來與另一個平面重疊，不論是部分重疊或是全部重疊，動畫會呈現哪個平面在前。

<video src="https://kstatic.googleusercontent.com/files/fb558bab9141d4f1560858f6a53d1c83aeed826aa2c816d0348f43787f3cbb634430ff8cd6232e58167516260ea28be7a3e990ecee474828cd2a423934120dbc" width="100%" controls=""></video>

<p class="annotation">當一個層面擴大時，可以藉由重疊於鄰近的層面來顯示其層高。</p>

#### 推動（Pushing）

在同一層高的平面可以推動相同路徑的其他平面。

<video src="https://kstatic.googleusercontent.com/files/6fb35a502dc12f7ae6954800191b67d2ed2033b688ff3137779262542b110d66af7137cb1842a5a50d1d8e375a4fb06d5178390dbe8e8b3dc1630dcae358b8aa" width="100%" controls=""></video>

<p class="annotation">當一個列表選項被選擇時，它會擴大並將其他項目推動開來。</p>

#### 縮放比例（Scaliing）

縮放一個平面的比例大小能夠強調其層高的變化。

<video src="https://kstatic.googleusercontent.com/files/59c2eeb69fadfa496d85e0ecae0b1f7a7d1759673648e888efa52dfa2d18f2ab91c09861fda10de09baf6ac5a41d8d546b79f5b3158918870b60dfa30b2fd6f3" width="100%" controls=""></video>

<p class="annotation">前景平面以及背景平面透過比例大小的縮放來強調層高變化。</p>

#### 視差（Parallax）

位於不同層高的多個平面以不同的速度移動產生景深，並且能將焦點放置於前景內容上。

<video src="https://kstatic.googleusercontent.com/files/3089f23326472c311f9984f2f05e1bd920bd79b75220bf112307d64f6836f5c8e573cc8440bdce2a09b3da1059262dd7e578645bb642c457e0d071c899de7a52" width="100%" controls=""></video>

<p class="annotation">前景層面移動較背景圖片快，這樣的效果製造出了景深。</p>

#### 結合動畫技巧（Combining motion techniques）

透過結合動畫技巧可以強調層高。

<video src="https://kstatic.googleusercontent.com/files/f0431cbfb8720743c6011ecacc5b697fb9bb6da42147c5cee8c8f79fbd7f1ea167ccca44f2cd9a4ecaad1f4371821426226f97a770bb9c8bd07014653fa1718b" width="100%" controls=""></video>

<p class="annotation">視差動畫以及縮放比例能夠強調出哪些平面的位置在前。</p>

---

## 層高等級（Elevation hierachy）

內容是否與其他內容相關，取決於彼此是否位於相同層高。

### 不同層高的內容（Content at different elevations）

通常，在其他平面前的平面是：

1. 內容較其他內容重要
2. 注目的焦點，如：對話框
3. 控制其後方的平面，如：應用程式列的互動

![image alt](https://lh3.googleusercontent.com/-djeHNq-CQUzYLZdwU_DmbXXiEqQxhwepxUnYwpkW_cs79fcA9bzk5MvrIkhQoNpRNwEkfLkmwkoy3995o7kzS_JOktNSUdJSSoc7GY=w1064-v0)

<p class="annotation">桌機介面的正視圖（1）與側視圖（2）呈現了如何將具有主要焦點的重要內容（B）顯示在具有次要焦點的內容（如註腳（A））前方。</p>

![image alt](https://lh3.googleusercontent.com/NnKjUILrGgvpxtH-LcOGV7fX5rErmB05b-cPb-Wmw8KMnXZUpFeRG5m6qAK2NQ9MuSMMq0ZVcMgTCC0pxUK9Op2g-o1LBDTM_ybkeVE=w1064-v0)

<p class="annotation">移動裝置介面的正視圖（1）與側視圖（2）呈現了將內容放置於較高的平面，如底部選單（A），可以在保持上下文的同時吸引目光。</p>

<video src="https://kstatic.googleusercontent.com/files/86c3bc3552a415061b6d81db26f3ec14fd6fc3898da0fb1f8a809a38bb66a1a48bc5f6a75b229740db103d0a35c76c0f0954ee4d2d153452e2a0922e69b306ed" width="100%" controls=""></video>

<p class="annotation">行動裝置介面的正視圖（1）與側視圖（2）呈現了置於較低層面的內容（A）通常是由位於其前方的平面所控制的，如側邊選單（B）。</p>

---

### 共同層面上的內容（Content on coplanar surfaces）

將平面置於相同層高使其成為共同平面，這可能象徵他們所含括的內容一樣重要。舉例來說，同一群組中的卡片有同等的重要性。

<video src="https://kstatic.googleusercontent.com/files/378f75e16e7f04ec1e937ddedc14abe446bf595eafff25e21cdb65d97c19ca54f2f5479d983927b9a3be68bbd0430c7bbdd72d15c05be0d42fb236b66f24e2df" width="100%" controls=""></video>

<ol class="annotation">
    <li>卡片（A, B）從前方來看都具有相同的層高，且兩者一起移動，這強調了兩者的內容屬於相同等級。</li>
    <li>相同元件的側視圖。</li>
</ol>

沒有呈現層高的平面可以顯示為共同平面。對於沒有呈現層高的平面，您若想要表現內容等級的差異，可以透過內容以及調整水平、垂直布局位置來表示他們之間的相對等級。

舉例來說，在具有共同平面的儀表板上，細節內容會依照語言文字的顯示方向，放置於主要內容旁邊。

![image alt](https://lh3.googleusercontent.com/c0MnFFL7Xqg-jSaafPRsVpbx8g514ZuiTVp8TWfQ_8b-WU2uReql5d73Ct8RA_O9Qqr-AsPgysK6JDO_VG098-6GPABZN071Cscr=w1064-v0)

<ol class="annotation">
    <li>一個桌機互動頁面（UI），從正面來看，顯示了同一高度上的平面（A,B,C）是如何根據英文內容，來從左至右表達其層次結構。</li>
    <li>相同元件的側視圖。</li>
</ol>

---

## 默認層高（Default elevations）

所有的元件都有靜止層高以及動態偏移層高的默認值。某些元件的層高高於其他元件，從而在所有元件之間建立了一致的層高順序。舉例來說，對話框總是出現在其他平面之前。

下表列出了靜止層高以及動態偏移層高的默認值。

### 默認層高值列表

| 元件（Component） | 默認值（dp）（Default elevation values (dp)） |
| ----------------- | -------- |
|   對話框   | 24     |
|   模式底板/模式側板  | 16     |
|   側邊選單  | 16     |
|   浮動操作按鈕（FAB-按壓式） | 12     |
|   標準底板/標準側板  | 8     |
|   底部選單  | 8     |
|   底部標題列  | 8     |
|   選單以及副選單  | 8     |
|   資訊卡（選取時）  | 8     |
|   含文字內容的按鈕（按壓狀態下）  | 8     |
|   浮動操作按鈕（FAB-靜止層高） Snackbar | 6     |
|   置頂標題列（滾動狀態）  | 4     |
|   置頂標題列（靜止層高）  | 0或4     |
|   刷新指示搜尋列（滾動狀態）  | 3     |
|   含文字內容的按鈕（靜止層高）  | 2     |
|   搜尋列（靜止層高）  | 1     |
|   資訊卡（靜止層高）  | 1     |
|   轉換  | 1     |
|   文字按鈕  | 0     |
|   標準側邊表格  | 0     |

---

### 默認層高值圖表

![image alt](https://lh3.googleusercontent.com/pEk_CLv7V6MroLmKY5rA5nCknpKI0ltFZn5yypHiAt0zJzWd5frkMaj2VXWpQmcPtoA_8P-2n0wg9I4JgCWSOKN5nUSgN7IActWvZw=w1064-v0)

<p class="annotation">剖面圖顯示了多種元件的靜止層高以及動態偏移層高。</p>

---

> 譯者：[Jia-Yu, Lin (Sally)](https://www.facebook.com/profile.php?id=100001823224077)
>
> 校稿：[Joanne Chen](https://www.facebook.com/profile.php?id=100000314569800)

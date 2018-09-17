[TOC]

---

# [搞懂px與pt](https://medium.com/uxabc/understanding-ui-units-8acdc0575388)

#### 快速結論
- 大約**163pixel/Inch(英吋)** 即**163ppi** 稱為**@1x**(1倍)
- 1pt固定為**1/72Inch**大小
- 在**@1x**中1pt就是**2x2pixel**

---
# 解析度
[全型號解析度](https://www.paintcodeapp.com/news/ultimate-guide-to-iphone-resolutions)

[使用Image.xcassets加入各式解析度圖片](https://www.youtube.com/watch?v=_36Y6rDcKP0)

```swift
UIImage(named: "image@2x.png") //避免使用這種做法
UIImage(named: "image") //讓ios自動選擇解析度
```

#### 快速結論
- 讓ios自動選擇圖片解析度
- 以pt(point)取代px(pixel)

---

# 用constraint解決layout在各機型寬高不同的問題

[Auto Layout新手指南](https://juejin.im/entry/587856d55c497d00588e4ead)

#### 快速結論
- 盡可能使用官方手段`storyboard`與`constraint`進行layout **避免自己寫code處理適應性**

---
# 影像縮放的contentMode
![w400](images/15369818055095.png)



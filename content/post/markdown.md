---
title: マークダウン記法
description: MarkDown記法について
date: 2021-04-22
categories:
  - "HTML"
tags:
  - "HTML"
  - "CSS"
  - "用語解説"
---
マークダウン記法の簡易まとめ
<!--more-->

## 1.見出し

HTML だと`<h1>`—`<h6>` にあたる要素でレベルが６段階あります。
`<h1>` が最も大きい見出しになり、 `<h6>` が最も小さくなります。

```html
# 見出し h1
## 見出し h2
### 見出し h3
#### 見出し h4
##### 見出し h5
###### 見出し h6
```
***

## 2.段落

改行の後に(スペース)空白を入れる。

## 3.リスト（順番番号なし）
*(アスタリスク),-(ハイフン),+(プラス)のどれかを
入力し、記号の後にスペースまたはタブで挿入する。

## 4.リスト（順番番号あり）
```html
1. 一番目
2. 二番目
3. 三番目
```
    
## 5.リンク：```[リンクテキスト](URL "タイトル")```
## 6.画像：`![代替テキスト](画像のURL)`
## 7.段落内での改行：行末にスペース2つ
## 8.コードの記述：バッククオート
## 9.引用　Blockquotes：>
## 10.テーブル(Hugoがサポートしている方式)
```html
| ID  | Make      | Model   | Year |
| --- | --------- | ------- | ---- |
| 1   | Honda     | Accord  | 2009 |
| 2   | Toyota    | Camry   | 2012 |
| 3   | Hyundai   | Elantra | 2010 |
```
| ID  | Make      | Model   | Year |
| --- | --------- | ------- | ---- |
| 1   | Honda     | Accord  | 2009 |
| 2   | Toyota    | Camry   | 2012 |
| 3   | Hyundai   | Elantra | 2010 |


## 11.コロンで左、中央、右揃えができる
```html
| Tables      | Are           | Cool         |
|:----------- |:-------------:| ------------:|
| align: left | align: center | align: right |
| align: left | align: center | align: right |
| align: left | align: center | align: right |
```
| Tables      | Are           | Cool         |
|:----------- |:-------------:| ------------:|
| align: left | align: center | align: right |
| align: left | align: center | align: right |
| align: left | align: center | align: right |

## 12.テーブル内マークダウン表記
```html
| Inline     | Markdown  | In                | Table      |
| ---------- | --------- | ----------------- | ---------- |
| *italics*  | **bold**  | ~~strikethrough~~ | `code`     |
```
| Inline     | Markdown  | In                | Table      |
| ---------- | --------- | ----------------- | ---------- |
| *italics*  | **bold**  | ~~strikethrough~~ | `code`     |

## 13.コード
```バッククオート３つでシンタックスハイライト```

{{< highlight html >}}
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Example HTML5 Document</title>
</head>
<body>
  <p>Test</p>
</body>
</html>
{{< /highlight >}}

## 14.その他 — abbr, sub, sup, kbd, etc.

<abbr title="Graphics Interchange Format">GIF</abbr> is a bitmap image format.

H<sub>2</sub>O

C<sub>6</sub>H<sub>12</sub>O<sub>6</sub>

X<sup>n</sup> + Y<sup>n</sup> = Z<sup>n</sup>

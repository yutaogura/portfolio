---
title: "このサイトについて"
date: 2021-01-24T06:00:20+06:00
description: このサイトの説明
draft: true
menu:
  sidebar:
    name: このサイトについて
    identifier: introduction-child
    parent: introduction-parent
    weight: 10
---

初めまして、おぐです！

この度、ポートフォリオサイトを作りました。
今までに作った物、これから作る物の置き場として利用していく予定です！

このサイトはHugoという静的サイトジェネレータをTohaというテーマを作っているのですが、Markdownの書き方が少し独特なので、このページは実験的に、いろいろな機能を使ってみたいと思います。


- ドキュメントサイト: https://toha-guides.netlify.app/posts/
- 上のgithubレポジトリ: https://github.com/hugo-toha/guides
### コードブロック
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
### 数式

### 表
Tables aren't part of the core Markdown spec, but Hugo supports them out-of-the-box.

   | Name  | Age |
   | ----- | --- |
   | Bob   | 27  |
   | Alice | 23  |

#### Blockquote with attribution

> Don't communicate by sharing memory, share memory by communicating.</p>
> — <cite>Rob Pike[^1]</cite>

## リスト

#### 順序つきリスト

1. First item
2. Second item
3. Third item

#### 順序なしリスト

* List item
* Another item
* And another item

#### 入れ子リスト

* Fruit
  * Apple
  * Orange
  * Banana
* Dairy
  * Milk
  * Cheese

## Other Elements — abbr, sub, sup, kbd, mark

<abbr title="Graphics Interchange Format">GIF</abbr> is a bitmap image format.

H<sub>2</sub>O

X<sup>n</sup> + Y<sup>n</sup> = Z<sup>n</sup>

Press <kbd><kbd>CTRL</kbd>+<kbd>ALT</kbd>+<kbd>Delete</kbd></kbd> to end the session.

Most <mark>salamanders</mark> are nocturnal, and hunt for insects, worms, and other small creatures.

[^1]: The above quote is excerpted from Rob Pike's [talk](https://www.youtube.com/watch?v=PAAkCSZUG1c) during Gopherfest, November 18, 2015.
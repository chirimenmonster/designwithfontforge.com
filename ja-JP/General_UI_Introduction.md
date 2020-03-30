---
published: true
layout: bookpage_ja-JP
weight: 16
category: Getting To Know FontForge
title: 一般的な UI の概要
---
<!--
published: true
layout: bookpage
weight: 16
category: Getting To Know FontForge
title: General UI Introduction
-->

<!--
FontForge has the same interface on Windows, Mac OS and GNU/Linux operating systems. 
-->
FontForge は、Windows、Mac OS、GNU/Linux オペレーティングシステムで共通のインターフェイスとなっています。

<!--
Here is a short introduction to the essential features by Dave Crossland at a Crafting Type workshop, a non-profit type design workshop that supports the FontForge project:
-->
FontForge プロジェクトをサポートする非営利のデザインワークショップである Crafting Type ワークショップで行われた、Dave Crossland による主要機能の簡単な紹介を以下に示します。

<iframe width="853" height="480" src="https://www.youtube-nocookie.com/embed/_EhwHL1aloI?rel=0&amp;showinfo=0&t=1m55s" frameborder="0" allowfullscreen></iframe>

<!--
There are 4 main windows: 
-->
下記の 4 つのメインウィンドウがあります:

<!--
#### 1. The Font View Window
-->
#### 1. フロントビューウィンドウ

<!--
This window appears when you first run FontForge. 
It shows a table of the glyphs in the font. 
-->
このウィンドウは FontForge を起動したときに最初に表示されます。
フォントに含まれるグリフの表が表示されます。

<!--
#### 2. The Character View Window
-->
#### 2. キャラクタービューウィンドウ

<!--
Double click a glyph in the Font View to open it in the Character View. 
This is where you can draw and edit glyphs, either one at a time with a tab interface, or side by side with a prepared text file of words to step through.
-->
フロントビューに表示されているグリフをダブルクリックするとキャラクタービューが開きます。
ここではグリフを描画したり編集したりすることができます。
グリフはタブインターフェースを使用して一つずつ選択するか、あらかじめ用意していおいた単語のテキストファイルを並べておいて連続して選択することができます。

<!--
#### 3. The Metrics View Window
-->
#### 3. メトリックビューウィンドウ

<!--
Go to Window, Metrics, or Metrics, Window. 
Or select some glyphs in the Font View and hit <kbd>Ctrl</kbd> + <kbd>K</kbd>. 
You can also drag and drop glyphs from the Font View to the Metrics View.
-->
「ウィンドウ」->「メトリック」、または「メトリック」->「ウィンドウ」で移動します。
または、フォントビューでいくつかのグリフを選択し、<kbd>Ctrl</kbd> + <kbd>K</kbd> を押します。
グリフをフォントビューからメトリックビューにドラッグアンドドロップすることもできます。

<!--
This is where you can adjust the spacing and kerning of your font.
You can also step through a prepared word list text file here.
-->
ここでフォントの間隔とカーニングを調整できます。
事前に用意しておいた単語リストのテキストファイルを使って連続して実行することもできます。

<!--
#### 4. The Font Info Window
-->
#### 4. フロントビューウィンドウ

<!--
Go to Elements, Font Info. 
Here you'll find all the _metadata_ about the font. 
-->
「エレメント」->「フォント情報」で移動します。
ここにはフォントに関するすべての「メタデータ」が表示されます。

<!--
#### 5. The Typesetting Environment, for Testing
-->
#### 5. テストのための組版環境

<!--
Outside any font editor, you'll need a typesetting system to test your fonts in use. 
This is one of the **big secrets** of professional type designers: 
A lot of the most important work in a typeface design project is done outside the font editor, in testing documents created in a typesetting system. 
The main systems are:
-->
フォントエディタの外部環境として、フォントをテストするための組版システムが必要となります。
これは、プロの書体デザイナーが抱えている**大きな秘密**の 1 つです。
書体デザインのプロジェクトで最も重要な作業の多くは、フォントエディタ以外の場所で行われるもので、それは組版システムで作成されたドキュメントのテストにあります。
主なシステムは次のようなものです：

<!--
* Web (Firefox, Chromium, etc)
* DTP tools (Scribus, Inkscape, etc)
* Word Processors (Libre Office, AbiWord, Calligra Words, etc)
* Programming Page Layout Processors (LaTeX, ConTeXt, SILE, ShoeBot, Even, etc)
-->
* ウェブ（Firefox, Chromium など）
* DTP ツール（Scribus, Inkscape など）
* ワードプロセッサー（Libre Office, AbiWord, Calligra Words など）
* ページレイアウト処理システム（LaTeX, ConTeXt, SILE, ShoeBot, Even, など）

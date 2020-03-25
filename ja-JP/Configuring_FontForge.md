---
published: true
layout: bookpage_ja-JP
weight: 16
category: Getting To Know FontForge
title: FontForge の設定
---
<!--
published: true
layout: bookpage
weight: 16
category: Getting To Know FontForge
title: Configuring FontForge
-->

<!--
FontForge can be fine-tuned in various ways.
Here are some tips and tricks for doing so.
You have many options for optimizing FontForge for your platform and workflow.
-->
FontForge はさまざまな方法で調整できます。
そのためのヒントとコツをいくつか紹介します。
プラットフォームやワークフローに合わせて FontForge を最適化する多くのオプションがあります。

<!--
Please [tell us](https://github.com/fontforge/designwithfontforge.com#how-to-contribute) us if you have any tips you want to share.
-->
共有したいヒントがあれば[連絡ください](https://github.com/fontforge/designwithfontforge.com#how-to-contribute)。

<!--
#### First Things First
-->
#### まずはじめに

<!--
When making any configuration changes, be sure to follow this:
-->
設定を変更するときは、必ず以下のようにしてください。

<!--
1. Quit FontForge (and X11)
2. Make the changes
3. Start FontForge and test your changes
-->
1. FontForge を終了する (X11 も)
2. 設定を変更する
3. FontForge を実行し、変更内容をテストする

## Windows

<!--
Currently we have nothing specific to the Windows distribution.
If you think of something, [tell us](https://github.com/fontforge/designwithfontforge.com#how-to-contribute).
-->
現在のところ、Windows ディストリビューションに固有の設定はありません。
何かあれば[報告してください](https://github.com/fontforge/designwithfontforge.com#how-to-contribute)。

## GNU+Linux

<!--
Currently we have nothing specific to any GNU+Linux distribution.
If you think of something, [tell us](https://github.com/fontforge/designwithfontforge.com#how-to-contribute).
-->
現在のところ、どの GNU+Linux ディストリビューションについても固有の設定はありません。
何かあれば[報告してください](https://github.com/fontforge/designwithfontforge.com#how-to-contribute)。

## Mac OS X

<!--
To open a long file or folder location path provided below:
-->
ファイルパスやフォルダーパスが長い場合には、次のようにして開きます：

<!--
1. Copy the path
2. `⌘ Tab` to switch to Finder
3. `⇧⌘G` to open the Go menu&nbsp;&nbsp;→&nbsp;&nbsp;Go to Folder item
4. `⌘V` to paste in the path
5. `Go` to open a new Finder window at that location
-->
1. パスをコピーします。
2. `⌘ Tab` で Finder を切り替えます
3. `⇧⌘G` で「移動」&nbsp;&nbsp;→&nbsp;&nbsp;「フォルダへ移動」ダイアログを開きます
4. `⌘V` でパスをペーストします
5. `移動` でその場所での新しい Finder を開きます。

<!--
#### Keyboard Shortcuts
-->
#### キーボードショートカット

<!--
Many dialog and menu items have one letter that is u<span class="underline">n</span>derlined.
These can be accessed immediately by pressing <kbd>Ctrl</kbd> + <kbd>Alt</kbd> and that key.
For example, if a dialog asks you if you're <span class="underline">O</span>K, press <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>o</kbd>.
-->
多くのダイアログおよびメニュー項目には、下線付きの文字が含まれています。
そうした項目には <kbd>Ctrl</kbd> + <kbd>Alt</kbd> とその文字のキーを押すことで簡単にアクセスすることができます。
たとえば、承認するかどうかを確認する <span class="underline">O</span>K のダイアログが表示された場合は、<kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>O</kbd> を押す、というようにします。

<!--
If you do not use a US English keyboard, you may find some of the keyboard shortcuts are silly.
Or, you might just want to customize them to be the way that you expect.
To change these keys open and edit the `default` text file, located here:
-->
US キーボード以外では、ショートカットの一部がおかしくなっていることがあります。
また、デフォルトのショートカットが気に入らない場合は、好みの動作になるようカスタマイズすることができます。
これらのキーを変更するには、次の場所にある `default` という名称のテキストファイルを編集します。

```
/Applications/FontForge.app/Contents/Resources/opt/local/share/fontforge/hotkeys/default
```

<!--
When you install the next release, all files inside `/Applications/FontForge.app` will be overwritten, so save a duplicate copy of your `default` file somewhere else, too.
-->
新しいリリースをインストールすると `/Applications/FontForge.app` 内のすべてのファイルが上書きされてしまうため、`default` のコピーを別の場所に保存しておいてください。

<!--
#### UI Size
-->
#### UI サイズ

<!--
If the UI looks too big or too small, it can be scaled to better fit your computer.
Open and edit the `resources` text file, located here:
-->
UI が大きすぎたり小さすぎたりする場合は、使用するコンピューターに合わせて拡大縮小できます。
以下のフォルダにある `resources` という名称のテキストファイルを開いて編集します。

```
/Applications/FontForge.app/Contents/Resources/opt/local/share/fontforge/pixmaps/resources
```

<!--
Add the line `Gdraw.ScreenWidthCentimeters: 34` if your screen is 34cm wide.
Try different values until you're happy.
-->
画面の幅が 34cm であれば、`Gdraw.ScreenWidthCentimeters： 34` という行を追加します。
納得いくまで、さまざまな値を試してください。

<!--
#### Bookmarks
-->
#### ブックマーク

<!--
In the file dialog there is a button to `Bookmark Current Dir`, but `Remove Bookmark...` doesn't work [#2054](https://github.com/fontforge/fontforge/issues/2054).
You can edit the list manually in the `FCBookmarks` section of the `prefs` file located at
-->
ファイルダイアログに `Bookmark Current Dir` （現在のディレクトリをブックマーク）というボタンがありますが、`Remove Bookmark...` （ブックマークを削除...）は機能しません [#2054](https://github.com/fontforge/fontforge/issues/2054)。
以下の場所にある `prefs` ファイルの `FCBookmarks` セクションの箇所でリストを直接編集できます。

```
~/.config/fontforge/prefs
```

<!--
Reset your bookmarks by opening Terminal and pasting the following text into Terminal:
-->
「ターミナル」を開き、次のテキストをターミナルに貼り付けて、ブックマークをリセットします。

```
sed -i bak -e 's/^FCBookmarks.*/FCBookmarks:     ~\/Library\/Fonts\/;\/Library\/Fonts\/;\/System\/Library\/Fonts\//g' ~/.config/fontforge/prefs;
```

<!--
Then press Enter to run this command.
If you see no errors, it worked correctly.
-->
次に、Enter キーを押してこのコマンドを実行します。
エラーが表示されなければ、正しく機能しています。

<!--
#### 3 button mouse
-->
#### 3 ボタンマウス

<!--
FontForge uses three mouse button clicks for some extra functions.
If you don't have a three button mouse you can emulate that by enabling it in X11/Xquartz preferences, in the `Input` section's option `Emulate three button mouse`
-->
FontForge は、いくつかの追加機能のために 3 つのマウスボタンを使用します。
3 ボタンマウスがない場合は、X11/Xquartz 環境設定で有効にして、`Input` （入力）セクションのオプション `Emulate three button mouse` （3 ボタンマウスをエミュレート）でエミュレートできます。

<!--
#### Change X11/XQuartz icon to FF icon
-->
#### X11/XQuartz アイコンを FF アイコンに変更する

<!--
If you primarily use X11 for FontForge, you can change its icon. Copy and paste the following text into the terminal and follow the instructions
-->
X11 で FontForge を使用している場合は、アイコンを変更することができます。
次のテキストをコピーしてターミナルに貼り付け、指示に従います

```
sudo cp -f /Applications/FontForge.app/Contents/Resources/FontForge.icns /Applications/Utilities/XQuartz.app/Contents/Resources/X11.icns | sudo touch /Applications/Utilities/XQuartz.app 
```

<!--
#### Window management
-->
#### ウィンドウの制御

<!--
FontForge isn't a native Mac app, so window handling can be slighty "off," especially on dual monitor systems.
To regain control of window positions, use the free, libre, open source [ShiftIt](https://github.com/fikovnik/ShiftIt) utility to assign keyboard shortcuts to set window positions.
-->
FontForge はネイティブの Mac アプリではないため、特にデュアルモニタシステムでは、ウィンドウがたまに操作できなくなる場合があります。
ウィンドウ位置の制御を取り戻すには、無料で自由なオープンソースの [ShiftIt](https://github.com/fikovnik/ShiftIt) ユーティリティを使用して、ウィンドウの位置を設定するためのキーボードショートカットを割り当てます。

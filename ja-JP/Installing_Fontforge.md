---
published: true
layout: bookpage_ja-JP
weight: 15
category: Getting To Know FontForge
title: FontForge のインストール
---
<!--
published: true
layout: bookpage
weight: 15
category: Getting To Know FontForge
title: Installing FontForge
-->

<!--
FontForge is libre software, so you can download, share and install copies without any restrictions on usage - both commercial or personal use is encouraged.
It is a community-maintained application, and anyone can contribute to the source code.
-->
FontForge は「リブレソフトウェア」（訳注: 自由ソフトウェア、フリーソフトウェアのフリーが「自由」の意であることを主張する場合によく用いられる）であるため、商用でも個人でも、使用上の制限なしに、ソフトウェアをダウンロードしたり共有したりインストールしたりすることができます。
これはコミュニティが管理するアプリケーションであって、誰でもソースコードに貢献することができます。

<!--
FontForge is available in easy to install packages for Windows, Mac OS X and GNU+Linux operating systems. 
-->
FontForge は、Windows、Mac OS X、GNU+Linux オペレーティングシステム用に使いやすいインストールパッケージが提供されています。

<!--
### Installing FontForge on Windows
-->
### Windows に FontForge をインストールする

<!--
An [installation guide](http://fontforge.github.io/en-US/downloads/windows/) is available for the official Windows builds, prepared by Jeremy Tan.
-->
Jeremy Tan が作成した公式の Windows 用[インストールガイド](http://fontforge.github.io/en-US/downloads/windows/)が用意されています。

<!--
### Installing FontForge on Mac OS X
-->
### Mac OS X に FontForge をインストールする

<!--
An [installation guide](http://fontforge.github.io/en-US/downloads/mac/) is available for the official Mac builds, prepared by Dr Ben Martin. 
-->
Dr Ben Martin が作成した公式の Mac 用[インストールガイド](http://fontforge.github.io/en-US/downloads/mac/)が用意されています。

<!--
### Installing on GNU/Linux
-->
### GNU/Linux にインストールする

<!--
The easiest method to get FontForge on your Linux machine is to use your Linux distribution’s package repository.
-->
Linux 機に FontForge をインストールする最も簡単な方法は、Linux ディストリビューションのパッケージリポジトリを使用することです。

<!--
#### Debian or Ubuntu
-->
#### Debian または Ubuntu

<!--
The FontForge package included in Ubuntu 14.04 by default dates from 2012, so it is preferable to install the more up-to-date package from the FontForge [Personal Package Archive (PPA)] (https://launchpad.net/~fontforge/+archive/ubuntu/fontforge).
-->
Ubuntu 14.04 に含まれる FontForge パッケージはデフォルトで 2012 年のものであるため、FontForge [Personal Package Archive (PPA)](https://launchpad.net/~fontforge/+archive/ubuntu/fontforge) から最新のパッケージをインストールすることをお勧めします。

<!--
Check that the helper script `add-apt-repository` is installed:
-->
ヘルパースクリプト `add-apt-repository` がインストールされていることを確認してください:
    
```sh
sudo apt-get install software-properties-common;
```

<!--
Add the FontForge PPA (which will also add the authentication key):
-->
FontForge PPA を追加してください（認証鍵も追加されます）:
    
```sh
sudo add-apt-repository ppa:fontforge/fontforge;
```

<!--
Update the software list to include packages from the PPA:
-->
PPA からダウンロードできるソフトウェアのリストを更新します:
    
```sh
sudo apt-get update;
```

<!--
Install FontForge:
-->
FontForge をインストールします:
    
```sh
sudo apt-get install fontforge;
```

#### Fedora

<!--
To install FontForge on your Fedora Linux desktop machine run the following yum command as the root user. 
This will require about 10MiB of download to complete.
-->
Fedora Linux のデスクトップ機に FontForge をインストールするには、root ユーザー権限で次の yum コマンドを実行します。
完了までには、約 10MiB （訳注: 1MiB = 1.049MB）をダウンロードする必要があります。

```
yum install fontforge;
```

<!--
If you have not compiled software on your Fedora machine, after installing gcc, automake, autoconf and others then you might get an error during the execution of autogen.sh with libtoolize. 
If that is the case you might need to install the libtool-ltdl-devel package on Fedora or a similar development package on another GNU+Linux distribution.
-->
使用している Fedora 機でソフトウェアをコンパイルしたことがない場合、gcc, automake, autoconf などをインストールしてから、libtoolize で autogen.sh を実行するとエラーになるかもしれません。
その場合は Fedora に libtool-ltdl-devel パッケージをインストールするか、別の GNU + Linux ディストリビューションに同様の開発パッケージをインストールする必要があります。

<!--
After issuing the yum install you should be able to run FontForge from your menu or directly from the konsole or gnome-terminal by issuing the `fontforge` command.
-->
yum インストールを実行すれば、メニューから FontForge が実行できるようになっているか、または konsole や gnome-terminal で `fontforge` コマンドを直接入力して FontForge を実行できようになっているはずです。

<!--
## Compile your own version from Github
-->
## GitHub から取得した独自のバージョンをコンパイルする

<!--
GitHub is a source-code hosting service where everyone can contribute to the development of a piece of software. 
It stores the current leading state of development of the application.
In some cases, perhaps because you want access to a feature not yet available in the release packages, you may wish to compile your own version from Github.
-->
GitHub は、誰もがソフトウェアの開発に貢献できるように用意されたソースコードホスティングサービスです。
GitHub にはアプリケーション開発の現在の主要な状態が保存されています。
ときには、リリースパッケージでまだ利用できない機能を使用したいとかいう目的で、Github から独自のバージョンを取得してコンパイルすることができます。

<!--
Full instructions are at <https://github.com/fontforge/fontforge/blob/master/INSTALL.md>
-->
完全な手順は <https://github.com/fontforge/fontforge/blob/master/INSTALL.md> で説明されています。

<!--
## Debugging the FontForge software
-->
## FontForge のデバッグ

<!--
See the [Debugging](When_Things_Go_Wrong_With_Fontforge_Itself) section for more information.
-->
詳細な解説は[デバッグ](When_Things_Go_Wrong_With_Fontforge_Itself)セクションを参照してください。

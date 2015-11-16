「**[MacVim](http://code.google.com/p/macvim/) ＋ [香り屋さんのパッチ](http://www.kaoriya.net/software/vim/) ＋ なるべく日本語化 ＝ 香り屋さんのWindows版の使い勝手に近いMacVim**」を**勝手に**目指すプロジェクトです。

[![](http://splhack.github.io/macvim-kaoriya/macvim-kaoriya-s.png)](http://splhack.github.io/macvim-kaoriya/macvim-kaoriya.jpg)

## MacVim ##

マルチウインドウが使えるMac OS XアプリケーションのVim(gVim)です。GUIを担当するMacVimと、Vim本体から構成されています。Vim本体はコンソールアプリケーションとしても使用できます。

## 香り屋版 ##

日本語を扱う上で便利な設定やスクリプトが追加されています。ローマ字のまま日本語をインクリメンタル検索できるmigemo機能が統合されています。詳しくは[こちら(http://d.hatena.ne.jp/thinca/20090619/1245338963)](http://d.hatena.ne.jp/thinca/20090619/1245338963)をご覧ください。

## MacVim-KaoriYa ##

MacVimに対して、香り屋パッチの統合、ローカライズ、MacVim固有の設定、日本語文字コード自動判別、必要なshared library、Perl/Python/Rubyのdynamic loading、Objective-C対応ctags、などを追加しています。[詳しくはこちらのページにまとめてあります](https://github.com/splhack/macvim-kaoriya/wiki/DiffMacVimVsMacVimKaoriYa)。インストールしてすぐ使えるのが目標です。もちろんTerminal.app、iTerm.app上で動くコンソール版Vimとしても使用できます。

詳しくはドキュメント「[はじめにお読みください](https://github.com/splhack/macvim-kaoriya/wiki/Readme)」をご覧ください

## インストール ##

[MacVim-KaoriYa GitHubリリースページ](https://github.com/splhack/macvim-kaoriya/releases/latest)からdmgファイルをダウンロードして、dmgファイルを開きます。MacVimアイコンをアプリケーションフォルダにドラッグするだけでインストール完了です。

## アップデート ##

MacVimに組み込まれた[Sparkle](http://sparkle.andymatuschak.org/)によるアプリケーション自動更新機能があり、[Sparkle用のfeed](https://raw.githubusercontent.com/splhack/macvim-kaoriya/master/latest.xml)を自動または手動で確認して、アプリケーションを更新することができます。

手動で行う場合は、インストール時と同じくMacVimアイコンをアプリケーションフォルダにドラッグして、上書きコピーすれば完了です。

## ドキュメント ##

[はじめにお読みください](https://github.com/splhack/macvim-kaoriya/wiki/Readme)

## ソースコードからのビルド [![Build Status](https://travis-ci.org/splhack/macvim.svg?branch=master)](https://travis-ci.org/splhack/macvim)[![Build Status](https://travis-ci.org/splhack/macvim-kaoriya.svg?branch=master)](https://travis-ci.org/splhack/macvim-kaoriya) ##

[ビルド方法のページ](https://github.com/splhack/macvim-kaoriya/wiki/Building)


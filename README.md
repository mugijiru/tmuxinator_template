# tmuxinator template #

## これは何? ##

[tmuxinator](https://github.com/tmuxinator/tmuxinator) 用の設定ファイルのテンプレート。
ただし思いっきり自分用

## 詳細 ##

### rails.yml ###

`~/projects/dev/` 以下に作った Rails プロジェクト用。
タスクランナーとして [Guard](https://github.com/guard/guard) を使うことを想定している。

0番目の window ではログファイルを表示
1番目の window は4分割してそれぞれに開発で見る物を表示

* rails dbconsole
* guard
* rails console
* zsh

### fuel.yml ###

`~/projects/dev/` 以下に作った FuelPHP プロジェクト用。
[FuelPHP](http://fuelphp.com/) 以外に
[Robo](http://robo.li/) というタスクランナーにも依存している。

0番目の window ではログファイルを表示。
その際に `fuel` という自分用に作って公開してないコマンドを叩いている。

1番目の window は4分割してそれぞれに開発で見る物を表示。

* mysql console
* FuelPHP console
* Robo(PHPのタスクランナー)
* zsh

## ライセンス ##

The MIT License (MIT)

Copyright (c) 2016 Mugijiru

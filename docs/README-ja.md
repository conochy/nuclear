# ![nuclear](https://i.imgur.com/oT1006i.png) 
[![Maintainability](https://api.codeclimate.com/v1/badges/a15c4888a63c900f6cc1/maintainability)](https://codeclimate.com/github/nukeop/nuclear/maintainability) [![Codacy Badge](https://api.codacy.com/project/badge/Grade/30750586202742279fa8958a12e519ed)](https://www.codacy.com/app/nukeop/nuclear?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=nukeop/nuclear&amp;utm_campaign=Badge_Grade) [![nuclear](https://snapcraft.io//nuclear/badge.svg)](https://snapcraft.io/nuclear) ![Travis](https://api.travis-ci.org/nukeop/nuclear.svg?branch=master)

無料のソースからストリーミングするスクトップ音楽プレーヤー

![Showcase](https://i.imgur.com/G9BqIHl.png)

# Links

[公式サイト](https://nuclear.js.org)

[Mastodon](https://mstdn.io/@nuclear)

[Twitter](https://twitter.com/nuclear_player)

サポート (Matrix): `#nuclear:matrix.org`

Discord: https://discord.gg/JqPjKxE

Readme の翻訳: 
* [ブラジル ポルトガル語](docs/README-ptbr.md)
* [スウェーデン語](docs/README-se.md)
* [日本語](docs/README-ja.md)

## これは何ですか？

nuclear は、インターネットの無料ソースからコンテンツを取得する、無料の音楽ストリーミングプログラムです。

これは、[mps-youtube](https://github.com/mps-youtube/mps-youtube) と似たような音楽プレーヤーですが、GUI を備えています。
また、オーディオにも重点を置いています。お金を払う必要がなく、より大きなライブラリを備えた Spotify を想像してみてください。

## 電気製品に宗教上の理由で反対している場合はどうなりますか？

[this](docs/electron.md) をご覧ください。

## 特徴

- YouTube (プレイリストとの統合を含む)、Jamendo、Audius、SoundCloud から音楽を検索して再生
- アルバムの検索 (Last.fm と Discogs を使用)、アルバムの表示、アーティストとトラック名に基づく自動の曲検索 (開発中、一部が正しく機能しないな場合があります)
- プレイリストとしてエクスポートできるソングキュー
- 保存されたプレイリストの読み込み (json ファイルに保存)
- Last.fm の聴いた音楽の追跡 (「再生中」ステータスの更新も行われます)
- レビュー付きの最新のトラックとアルバム
- ジャンル別のブラウジング
- ラジオモード (類似のトラックを自動的にキューに追加する)
- 無制限のダウンロード (YouTubeを利用)
- リアルタイムの歌詞表示
- 人気の曲の閲覧
- お気に入りのトラックのリスト
- ローカルのライブラリを開く
- アカウントの登録が不要
- 広告なし
- CoC なし
- CLA なし

## マニュアルとドキュメント

https://nuclearmusic.rtfd.io/

## コミュニティが管理するパッケージ

これは、さまざまなパッケージ マネージャー向けのパッケージのリストです。そのほとんどは第三者によって管理されています。メンテナーの方々のご尽力に感謝いたします。

| パッケージタイプ| リンク                                                 | メンテナー                                    |
|:--------------:|:-------------------------------------------------------:|:---------------------------------------------:|
| AUR (Arch)     | https://aur.archlinux.org/packages/nuclear-player-bin/  | [advaithm](https://github.com/advaithm)       |
| AUR (Arch)     | https://aur.archlinux.org/packages/nuclear-player-git   | [advaithm](https://github.com/advaithm)       |
| Choco (Win)    | https://chocolatey.org/packages/nuclear/                | [JourneyOver](https://github.com/JourneyOver) |
| Homebrew (Mac) | https://formulae.brew.sh/cask/nuclear                   | Homebrew                                      |
| Snap           | https://snapcraft.io/nuclear                            | [nukeop](https://github.com/nukeop)           |
| Flatpak        | https://flathub.org/apps/details/org.js.nuclear.Nuclear  | [advaithm](https://github.com/advaithm)       |

私(advaithm) に彼女のサーバーをコンパイルマシンとして使用させてくれた [ayyeve](https://github.com/ayyEve) に感謝いたします。

## コミュニティの翻訳

nuclear はいくつかの言語に翻訳されており、さらに翻訳してくれる協力者を探しています。以下は、現在利用可能な言語のリストと、nuclear を翻訳するのを手伝った協力者の一覧です。
| Language             | Contributor                                                                                          |
|:--------------------:|:----------------------------------------------------------------------------------------------------:|
| 英語                 | N/A                                                                                                  |
| フランス語           | [charjac](https://github.com/charjac), [Zalax](https://github.com/Zalaxx)                            |
| オランダ語           | [Vistaus](https://github.com/Vistaus)                                                                |
| デンマーク語         | [Hansen1992](https://github.com/Hansen1992)                                                          |
| スペイン語           | [mlucas94](https://github.com/mlucas94), [emlautarom1](https://github.com/emlautarom1)               |
| ポーランド語         | [kazimierczak-robert](https://github.com/kazimierczak-robert), [gradzka](https://github.com/gradzka) |
| ドイツ語             | [schippas](https://github.com/schippas)                                                              |
| ロシア語             | [ramstore07](https://github.com/ramstore07), [dmtrshat](https://github.com/dmtrshat)                 |
| ブラジル ポルトガル語| [JoaoPedroMoraes](https://github.com/JoaoPedroMoraes)                                                |
| トルコ語             | [3DShark](https://github.com/3DShark)                                                                |
| イタリア語           | [gello94](https://github.com/gello94)                                                                |
| スロバキア語         | [MartinT](https://github.com/MartinTuroci)                                                           |
| チェコ語             | [PetrTodorov](https://github.com/PetrTodorov)                                                        |
| タガログ語           | [giftofgrub](https://github.com/giftofgrub)                                                          |
| 繁体字中国語         | [oxygen-TW](https://github.com/oxygen-TW)                                                            |
| スウェーデン語       | [PalleKarlsson](https://github.com/PalleKarlsson)                                                    |
| ギリシャ語           | [Shuin-San](https://github.com/Shuin-San)                                                            |
| 日本語               | [conochy](https://github.com/conochy)                                                                |

## 開発プロセス

まず最初に、必ず[貢献者用 Wiki](https://github.com/nukeop/nuclear/wiki/Contributing) をチェックしてください。

npm を使用します:
```shell
$ npm install # 依存関係をインストールします
$ npm start
```

Webアプリをロードして nuclear を実行する新しいウィンドウが開きます。

---
現在の OS 用にビルド:
```shell
$ lerna bootstrap
$ npm run build
```

`build` の代わりに `build:all` を使用してすべての OS 用にビルドできます。ビルドしたバイナリは `packages/app/release` にあります。

---
Docker を使用して開発環境を実行することも可能ですが、これは実験的なものと見なす必要があります。

docker と docker-compose が必要になります。また、root ユーザーが X11 ディスプレイに接続できるようにする必要があります。その後、docker-compose を実行します。:

```shell
$ xhost SI:localuser:root
$ sudo docker-compose up dev
```
flatpak バージョンを作成することもできます。gobject-introspection と flatpak-builder をインストールする必要があります。その後、コンパイルプロセスのために flatpak-builder に必要なランタイムと依存関係をインストールする必要があります。flatpak 19.08 が必要になります。
```shell
$ flatpak install flathub org.freedesktop.Platform
$ flatpak install flathub org.freedesktop.Sdk
$ flatpak install flathub io.atom.electron.BaseApp
```
次に、プロジェクトをビルドします。(`--verbose` を使用してより多くの出力を取得できます):
```shell
$ flatpak-builder build-dir org.js.nuclear.Nuclear.json
```
ビルドしたアプリを実行する: 
```shell
$ flatpak-builder --run build-dir org.js.nuclear.Nuclear.json run.sh
```
アプリをローカルリポジトリに変えることができます。現在、ファイルは最新リリースをビルドします。

## スクリーンショット

これは、プログラムの改良に応じて更新されます。

![アルバムの検索](https://i.imgur.com/idFVnAF.png)

![アルバムの表示](https://i.imgur.com/Kvzo3q7.png)

![アーティスト ビュー](https://i.imgur.com/imBLYl3.png)

![ダッシュボードの話題の新曲](https://i.imgur.com/bMDrR4M.png)

![ダッシュボードのジャンル](https://i.imgur.com/g0aCmKx.png)

![プレイリスト](https://i.imgur.com/2VMXHDC.png)

![歌詞](https://i.imgur.com/7e3DJKJ.png)

![イコライザ](https://i.imgur.com/WreRL0w.png)

## ライセンス

このプログラムはフリーソフトウェアです。Free Software Foundation によって公開されている GNU Affero General Public License(AGPL) 3 、または(オプションで)それ以降のバージョンの条件の下で、再配布・改変することができます。
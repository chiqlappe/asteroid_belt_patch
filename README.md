# PC-8001 "ASTEROID BELT"用 インベーダー音源パッチ

## 目的
[@Bonezine](https://twitter.com/Bonezine)さんが製作されたインベーダー音源を使ってゲームの効果音を出力する

## 使い方
1. ゲームのBASICファイルと機械語ファイルをロードする
2. BASICの150行を`CLEAR 300,&HCFFF`に修正する
3. このパッチプログラムをロードする
4. モニタから`GD000`を実行する
5. ベーシックから`RUN`を実行する

* パッチを当てた機械語プログラムを保存するには、モニタから`WD000,E6FF`を実行して下さい
* 音が止まらない時は`OUT 16,255`を実行して下さい

[1978年のゲームサウンド再現計画～最終章～【基板Ｚ】](https://bonezine.booth.pm/items/1549865)

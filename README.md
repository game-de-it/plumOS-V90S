# plumOS-V90S
plumOS-V90S


<img src="https://github.com/game-de-it/plumOS-V90S/blob/main/asset/plumOS-V90S_logo.png" width="640">  
  
<img src="https://github.com/game-de-it/plumOS-V90S/blob/main/asset/sc01.jpg" width="320">  

<img src="https://github.com/game-de-it/plumOS-V90S/blob/main/asset/sc02.jpg" width="320"> <img src="https://github.com/game-de-it/plumOS-V90S/blob/main/asset/sc03.jpg" width="320">   
<img src="https://github.com/game-de-it/plumOS-V90S/blob/main/asset/sc04.jpg" width="320"> <img src="https://github.com/game-de-it/plumOS-V90S/blob/main/asset/sc05.jpg" width="320">     






---
# はじめに
[Click here for the English version of the explanation](./README_EN.md)

plumOS-V90SはStockOS(Batocera)をベースにして作られたCFWです
Batoceraの操作方法については下記リンクを参照してください
https://wiki.batocera.org/start


## ダウンロード
[「Releasesページ」からSDイメージファイルをダウンロードできます](https://github.com/game-de-it/plumOS-V90S/releases)



## 基本的な機能
- [pyxel](https://github.com/kitao/pyxel) が利用可能
- Portmasterが利用可能
- OD-Commanderが利用可能
- SSH接続が可能
   - ユーザ名は `root` 、パスワードは `linux`
- samba接続が可能
   - ユーザ名は `root` 、パスワードは `linux`
- yabasanshiroコアを変更してパフォーマンスアップ
- wifi接続時に自動時刻合わせされます
   - これは実験的な機能であり、あなたのグローバルIPアドレスから判断される地域・場所によって時刻が自動的に設定されます
- RetroarchでUSB-DAC利用時のノイズ解消
- 音量を150%までブースト可能

## 既知の問題
- スクレイピング機能は利用できません
- Portmasterの動作についてはお答えできませんので、Portmasterのdiscordなどで情報を収集してください

## OSのホットキー
| Button Combo | Action | 
|:-----------|------------:|
| SELECT+Vol+       |        画面輝度を上げる |
| SELECT+Vol-       |        画面輝度を下げる |
| SELECT+R2       |        左アナログスティック機能が有効 |

> [!IMPORTANT]
> SELECT+R2を押すとDパッドがアナログスティック機能として擬態するため、カーソル移動などができなくなる場合がありますので注意してください。  
> 再度SELECT+R2を押すとDパッドが有効になり、カーソル移動などができるようになります.  


## Retroarchの仕様
- RetroArchのホットキー
  - ※Hotkeyの設定はsystemディレクトリ配下にある`Batocera.conf`ファイルを編集することで変更可能です  

| Button Combo | Action | 
|:-----------|------------:|
| SELECT+B     |      Retroarchメニュー表示 |
| SELECT+R       |        ステートセーブ |
| SELECT+L     |      ステートロード |
| SELECT+R2     |      ファストフォワード |
| SELECT+L2     |      スローモーション |
| SELECT+X     |      スナップショット |
| SELECT+Y     |      FPS表示 |

> [!WARNING]
> SELECT+R2 (ファストフォワード)は前述したDパッドを左アナログスティックに擬態する機能と競合します。  
> Retroarchで動作する多くのゲームでは左アナログスティックはDパッドの代わりになるため操作に支障が出ることはありません。  
> もしカーソル移動などができなくなった場合は再度SELECT+R2を押してください。  

## USB-DACについて
- ゲーム中でもUSB-DACを接続したり取り外ししたりできますが、できるだけゲームを始める前にUSB-DACを抜き差ししてください

## USB Wifiドングルについて
<img src="https://github.com/game-de-it/plumOS-V90S/blob/main/asset/sc06.jpg" width="320">  <img src="https://github.com/game-de-it/plumOS-V90S/blob/main/asset/sc07.jpg" width="320">   

- 動作確認できているWifiドングルは`TP-Link Archer T3U Nano/A`です
    - 消費電力が大きいので必要ない場合は本体から取り外しておくことをお勧めします 

以上  


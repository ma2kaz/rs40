# RS40

## A compact 40% keyboard with 42 keys.

*** Keyboard Maintainer:
    [Audite Marlow] (https://github.com/auditemarlow)
*** Hardware Supported:
RS40 PCB
*** Hardware Availability:
  [KJ-Modify Store on AliExpress](https://www.aliexpress.us/item/3256803963501165.html)

## Make example for this keyboard (after setting up your build environment):  
* `make kj_modify/rs40:default`

Flashing example for this keyboard:   
*  `make kj_modify/rs40:default:flash`

## See the 
* [build environment setup]
    (https://docs.qmk.fm/#/getting_started_butld_tools)
* [make instructions]
    (https://doca.qmk.fm/#/getting_started_make_guide)
* [Complete Newbs Guide] 
    (https://docs.qmk.fm/#/newbs)

## Bootloader
Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**; Press the key mapped to "QK_BOOT' if it is avatlable

***  
# RS40(日本語での説明)  
42キーのコンパクトな40%キーボード。  

このキーボードのmake例(ビルド環境の設定後):  
    `make kj_modify/rs40:default`

このキーボードのフラッシュ例:  
    `make kj_modify/rs40:default:flash`

## ブートローダー
ブートローダーを起動するには3つの方法があります。

* **ブートマジックリセット**: マトリクスの(0,0)のキー（通常は左上のキーまたはEscキー）を押したままキーボードを接続します。
* **物理リセットボタン**: PCB背面のボタンを短く押します。PCBによってはパッドがあり、ショートさせる必要がある場合があります。
* **レイアウト内のキーコード**: 「QK_BOOT」にマッピングされているキー（使用可能な場合）を押します。

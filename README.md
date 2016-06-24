NoteSkin hanubeki
=================

A simple flat -- but huge -- NoteSkin for StepMania 5.1.
A goal of this noteskin is to support every gametype (except lights).

If you are looking for 5.0.x version, see [5.0-final](https://github.com/hanubeki/noteskin-hanubeki/tree/5.0-final) tag.

##Limitation of this NoteSkin##
No routine masks (only quanta mode supported).
In routine, holds are not fully colored by player.

##NoteSkin Parameters##

###Color Type###
* Quantize, Column, Split, Alternate, Symmetric
    * [en] Choose coloring method of note.
    * [ja] ノートの色付け方法を選択します。
    * Alternate and Symmetric are same way if column number is odd.

###Quanta Mode###
* Default, 3.9 Note, 3.9 Solo, 4.0 Bold, ITG, DDR Note, PIU Rhythm, Mungyodance, Pulsen Shapes
    * [en] Choose quantize mode.
    * [ja] クォンタイズのモードを選択します。

###Quanta Multiply###
* Default, Halved, Thirdsed, Quartered
    * [en] Choose quantize multiplier.
    * [ja] クォンタイズの基準となる倍率を選択します。

###Mine Color###
* False, True
    * [en] Choose if mines to be colored same as normal notes.
    * [ja] マインノートを通常ノートと同じように色分けするか選択します。

###Note Type###
* Normal, Bar (Narrow), Bar (Wide), Circle
    * [en] Choose shape of note.
    * [ja] ノートの形状を選択します。

###Lift Type###
* Octagon, Arrow
    * [en] Choose shape of lifts.
    * [ja] リフトの形状を選択します。
    * Using "Arrow" with Split/Alternate/Symmetric coloring is not recommended.

###(beat) Scratch Side###
* Left, Right
    * [en] Choose side of scratch. If doubles chart, only affected to P1.
    * [ja] スクラッチの位置を選択します。ダブル譜面の場合、P1側のみ影響します。
    * It will require post-alpha2 build.

##Known problems##
* Active hold head has offset if Visual Delay is set.

Fllowing problems are not confirmed in alpha 2:
* Crash while playing Springtime pump-single Expert (bundled with SM5)

##License##
This work is licensed under the Creative Commons Attribution-ShareAlike 4.0
International License. To view a copy of this license,
visit http://creativecommons.org/licenses/by-sa/4.0/.

##Topic at StepMania forum##
[NoteSkin hanubeki](http://www.stepmania.com/forums/themes/show/4557)

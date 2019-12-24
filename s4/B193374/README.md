# サンプルで提供されている Frequencer.java のコードを読み、問題を発見しそれを書き出せ。

Sample1を使用した  

- frequency()を実行する前にsetSpace()並びにsetTargetを実行した際にエラーが発生するが、それに対しての処理が存在していない。
- class Frequencer Line 30のfor loopに関して、indexOutOfBoundsExceptionが発生する可能性がある。 (spaceの長さがtargetの長さで割り切れない場合) : 修正済み

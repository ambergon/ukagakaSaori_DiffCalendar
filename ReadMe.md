# ukagakaSaori_DiffCalendar
日付同士の引き算を行い、差を日数で取得するSaori-univarsalです。


## 式
Aのyyyy/mm/dd - Bのyyyy/mm/dd = 差の日数


## 使い方
サンプルはyayaで書いています。<br>
```
_res = FUNCTIONEX( "./dll/ukagakaSaori_DiffCalendar.dll" , "A年" , "A月" , "A日" , "B年" , "B月" , "B日" )
_res = FUNCTIONEX( "./dll/ukagakaSaori_DiffCalendar.dll" , "2023" , "4" , "1" , "2023" , "2" , "1" )
-> _res = 59

_res = FUNCTIONEX( "./dll/ukagakaSaori_DiffCalendar.dll" , "2023" , "1" , "1" , "2023" , "4" , "1" )
-> _res = -90 
```
0日や0月は存在しないので、それらを入力するとエラーになります。


## 動作確認環境
Windows 10<br>
SSP/2.6.51


## 注意事項
このプログラムを使ったいかなる問題や損害に対して、私は責任を負いません。<br>
また、ゴーストなどに同梱して配布していただいて構いません。


## Author
ambergon

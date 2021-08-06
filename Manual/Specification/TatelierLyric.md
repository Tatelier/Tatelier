# Tatelier 歌詞ファイル 仕様(仮)
Tatelierは歌詞ファイル(*lrc)を利用できるが、Tatelier独自の歌詞ファイル(tllyric)も定義している。

## 概要
拡張子 : tllyric
tllyricでは、lrcでは表現できなかった歌詞の演出やフォントサイズの個別していなどに対応している。

### 歌詞の時間指定

![ScreenShot](https://user-images.githubusercontent.com/77183438/128531331-b179160b-5109-40c5-a8e6-d1e2700d04ca.png)


上記ように歌詞を指定します。

歌詞を指定したらtjaに「LYRIC:」で歌詞ファイル名を指定します。LYRIC命令がない場合は音源ファイルと同名の歌詞ファイル(.lrc)を見つけた場合、歌詞ファイルを読み込みます。

![ScreenShot](https://user-images.githubusercontent.com/77183438/128530427-8012a9d9-7017-4474-a2da-b24a1e99ac62.png)

pandoc sample.md --from=markdown --to=docx --standalone --reference-doc=reference.docx --output=sample.docx
> # heading1 {#p2}
heading1本文一行目

## heading2 
heading2本文

##### heading5
heading5本文  
Here is a footnote reference,[^1] and another.[^longnote]

[^1]: 脚注その1

[^longnote]: これは脚注その2に割り振られます

######### heading8
heading8本文。  

######### heading9
heading9本文。  

+---------------+---------------+--------------------+
| 名称          | 金額          | Advantages          |
+:=============:+==============:+:===================+
| お茶          | 2000円        | - 名産品            |
|               |               | - 新茶             |
+---------------+---------------+--------------------+
| お水          | 130円         | - 天然水            |
+---------------+---------------+--------------------+

[heading1へのリンク確認](#p2)  

* 記号*か+か-を先頭につける。テキストとの間にはスペース
* 記号*か+か-を先頭につける。テキストとの間にはスペース
    + インデントさせる場合は4つスペース
        + さらにインデントさせる場合は8つスペース


1. 数字,ピリオド,スペースで順序付き
画像も。

![テストイメージ](test.bmp)
aaa
ddd   

画像も。

![テストイメージ](test.bmp)
aaa
ddd   

画像も。

![テストイメージ](test.bmp)
aaa
ddd   

画像も。

![テストイメージ](test.bmp)
aaa
ddd   
dsadfafas

fdsafa

ddas   
ss


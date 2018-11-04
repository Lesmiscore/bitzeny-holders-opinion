# bitzeny-holders-opinion
以下の内容についてBitZenyホルダーの意見を集めます    
なおnao20010128naoはCoreDevの一人ですが、あくまでも参考にしかなりません。**個人的なものです**    
最終決定はCoreDevによって行われます

## 投票方法
- `ZjaTKHiqLV5wsXBAMvqUFKEjAfzbiRGrNz`にOP_RETURN(コメント)とともに少額送金    
コメント内容は以下に示す`TEXT`を使うこと    
秘密鍵所有証明:     

```
テキスト: nao20010128nao
署名: TODO
```

- テキストファイルに署名とテキスト、アドレスを付けてPRを送る     
署名の時は、上から    
テキスト→以下に示す`TEXT`を使う     
アドレス→投票するアドレス    
署名→上記のアドレスとテキストによるEC署名    
の内容でお願いします    
ファイル名は`アドレス.txt`とします
例: ファイル名: `ZenyHime...A.txt`    
```
ROLLBACK
ZenyHime...A
(ウォレットから提示された署名 Base64)
```


票数は残高とします。(1ZNY=1票、小数点以下そのまま)

## `TEXT`について
選択肢の最後にある`ROLLBACK`にみたいになってる部分です。

## Vote 1: BitZenyへのCVE-2018-17144を用いた攻撃への対策
選択肢: 
- 無理やりロールバックする (`ROLLBACK`)
- z2.0.2以外を拒否する (`DENYUNPATCHED`)

その他選択肢あったら受け付けます

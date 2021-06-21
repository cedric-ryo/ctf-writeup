# Welcome
## 下記のbase64でエンコードされた文字列をデコードする
![代替テキスト](./スクリーンショット%202021-06-20%2016.31.36.png))

## Python3で文字列をデコードするコード例
```python
import base64
print(base64.b64decode('d2UlN0I1ODRjNGNiMC1jYjU4LTQ1YWItOTNhNC0yOWY1YmRhYzlmMjJAaGVsbG9faGFja2VycyU3RSU3RA==').decode())
```

## 上記を実行した結果
```shell
❯ python3 solve.py 
we%7B584c4cb0-cb58-45ab-93a4-29f5bdac9f22@hello_hackers%7E%7D
```

## ascii部分を置換する
%7B => {
%7E => ~
%7D => }

## flag
we{584c4cb0-cb58-45ab-93a4-29f5bdac9f22@hello_hackers~}


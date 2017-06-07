## jupyter notebook(后缀为.ipynb文件使用方法)

打开cmd命令行，进入对应文件目录，输入jupyter notebook,即可在浏览器中打开对应文件。

## 去掉非ascii符
```
label_noascii = ''.join([k if ord(k) < 128 else '' for k in label_ori])
```

## unicode转str
```
label_str = label_noascii.encode()
```

## 去掉字符串中标点符号
```
label_no_punctuation = label_str.translate(None, string.punctuation)
```

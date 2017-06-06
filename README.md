# qrcode
Python QR code module.
直接运行qrcode_example.py文件会生成两张jpg格式的图片。
其中example.jpg内容是我的学号JL16110006（通过微信扫一扫就可以扫出来内容）。
example.jpg的内容是Python QR code！ 是用来做测试用的。
如果想自己定义内容也可以：需要如下命令。

>>> import qrcode


>>> qrcode.generate('你想要的内容')    # 内容最好是英文的，因为编码的地方还有一点问题，汉语会报错。

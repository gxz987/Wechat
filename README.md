一个非常有意思的 python 程序，基于 itchat 实现微信控制电脑。你可以通过在微信发送命令，来拍摄当前电脑的使用者，然后图片会发送到你的微信上。甚至你可以发送命令来远程关闭电脑。
此次程序使用的环境是 python3.6 + windows10，在运行程序之前请先确保你已经安装好了 opencv-python 和 matplotlib。通过 pip install 即可安装。

程序主要是通过使用 itchat 库来登录到微信网页端，然后通过 itchat 来发送消息和接收消息。并通过 opencv 来调用电脑的摄像头，把当前使用电脑的用户拍照下来，发送到你的微信上。至于远程关机是通过调用 os 库，发送 cmd 命名即可实现



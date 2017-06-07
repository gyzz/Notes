# screen 虚拟窗口
## 创建窗口
```
screen
```
## 创建一个执行vi test.c的窗口会话
```
screen vi test.c
```
## 创建一个名字为yourname的窗口
```
screen -S yourname
```
## 断开窗口连接
ctrl+a  d
## 关闭窗口
```
exit
```
## 查看存在的screen窗口
```
screen -ls
```
## 重新连接screen窗口
```
screen -r 窗口进程号
```
or
```
screen -d -r 窗口名字 

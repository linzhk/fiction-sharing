# 数据总览

## 小说原始数据

一共4623篇科幻小说，大小共2.5G，获取方式：
链接：https://pan.baidu.com/s/1ZREEGlc5q_KR6NBW4aPGow 
提取码：yiif

或者群里找镇坤要百度云盘的会员账号下载。该文件同时存放于网盘中。路径“我的网盘/data_1.json”

### 数据格式

使用如下代码打开得到：
```python
import json
with open('data_1.json' , 'r') as f:
    data = json.load(f)
```
一个拥有4623个元素的list,每个元素是一个字符串。字符串通过"<line>"分隔了行。并且尽我所能洗掉了一些无关的数据。

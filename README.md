# call_useragent

## 安装

`pip install --user call_useragent`

## 使用

1. 随机调用

```python
import call_useragent
headers = {'User-Agent': call_useragent.random()}
```

后续也许会有其他功能。

补充：

**head.py** 文件中的所有请求头来自于https://fake-useragent.herokuapp.com/browsers/0.1.11 ，感谢原作者的贡献。

fake-useragent 仓库地址：https://github.com/hellysmile/fake-useragent

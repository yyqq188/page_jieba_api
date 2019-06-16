# page_jieba_api
把提供的网页中的文字分词后计算topn并返回
适合静态页面和动态加载的页面

###------------------------
# 用法

```
pip3 install -r requirements.txt
pip install page_topn
from page_topn import pagetopn
```
### 静态页面 根据提供的网页取top10的关键词

`pagetopn.page_topn(url="xxx",10)`

### 动态页面 根据提供的网页取top10的关键词

`pagetopn.page_topn(url="xxx",10)`

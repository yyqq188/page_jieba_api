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

# 对外提供的服务
### 静态网页
`http://127.0.0.1:9012/?url=http://zfcg.wlmq.gov.cn/infopublish.do?method=infoPublishView&infoid=89780E928AE02608E05311C410AC3412&num=10&isdynamic=n`

### 动态网页 需要指定好chromedriver(浏览器驱动的地址)
`http://127.0.0.1:9012/?url=http://zfcg.wlmq.gov.cn/infopublish.do?method=infoPublishView&infoid=89780E928AE02608E05311C410AC3412&num=10&isdynamic=d&driver_path=/home/yhl/chromedriver`

### 使用Scrapy或Requests递归抓取[微信搜索](http://weixin.sogou.com/weixin)结果

使用Scrapy方法 或者 使用Requests+BeautifulSoup

**使用Scrapy方法：**  

* 将querystring替换为你要查询的单词

* type可以选择

* i的范围可以调整，对应查询的搜索结果页面数目  

具体可以到scrapy官网上查询学习: https://docs.scrapy.org/en/latest/intro/tutorial.html
目前的wwjtest就是参考scrapy官网的tutorial写的， 使用scrapy crawl wwjtest 运行

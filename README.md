##开始
给爬虫url管理器一个url。
##循环
- 调度器从url管理器中获得一个url
- 调度器将这个url传递给下载器
- 调度器将下载器的结果传递给解析器。
- 解析器将解析的结果进行处理。
  将目的数据进行存储。
  将可用的url传递给url管理器




###Scrapy
HTML, XML源数据 选择及提取 的内置支持
提供了一系列在spider之间共享的可复用的过滤器(即 Item Loaders)，对智能处理爬取数据提供了内置支持。
通过 feed导出 提供了多格式(JSON、CSV、XML)，多存储后端(FTP、S3、本地文件系统)的内置支持
提供了media pipeline，可以 自动下载 爬取到的数据中的图片(或者其他资源)。
高扩展性。您可以通过使用 signals ，设计好的API(中间件, extensions, pipelines)来定制实现您的功能。
内置的中间件及扩展为下列功能提供了支持:
cookies and session 处理
HTTP 压缩
HTTP 认证
HTTP 缓存
user-agent模拟
robots.txt
爬取深度限制
针对非英语语系中不标准或者错误的编码声明, 提供了自动检测以及健壮的编码支持。
支持根据模板生成爬虫。在加速爬虫创建的同时，保持在大型项目中的代码更为一致。详细内容请参阅 genspider 命令。
针对多爬虫下性能评估、失败检测，提供了可扩展的 状态收集工具 。
提供 交互式shell终端 , 为您测试XPath表达式，编写和调试爬虫提供了极大的方便
提供 System service, 简化在生产环境的部署及运行
内置 Web service, 使您可以监视及控制您的机器
内置 Telnet终端 ，通过在Scrapy进程中钩入Python终端，使您可以查看并且调试爬虫
Logging 为您在爬取过程中捕捉错误提供了方便
支持 Sitemaps 爬取
具有缓存的DNS解析器

address: http://doc.scrapy.org/en/latest/

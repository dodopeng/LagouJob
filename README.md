# LagouJob
#拉勾网职位数据分析

![LagouIcon](http://pstatic.lagou.com/www/static/common/widgets/header_c/modules/img/logo_d0915a9.png)
###主要功能

1. 利用爬虫获取[拉勾网](www.lagou.com)招聘数据，了解互联网行业最新职位动向

2. 借助Excel2013进行统计分析与可视化

3. 对每个职位的详情数据进行二次抓取，进行分词、统计，获取标签云，生成对于每类职位的__职位印象__


###使用方法
1. 从github地址clone下该project

2. 更改 __job.xml__ 的路径

3. 运行 __lagouspider.py__ 获取拉勾网json数据

4. 运行 __excelhelper.py__ 生成每份职业对应的Excel

5. 运行 __jobdetailspider.py__ ,对招聘信息详情进行二次爬取  ----V1.3 updated

6. 运行 __analyser.py__ 分词，获取排名前20的热度词 ----V1.3 updated

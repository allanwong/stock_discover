# 国内股票筛选器
【感谢雪球和果仁，因为用到了雪球筛选器的接口和果仁历史数据的接口】

该库的目标是通过一些财经类网站股票接口，做价值投资的初筛，生成一些有用的图表，辅助股票投资

目前完成的功能是能通过雪球筛选器的接口，能添加【近几年ROE、近几年营收、利润、毛利率、净利率，市盈率，市净率等指标】作为筛选条件，查询符合条件的股票。然后会通过这些数据画出一些相关指标的变化图表

使用该库前，需要通过浏览器开发者工具或者抓包拿到雪球和果仁登录后请求接口的cookie，创建cookie_guoren.txt文件填写雪球的cookie,创建cookie_xueqiu.txt文件填写果仁的cookie

下面是目前生成的图片样例,拿了茅台和兴业做例子
 ![image](https://github.com/pinguo-chexing/stock_discover/blob/master/screenshots/%E8%B4%B5%E5%B7%9E%E8%8C%85%E5%8F%B0_SH600519.png)
 ![image](https://github.com/pinguo-chexing/stock_discover/blob/master/screenshots/%E5%85%B4%E4%B8%9A%E9%93%B6%E8%A1%8C_SH601166.png)



scrapy shell
fetch("http://www.aastocks.com/tc/stocks/news/aafn/popular-news")
response.css("table tbody tr td div div::text").getall()
response.css("#cp_ucAAFNSearch_repNews_lnkNews_3").getall()

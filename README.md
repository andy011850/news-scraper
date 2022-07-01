# news-scraper #

## 專案介紹 ##

本專案為Scrapy網頁爬蟲框架的教學系列範例程式碼，以[INSIDE硬塞的網路趨勢觀察網站－AI新聞](https://www.inside.com.tw/tag/ai)網頁為例，來分享Scrapy網頁爬蟲框架的常見應用，可以搭配以下的部落格文章來進行學習：

- [x] [[Scrapy教學1]快速入門Scrapy框架的5個執行模組及架構](https://www.learncodewithmike.com/2020/12/python-scrapy-architecture.html)
  - scrapy的框架在透過實際使用後會比較能了解，但是不了解也沒關係，因為會經常撰寫的只有spiders主程式的部分
  - 本教程假設學員已熟悉BeautifulSoup、Selenium等爬蟲工具
  - Downloader下載下來的是網頁的HTML原始碼

- [x] [[Scrapy教學2]實用的Scrapy框架安裝指南，開始你的第一個專案](https://www.learncodewithmike.com/2020/12/scrapy-installation.html)
  <pre><code>$ pip install scrapy
  $ scrapy bench
  
  $ scrapy startproject 你的專案名稱 .
  $ cd 專案
  $ scrapy genspider 網頁爬蟲檔案名稱 目標網站的網域名稱
  </pre></code>

- [x] [[Scrapy教學3]如何有效利用Scrapy框架建立網頁爬蟲看這篇就懂](https://www.learncodewithmike.com/2021/01/scrapy-create-spider.html)
  - start_urls可以是想要爬取的一至多個網頁網址清單
  - HTML原始碼，在使用BeautifulSoup後，可以有效的提取某些HTML資訊

* [[Scrapy教學4]掌握Scrapy框架重要的CSS定位元素方法](https://www.learncodewithmike.com/2021/01/scrapy-css-selectors.html)

* [[Scrapy教學5]掌握Scrapy框架重要的XPath定位元素方法](https://www.learncodewithmike.com/2021/01/scrapy-xpath-selectors.html)

* [[Scrapy教學6]解析如何在Scrapy框架存入資料到MySQL教學](https://www.learncodewithmike.com/2021/01/writing-data-to-mysql-in-scrapy.html)

* [[Scrapy教學7]教你Scrapy框架匯出CSV檔案方法提升資料處理效率](https://www.learncodewithmike.com/2021/01/scrapy-export-csv-files.html)

* [[Scrapy教學8]詳解Scrapy框架爬取分頁資料的實用技巧](https://www.learncodewithmike.com/2021/02/scraping-multiple-pages-with-scrapy.html)

* [[Scrapy教學9]一定要懂的Scrapy框架結合Gmail寄送爬取資料附件秘訣](https://www.learncodewithmike.com/2021/02/scrapy-sending-gmail.html)

* [[Scrapy教學10]不可不知的Scrapy框架爬取下一層網頁資料實作](https://www.learncodewithmike.com/2021/02/scrapy-follow-links-and-collect-data.html)



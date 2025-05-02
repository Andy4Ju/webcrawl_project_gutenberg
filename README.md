# Project Gutenberg
* 爬取中文書籍，共 355 本(不含重複)。  
Crawl Chinese books, a total of 355 books (excluding duplicates).

## 安裝套件 Installed Packages
- requests (2.32.3)
- beautifulsoup4 (4.12.3)
- selenium (4.31.0)


## 成果 Result
[Video](https://drive.google.com/file/d/19jMXPMGv8AtIUjUj_xqiuHw9wNEBUqhd/view?usp=drive_link)

## 其它 Others
* 尚有部分文章擷取內容不足，初步判斷為以下原因：
  * 正規判斷式設計不足（部分文章內容被判斷為英文內容而被剔除）
  * 部分文章內容儲存在非標籤\<p\>之中

仍須進行調整


* Some articles still have incomplete extracted content. Preliminary analysis indicates the following reasons:
  * Insufficient regular expression design – Certain paragraphs were mistakenly identified as English content and thus excluded.
  * Content not stored within \<p\> tags – Some article text resides in alternative HTML structures.
 
Further adjustment is still required.

# **台科 GPA 查詢系統**
        由於台科官方網站並未給予學生可以查詢過去課程之資訊(包括成績)，因此想嘗試製作一個簡易的網站可以了解各個課程的成績分布情況，以了解各個老師的評分習慣。
## **Automated_Feature_Extraction.ipynb:**
        1. 讀取台科成績分布表之 PDF 檔
        2. 將 PDF 檔之內容整理成 dataframe 形式
        3. 以 webdriver 從台科課程查詢網站查詢 dataframe 中課程的教師名稱
        4. 將 dataframe 變成 database (ntust_grades.db)
## **GPA_search.html:**
        1. 嘗試製作台科 GPA 查詢之網站

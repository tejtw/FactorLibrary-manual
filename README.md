# 部屬方式

1. 切換至branch gh-pages

2. 修改任一md檔或架構後，cmd輸入jupyter-book build . 重新根據新的md或架構生成靜態網頁html

3. cmd輸入ghp-import -n -p -f _build/html 部屬新生成的html至github page
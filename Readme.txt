Git 和 GitHub 是兩個有關聯但不同的東西，Git 是一種版本管理的工具, 如同svn, 微軟的team foundation server。

GitHub 則是一個網站提供免費的空間讓你擺放你程式的Source Code (原始碼)
不過免費是有條件的，只要用免費的方案，Source code 就會是Open的, 大家都可以下載與觀看，如果不要Open, 那就使用付費方案吧。
=========================================================================
所以我們就直接在bash底下操作了 https://progressbar.tw/posts/3

https://github.com/twtrubiks/Git-Tutorials

github基本教學 - 從無到有 https://www.youtube.com/watch?v=py3n6gF5Y00

Windows: git bash

Linux : shell bash

4. 執行Git Bash
如果想查詢自己在哪個目錄的話, 可以使用指令 pwd
列出資料夾底下所有的檔案 可以用ls

$ ls

MinGW預設是不支援中文, 所以你會看到很多XXXX開頭的檔案

C:\Users\david\OneDrive\桌面\Test1

清空文字可以下 clear

$ clear

 

進入資料夾就是 cd

比方進入桌面

$ cd  Desktop

使用git bash 進入我們建的Test123

$ cd Desktop

$ cd Test1

5. 將Test1 初始化, 變成git Repo, 也就是git 的倉庫

$ git init     
6. 將 Readme.txt 加入版本管理

$ git add Readme.txt      (指令意義: 將Readme.txt "的改變" 加入版本管理)

或是可以改下這個指令

$ git add -f --all               (指令意義: 將目前所在的資料夾裡 "所有的檔案" "的改變" 強制 加入版本管理)

這裡用"的改變" 是因為, git add 指令不完全是, 將某個檔案加入版本管理

而是看目前git的記錄 和 目標檔案的內容有沒有差異 

有的話就會加進去, 而我們因為剛初始化, 所以git 裡面沒有紀錄

因此比對的結果會是整個檔案都不在, 加入整個檔案.

$ ls     <!--資料夾底下輸入查詢指令 -->

$ ls -al   <!-- 加al 此資料夾下查包含隱藏檔 -->

$ git status查詢，查詢狀態會告訴你


 

 
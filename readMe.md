### 第一次使用git

版本控制的簡單指令
- git config --global [user.name](http://user.name) “<name>” : 修改者的名字
- git config --global [user.email](http://user.email) “<Email>” : 修改者的Email
- git init: 啟動git，會在資料夾中出現隱藏的.git資料夾，存放修改的歷史
- git status: 會顯示資料夾內檔案的狀態
- git add <檔案名稱>: 檔案會顯示"A"表示已加入追蹤名單
    - 可用萬用字元如：*.ipynb，表示所有.ipynb的檔案
    - git a .：表示所有變更都加入到暫存區
- git commit -m <顯短的訊息>: 留下訊息表示提交的目的及內容變化
- git log: 查看提交的歷史
- git diff <檔案編號> —<檔案名稱>: 比較新舊版本差異
- git checkout <檔案編號> —<檔案名稱>: 還原版本
- git reset —hard <目標還原點編號>: 回到之前的還原點，並且刪除還原點後面的存檔紀錄，不可逆!!!!!

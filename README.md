# Git-practice
---
首先先將
git版本控制練習

初次設定
---
在安裝git後首先必須先設定使用者名稱和Email。這邊使用者名稱與Email皆與github一致。
```sh
$git config --global user.name "your_userID"
$git config --global user.email "your_email"
```
輸入`git config --list`確認使用者名稱與email設定成功
```sh
user.email=your_email
user.name=your_userID
```
將現有資料夾初始化倉儲
---
#### 創建一個新資料夾
作為練習我們可以先創一個新資料夾
```sh
mkdir git_test
cd git_test
```

如果想使用git追蹤現有專案，只須進入該專案資料夾並執行
```sh
$git init
```
如果資料夾不是空的，可以使用`git add`指令來追蹤你想追蹤的檔案，也可以使用`git add .`追蹤資料夾內所有檔案，最後在執行`git commit`進行提交

#### 檢查你的檔案狀態














將現有的倉儲複製到電腦中
---
若想要取得現有倉儲中的專案，可以使用`git clone`將gitbub上的專案複製到主機中，例如下方案例，透過`git clone`+專案的`url`即可
```sh
https://github.com/terry105040819/DADA2_pipeline.git
```

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
$mkdir git_test
$cd git_test
```

如果想使用git追蹤現有專案，只須進入該專案資料夾並執行
```sh
$git init
```
#### 檢查你的檔案狀態
在倉儲中新增或刪除檔案後，先利用`git status`查詢更改項目與那些項目還沒追蹤
```sh
(base)$git status

On branch main

No commits yet

Untracked files:
(Use "git add <file>..." to include in what will be committed)
    folder1/
    folder2/
```

如果要追蹤這些項目可以使用`git add`並將這些項目輸入，也可以使用`git add .`將所有項目加入追蹤
```sh
將所有檔案加入追蹤
$git add

僅將指定檔案加入追蹤
$git add folder3
``` 

#### 將檔案










將現有的倉儲複製到電腦中
---
若想要取得現有倉儲中的專案，可以使用`git clone`將gitbub上的專案複製到主機中，例如下方案例，透過`git clone`+專案的`url`即可
```sh
https://github.com/terry105040819/DADA2_pipeline.git
```

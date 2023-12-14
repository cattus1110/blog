title: Git 語法教學
author: cattus1110
author_id: defaultAuthorId
language: zh-TW
tags:
  - Git
  - 語法教學
  - ''
categories:
  - Git 課程
date: 2023-12-15 05:29:00
---
Git 是一個分佈式版本控制系統，用於協作軟體開發，跟蹤變更，並管理程式碼的歷史記錄。以下是一些 Git 的基本語法和指令。

## 1. 設定 Git

在使用 Git 之前，您需要設定您的使用者名稱和電子郵件地址。

```shell
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"
```

## 2. 初始化儲存庫

要開始使用 Git，您需要初始化一個儲存庫。

```shell
git init
```

## 3. 複製儲存庫（Clone）

複製一個現有的遠端儲存庫到您的本地機器。

```shell
git clone remote_repository_url
```

## 4. 提交變更（Commit）

將已修改的檔案提交到儲存庫。

```shell
git add filename
git commit -m "Commit message"
```

## 5. 分支管理（Branching）

創建、切換和合併分支。

```shell
git branch branch_name
git checkout branch_name
git merge branch_name
```

## 6. 檢視提交歷史

查看提交歷史和差異。

```shell
git log
git diff
```

## 7. 遠端儲存庫（Remote Repositories）

添加、刪除和管理遠端儲存庫。

```shell
git remote add remote_name remote_repository_url
git remote remove remote_name
git remote -v
```

## 8. 拉取和推送（Pull and Push）

拉取遠端儲存庫的變更並推送您的變更。

```shell
git pull
git push
```

## 9. 解決衝突（Resolving Conflicts）

當多個分支產生衝突時，解決衝突。

## 10. 標籤（Tags）

創建和管理標籤以標記特定的提交。

```shell
git tag tag_name
```

## 11. 忽略檔案（.gitignore）

建立一個 .gitignore 檔案以忽略不需要跟蹤的檔案。

## 12. 暫存（Stash）

臨時儲存目前的工作，以在其他分支上工作。

```shell
git stash save "Stash message"
git stash list
git stash apply stash@{n}
```

## 13. 重置（Reset）

重設提交的 HEAD 以及在不同模式下回復檔案。

```shell
git reset commit
git reset file
git reset --hard commit
```
# Git × GitHub 零基礎協作練習

適合：從未學過程式的大學生。使用 Windows＋PowerShell 7，以純文字檔完成真正的 GitHub 協作，不需要寫程式，也不用安裝 Node.js。

教材庫：[robylin829/git-team-practice](https://github.com/robylin829/git-team-practice)。學生請在本頁上方選 **Code → Download ZIP**，解壓縮後開始；每個人都會建立自己的練習儲存庫。

情境：你和同學共同維護「小組報告任務板」。每人建立自己的 GitHub 私有儲存庫，再互相擔任審查者。所有人都要親手完成上傳、分支、Pull Request（PR）、Review、合併與同步。

## 從這裡開始

1. 閱讀 [環境準備與登入](docs/00-環境準備.md)，完成 Git、GitHub CLI 與 GitHub 帳號準備。
2. 按順序執行 [學生操作手冊](docs/01-學生操作手冊.md)，每段都附目的、指令及驗收。
3. 和同學完成 [雙人協作與 Review](docs/02-雙人協作.md)。PR 需要另一位同學實際讀取、留言與核准。
4. 填寫 [繳交表](SUBMISSION.md)，依教師要求繳交。

遇到問題先看 [排錯手冊](docs/03-排錯手冊.md)；上課時可搭配 [指令小抄](docs/04-指令小抄.md)。教師備課請看 [教師手冊](docs/05-教師手冊.md)。

## 做完會留下什麼

- 一個自己擁有的 GitHub 私有儲存庫。
- `main` 與 `feat/task-status` 分支，以及有原因的 Commit。
- 一筆刻意製造的錯誤提交，和一筆 `revert` 修正紀錄。
- 一個由同學 Review、已合併的 PR。
- 在同學儲存庫留下的實際 Review，及自己的驗證紀錄。

## 專案內容

```text
git-team-practice/
├── README.md                     課程入口
├── task-status.txt               任務狀態，起始值 todo
├── team-plan.md                  小組報告情境
├── SUBMISSION.md                 個人繳交表範本
├── .gitignore                    不上傳備份、個資與登入資料
├── .gitattributes                統一文字換行
├── .github/pull_request_template.md
└── docs/                         環境、操作、協作、排錯與教師手冊
```

`status-guide.txt` 會由你在練習中建立，不是漏檔。本教材沒有附 `.git` 歷史，讓你親手從 `git init` 建立第一筆 Commit。也沒有預先代建遠端儲存庫；每位同學會在自己的帳號實際建立。

## 操作約定

- 所有指令使用 **PowerShell 7**，不是 CMD 或 Git Bash；macOS／Linux 學生請由教師先協助調整檔案操作指令，Git／gh 指令相同。
- 指令一段一段執行，出錯就停下；不要一次貼完整份教材。
- 只操作這份專案的副本；密碼、Token、姓名學號及私人檔案不要提交。
- 需要刪除檔案時，先用檔案總管移到垃圾桶；無法移入時停止並請教師協助。練習不需要刪除任何檔案或分支。

## 教材來源

依 [使用者提供的 HackMD：Git／GitHub](https://hackmd.io/UNOduc7MTTiZYFzy9pgdsw) 重新設計為零基礎操作課程，保留 Feature Branch、Atomic Commit、PR／Review、restore／revert 主軸。安裝、GitHub CLI 與 Git 操作另參考 [官方文件](docs/06-參考與驗證.md)。

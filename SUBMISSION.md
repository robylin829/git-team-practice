# Git／GitHub 個人繳交表

請複製本表到課程平台或自己的作業文件後填寫，不必為繳交本表額外修改練習儲存庫。
私人儲存庫需要邀請教師後才能閱讀；不要為了交作業直接公開。

## 連結與紀錄

- 課程使用的暱稱：
- 自己的 GitHub 儲存庫網址：
- 自己已合併的 PR 網址：
- 同學核准自己 PR 的 Review 網址：
- 自己在同學 PR 留下的 Review 網址：
- 第一筆 Commit SHA：
- 狀態說明 Commit SHA：
- BROKEN Commit SHA：
- Revert Commit SHA：
- main 合併後的 Commit SHA：

## 操作證據

- [ ] 環境：git --version、gh --version、PowerShell 主版本。
- [ ] GitHub 儲存庫能看到 main 與 feat/task-status。
- [ ] restore 前為 BROKEN，後為 todo；前後 HEAD SHA 相同。
- [ ] restore --staged 後，內容仍為 BROKEN，但 staged diff 為空。
- [ ] revert 前後兩筆 Commit 均保留；結果為 todo。
- [ ] PR 的 Files changed 與 Review；PR 狀態為 Merged。
- [ ] 同步 main 後，git status 顯示工作目錄乾淨。
- [ ] 自己的 Review 有「觀察、重現、結果／建議」，而非只有「OK」。

證據放課程平台；截圖勿包含登入驗證碼、Token、私人信箱或其他專案內容。

## 用自己的話回答

1. Git 和 GitHub 各負責什麼？
2. add、commit、push 有何不同？為什麼 commit 後 GitHub 不會自動出現？
3. 工作目錄、暫存區、Commit 分別像什麼？
4. restore --staged 有沒有把檔案內容改回去？
5. 為什麼已推送的錯誤用 revert？歷史留下什麼？
6. 這次的 Commit 為什麼需要？你怎麼驗證？
7. 你的同學指出什麼，或實際重現了什麼？

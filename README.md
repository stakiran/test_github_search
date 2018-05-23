# test_github_search

# 結論
部分一致じゃなくて単語一致でした。

- **部分一致** 検索は使えません
- 使えるのは単語一致のみ
- 単語 ≒ 記号で区切られた区間

特に日本語だと `print('内部エラーです')` に対する単語は「内部エラーです」のみであり、「内部」でも「エラー」でもヒットしない。

# Q: 部分一致使いたいけどどうすればいいの？
Ans: Clone してから Grep とかして。

# 調査メモ
- https://github.com/stakiran/test_github_search/issues/1

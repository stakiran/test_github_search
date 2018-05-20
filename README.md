# test_github_search
github.com の(Repository 内)Search がどれだけ役立たないかを検証する

# 結論
- **部分一致** 検索は使えません
- 使えるのは単語一致のみ
- 単語 ≒ 記号で区切られた区間

特に日本語だと `print('内部エラーです')` に対する単語は「内部エラーです」のみであり、「内部」でも「エラー」でもヒットしない。

# 調査メモ
- https://github.com/stakiran/test_github_search/issues/1

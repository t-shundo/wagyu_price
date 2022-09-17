# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？

### リモートリポジトリはオンライン上配置して複数の人で共有するためのリポジトリ。ローカルリポジトリは一人一人が使用するために自分のPC上に配置するためのリポジトリ。


## プッシュとマージの違いは何でしょうか？

### プッシュはローカルリポジトリの作業内容をリモートリポジトリに反映すること。マージは別のブランチの作業内容を他のブランチに取り込むこと。


## コミットとプッシュの違い

### コミットはブランチの作業内容を保存すること。プッシュはローカルリポジトリのブランチでの作業内容をリモートリポジトリに反映すること。


## コミットのメッセージはどのように書いてあげるのが最適でしょうか？

### どのような作業を行った履歴なのか明確に示し、後で確認する際にわかりやすいようにする。


## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？

### ローカルでマージし、そのままプッシュしてしまうと他の人からのコードレビューを受けずにリモートに反映されてしまうため、バグに気づかない可能性がある。そのため、プルリクエストでマージする前に他の人からコードレビューを受けることでバグの発生を抑えることができる。


## コンフリクトを起こしてしまった場合、どう対処すべきですか？

### 状況によって、先にマージされた変更内容を取り込むか、後にマージ使用とした変更内容を取り込むか、どちらの変更内容も取り込むか選択する。

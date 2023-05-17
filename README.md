# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？
- リモートリポジトリとは外部のサーバに配置して複数人で共有するためのリポジトリ
- ローカルリポジトリとはユーザー一人一人が利用するために、自分の手元のマシン上に配置するリポジトリ

## プッシュとマージの違いは何でしょうか？
- プッシュは今いるブランチの内容を指定したブランチへ反映
- マージは指定したブランチの内容を今いるブランチへ反映

## コミットとプッシュの違い
- コミットは自分の手元のマシン内のブランチへ変更内容を記録
- プッシュはリモートリポジトリへ自身のマシン内でコミットした内容を反映

## コミットのメッセージはどのように書いてあげるのが最適でしょうか？
- 一目で変更内容がわかるように端的に要点をかいつまんで

## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？
- ローカルでマージするときとプルリクエストでマージするときの違いは直接変更が反映されるか、リクエストしたあとに承認があってから変更内容が反映されるかという点である

## コンフリクトを起こしてしまった場合、どう対処すべきですか？
- マージするブランチ( **theirs** )の変更点を理解し、矛盾なくマージされる側( **ours** )とマージする
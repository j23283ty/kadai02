## Gitのミニレポート
### Q3-1. Git同様のバージョン管理システムの1つにSubversionがある。Subversionの特徴および問題点を説明せよ。
* 特徴
Subversionはサーバにのみレポジトリを持つバージョン管理システム。Gitと同様に複数人でのソースコード管理を行うことができる。
* 問題点
サーバにしかレポジトリがないため、Gitのようにローカルにコミットすることができず、こまめにコミットすることができなくなる。
### Q3-2. Subversionの問題点をGitではどのように解決しているか説明せよ。
* Subversionの問題点
サーバにしかレポジトリがないため、Gitのようにローカルにコミットすることができず、こまめにコミットすることができなくなる。
* Gitにおける解決方法
Gitではローカルにサーバのレポジトリをクローンして使用し、そのローカルのレポジトリに対してコミットをすることができるので、こまめにコミットをすることができる。
### Q3-3. Gitの機能の中で、複数人でのシステム開発において、特に重要となる機能を1つ選び説明せよ。
* 複数人でのシステム開発で重要となるGitの機能
複数人がそれぞれのローカルにレポジトリをクローンしてファイルを変更できる機能
* その理由（具体的な状況とその機能を使った役割分担など）
複数人が同時にそれぞれのファイルに対して変更を加えるとき、それぞれの差分だけをサーバのレポジトリに更新をかけることができるため。

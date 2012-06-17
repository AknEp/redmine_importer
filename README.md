# importer

RedmineにチケットのCSVインストール機能を追加するプラグイン

## How To Install 

Redmine をインストールしているパス上の "vendor/plugins" に移動します。

そこで 
$ git clone git://github.com/AknEp/redmine_importer.git
として下さい。

次に、依存ライブラリをインストールするために
$ cd redmine_importer
$ bundle install
としてください。
上記の代わりに
$ gem install fastercsv
でも構いません。

Redmineを再起動すれば、反映されてると思います。
使い方は以下のリンクを追ってみて下さい。

## 参考になる情報
* [RedmineにCSV Importer Pluginインストール](http://il-all.blogspot.jp/2012/02/redminecsv-importer-plugin.html )
* [RedmineでCSV Importer Pluginを使う時のメモ](http://il-all.blogspot.jp/2012/03/redminecsv-importer-plugin.html )

This plugiin is based on https://github.com/farend/redmine_importer
Fixed bugs & wrote README files.

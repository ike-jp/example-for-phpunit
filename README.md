Example for minimal PHPUnit and Mockery
===================================

Installation
-----------------------------------

### Windows

+ Composerをインストーラでインストールする
+ composer.jsonをプロジェクトディレクトリに作成する
+ composer.jsonにPHPUnitとMockeryのインストール設定を記述する
+ コマンドラインで`composer install`を実行する
+ phpunit.xmlを作成する
+ Mockery Adapterファイルをphpunit.xmlに追記する
+ phpunit.xmlにテスト対象のディレクトリを記述する
+ PHPUnitのbootstrapファイルを作成する


Memo
-----------------------------------

### ./vendor/bin/phpunitを実行した場合

phpunit.xmlのfilter.whitelist.directoryに書いたディレクトリにある
Testサフィックスを持つファイルがテスト対象となる。


Refs
-----------------------------------

### phpunit.xml

> Ytake Blog. - PHPUnitの設定は正しくしよう
> http://blog.comnect.jp.net/blog/123

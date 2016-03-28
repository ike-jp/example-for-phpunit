Example for minimal PHPUnit and Mockery
===================================

Installation
-----------------------------------

### Ubuntu

+ sudo apt-get install php5-cli
+ sudo apt-get install composer
+ composer install

### Windows

+ XAMPPインストール
+ Composerをインストーラでインストール
+ composer install


PHPUnit + Mockery導入手順
-----------------------------------

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

### Install

> PHPUnit - PHPUnitのインストール  
> https://phpunit.de/manual/current/ja/installation.html#installation.phar

### phpunit.xml

> PHPUnit - 付録C XML 設定ファイル  
> https://phpunit.de/manual/current/ja/appendixes.configuration.html

> Ytake Blog. - PHPUnitの設定は正しくしよう  
> http://blog.comnect.jp.net/blog/123

### Mockery

> Mockery 0.8.0 日本語ドキュメント  
> http://kore1server.com/202/Mockery+0.8.0+%E6%97%A5%E6%9C%AC%E8%AA%9E%E3%83%89%E3%82%AD%E3%83%A5%E3%83%A1%E3%83%B3%E3%83%88

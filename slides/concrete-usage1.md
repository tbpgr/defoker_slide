* 当日日付の作業フォルダを作成

~~~bash
$ defoker today
$ ls -F | grep /
20141002/
~~~

* 翌日の作業フォルダを名前付きで作成

~~~bash
$ defoker tomorrow -a hoge
$ ls -F | grep /
20141003_hoge/
~~~

* 連続した日付の作業フォルダを作成

~~~bash
$ defoker days 20141002 -c 5
$ ls -F | grep /
20141002/
20141003/
20141004/
20141005/
20141006/
~~~

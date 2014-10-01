* 当月の作業フォルダを作成

~~~bash
$ defoker this_month
$ ls -F | grep /
201410/
~~~

* 前月の作業フォルダを名前付きで作成

~~~bash
$ defoker previous_month -a hoge
$ ls -F | grep /
201409_hoge/
~~~

* 連続した月の作業フォルダを作成

~~~bash
$ defoker months 201410 -c 5
$ ls -F | grep /
201410/
201411/
201412/
201501/
201502/
~~~

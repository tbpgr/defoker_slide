* 当年の作業フォルダを作成

~~~bash
$ defoker this_year
$ ls -F | grep /
2014/
~~~

* 前年の作業フォルダを名前付きで作成

~~~bash
$ defoker previous_year -a hoge
$ ls -F | grep /
2013_hoge/
~~~

* 連続した年の作業フォルダを作成

~~~bash
$ defoker years 2014 -c 5
$ ls -F | grep /
2014/
2015/
2016/
2017/
2018/
~~~

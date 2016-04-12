test
====

test

python 官网 https://www.python.org

```
$tar zxvf Python-2.7.6.tgz
$cd Python-2.7.6
$./configure --prefix=/usr/local/python-2.7.6    #重要，指定python的安装路径，可以自己设置。
$make
$sudo make install
```

```
$mv /usr/bin/python /usr/bin/python2.4   #根据需要来 
$ln -s /usr/local/python-2.7.6/bin/python /usr/bin/python
```

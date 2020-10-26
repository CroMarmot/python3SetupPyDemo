# 安装


```
pip install setuptools --user
```

执行`python3 setup.py bdist_egg`即可打包一个test的包了

执行`python3 setup.py install --user` 安装包，在`~/.local/lib/python3.8/site-packages`文件夹下

打开python终端

```
>>> import demo
>>> demo.test()
hello world!
>>>
```

说明安装成功，并调用成功


创建一个虚拟环境：
$ mkvirtualenv my_project
在虚拟环境上工作：
$ workon my_project


$ mkproject myproject

停止是一样的：
$ deactivate
删除：
$ rmvirtualenv my_project

lsvirtualenv
列举所有的环境。
cdvirtualenv
导航到当前激活的虚拟环境的目录中，比如说这样您就能够浏览它的 site-packages 。
cdsitepackages
和上面的类似，但是是直接进入到 site-packages 目录中。
lssitepackages
显示 site-packages 目录中的内容。


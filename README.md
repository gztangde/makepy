# python总结

## 代码部分

***



<u>文件移动和复制操作</u>

~~~copyFile
import os, random, shutil
shutil.move(oldnamepath, newnamepath)
~~~

<u>遍历某一路径下的所有文件</u>

~~~
import os
path=×××
file=os.listdir(path)
for i in file:
	***
~~~

<u>去掉某一文件的头和尾</u>

~~~
.rstrip('*') ##去尾
.lstrip('*') ##去头
~~~

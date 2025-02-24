**os.path.basename**
Python 中 os.path 模块的一个函数，用于获取指定路径的最后一个组件

**<font color=red>示例**
```
import os

path = '/home/user/documents/file.txt'
folder_name = os.path.basename(path)
print(folder_name)  

# 输出: file.txt

```

**os.path.join**
用于将多个路径组件合并成一个路径。
```
import os

folder1 = '/home/user'
folder2 = 'documents'
folder3 = 'files'
file_name = 'file.txt'

full_path = os.path.join(folder1, folder2, folder3, file_name)
print(full_path)  

# 输出: /home/user/documents/files/file.txt

```
*** *** *** ***
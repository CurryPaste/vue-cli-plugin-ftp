# 白名单-删除思路

> 正常思路
> 删除文件夹，顺带会把文件夹里面的文件一并删除
> 
> 但用 `ftp` 的 `rmdir` 方法删除文件夹，需要保证文件夹是空文件夹
> 所以删除功能就需要分成两个部分
> 删除文件和删除文件夹

### 主要步骤
- 删除文件
- 删除文件夹

# 默认文件

## 概述

指定站点的默认文件。每行一个，优先级由上至下。

例如：

```
index.php
index.html
helloworld.htm
```

则用户访问域名时，首先寻找是否有 index.php 文件，找到则返回 index.php ，否则开始寻找 index.html ，以此类推，直到 helloworld.htm 也不存在时，返回 404 错误。
# MD5校验工具
计算文件MD5并保存结果/ 将文件MD5与与保存的结果对照。

## 功能说明
### MD5Checker.exe:<br>
计算当前路径下所有文件的MD5值，并保存为json。<br>
载入储存MD5值的json文件，与当前目录下所有文件比对。<br>
### FastCheck.exe:<br>
打开后直接进行MD5校验，无需额外操作。

## 使用提示
软件会在读取文件列表时屏蔽自身和md5.json文件。<br>
因此如果两者共存在一个目录下，使用FastCheck验证时会提示找不到文件FastCheck.exe，而有新文件MD5Checker。
目前已支持读取下级文件夹内的文件

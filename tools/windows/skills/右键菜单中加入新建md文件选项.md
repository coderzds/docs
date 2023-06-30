**新建一个文本，把后缀改为`reg`，将下面代码贴入，修改Typora路径，执行即可**

```bash
Windows Registry Editor Version 5.00

[HKEY_CLASSES_ROOT\.md]
@="typora.md"
"icon"="D:\xxx\xxx\Typora\Typora.exe" \\ 你的typora安装路径
[HKEY_CLASSES_ROOT\.md\OpenWithProgids]
"Typora.md"=""
"VSCode.md"=""

[HKEY_CLASSES_ROOT\.md\ShellNew]
"NullFile"=""
```


# Apktool

逆向apk文件，提取apk中url

## linux grep

```
grep -ohr -E "https?://[a-zA-Z0-9\.\/_&=@$%?~#-]*" /绝对路径/apktool解压的包 |sort|uniq >> result.txt
```

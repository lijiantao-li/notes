# 压缩

## 压缩格式

* zip 
* tar.gz
* tar.bz2
* tar.xz
* tar.Z

其中tar是打包格式，gz和bz2指的是压缩格式：gzip和bzip2


## 压缩命令
filename.zip 的压缩：

```
zip -q -r  filename.zip /filename
```

filename.tar.gz 的压缩：

```
tar -zcvf filename.tar.gz /filename
```

filename.tar.bz2 的压缩：

```
tar -jcvf filename.tar.bz2 /filename
```

filename.tar.xz 的压缩:

```
tar -Jcvf filename.tar.xz /filename
```

filename.tar.Z 的压缩：
```
tar -Zcvf filename.tar.Z /filename
```
* j代表tar.bz2，
* c为压缩,x为解压
* v详细信息
* f文件

## 解压命令

filename.zip 的解压：

```
unzip filename.zip
```

filename.tar.gz 的解压：

```
tar -zxvf filename.tar.gz
```

filename.tar.bz2 的解压：

```
tar -jxvf filename.tar.bz2
```

filename.tar.xz 的解压:

```
tar -Jxvf filename.tar.xz
```

filename.tar.Z 的解压：
```
tar -Zxvf filename.tar.Z
```


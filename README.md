# mkbootimg

## 下载
```
git clone https://github.com/sbwml/mkbootimg /opt/mkbootimg
```

## 设置变量
```
export PATH="/opt/mkbootimg:$PATH"
```

# 解包 & 打包 小米6 boot.img

## 解包
```
unpack boot.img
```
解包文件存放在当前位置 "boot-tmp" 目录上。


## 打包
```
repack
```
会在当前目录生成 new-boot.img

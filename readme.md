# ncm patch script

Ubuntu 22.04下网易云音乐的修复脚本

修复后打包成deb，使之可以在Ubuntu22.04下正常运行，顺便修复就没正常过的无损音乐

thanks [Huang-Huang Bao](https://blog.eh5.me/fix-ncm-flac-playing/)

## 使用

直接执行脚本，一切正常的话，会在当前目录生成一个修复后的deb

## Failed to load module "canberra-gtk-module"
```
sudo apt install libxcb-xinerama0
```

##  Cannot open shared library (null) (/usr/lib/x86_64-linux-gnu/./alsa-lib/./libasound.so.2 
```
sudo ln -f /usr/lib/x86_64-linux-gnu/libasound.so.2.0.0 /usr/lib/x86_64-linux-gnu/./alsa-lib/./libasound.so.2
```

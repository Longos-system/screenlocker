# LongOS屏幕锁程序

## 第三方代码

kcheckpass

### Debian/Ubuntu依赖包

```
sudo apt install libpam0g-dev libx11-dev -y
```

## 构建

```shell
mkdir build
cd build
cmake -DCMAKE_INSTALL_PREFIX:PATH=/usr ..
make
```

## 安装

```shell
sudo make install
```

## License

This project has been licensed by GPLv3.

# 101Assignment7

Games101作业6-7，主要实现BVH和cpu光线追踪。

已实现内容：
* 光线追踪
* BVH

多线程加速目前有bug，未处理。因此，渲染速度特别慢。

# 256采样康奈尔盒渲染图
![spp256](https://github.com/Auggst/101Assignment7/blob/main/output/spp256.ppm)

# 环境
wsl2子系统或linux系统
```
git clone https://github.com/Auggst/101Assignment7.git
mkdir build && cd build
camke ..
make -j4
./RayTracing
```


* cmake 3.10及以上

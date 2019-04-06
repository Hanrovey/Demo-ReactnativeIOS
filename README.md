# Demo-ReactnativeIOS
React Native集成到原生iOS项目

针对目前项目需求，部分功能需要动态热部署，因此考虑使用React Native。下面有个Demo介绍原生iOS项目是如何与React Native集成的。先贴下React Native中文网是官方教程：React Native嵌入到现有原生应用。
对老项目来说，官方推荐使用第三方包管理器CoCoaPods来自动集成，但是考虑到目前我们项目中没有使用CoCoaPods，原因如下：

1、CoCoaPods 克隆第三方代码简直是慢
2、CoCoaPods会自动创建一些目录，不利于项目管理。
综上所述，因此采用手动集成，下面介绍手动集成方法。

具体步骤参考原文：https://blog.csdn.net/Hanrovey/article/details/89055560 

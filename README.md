# Setup Dev

- [简体中文](README.md)
- [English](README.en.md)

## 介绍

- 这是一个用于搭建`C++`开发环境的脚本集合；
- 部分脚本来自于 [runner-images](https://github.com/actions/runner-images)；

## 目录

1. [ubuntu](ubuntu)——ubuntu中的安装脚本
   1. [build-qt5](/ubuntu/build-qt5)——qt5源码编译安装
      1. [build.sh](/ubuntu/build-qt5/build.sh)——`qt5`源码下载，并根据当前gcc target 信息，编译；
      2. [install-dep](/ubuntu/build-qt5/install-dep.sh)——安装构建`qt`所需的依赖项；
   2. [build-mpv.sh](/ubuntu/build-mpv.sh)——mpv源码编译libmpv.so；
   3. [configure-apt-sources.sh](/ubuntu/configure-apt-sources.sh)——配置`apt`源为`ustc`的`mirrors`；
   4. [configure-git.sh](/ubuntu/configure-git.sh)——配置`git`信息;
   5. [export-vcpkg-path.sh](/ubuntu/export-vcpkg-path.sh)——集成`vcpkg`中的库到环境变量中；
   6. [install-appimagetool.sh](/ubuntu/install-appimagetool.sh)——安装appimagetool;
   7. [install-cmake.sh](/ubuntu/install-cmake.sh)——安装cmake;
   8. [install-linuxdeployqt.sh](/ubuntu/install-linuxdeployqt.sh)——安装`linuxdeployqt`，x86_64版本可以考虑直接从[github](https://github.com/probonopd/linuxdeployqt/releases/download/continuous/linuxdeployqt-continuous-x86_64.AppImage)上下载；
   9. [install-patchelf.sh](/ubuntu/install-patchelf.sh)——安装`patchelf`，也可以直接使用apt安装；
   10. [install-vcpkg.sh](/ubuntu/install-vcpkg.sh)——安装`vcpkg`，并配置环境变量;
   11. [install.sh](/ubuntu/install.sh)——辅助的`shell`函数集合；

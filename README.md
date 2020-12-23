# Deepin wine for Ubuntu 20.04

## Introduction 介绍

本项目是根据 https://github.com/wszqkzqk/deepin-wine-ubuntu 制作的新版Deepin Wine (deepin-wine-2.18-22~rc0).

## Install 安装

```sh
git clone --depth 1 git@github.com:zitsen/deepin-wine-ubuntu.git
cd deepin-wine-ubuntu
./install.sh
```

## 安装应用

`apps`目录下包含微信2.6.8及企业版微信，安装之前需要安装文泉驿字体(QQ也需要)

```sh
sudo apt install fonts-wqy-zenhei fonts-wqy-microhei
```

之后使用`apt`或`dpkg`安装：

```sh
sudo apt install ./*.deb  # 单独安装一个应用，指定全路径即可
#sudo dpkg -i ./*.deb
```

其他应用请移步 http://packages.deepin.com/deepin/pool/non-free/d/ 查看支持的应用。

列表如下：

应用 | 路径 | 版本
--- | --- | ---
WinRAR | deepin.cn.com.winrar | [5.3.0deepin2](http://packages.deepin.com/deepin/pool/non-free/d/deepin.cn.com.winrar/deepin.cn.com.winrar_5.3.0deepin2_i386.deb)
Cjsc | deepin.com.95579.cjsc | [10.6deepin2](http://packages.deepin.com/deepin/pool/non-free/d/deepin.com.95579.cjsc/deepin.com.95579.cjsc_10.6deepin2_i386.deb)
AAA Logo | deepin.com.aaa-logo | [4.1.1deepin2](http://packages.deepin.com/deepin/pool/non-free/d/deepin.com.aaa-logo/deepin.com.aaa-logo_4.1.1deepin2_i386.deb)
百度云盘 | deepin.com.baidu.pan | [5.7.3deepin0](http://packages.deepin.com/deepin/pool/non-free/d/deepin.com.baidu.pan/deepin.com.baidu.pan_5.7.3deepin0_i386.deb)
-| deepin.com.cmbchina | [7.6.0deepin0](http://packages.deepin.com/deepin/pool/non-free/d/deepin.com.cmbchina/deepin.com.cmbchina_7.6.0deepin0_i386.deb)
-| deepin.com.foxmail | [7.2deepin3](http://packages.deepin.com/deepin/pool/non-free/d/deepin.com.foxmail/deepin.com.foxmail_7.2deepin3_i386.deb)
-| deepin.com.gtja.fuyi | [2.20deepin2](http://packages.deepin.com/deepin/pool/non-free/d/deepin.com.gtja.fuyi/deepin.com.gtja.fuyi_2.20deepin2_i386.deb)
-| deepin.com.qq.b.crm | [2.10.2876deepin2](http://packages.deepin.com/deepin/pool/non-free/d/deepin.com.qq.b.crm/deepin.com.qq.b.crm_2.10.2876deepin2_i386.deb)
-| deepin.com.qq.b.eim | [1.90.2220deepin1](http://packages.deepin.com/deepin/pool/non-free/d/deepin.com.qq.b.eim/deepin.com.qq.b.eim_1.90.2220deepin1_i386.deb)
-| deepin.com.qq.im | [9.1.8deepin0](http://packages.deepin.com/deepin/pool/non-free/d/deepin.com.qq.im/deepin.com.qq.im_9.1.8deepin0_i386.deb)
-| deepin.com.qq.im.light | [7.9.14308deepin8](http://packages.deepin.com/deepin/pool/non-free/d/deepin.com.qq.im.light/deepin.com.qq.im.light_7.9.14308deepin8_i386.deb)
-| deepin.com.qq.office | [2.0.0deepin4](http://packages.deepin.com/deepin/pool/non-free/d/deepin.com.qq.office/deepin.com.qq.office_2.0.0deepin4_i386.deb)
-| deepin.com.qq.rtx2015 | [8.3.649.1deepin0](http://packages.deepin.com/deepin/pool/non-free/d/deepin.com.qq.rtx2015/deepin.com.qq.rtx2015_8.3.649.1deepin0_i386.deb)
微信 | deepin.com.wechat | [2.6.8.65deepin0](http://packages.deepin.com/deepin/pool/non-free/d/deepin.com.wechat/deepin.com.wechat_2.6.8.65deepin0_i386.deb)
企业微信 | deepin.com.weixin.work | [2.8.10.2010deepin0](http://packages.deepin.com/deepin/pool/non-free/d/deepin.com.weixin.work/deepin.com.weixin.work_2.8.10.2010deepin0_i386.deb)
-| deepin.net.263.em | [6.7deepin1](http://packages.deepin.com/deepin/pool/non-free/d/deepin.net.263.em/deepin.net.263.em_6.7deepin1_i386.deb)
CAJ Viewer | deepin.net.cnki.cajviewer | [7.2deepin0](http://packages.deepin.com/deepin/pool/non-free/d/deepin.net.cnki.cajviewer/deepin.net.cnki.cajviewer_7.2deepin0_i386.deb)
7-zip| deepin.org.7-zip | [15.14deepin2](http://packages.deepin.com/deepin/pool/non-free/d/deepin.org.7-zip/deepin.org.7-zip_15.14deepin2_i386.deb)
-| deepin.org.foobar2000 | [1.3.9deepin2](http://packages.deepin.com/deepin/pool/non-free/d/deepin.org.foobar2000/deepin.org.foobar2000_1.3.9deepin2_i386.deb)

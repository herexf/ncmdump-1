Netease Cloud Music Copyright Protection File Dump
===========

## 简介
因为最近买了个WALKMAN 发现网易云音乐有的音乐下载的文件是ncm受保护的文件 没法放到里面听 所以这个工具诞生了 用于将ncm格式转回原有的格式. 自动设置封面以及标题作者专辑等信息. 请勿传播扩散送给有缘人. 本来代码用C写的结果没找到支持flac meta数据修改的库强行转c++ 蓝瘦

## 便捷式传送门

Windows GUI版本 [ncmdump-gui](https://github.com/anonymous5l/ncmdump-gui)

Windows GUI应用程序 [ncmdump-gui-release](https://github.com/anonymous5l/ncmdump-gui/releases/tag/fully) 运行库基于 `.NetFramework 4.6.1` 

## 依赖库
	* openssl
	* taglib

## 使用
	ncmdump [files]...

# FitDiT-OneClick
FitDiT虚拟试衣软件免安装部署一键启动整合包

## FitDiT介绍
![](https://raw.githubusercontent.com/BoyuanJiang/FitDiT/refs/heads/main/resource/img/teaser.jpg)

FitDiT是一款效果不错的虚拟试衣软件，软件可以将一张模特图片和一张衣服图片重新合成为一张图片，让模特穿上指定服装，操作简单，快速高效，非常强大的一个AI换装工具。

## FitDiT整合包说明
首先到网盘内将软件压缩包下载到本地电脑上并解压，然后双击运行启动软件.exe.

软件有四种启动模式可选，由模式一到模式四，处理速度会越来越慢，但对电脑配置要求也越来越高，高配电脑选模式一，低配电脑选模式四，具体执行速度可自行测试效果。

整合包只打包了一部分模型，软件第一次运行的时候会自动下载所缺少的模型，如果你自动下载速度较慢的话，可以把网盘内的hf压缩包下载到软件项目文件夹内并解压。模型路径文件夹结构为:

FitDiT

      -hf

          -models–laion–CLIP-ViT-bigG-14-laion2B-39B-b160k

          -models–openai–clip-vit-large-patch14

启动软件后模型文件都准备完毕的话，会自动打开webUI操作界面。软件操作比较简单。

首先上传一张模特图片，然后右侧上传一张需要替换成的服装图片。然后点击右下方按钮【Step1:Run Mask】


软件会先生成一个蒙版图片，显示哪些区域将会修改，如果你对要修改的区域不满意，可以设置mask offset top，mask offset bottom，mask offset left，mask offset right来调整蒙版图片的上下左右边缘区域。对蒙版图片选定区域满意的话，可以点击按钮【Step2:Run Try-on】来生成试衣效果图。这个过程时间可能会比较长，具体由电脑配置决定。

如果你电脑配置不高的话，你可以调小图片尺寸，将【Try-on resolution】设置为最小的768×1024.

【Garment category】设置里你可以设置服装类型，如Upper-body上衣，Lower-body下装，Dresses全身的裙子。不同服装类型，生成的蒙版图片区域位置不同。

图片合成完成后，你可以鼠标右键点击图片选择图片另存为，将图片保存下来，默认是webp格式图片，你可以自行转换为其它格式图片使用。

视频教程及效果演示：[youtube>>](https://www.youtube.com/watch?v=SpNM1sed2tk)

## 注意事项
建议英伟达显卡显存6G以上用户体验

只支持windows10或11系统

软件运行路径中不要有非英文字符和空格

## 虚拟试衣软件FitDiT整合包下载链接：
夸克网盘：https://pan.quark.cn/s/9344eceaf903

迅雷：https://pan.xunlei.com/s/VOLCuCM9VupAZB9ZaEpvK6U0A1?pwd=tyvn#

## FitDit 项目链接
https://github.com/BoyuanJiang/FitDiT

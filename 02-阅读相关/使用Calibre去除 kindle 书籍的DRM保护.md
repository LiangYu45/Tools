
## 前言

### 什么是DRM保护

DRM，全称 Digital Rights Management（数字版权管理），是随着电子音频视频节目在互联网上的广泛传播而发展起来的一种新技术。出版者利用这些技术保护有数字化内容（例如：软件、音乐、电影），防止数字出版物被非法复制，或者在一定程度上使复制很困难，使得最终用户必须得到授权后才能使用数字媒体。解释听起来很官方，其实在这里我们只需要知道DRM是为了保护电子书版权而使用的一种限制技术就可以了。

### 为什么要破解 DRM 保护

为了保护电子书的版权，亚马逊提供的 azw3 或者 kfx 格式电子书都是经过 DRM 加密了的，即便是获取到了 azw3 格式的电子书文件，也无法直接在其他阅读器或阅读设备上阅读。

破解 kindle 电子书之后，有两个好处：

1、我只想保证我买过的书不会被消失（不鼓励传播盗版书）。因此，建议把电子书备份到本地。

2、将 kindle 电子书转换成 epub 格式，这样的话，在其他平台的软件（比如 iBooks软件）上也能打开电子书。

## 如何破解 kindle 电子书的 DRM 保护

### 破解 DRM 保护的准备工作

在开始破解 DRM 保护之前，我们需要准备好以下内容：

- 1、记下你的亚马逊账号绑定的 Kindle 设备的序列号

- 2、带 DRM 保护的电子书

- 3、安装 DRM 移除软件：Calibre 软件 + DeDRM 插件 + KFX input 插件。

下面分别详细介绍。

### 步骤1、记下 Kindle 设备的序列号

我们可以通过以下任何一种方式，找到 kindle 设备的序列号

- 包装盒或保修单

- kindle 阅读器

- Amazon官网 -> 管理我的内容和设备

### 步骤2、准备好需要移除 DRM 保护的电子书到本地

把需要破解的 azw 或 azw3 格式的电子书下载到本地，获取方式有以下几种：

- 方式一：从亚马逊云端下载（推荐）

登录亚马逊官网，在「**管理我的内容和设备**」里找到这本书，点击电子书旁边的【…】按钮，选择「**过电脑下载 USB 传输**」，选择你的 Kindle 设备，点击【下载】按钮把电子书下载到电脑中，然后再按照本文的方法进行破解即可。

- 方式二：从 Kindle 阅读软件的目录中拷贝

需要安装 Kindle 桌面客户端软件。如果没有安装请先在下面的列表中选择合适您的系统版本安装。安装完成后打开软件，用亚马逊账号登录，然后下载想要破解的电子书，再从相应电子书存放路径中找到它们（文件名类似于“B0080BKP1K_EBOK.azw”这种），请将它们拷贝到如桌面等任意位置备用。

Kindle for Windows 版：官方去下载。电子书存放路径：C:\Users\你的用户名\Documents\My Kindle Content

Kindle for Mac 版：官方去下载。电子书存放路径：/Users/你的用户名/Library/Application Support/Kindle/My Kindle Content

- 方式三：直接从 Kindle 阅读器中拷贝。

用USB线将 Kindle 连接到电脑，打开 Kindle 驱动器，在根目录里的 Documents 文件夹内找到 azw 或 azw3 格式的电子书文件将其拷贝出来。这种方法现在不建议使用，因为最新版本固件已经将下载到 Kindle 中的电子书中的图片抽离出去，导致直接复制的电子书缺失图片。

### 步骤3、安装 DRM 移除软件：Calibre 软件 + DeDRM 插件 + KFX input 插件

（1）安装 Calibre 软件。

（2）安装DeDRM 插件。

（2）添加序列号。在Calibre 首选项—插件—文件类型插件 中找到DeDRM，双击打开，然后单击 eInk Kindle ebooks，添加Kindle设备序列号。

## 参考链接

- [Calibre 和DeDRM 插件破解亚马逊azw格式电子书【荐】](https://www.jianshu.com/p/7e2bfacaba37)

- [将 Kindle 电子书备份到 Calibre 书库【荐】](https://maajiaa.wordpress.com/2018/07/19/kindle-to-calibre/)

- [买过的 Kindle 电子书消失了](https://maajiaa.wordpress.com/2018/07/19/purchased-kindle-ebook-disappeared/)

- <http://www.jianshu.com/p/d838f593c8ca>




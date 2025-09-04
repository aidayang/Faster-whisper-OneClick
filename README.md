# Faster-whisper-OneClick

faster-whisper是一款非常热门的语音识别转文字工具，识别速度很快，而且显存使用量要比OpenAI 的Whisper低，为了帮助大家快速上手体验这个非常强大的应用，我制作了Windows版的一键启动整合包，并制作了一个GUI操作界面。下载解压即可直接运行使用。同时制作了在线版，没有了电脑配置要求。

### 2025-09-04更新至最新1.2版本

## 整合包使用说明

压缩包下载解压后，运行【启动软件.exe】。软件支持处理mp3,wav,mp4格式音视频。也支持批量处理。可以将需要处理的音视频文件或文件夹鼠标左键按住拖动到软件窗口中。软件会自动识别路径并填充文本编辑框。

如果选择更高模型的话，软件会自动下载模型。模型下载源为国内站点。

batch size:就是批处理大小，值越大，处理速度越快，但是对电脑配置要求也越高。默认值为4，相对较小。可以根据你电脑显存使用情况适当调高该值。

计算精度：默认float16，int8速度更快，显存消耗也会更少。

翻译工具：支持百度在线翻译和ollama本地大语言模型翻译

翻译目标语言：想把识别出的文本翻译成什么语言的文本

点击【开始处理】按钮后软件就会开始处理选定的内容，识别结果保存在项目文件夹内的outputs文件夹内。

支持批量操作

视频教程：https://www.youtube.com/watch?v=jWyKD3VWTdw


## Faster-whisper一键启动整合包下载链接

https://pan.quark.cn/s/8083af4f42c2

## 在线一键启动

[点击使用云镜像>>](https://www.compshare.cn/images/2Q5RpY56alak?referral_code=FlfHWpg22A9EnXni6kYKRv&ytag=GPU_yy_nuowa)

## Faster-whisper项目链接

[https://github.com/SYSTRAN/faster-whisper](https://github.com/SYSTRAN/faster-whisper)

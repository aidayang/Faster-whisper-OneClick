# Faster-whisper-OneClick

faster-whisper是一款非常热门的语音识别转文字工具，识别速度很快，而且显存使用量要比OpenAI 的Whisper低，为了帮助大家快速上手体验这个非常强大的应用，我制作了Windows版的一键启动整合包，并制作了一个GUI操作界面。下载解压即可直接运行使用。

## 整合包使用说明

压缩包下载解压后，运行【启动软件.exe】。软件支持处理mp3,wav,mp4格式音视频。也支持批量处理。可以将需要处理的音视频文件或文件夹鼠标左键按住拖动到软件窗口中。软件会自动识别路径并填充文本编辑框。

软件包只打包了small模型，如果选择更高模型的话，软件会自动下载模型。模型下载源为国内站点。

batch size:就是批处理大小，值越大，处理速度越快，但是对电脑配置要求也越高。默认值为4，相对较小。可以根据你电脑显存使用情况适当调高该值。

计算精度：默认float16，int8速度更快，显存消耗也会更少。

翻译工具：国外用户用Google，国内用户用百度

翻译目标语言：想把识别出的文本翻译成什么语言的文本

点击【开始处理】按钮后软件就会开始处理选定的内容，识别结果保存在项目文件夹内的outputs文件夹内。

视频教程：[youtube](https://www.youtube.com/watch?v=ZBij8jrDM0M)


## Faster-whisper一键启动整合包下载链接

夸克网盘：[https://pan.quark.cn/s/8083af4f42c2](https://pan.quark.cn/s/8083af4f42c2)

百度网盘：[https://pan.baidu.com/s/1T62g8g_nICQmYCXZMkQmHw?pwd=7qh1](https://pan.baidu.com/s/1T62g8g_nICQmYCXZMkQmHw?pwd=7qh1)

## Faster-whisper项目链接

[https://github.com/SYSTRAN/faster-whisper](https://github.com/SYSTRAN/faster-whisper)

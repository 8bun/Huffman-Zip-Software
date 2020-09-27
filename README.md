# huffmanZip
基于哈夫曼压缩原理实现的压缩软件，软件界面采用QT进行实现。
#提示
用于测试的文件格式不限，如果是未压缩格式（非jpg，png，mp4，mp3）等压缩效果会更明显，尽量在1GB之内（虽然没有限制大小），实测“速度优先”模式情况下，1GB压缩需要>=1min。
可以压缩目录（压缩多个文件打包），但是只能压缩打包该目录下的文件，不能打包该目录下的目录，如果目录下只有目录而没有文件，那么压缩该目录时视为压缩空目录。
#文件夹说明：
#
【Source_Code】
[ag]算法功能模块
[res]资源文件夹
其他的都是qt的工程文件，这里可以重新构建qt的工程项目。
#
【ag】
由于涉及到多线程和zip格式编码处理，原项目（解决方案）过大，只展示huffman算法部分的C++代码。
#
【image】
把donate.png去掉了

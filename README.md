# cat
这两个代码的主要功能是实现有猫靠近就自动出粮的喂猫任务。
首先我们用到两个单片机esp32与esp32cam， esp32主要负责调动舵机与蜂鸣器等硬件实现出粮功能，esp32主要负责定时拍照并选送给服务器辅助完成识别猫的功能。
这次任务过程中我们主要借鉴了以下文章：
1.飞桨官方模型库介绍文档
2.esp系列使用手册
3.htts://aistudio.baidu.com/aistudio/projectdetail/2324551?channelType=0&channel=0
4.https://aistudio.baidu.com/aistudio/projectdetail/3997808?channelType=0&channel=0
5.being“esp32cam定时拍照保存”相关文档
6.如有遗漏，敬请联系。

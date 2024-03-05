# base
这里是整个项目可能用到的网络文献集合

## 家庭网格系统
这里需要获取盲人家中的路线图，暂定为使用ESP8266模块进行无线AP定位，使用RSSI定位算法，并绘制网格图。唯一需要提前输入的数据为房间的长和宽。

[基于ESP8266的无线定位室内寻物系统设计](https://xueshu.baidu.com/usercenter/paper/show?paperid=14080020rf0y0cn0yt4200g0gc656310)

[ESP8266如何用WiFi实现无线定位](https://zhuanlan.zhihu.com/p/658148405)

[ESP826调试工具](https://docs.ai-thinker.com/tools)


## 火灾判断
火灾判断使用了红外和温度模块进行火灾的定位。

[基于ESP8266和Zigbee的宿舍火情监测预警系统](https://wenku.baidu.com/view/f26f8cf55322aaea998fcc22bcd126fff6055d59?_wkts_=1709603353694)

[基于esp8266单片机的智能安防报警系统设计与实现](https://gitee.com/rise2629/esp-intelligent-security)
## 寻路算法

寻路算法部分是整个系统的核心，这里我们使用了A star算法，A star 最有用的地方在于代价可控，你可以通过调整代价来选择深度优先或广度有点。

当你在实际寻路过程中并不需要太精确的结果时，通过调整估值函数，大概率会遍历更少的点。

[A\*寻算法详解](https://www.bilibili.com/video/BV1bv411y79P/)

[利用Python实现A\*算法路径规划](https://zhuanlan.zhihu.com/p/136920201)

## 自动化任务

自动化任务系统会在火灾发生时根据火情大小来判断的执行的任务。这部分实现起来比较容易。

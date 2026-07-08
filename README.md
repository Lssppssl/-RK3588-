# -RK3588-
设计并实现了一款基于瑞芯微RK3588异构计算平台的智能水文检测工控机。系统采用统一封装测流计算与管控规则、双端交互层分别适配现场触控与远程监管场景的分层架构，基于Buildroot深度定制嵌入式Linux系统镜像，完成内核裁剪、第三方库交叉编译与依赖适配；集成IO管控、PWM波形生成、SPI高速通信、RTC时钟校准、多链路网络切换等全量工业外设能力；内置STIV时空图像法、LK光流法、STE-OF法三种非接触式视频测流算法，依托PostgreSQL实现测流数据的全生命周期持久化，构建“本地Qt终端+Web远程管理平台”的双端管控体系。测试结果表明，系统外设控制响应时延低、测流算法运行稳定、网络切换无业务中断，可为中小河流、灌区、山洪预警等场景提供高可靠、低成本的非接触式水文监测解决方案。
## 系统镜像百度网盘链接
通过网盘分享的文件：update.img
链接: https://pan.baidu.com/s/1APvGnMw6yWDIXnME84wA1w 提取码: 7xhk

## web源码百度网盘链接
通过网盘分享的文件：hydrology_web.7z
链接: https://pan.baidu.com/s/1t6ClkHSjTZOIEcHdUjqUIA 提取码: 18dc
## PPP拨号
通过网盘分享的文件：ppp.7z
链接: https://pan.baidu.com/s/17qsXLoFEVwdsw4iqMxXdyQ 提取码: 5mhy

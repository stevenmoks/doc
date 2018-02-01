# doc
文档专区

Car-eye 车联网管理开源系统提供一种开放性平台，方便方案公司，设备厂家，使用者可以快速地找到适合自己的需求的资源，包括硬件和软件解决方案，方便自己管理
车辆的工具。
目前系统主要分成几大部分：1. 设备子系统（包括硬件解决方案，处理器操作系统，各种驱动，流媒体，OBD，车载APP等）
2. 平台 包括车辆管理系统，流媒体平台，各种云服务器
3. 设备，包括各种手机APP,车载APP，网页网站，基于微信H5的客户端等
整个系统构成了如下图：
![](https://github.com/Car-eye-admin/doc/raw/master/车辆管理平台.jpg)
1. car-eye 车辆管理平台

car-eye车辆管理平台是进行进行车辆管理的中心，其中包含数据库服务器，web框架，也包含音视频流媒体服务。平台采用808协议实现企业业务数据传输和处理。采用oracle数据库管理设备数据，前段平台采用extjs框架，成熟稳定可靠，流媒体服务采用成熟稳定的RTSP协议传输音视频。数据库和流媒体服务相互支撑是car-eye平台功能强大所在。

2. car-eye device 子系统
car-eye device子系统是设备接入解决方案，这里包含到各种车载软件解决方案。包括GPS终端APP,行车记录仪，对讲APP等。各种软件方便用户快速集成到自己的系统中

3. car-eye client 子系统
car-eye client子系统是手机客户端，PC客户端接受系统，为用户提供界面，更加方便地远程操控自己的车辆。

4. car-eye OBD 子系统
car-eye client子系统是车辆管理系统中车内系统跟车辆管理系统的接口，用户可以通过该软件实现对车的直接控制


car-eye车辆管理平台：www.car-eye.cn; car-eye开源平台网址：https://github.com/Car-eye-admin/ 有关car-eye技术咨询可以加QQ群590411159,car-eye 客户QQ账号：2456348001



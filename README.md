# 物联大师

[![Go](https://github.com/zgwit/iot-master/actions/workflows/go.yml/badge.svg)](https://github.com/zgwit/iot-master/actions/workflows/go.yml)
[![Go](https://github.com/zgwit/iot-master/actions/workflows/codeql-analysis.yml/badge.svg)](https://github.com/zgwit/iot-master/actions/workflows/codeql-analysis.yml)
[![codecov](https://codecov.io/gh/zgwit/iot-master/branch/main/graph/badge.svg?token=AK5TD8KQ5C)](https://codecov.io/gh/zgwit/iot-master)
[![Go Reference](https://pkg.go.dev/badge/github.com/zgwit/iot-master.svg)](https://pkg.go.dev/github.com/zgwit/iot-master)
[![Go Report Card](https://goreportcard.com/badge/github.com/zgwit/iot-master)](https://goreportcard.com/report/github.com/zgwit/iot-master)


物联大师是开源免费的物联网边缘计算网关系统，区别于传统的工业智能网关，物联大师采用Go语言进行编程实现，有以下诸多优点：
- 单一程序文件，免安装
- 最低内存只需要64MB
- 能够支持多种操作系统和处理器架构
- 支持使用Lua脚本扩展协议
- 支持使用JS脚本实现边缘计算
- 支持智能家居应用场景，定时和联动控制
- 支持WebRTC点对点视频传输
- 远程托管，服务器统一配置

物联大师，物联小白 是本易物联设备托管云平台的一部分，更多信息请关注：[链接](_blank)


## 南向协议库
- [x] Modbus RTU
- [x] Modbus TCP
- [ ] Modbus ASCII（使用比较少，暂不做支持）
- [ ] PLC
- - [x] Siemens 西门子 s7 fetchwrite mpi ppi
- - [x] Mitsubishi 三菱 melsec
- - [x] Omron 欧姆龙 fins hostlink
- - [ ] AB df1
- - [ ] Delta 台达 dvp
- - [ ] Keyence 基恩士 melsec
- - [ ] Panasonic 松下 melsec newtocol
- - [ ] Fuji 富士 spb
- - [ ] Fatek 永宏
- [ ] BACnet智能建筑协议
- [ ] KNX智能建筑协议
- [x] DL/T645-1997、2007 多功能电表通讯规约
- [ ] DL/T698.45-2017 国网电力通讯规约
- [x] CJ/T188-2004、2018 户用计量仪表数据传输技术条件
- [ ] IEC 101/103/104 电力系统远程控制和监视的通信协议
- [ ] IEC 61850 电力系统自动化领域全球通用协议
- [ ] SL/T427-2021 水资源监测数据传输规约
- [ ] SL/T651-2014 水文监测数据通信规约
- [ ] SL/T812.1-2021 水利监测数据传输规约
- [ ] SZY206-2016 水资源监测数据传输规约


## 北向云平台
- [x] 本易物联设备托管云
- [x] HTTP
- [x] MQTT
- [ ] 主流云平台
- - [ ] 阿里云
- - [ ] 腾讯云
- - [ ] 华为云
- - [ ] 百度云
- - [ ] 京东云
- - [ ] 涂鸦云
- - [ ] OneNET



## 联系方式

南京本易物联网有限公司

- 邮箱：[jason@zgwit.com](mailto:jason@zgwit.com)
- 手机：[15161515197](tel:15161515197)(微信同号)


## 开源协议

[GPL](https://github.com/zgwit/iot-master/blob/main/LICENSE)

补充：产品仅限个人免费使用，商业需求请联系我们

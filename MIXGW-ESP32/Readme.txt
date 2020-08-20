该版本使用公模外壳，4色灯，CH340C LDO输出3A，要求电源输出大于1A以上并且电源输出稳定。

集成SX1278-LORA模块，NRF24模块，插件和贴片，集成ZIGBEE E18模块

外部SMA天线接口一个，使用NRF24和ZIGBEE，你必须对外壳开孔。

BOM表中，模拟开关暂时没有应用。


公模外壳https://item.taobao.com/item.htm?spm=a1z09.2.0.0.72292e8dVZ4hSx&id=527227835567&_u=21rtg20d410

ZIGBEE 需要CC-DEBUGER刷机，不支持软件OTA，预留RST-DC-DA-V-G接口

使用MYS核心同步支持MYSENSORS网关和ZIGBEE-TCP网关模式 ZIGBEE使用IOB插件，MYS使用MQTT


# [FR8016HA](https://doc.soc.xin/FR8016HA)

* [freqchip](https://www.freqchip.com/): [Cortex-M3](https://github.com/SoCXin/Cortex)
* [L1R1](https://github.com/SoCXin/Level): 48 MHz

## [简介](https://github.com/SoCXin/FR8016HA/wiki)

[FR8016HA](https://www.freqchip.com/fr801xh)

### 关键参数

* 48MHz Cortex-M3
* 集成150KB MASK ROM，最高48KB SRAM；
* 集成4M Flash ROM，用于用户空间软件与数据；
* 支持蓝牙 5.0 LE，支持 2M, 1M, 500K, 125K 数据速率；
    * TX 发射功率：+3dBm
    * RX 接收灵敏度：-93dBm@1Mbps
* 集成电池充电Battery Charger；
* 集成LDO可以对外供电；
* 单声道音频Audio CODEC
    * 16位Audio CODEC。对应DAC SNR（信噪比）96dB，THD（总谐波失真）-86dB；ADC SNR 84dB，THD -83dB

FR8016H的Tx peak电流8mA，Rx peak电流9.7mA，深度睡眠电流（48K保留RAM维持）平均功耗6.1μA，关断平均功耗2.7μA。

## [资源收录](https://github.com/SoCXin)

* [参考资源](src/)
* [参考文档](docs/)
* [参考工程](project/)

## [选型建议](https://github.com/SoCXin/FR8016HA)

CEVA曾在2017年年中发布消息提及富芮坤获得RivieraWaves Bluetooth低功耗技术授权，将IP应用于FR801x系列。

[FR8016HA](https://github.com/SoCXin/FR8016HA) 差异化竞争的核心的确在集成的Audio CODEC和PMU，是涂鸦 [BF6H-M模组](https://developer.tuya.com/cn/docs/iot/BF6H-M-module-datasheet?id=Kba01dc5q249y) 主控芯片


## [www.SoC.xin](http://www.SoC.Xin)

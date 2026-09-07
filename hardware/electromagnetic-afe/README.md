# 八通道 INA2128 电磁模拟前端

用于八路电磁传感器信号的差分放大、半波检波、包络滤波和 ADC 输出。四颗 INA2128 构成八路对称通道。

| 文件 | 用途 |
|---|---|
| `eight-channel-ina2128-afe.pdf` | 原理图快速预览 |
| `eight-channel-ina2128-afe.SchDoc` | Altium 原理图源文件 |
| `eight-channel-ina2128-afe.PcbDoc` | Altium PCB 源文件 |

原理图可确认每路 1 kΩ 增益电位器及 51 kΩ/0.1 μF 包络网络。重新投板前请复核模拟地、通道一致性、增益和 ADC 输入范围。

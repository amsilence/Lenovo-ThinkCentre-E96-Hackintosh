# Lenovo ThinkCentre E96 hackintosh

## 联想 ThinkCentre E96 台式电脑配置信息

> E96台式机是公司的电脑，这次更新EFI后，后续不会在进行更新。需要换回公司的标准系统


|  CPU   | I7 8700                             |
| :----: | ----------------------------------- |
|  主板  | 联想313A（B360芯片组）有2个HDMI接口 |
|  内存  | 8G*4 DDR4 2400                      |
|  显卡  | UHD 630                             |
|  声卡  | ALC 662                             |
|  网卡  | RTL8168/8111/8112                   |
|  磁盘  | 铠侠M.2 NVME 1T                     |
| 显示器 | LEN S27i-10                         |

## opencore引导信息

1. opencore版本为：1.0.2正式版
2. EFI配置支持的系统：macOS 11.x/macOS 12.x/macOS 13.x/macOS 14.x/macOS 15.x

## 其他注意事项

1. EFI未进行USB驱动定制，需要USB定制的可以自行定制
2. 需要调整BIOS里面IDG内存大小为64MB
3. 需要关闭BIOS没得安全模式，TPM2.0，CMS

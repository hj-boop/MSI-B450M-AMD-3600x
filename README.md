# MSI-B450M-AMD-3600x
Hackintosh EFI

# 参考文档

https://dortania.github.io/OpenCore-Install-Guide/

https://apple.sqlsec.com/



# 电脑配置

| 规格   | 详细信息                                |
| ------ | --------------------------------------- |
| 处理器 | AMD Ryzen 5 3600X 6-Core 六核           |
| 主板   | 微星 B450M MORTAR                       |
| 显卡   | AMD Radeon RX 6600                      |
| 声卡   | 瑞昱 ALC892 @ AMD High Definition Audio |
| 网卡   | 瑞昱 RTL8168/8111/8112                  |



## 注意

自己是做的双系统，win10 + macOS Monterey 12.2。微星主板关闭 CSM，再开启 Above 4G 发现进不去 win10 了，关了 Above 4G 又进不去苹果。最后关闭 Above 4G，在 boot-args 添加 npci=0x2000 解决了
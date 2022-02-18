# ASUS-ROG-STRIX-Z490I-HACKINTOSH
# 华硕z490i黑苹果

## 电脑配置：

- cpu：i7-10700
- 显卡：撼讯RX6600XT竞技（别问为什么不买红魔，机箱尺寸实在脑残，后悔中）
- 主板：ASUS ROG STRIX Z490I 
- 网卡：AX201（该主板Wi-Fi采用CNVI协议，不支持替换Z3和Z4，本人已尝试，分享一下）
- 硬盘：
  - m.2-1 --> SN750 1T（mac）
  - m.2-2 --> 三星980pro 1T(win 10)
  - SATA3 --> 希捷1T(文件存档，早知道再买大一点
- 机箱：乔思伯 bo 100（脑残机箱，等会儿解释）

**参考EFI链接：https://github.com/jergoo/Hackintosh-ROG-STRIX-Z490I，感谢 jergoo ，EFI已经很完美了**

## 我做的修改：
1. Intel wifi 和 intel 蓝牙，jergoo是采用了博通免驱卡，我才用了intel wifi
2. 补齐了电源5项，其实没什么用，强迫症而已
3. 替换了我笔记本的EFI主题，挺好看的，不知道是谁做的，感谢感谢

## 我遇到的问题：

1. Monterey 12.2中， intel Wi-Fi 的stable 版本不支持，跑完码后黑屏，要用alpha版本
2. 貌似usb定制完要重置nvram才生效，不然还是睡眠秒醒
3. 垃圾乔思伯 bo 100机箱，独显那儿多出来一块挡板，导致我dp口只能用一个，还有一个hdmi口，以后如果要用估计还得买直角的dp线

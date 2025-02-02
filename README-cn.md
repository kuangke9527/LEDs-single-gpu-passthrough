# ledis的单显卡直通教程
[英文版本](README.md)

这是我的单显卡直通配置过程;我在多个不同配置的电脑上都试过，这个方法都成功了。<br>
如果有问题可以去B站上找我, 视频教程链接：*还没做完*https://space.bilibili.com/589560036 <br>
<br>
我这里讲的是AMD处理器（英特尔的也差不多，个别参数会不一样）; 系统是Arch, 如果是其它发行版一些软件名和文件位置可能会不太一样。<br>

---
更新日期：2021年12月26日
添加了更适合英伟达显卡直通的脚本  
---

**我的电脑配置**
- 处理器: AMD 锐龙 3900x 12核
- 显卡: 微星 Radeon RX 560 4GT LP 超频
- 主版：玩家国度 ROG Strix B550-A GAMING 吹雪
- 内存: 32GB 3200Mhz 双通道
- 系统: Arch Linux 5.11
- 桌面环境: KDE Plasma 5.21 X11

* * *
**步骤**
1. [配置一个简单的KVM（非直通）](VFIO/Setting%20up%20a%20basic%20KVM%20cn.md)
2. [Libvirt 钩子](VFIO/Libvirt%20Hooks%20cn.md)
3. [QEMU和Libvirt的配置](VFIO/Configure%20Libvirt%20cn.md)
4. [显卡直通](VFIO/Setting%20up%20Passthrough%20cn.md)
5. [some other things](VFIO/Debugging%20and%20other%20features.md)

* * *
**其它资源**
- Arch Wiki [PCI passthrough](https://wiki.archlinux.org/index.php/PCI_passthrough_via_OVMF) 
- GitLab [RisingPrismTV's script](https://gitlab.com/risingprismtv/single-gpu-passthrough)

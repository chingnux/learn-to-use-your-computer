如何选取硬件
----------------

选取硬件最基本的原则，是根据软件选硬件。其次是考虑成本、性能、功耗等方面的需求。

因为我们需要在计算机上使用GNU/Linux操作系统，所以选择的硬件都必须要能在GNU/Linux下正常工作。

CPU
~~~~

大部分CPU都可以运行GNU/Linux. 考虑到现在个人计算机最成熟的体系结构是AMD64，GNU/Linux对这个体系结构的支持也很好，我们选择使用基于Intel或者AMD的AMD64处理器的平台。

显卡和GPU
~~~~~~~~~~

Intel和AMD近几年的处理器的核芯显卡对GNU/Linux的支持都很好。同时，核芯显卡的性能已经可以满足大部分的需求，因此没有必要再添加独立显卡。

在独立显卡中，NVIDIA的显卡对GNU/Linux的支持很差，并且他们的驱动开发者和自由软件用户社区也没有很好的合作，因此建议不要使用NVIDIA的显卡。

网络设备
~~~~~~~~~~

大部分以太网控制器都能在GNU/Linux下很好地工作。

在WiFi设备中，Atheros的802.11n设备在因无需私有固件，在自由软件社区中非常受欢迎。虽然不支持新的WiFi标准，但已经足够使用。需要避免使用的是Broadcom的无线网卡，它对GNU/Linux的支持非常差。

大多数的蜂窝网络调制解调器在GNU/Linux下都能使用。

打印机
~~~~~~~~~~

在打印机中，大部分的HP的打印机在GNU/Linux中有比较好的支持。HPLIP的网站 [1]_ 提供HP打印机驱动支持的型号。


.. [1] https://hplipopensource.com/

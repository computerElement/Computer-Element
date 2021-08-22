# Computer-Element

本项目主要目标是参考《计算机系统要素》(ISBN：9787121033360)一书,实现一个操作系统
The Elements of Computer Systems: Building a Modern Computer from First Principles
## 工具链准备
所有需要用到的软件可在作者提供的网站下载:https://www.nand2tetris.org/software.

压缩包名为:Nand2tetris Software Suite

解压后有tools和projects两个文件夹.

其中,tools文件夹存放解题所需的软件,也即硬件仿真软件(通过HardwareSimulator.bat启动),.
## 第一章

本章主要为在Nand gate的基础上实现其他gate。Nand gate已在软件HardwareSimulator中默认实现.

Nand与其他基本逻辑门的关系请参考:https://en.wikipedia.org/wiki/NAND_logic 。

Nand和Mux的关系请参考:http://nand2tetris-questions-and-answers-forum.32033.n3.nabble.com/On-the-implementation-of-the-ALU-without-Multiplex-td4026464.html

多位多通道门请参考:https://nand2tetris-hdl.github.io/#mux416
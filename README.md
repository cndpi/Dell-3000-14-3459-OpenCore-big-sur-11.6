# Dell-3000-14-3459-OpenCore-big-sur-11.6

原来的OC0.7.4也是github上来也是DELL，但机型不一样。而且WIN开机蓝屏。并且原来USB只能使用2个。但本机器是3个USB接口。

修复双系统win764启动正常不蓝屏和USB问题，主要是GUPC补丁引起的。。删除所有GUPC to XUPC，就可以了。增加inter原生WIFI和蓝牙kext。

CPU: I5 6200U<br>
内存：4G <br>
SATA：240固态<br>
集成显卡：HD520
WIFI：inter 3160<br>
蓝牙：inter<br>
声卡：ALC255，补layout id: 3<br>
模拟机型：Macbook pro 13，1<br>

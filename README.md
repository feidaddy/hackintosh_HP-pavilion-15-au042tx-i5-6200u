HP Pavilion 15-au042tx 笔记本电脑
===

-------
    
   中文｜[English](https://github.com/feidaddy/hackintosh_HP-pavilion-15-au042tx-i5-6200u/blob/main/readme%20en.txt)
    
-------    
cpu: 

    英特尔酷睿 i5-6200U 2.3GHz、Turboboost 2.8GHz     
cpu平台：

     Skylake
     
显卡:

     英特尔高清显卡 520
     
     英伟达 Geforce 940MX
     
内存:

     8 GB DDR4l 2133MHz
     
主板：

    惠普 820C v82.39
    
BIOS：

    惠普 Insyde F.52
    
声卡：

    瑞昱 ALC 295
    
蓝牙：

    Realtek 蓝牙 4.0 适配器
    
无线网卡：

    Realtek RTL8723BE 802.11 bgn Wi-Fi 适配器 （ac-3165）
    
以太网：

    Realtek RTL8139 / 810x 快速以太网适配器
    
读卡器：

    Realtek PCI-E 读卡器
    

正常设备：

        英特尔高清显卡 520
        
        图形加速 Inte Quick Sync
        
        声卡用Fn+F6/Fn+F7/Fn+f8，分别静音，减小音量和增大音量
        
        触控板 - 无手势
        
        USB 2.0 端口  （未定制usb端口）
        
        内置音频  （alcidi=24）
        
        3.5 迷你插孔耳机接口   (插入拔出均无异常)
        
        以太网 （理论上支持，无接网线，未测试）
        
        无线上网：
        
              itlwm+heliport.app
              
            后续更新了
            
              airportitlwm ，并启用原生wifi部件
              
              #优先建议使用这个驱动，并且与上面的驱动有冲突，只能二选一#
              
        蓝牙 （未测试，能正常打开关闭 - -）
        
        

不能正常设备：

        Nvidia Geforce 940MX
        
        Usb 3.0
        
        显示器亮度
        
        cpu风扇转速
        
        cpu温度
        
        
未测试：       

        电池电量（因为我的电池已经卸下了，所以并不清楚能不能正常显示）
        
        FaceTime
        
        iMassage
        
        HandOff
        
        Continuity
        
        HDMI
        
        dvd光驱（在 macOS 中可以识别，您甚至可以通过在界面中按几个按钮来打开它，但我没有 DVD/CD 来检查光驱的运行情况）
        
        
测试系统：
     
        macos 11 （理论上支持到11.5.2 + 12 beta）
        
        
引导：
        
        opencore
        
        
-------        
        


* 相关下载：

[一键hidpi](https://github.com/feidaddy/hackintosh_HP-pavilion-15-au042tx-i5-6200u/blob/main/%E4%B8%80%E9%94%AEhidpi.zip)

[菜单栏修改分辨率](https://github.com/feidaddy/hackintosh_HP-pavilion-15-au042tx-i5-6200u/raw/main/RDM.zip)

[菜单栏修改屏幕亮度](https://github.com/feidaddy/hackintosh_HP-pavilion-15-au042tx-i5-6200u/blob/main/QuickShade.zip)

   * 无线上网驱动：

   [itlwm](https://github.com/OpenIntelWireless/itlwm) + [heliport](https://github.com/OpenIntelWireless/HeliPort)

   [airportitlwm](https://github.com/kwangle912/AirportItlwm-for-Hackintosh)


------- 

* 同配置其他引导:

[clover](https://github.com/Drovosek01/hackintosh_HP_Pavilion_15-au028ur_i5-6200U)
 来自大佬 [@Drovosek01](https://github.com/Drovosek01) 应该可以支持到10.15.x,算是完美EFI了，缺少的驱动可以用上述的[WIFi驱动](https://github.com/kwangle912/AirportItlwm-for-Hackintosh)，[蓝牙驱动](https://github.com/OpenIntelWireless/IntelBluetoothFirmware)

------- 

* [联系我](http://wpa.qq.com/msgrd?v=3&uin=627791772&site=qq&menu=yes)
    企鹅号：   627791772

------- 

* 特别感谢：
   * [@黑果小兵](https://github.com/daliansky)提供的安装镜像
   * [@kwangle912](https://github.com/kwangle912/AirportItlwm-for-Hackintosh)提供英特尔无线驱动
   * [@LZJZMT](https://github.com/LZJZMT/OC-Gen-X)提供opencore配置生成器
   * [@Drovosek01](https://github.com/Drovosek01/hackintosh_HP_Pavilion_15-au028ur_i5-6200U)提供基础efi

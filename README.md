# 由于本地编译速度更快，本仓库不再更新。

自用竞斗云编译

自用星际宝盒编译

自用NEWIFI 3 编译

> 已加入passwall插件

食用说明

***

1. 运行此仓库的actions
2. 根据自己需求选择是否连接ssh，改变输入框的false为有链接ssh的需求
   
   即非false为开启ssh链接，false为不开启ssh，直接使用仓库指定文件进行编译
   
   ***
3. 进入运行中的github action详情页，稍等七至八分钟，等待出现tmate链接，点击进入
4. 黑框内按下键盘 Ctrl + C
5. 键入
   ```
   cd openwrt && make menuconfig
   ```
6. 插件选取成功，记得按tab到save保存配置，然后连续按几次Esc键返回到命令行
7. 键入
   ```
   touch /tmp/finished
   ```

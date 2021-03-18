# 自用竞斗云编译
# 自用星际宝盒编译

已加入passwall插件

## 食用说明
## 需要ssh链接至机器以自行选取插件
### 0  运行此仓库的actions
### 1  根据自己需求选择是否连接ssh，改变输入框的false为有链接ssh的需求
即非false为开启ssh链接，false为不开启ssh，直接使用仓库指定文件进行编译
### 2  进入运行中的github action详情页，稍等七分钟，等待出现tmate链接，点击进入
### 3  按下键盘Ctrl + C
运行cd openwrt && make menuconfig
### 4  插件选取成功，记得tab到save保存配置，然后连续按Esc返回到命令行

### 5  键入 touch /tmp/finished 即可开始编译

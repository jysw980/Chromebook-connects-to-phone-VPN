# Chromebook-connects-to-phone-VPN
# 手机VPN共享到Chromebook完成激活
# 准备工作

 - kexue上网APP：推荐ikuuu，[网址](https://ikuuu.pw/auth/register?code=dke6)。按照教程安装并配置好Clash。本文以华为MATE20手机为例。
 - 需要kexue上网的设备，如chromebook。

# 第一步：配置手机
 1. 打开手机热点。
 2. 打开clash，选择全局代理模式
 3. 确认手机可以访问wai网
 4. 回到clash，点击设置-覆写-修改HTTP端口为7890***记住此端口号***-启用允许来自局域网的连接-保存
 5. 打开手机设置-关于手机-状态信息-获得IP地址，如（198.168.3.5）***记住此地址***
# 第二步：配置chromebook
连接到你的手机热点，然后查看详情配置代理，选择手动配置代理，前两行输入上一步得到的IP地址和端口，第三行不用管，最后点击保存。
# 第三步：享受kexue上网吧！

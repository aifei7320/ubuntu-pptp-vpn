# pptp-vpn
```bash
sudo wget https://github.com/JackYang500/pptp-vpn/releases/download/v1.0/setup.sh
sudo chmod a+x setup.sh
sudo sh setup.sh
```
# Ubuntu pptp vpn搭建脚本
* 如果无法一键安装请编辑sh文件，查看注释进行调整
  * 如果源有问题的同学，请参考Github https://github.com/JackYang500/ubuntu-aliyun-sources
  * 如果源有问题的同学，请参考CSDN https://blog.csdn.net/weixin_43960643/article/details/88400055
  * 修改账号密码 /etc/ppp/chap-secrets
  * 修改网卡eth0为真实网卡 iptables -t nat -A POSTROUTING -s 192.168.2.0/24 -d 0.0.0.0/0 -o eth0 -j MASQUERADE
  
# Wechat
ylf283598349
# 注意
* 本教程仅供学习测试用途。
* 如有问题，可联系作者一起交流。

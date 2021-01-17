# VMware Workstation Systemd 单元
## 这些服务用于管理VMware Workstation,针对Arch所写;
### 喜欢Arch的唯一理由,一切自己动手,一切自己说了算;


## 服务类型;
```ruby
vmware_vmmon.service    #虚拟机监视器;
vmware_vmnet.service    #虚拟以太网;
vmware_usb.service      #USB加载服务;
vmware_vmci.service     #虚拟机通信接口;
vmware_vmsock.service   #VMCI套接字家族;
vmware_vmblock.service  #阻止文件系统;
vmware_authentication.service   #身份验证守护程序;
```

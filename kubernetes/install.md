# k8s

## steps
- `sudo apt   install -y kubelet=1.18.20-00 kubeadm=1.18.20-00 kubectl=1.18.20-00`
- `sudo apt install ipset ipvsadm`
```bash
# kubectl taint node master0 node-role.kubernetes.io/master:NoSchedule-
# mkdir -p /etc/sysconfig/modules/ && sudo vim /etc/sysconfig/modules/ipvs.modules
#!/bin/bash
modprobe -- ip_vs
modprobe -- ip_vs_rr
modprobe -- ip_vs_wrr
modprobe -- ip_vs_sh
modprobe -- nf_conntrack
```

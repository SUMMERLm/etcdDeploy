root@master:~# kubectl exec etcd-0 -c etcd -- etcdctl set mykey myvalue
myvalue
root@master:~# kubectl exec etcd-0 -c etcd -- etcdctl get mykey myvalue
myvalue
```bash
$ git clone https://github.com/JeongsikKang/kube-plugins.git

$ sudo apt-get install -y bc

$ sudo cp kube-plugins/examples/kubectl-htop $(which kubectl | sed 's/kubectl//')kubectl-htop

$ kubectl htop -n kube-system # or kubectl htop
POD                                CPU CPUBAR(|:100m)                    MEMORY MEMORYBAR(|:100Mi)
kube-apiserver-master              33m [                              ]   527Mi [|||||                         ]
kube-controller-manager-m ..       25m [                              ]    72Mi [                              ]
kube-dns-86bcbdf858-68nvs           2m [                              ]    31Mi [                              ]
...
```

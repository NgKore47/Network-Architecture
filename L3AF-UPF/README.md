# L3AF Deployment & Integration with UPF

Currently tested in VM only.

This is the network architecture we are using for the L3AF deployment and its integration with UPF:

![l3af](./images/UPF+L3AF-NetStack.png)

- ebpf package repository to load ebpf programs at xdp hook point.
- AF_XDP socket will be used.

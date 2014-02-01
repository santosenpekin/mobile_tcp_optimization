mobile_tcp_optimization
=======================

###Linux TCP 优化项目

该项目针对移动互联网高延迟，信号干扰情况丢包而非链路丢包及网络拥塞丢包而设计的。
通过调整 RTO, initial CWND, restart CWND, retransmit 等参数，及改善拥塞算法，改善发包频率，对移动互联网的单边TCP进行加速。

该工程基于Linux-3.8内核实现，所有的补丁都是基于该内核实现。

###作者邮箱:santosenpekin@163.com

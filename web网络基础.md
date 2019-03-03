# TCP/IP分层管理

## 应用层

### FTP （File Transfer Protocol）。文件传输协议

### DNS（Domain Name System）。域名系统

### HTTP（HyperText Transfer Protocol ）。超文本传输协议

- URI

	- 协议方案名

		- https:

	- 登陆信息（认证）

		- user:用户名。或者data:数据。或者javascript:脚本

	- 服务器地址

		- DNS可解析的名称

			- hackr.jp 

		- IPv4

			- 192.168.1.1

		- IPv6

			-  [0:0:0:0:0:0:0:1] 

	- 服务器端口号

		- :80

	- 带层次的文件路径

		- /dir/index.htm

	- 查询字符串

		- ?uid=1

	- 片段标志符

		- #ch1

## 传输层

### TCP（Transmission Control Protocol）。传输控制协议

- BSS（Byte Stream Service）。字节流服务。

	- 报文段（segment） 为单位

- 三次握手（three-way handshaking）策略

	- A send SYN（synchronize）to B
	- B return ACK（acknowledgement）/ SYN to A
	- A send ACK to B

### UDP（User Data Protocol ）。用户数据协议

## 网络层 / 网络互连层

### IP （Internet Protocol ）。互联网协议

- IP 地址
- MAC地址

  （Media Access Control Address）。网卡固定地址。一般不变。

### ARP（Address Resolution Protocol ）。解析地址协议

IP 间的通信依赖 MAC 地址。 
在网络上， 通信的双方在同一局域网（LAN） 内的情况是很少的， 通常是经过多台计算机和网络设备中转才能连接到对方。而在进行中转时， 会利用下一站中转设备的 MAC地址来搜索下一个中转目标。 
这时， 会采用 ARP 协议（AddressResolution Protocol）。ARP 是一种用以解析地址的协议， 根据通信方的 IP 地址就可以反查出对应的 MAC 地址。

## 链路层 / 数据链路层  / 网络接口层

### 操作系统

### 硬件设备驱动

### NIC（Network Interface Card）。网络适配器 / 网卡

### 光纤


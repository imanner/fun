


传输层的主要作用在ip层建立的两个主机间的链接上建立两个进程间的链接。  
在这一层主要是两个协议 一个是面向链接的tcp 一个是无连接的udp。  

##### 之前看到的一个问题是 既然ip是无连接的 不可靠的，udp也是无连接的不可靠的，为什么要有udp的存在？  
按照我现在的理解 这里的答案主要就是因为ip层建立的是端到端的链接， 是两个主机间的。  
具体到执行的话是主机中的进程执行，而运输层的udp 和 tcp 都有端口这个概念。也就是依靠  
这个端口来执行具体的进程间的通信。
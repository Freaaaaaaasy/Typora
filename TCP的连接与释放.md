# TCP的连接与释放



## 1 首先下图在packt tracer中搭建计算机网络

<img src="C:\Users\76585\Desktop\网络体系结构\TCP连接与释放\image-20251026162325115.png" alt="image-20251026162325115" style="zoom:80%;" />

## 2 对设备进行ip和网关的设置，具体设置如下图

- PC0的设置：

<img src="C:\Users\76585\Desktop\网络体系结构\TCP连接与释放\image-20251026162528900.png" alt="image-20251026162528900" style="zoom:80%;" />

​                     

- PC1的设置：

  <img src="C:\Users\76585\Desktop\网络体系结构\TCP连接与释放\image-20251026162612475.png" alt="image-20251026162612475" style="zoom:80%;" />

  <img src="C:\Users\76585\Desktop\网络体系结构\TCP连接与释放\image-20251026162649701.png" alt="image-20251026162649701" style="zoom:80%;" />

- Server的设置：

  <img src="C:\Users\76585\Desktop\网络体系结构\TCP连接与释放\image-20251026162801336.png" alt="image-20251026162801336" style="zoom:80%;" />

  <img src="C:\Users\76585\Desktop\网络体系结构\TCP连接与释放\image-20251026162816506.png" alt="image-20251026162816506" style="zoom:80%;" />

- Router的设置：

  <img src="C:\Users\76585\Desktop\网络体系结构\TCP连接与释放\image-20251026162928187.png" alt="image-20251026162928187" style="zoom:80%;" />
  
   
  
  <img src="C:\Users\76585\Desktop\网络体系结构\TCP连接与释放\image-20251026162952992.png" alt="image-20251026162952992" style="zoom:80%;" />



 

## 3 打开仿真模式（Simulation）

<img src="C:\Users\76585\Desktop\网络体系结构\TCP连接与释放\image-20251026163200332.png" alt="image-20251026163200332" style="zoom: 50%;" />

## 4 选择Edit Filters，勾选TCP和HTTP协议

<img src="C:\Users\76585\Desktop\网络体系结构\TCP连接与释放\image-20251026163318705.png" alt="image-20251026163318705" style="zoom:50%;" />

<img src="C:\Users\76585\Desktop\网络体系结构\TCP连接与释放\image-20251026163349526.png" alt="image-20251026163349526" style="zoom:50%;" />

## 5 打开PC0，进入web浏览器，在地址栏输入192.168.2.100，然后点击go

<img src="C:\Users\76585\Desktop\网络体系结构\TCP连接与释放\image-20251026163525368.png" alt="image-20251026163525368" style="zoom:50%;" />

## 6 等待数据包的传输，传输结束如图所示

<img src="C:\Users\76585\Desktop\网络体系结构\TCP连接与释放\image-20251026163855873.png" alt="image-20251026163855873" style="zoom:50%;" />
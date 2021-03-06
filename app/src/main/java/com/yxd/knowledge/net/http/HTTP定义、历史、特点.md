## 什么是HTTP？
<font color=#dea32c>**超文本传输协议**</font>，基于<font color=#dea32c>**请求与响应**</font>，<font color=#dea32c>**无状态**</font>的，<font color=#dea32c>**应用层**</font>的协议。  
基于<font color=#dea32c>**TCP / IP**</font>协议传输数据，应用最为广泛的网络协议。  
设计初衷是为了提供一种发布和接受HTML页面的方法。

## 发展历史
|版本|产生时间|内容|发展现状|
|----|----|----|----|
|HTTP 0.9|1991年|规定CS通信格式，只能GET请求|未作为正式标准|
|HTTP 1.0|1996年|不限制传输格式，增加多个命令|正式作为标准|
|HTTP 1.1|1997年|<font color=#dea32c>**长连接**</font>，节省带宽，HOST域，管道机制，分块传输编码|2015年前使用最为广泛|
|HTTP 2.0|2015年|<font color=#dea32c>**多路复用，服务器推送，头信息压缩，二进制协议**</font>等|逐渐覆盖市场|

## 特点
### 无状态
HTTP协议对客户端没有状态存储，对事务处理没有"记忆"能力。
> 例如，登录网站时如果不把数据保存到Cookie中，那么下次访问时还要重新登录。
***
### 无连接
HTTP/1.1以前：每次请求都要经过🤝x3👋🏻x4，重连服务器。
***
### 基于<font color=#dea32c>**请求**</font>和<font color=#dea32c>**响应**</font>
有客户端发起请求，服务端响应。
***
### 简单、快速、灵活
***
### 通信使用<font color=#dea32c>**明文**</font>
请求响应不会对通行方进行确认，无法保证数据安全性。
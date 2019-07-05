# spring-parent
<h3>JWT</h3> 

JSON WEB TOKEN（JWT）是目前最流行的跨域身份验证解决方案，服务器不保存任何回话信息，即服务器变为无状态。

* JWT TOKEN分为如下三部分： <br> 
+ JWT头：JWT头部分是一个描述JWT元数据的JSON对象  <br>
* 有效载荷：  有效载荷部分，是JWT的主体内容部分，也是一个JSON对象，包含需要传递的数据。<br>
- 签名：签名哈希部分是对上面两部分数据签名，通过指定的算法生成哈希，以确保数据不会被篡改。<br>
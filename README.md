# WebApiDemo
接口安全
出处：http://www.cnblogs.com/codeon/p/6123863.html

注：demo不能直接运行，需要把两个web项目配置到iis中，api代表接口提供方，他的主域需要配置到business的webconfig中，在浏览器地址栏分别请求business中的各个调用接口方法来实现接口调用。

1、如果想验证参数错误，需要在请求接口时打个断点把接口url取出，篡改url参数，然后在浏览器中模拟请求

2、如果想验证接口超时，需要在请求接口时打个断点把接口url取出，然后等到了超时时间，然后在浏览器中模拟请求

3、如果想验证私钥错误，需要在请求接口时打个断点把接口url取出，然后修改business的私钥配置，然后在浏览器中模拟请求
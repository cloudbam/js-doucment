### 区别一：

```
  get重点在从服务器上获取资源，post重点在向服务器发送数据； 
```

### 区别二：

```
  get传输数据是通过URL请求，以field（字段）= value的形式，置于URL后，并用"?"连接，多个请求数据间用"&"连接，如http://127.0.0.1/Test/login.action?name=admin&password=admin，这个过程用户是可见的； 
	post传输数据通过Http的post机制，将字段与对应值封存在请求实体中发送给服务器，这个过程对用户是不可见的；
```

### 区别三：

```
 Get传输的数据量小，因为受URL长度限制； Post可以传输大量数据，所以上传文件时只能用Post方式； 
```

### 区别四：

```
 get是不安全的，因为URL是可见的，可能会泄露私密信息，如密码等； post较get安全性较高； 
```





https://www.kancloud.cn/lixu/interview/907142
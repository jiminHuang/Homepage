# tornado
the base image of tornado<br/>tornado 网络服务器的基础镜像
### download
``` docker pull companyservice/tornado ```
### How to use this image
downlad and run the container based on the image<br/>
下载并运行基于镜像的容器<br/><br/>
``` docker run -d -P -v ($PWD):/server companyservice/tornado ```</br><br/>
the volume directory ```/server```is used to update the server code, 
```server.py``` is required to be the main python file</br>
```/server``` 是服务器代码的挂载目录，确保```server.py```是服务器启动文件

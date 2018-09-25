## 1、  netcat安装
### 1.下载
本地下载：https://sourceforge.net/projects/netcat/files/netcat/0.7.1/netcat-0.7.1.tar.gz/download

上传至服务器

当然，也可以直接在服务器上wget https://sourceforge.net/projects/netcat/files/netcat/0.7.1/netcat-0.7.1.tar.gz/download

### 2. 解压到指定目录

tar zxf netcat-0.7.1.tar.gz -C /opt/soft/

### 3. configure && make && make install

#### 进入到netcat安装的 **主目录**

主目录：【查看图片】netcat-home.png


####  **configure**
 
检测你的安装平台的目标特征

主目录下执行命令： ./configure

控制台打印：【查看图片】configure-print.png

configure之后新增内容：【查看图片】new-add-content-after-configure.png

####  **make && make install**
 
编译和安装

主目录下执行命令：make && make install

#### **最终主目录下的src目录中产生netcat可执行的二进制文件**

### 4. 测试

执行命令 nc -help

控制台打印：【查看图片】nc-help-print.png

## 2、  netcat使用

待完善

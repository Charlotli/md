**CentOS7 安装 Docker、Nginx、Mysql 、Net6**

**Docker 安装**

1.使用以下命令更新 CentOS 系统，确保已经安装了最新的软件包和依赖项。

`sudo yum update `

安装 Docker 依赖项：Docker 运行需要一些依赖项，使用以下命令安装这些依赖项。

`sudo yum install -y yum-utils device-mapper-persistent-data lvm2` 

添加 Docker Yum 源：使用以下命令添加 Docker Yum 源。

`sudo yum-config-manager --add-repo https://download.docker.com/linux/centos/docker-ce.repo` 

sudo yum install -y docker-ce

sudo systemctl start docker




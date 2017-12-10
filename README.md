# Hadoop Demo
学习 hadoop

## 安装部署

使用 Maven 打包后，在 hadoop 安装目录创建 myapp 文件夹

```shell
cd /usr/local/Cellar/hadoop/2.8.2
mkdir myapp
```

然后将 jar 文件移动到 myapp 中。接着，输入以下命令

```shell
hadoop jar ./myapp/HDFSExample.jar
```
或者
```shell
java -jar ./myapp/HDFSExample.jar
```
注意修改 maven-jar-plugin 的设置
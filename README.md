# HomeWork_GO_Package
第三周作业，go语言包

**操作系统：Win10**

配置环境变量：<br/>
![](./imgs/image001.png)<br/>
![](./imgs/image003.png)<br/>

使用 github.com/Yqccc 作为基本路径：<br/>
![](./imgs/image004.png)<br/>

创建hello文件夹，创建hello.go，并在VSCode中编写代码：<br/>
![](./imgs/image005.png)<br/>
![](./imgs/image007.png)<br/>

打开cmd，cd到hello.go所在文件夹，并使用install产生一个可执行的二进制文件：<br/>
![](./imgs/image008.png)<br/>

打开bin文件夹，发现有相应的可执行文件hello.exe：<br/>
![](./imgs/image009.png)<br/>

cd到bin文件夹，输入hello，得到输出：<br/>
![](./imgs/image011.png)<br/>

在src\github.com\Yqccc创建stringutil文件夹来保存库：<br/>
![](./imgs/image012.png)<br/>

创建reverse.go并在VSCode编写代码：<br/>
![](./imgs/image014.png)<br/>
![](./imgs/image016.png)<br/>

用 go build 命令来测试该包的编译：<br/>
![](./imgs/image017.png)<br/>

修改hello.go:<br/>
![](./imgs/image018.png)<br/>

对hello.go进行install:<br/>
![](./imgs/image019.png)<br/>

运行hello.exe:<br/>
![](./imgs/image020.png)<br/>

对reverse.go进行install:<br/>
![](./imgs/image021.png)<br/>

查看pkg\windows_amd64\github.com\Yqccc发现有stringutil.a包：<br/>
![](./imgs/image022.png)<br/>

创建reverse_test.go并编写代码：<br/>
![](./imgs/image024.png)<br/>
![](./imgs/image026.png)<br/>

进行go test测试，通过：<br/>
![](./imgs/image028.png)<br/>
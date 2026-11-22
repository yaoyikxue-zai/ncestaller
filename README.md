
# 特别注意⚠<br>
<body> 注意要在支持的环境里执行</body><br>
那些不会git 命令的或者不想学或者用git命令的人，可以在上线后去Releases页面下载对应的包然后放对应环境解压 执行上面的命令做同样的流程

# FAQ <br>
## •关于赞助方式会公布到哪些地方
 ```text
  ∆1:Github
  /
更多敬请期待，没在这更新的就说明不是我的，正常情况下会在这标注/
 ```
## •交互模式怎么使用?
```text
∆:输入软件名字或者部分网站的名字，如果收录了，就会有详细信息
```
## •交互模式下停止运行的命令
```bash
exit

```
## •关于一键部署 <br>
脚本支持一键部署,git好仓库后执行以下命令:
```bash
mkdir temp && mv ncestaller temp && cd temp/ncestaller/ncestaller/Pkg && unzip ncestaller_ForTermux.zip && cd && cd temp/ncestaller && chmod 755 ncestaller/Pkg/ncestaller && mv ncestaller /data/data/com.termux/files/home && cd && rm -rf temp && ./ncestaller/Pkg/ncestaller installer ncestaller && rm -rf ncestaller
```
同样也支持 
```bash
ncestaller uninstall
```
<br>

更多命令可以在安装后执行:
```bash
ncestaller -h 
```
或者
```bash
ncestaller --helps
```
### •termux 通过Releases下载部署的命令
注意！ 包要在当前目录🫠，如果不在，前面必须带上你的目录比如
```bash
unzip /storage/emulated/0/ncestallerForTermux.zip
```
```bash
unzip ncestaller_ForTermux.zip && rm -rf ncestaller_ForTermux.zip && chmod 755 ncestaller && ./ncestaller installer ncestaller
```
<br>如果需要帮助可以优先查看helps.help,稍后会更新更多常见问题解答😌
<br>
- - -
也可以通过这里赞助..🥺

<img src="赞赏码.png" width="240">

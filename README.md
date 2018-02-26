# Meme-Fight
a html5 mutiplayer game
#游戏简介
![demo](https://raw.githubusercontent.com/guanyuxin/baogame/master/doc/demo.png)
###游戏目标:
	把其他人推下水
	使用道具消灭其他人
	have fun
	
#搭建服务器方法

```
git clone https://github.com/imudges00lipeiran/Meme-Fight
cd Heme-Fight
npm install
node app.js
```

3.打开http://localhost:8030  就可以开始游戏

4.把localhost替换成你的域名或者ip，然后分享给你的朋友，一起玩吧
#服务器管理

```
#启动参数：
node app.js [port=端口，默认8030] [code=管理员口令，默认admin] [room=房间数目，默认1]
```
http://localhost:port/admin  可以进入管理界面，需要localStorage中设置code=管理员口令，然后可以创建物品或者封禁用户ip

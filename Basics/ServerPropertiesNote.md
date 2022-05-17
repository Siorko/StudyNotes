# server.properties配置文件译文

!> server.properties文件是服务器的所有设置的文件  
 =  后面的为值  # 开头的为注释不影响配置运行  
  该配置文件修改后必须重启服务器才会生效。   

#Minecraft server properties  

#设置0不会禁用出生点保护，但会保护出生点的一个小方块。  
#设置为1，会保护3X3。设置为2，会保护5X5。3会保护7X7 以此类推      	
**spawn-protection=16**   
#tick的最大加载毫秒数（超过这个时间将判定服务器崩溃）  
**max-tick-time=60000**   
**server-name=Unknown Server**  
#本属性质用于自定义世界的生成。详见超平坦世界和自定义了解正确的设定及例子。  
**generator-settings=**  
#为true时以上一次玩游戏的模式进入，false以默认游戏模式进入   
**force-gamemode=false**	  
#是否生成地狱  
**allow-nether=true**  
#玩家第一次进入的模式 0生存1创造2冒险3旁观者	  
**gamemode=0**	  
#实体游戏渲染距离（10~1000）	  
**broadcast-console-to-ops=true**	
#是否允许启用GameSpy4协议的服务器监听器	  
**enable-query=false**	  
#设置服务器将在玩家的空闲时间达到多少时间（单位：分钟）时将玩家踢出服务器（为0时不会启动这个选项）	  
**player-idle-timeout=0**	  
#游戏难度 0和平 1简单 2普通 3困难	  
**difficulty=1**	  
#是否生成怪物	  
**spawn-monsters=true**	  
#设定使用/op命令时OP的权限等级。所有存档会从之前的存档继承能力和命令。	  
1 - OP可以绕过重生点保护。	  
2 - OP可以使用所有单人游戏作弊命令(除了/publish，因为不能在服务器上使用；/debug也是)并使用命令方块。命令方块和领域服服主/管理员有此等级权限。	  
3 - OP可以使用大多数多人游戏中独有的命令，包括 /debug，以及管理玩家的命令(/ban，/op等等)。	  
4 - OP可以使用所有命令，包括 /stop, /save-all, /save-on 和 /save-off。	  
**op-permission-level=4**	  
#是否开启PVP	  
**pvp=true**	  
**snooper-enabled=true**	  
#是否允许服务端定期发送统计数据到http://snoop.minecraft.net 	  
#地图默认类型 Default=默认，FLAT=超平坦，LARGEBIOMES=巨型生物群系	  
**level-type=DEFAULT**	  
#自动开启困难模式 死后变观察者	  
**hardcore=false**	  
#是否启动命令方块	  
**enable-command-block=false**	  
#玩家最大在线量	  
**max-players=20**	   
**network-compression-threshold=256** 	 
#资源包的SHA-1值	  
**resource-pack-sha1=**  	
#设置可让世界边界获得的最大半径值，单位为方块	  
**max-world-size=29999984**	   
#服务器端口(25565为默认端口，联机时无需输入)	  
**server-port=25565**	  
#服务器的IP	  
**server-ip=**	  
#是否生成NPC	  
**spawn-npcs=true**	  
#是否允许飞行	  
**allow-flight=false**	   
#地图文件夹名称	   
**level-name=world**	  
#可视距离(是以玩家为中心的半径)	   
**view-distance=10**	  
**resource-pack=**	   
#是否生成动物	   
**spawn-animals=true**	   
#是否生成白名单，没有白名单的服务器自动拒绝	  
**white-list=false**	  
#是否生成建筑物(包括村庄和地牢)	  
**generate-structures=true**	 
#是否开启正版验证	  
**online-mode=true**	 
#最大建筑高度，最大256	   
**max-build-height=256**	  
#地图种子，在生成地图之前填入	  
#可生成特定的地图，例子：minecraft，404，1a2b3c	  
**level-seed=**	  
#是否禁止使用加速器的玩家加入服务器（true为禁止，false为允许）	  
**prevent-proxy-connections=false**	  
#是否开启远程访问服务器控制台。技术人员可选。	  
**enable-rcon=false**	  
#服务器欢迎信息(显示在玩家联机页面)，中文需中文补丁支持和转码，推荐EmEditor文本编辑器，自带转码功能	  
**motd=A Minecraft Server**	  




# Small_qq ( 持续完善中 )
* 作者: Lin-R

##意愿
* 通过自己粗糙的Code去尝试实现QQ机器人底稿!
* 希望能够让更多的喜欢Python,喜欢尝试的朋友可以对此底稿进行个性化的设计
* 欢迎一起完善机器人! 

##使用步骤
* 1.执行run.py, 然后打开config/qrcode.png 进行扫码登录

##已实现的功能
* 1.能够收发私人消息和群消息, 讨论组消息尚未完善
* 2.能够将多个群合并到一起,通过机器人,将消息发送到另外在列表的群
  * 打开广播开关:  
  
  [Control]  

  open_groupborad=1  
  
  config/main.conf  
  
  
  * 配置广播群列表
  `[Boradcast]
  name1='test2'
  name2='TestTest`
 

* 3.扩展功能库放在extends目录, 现在已接入功能有
  * [Function] only support:
  * 1.#learn# 关键字 需要记录的内容
  * 2.#use# 关键字
  * 3.#show# 
  * 4.#weather# 中国市级城市名





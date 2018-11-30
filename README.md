# API_ML_AI
Final project product requirements


|         |            |
| ------------- |:-------------:|
| Target release     | 未定 |
| Epic      |  植物识别与类似植物推荐   |
| Document status | 已开始      |
| Designer        | 靳诗雅 |
| Developer       | 靳诗雅 |
| QA | 靳诗雅  |


## Goals
* 随时随地，拿起手机，满足用户想要知道植物名称、鲜花花语名字的好奇心，让你轻松变身植物专家。
* 并通过查询得到的结果，找寻到相关植物介绍.
* 能“知道更多”，在识别眼前植物的同时，并将获得类似植物的推荐信息.


## Background and strategic fit
* 当我们从别处听到好听的音乐但不知道歌名时，我们会用音乐播放器等 APP 把歌名给识别出来，补充了许多遗憾，听到更多喜欢的音乐。而远足看风景或从一盆盆栽中偶遇美丽的植物、花朵，却不知道那到底是什么植物、什么花，有什么特质跟花语，也实在是件令人遗憾的事情。所以通过植物识别可以满足用户的好奇心，让你轻松变身植物专家.  
* 产品使用图像识别，用拍照就能检测出植物的品种.  
* 如果用户对类似植物感兴趣，可以点击“知道更多”来实现相关类似植物的介绍.


## Assumptions
* 用户使用该产品时，主要是在手机的环境下.  
* 用户上传的植物图片，可能会含有多种植物.  
* 可能会由于泛化能力弱，导致植物检测错误.  
* 主要是针对图片中最突出和数量最多的植物品种作为识别，并介绍该植物的名称、属性等信息。（如植物识别玫瑰，则介绍玫瑰花语、玫瑰种植需知等，希望可以推荐白玫瑰、蓝玫瑰等类似植物信息）


## Requirements
|    #     |    Title     |       User story     |      Importance     |      Notes     |
| ------------- |:-------------:|:-------------:|:-------------:|:-------------:|
| 1        |   输出植物名称后，想知道更多信息    | 需要点击知道更多 | Must Have |  |  
| 2        |   输出植物名称后，推荐类似植物植物    | 需要点击知道更多 | Must Have |  |  



## User interaction and design  
![Image text](./pro.jpg)


## Questions
|    Question     |       Outcome     |
| ------------- |:-------------:|
|   如何实现输出植物结果与地图的联系      |      |  
|   百度地图如何显示附近人识图环境      |      | 
|   如何实现识别植物的类似植物推荐      |      | 



## Not doing
* 推荐系统.  


### 效果图  
* [原型效果链接](https://kkrrystal2.github.io/prototype/)

![Image text](./pro.jpg)

### 功能
* 识别植物
* 介绍相关植物的信息（分享附近的人的识图环境，可以快速发现周边花卉，欣赏植物景点）  
* 针对主要植物信息作辨别（如植物识别为红玫瑰，则推荐其他白玫瑰、粉玫瑰、蓝玫瑰的信息）


### 用到的API
* 百度植物识别API  
* 百度地图API

### 已实现的功能  
* 可拍照识别植物  
* 可查看相关植物信息  
* 目前进度  

![Image text](./目前进度.gif)


### 待解决
* 植物和相关植物推荐不能实现联动    

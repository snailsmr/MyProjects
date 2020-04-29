### 专业技能  
1、	熟悉 Java 语言，掌握 Python 语言，熟悉常用数据结构，了解多线程、常用集合及部分底层源码实现。   
2、	熟悉掌握  Springboot  以及  MyBatis 框架，并有相关项目实践。了解 SSM、SpringCloud、Hadoop。    
3、	熟悉  MySQL  数据库，掌握Linux常用操作，了解  Redis  等非关系型数据库。  
4、	熟悉 Git、Maven、Idea、Postman 等工具的使用，具有 layUI+jQuery 等前端框架使用基础。   
5、	对 HTTP、TCP/IP 等网络协议知识有一定了解，具有 前后端分离 项目实践经验。   
6、	了解 ML 算法、个性化推荐系统  具备相关项目实践，具有开发  网络爬虫  、多人协作开发模式 的经验。    
7、	具有带领团队开发项目经验，乐于听取他人意见或建议, 擅长团队合作, 有较强的抗压能力。  

### 以下内容为本人项目详细介绍 
---
#### 项目预览：  
1.	高校科研项目管理系统 （2020.01-2020.03）
2.	智慧食堂 （2018.12-2019.02）
3.	快背单词 （2018.08-2019.03）
4.	E回声音乐APP个性化推荐系统 （2017.03-2018.05）
5.	学术论文《基于TF-IDF算法在协同过滤推荐算法的应用研究》（2018.11-2019.04）
6.	运用文本相似度实现（证券）智能客服系统 （2018.12-2019.03）
7.	智能型教育机器人——童乐 （2019.03-2019.05）  
8.	基于抽取式文本摘要提取的算法的新闻阅读系统 （2019.02-2019.03）  

--- 
#### 详细介绍：   

#### 一、高校科研项目管理系统  2020.01-2020.03   
***项目简介：*** 该项目主要完成了对高校科研项目的申报、评审等完整生命周期的流程控制和数据信息管理功能。系统在权限管理、信息统计分析模块具有一定的难点和亮点。采用前后端分离、B/S结构，MySQL数据库，后端主要使用了springboot+mybatis框架开发完成，前端采用了layUI+jQuery框架实现。本人独立完成了整个项目。  
***本人职责：***
1.	根据需求分析完成数据库设计、数据表的创建、SQL语句的优化。
2.	完成系统所有功能模块的前端页面的设计及实现，后端接口的编写及测试。
3.	完成新闻爬虫的开发、基于抽取式的文章摘要自动生成算法的搭建及实现。
4.	编写项目文档，完成对系统的日常维护。

---
#### 二、智慧食堂  2018.12-2019.02    
***项目简介：*** 该项目由学校牵头组建师生团队共同研发完成，现已投入运营使用。主要缓解了高校学生就餐时饭堂的同时容纳学生就餐数的压力。学生通过手机下单，食堂接单后进行配餐、配送至指定保温柜后，学生可远程开锁保温柜取餐。本项目软硬件结合，后端主要使用springboot框架搭建，硬件主要由树莓派控制，远程开锁使用了MQTT通信协议。本人在其中主要担任了开发组后端开发成员的角色。  
***本人职责：***
1.	参与项目二期需求讨论、食堂管理模块的二次开发。
2.	编写项目文档，完成对负责模块的日常维护。

---
#### 三、快背单词 2018.08-2019.03      
***项目简介：*** 该项目为校内创业团队作品，系一个英语单词背诵助记安卓APP，主要功能为提供用户滑块式记词的新型背单词交互方式，以及添加个性化背诵提醒功能。本人在其中主要担任了后端开发的角色。  
***本人职责：***
1. 完成所有英语词库的爬取（Python），主要使用了BeautifulSoup工具库，分析了必应词典网页结构，获取查词接口，间接爬取单词数据，并经过简单清洗后存入MySQL数据库。
2.	完成后端单词管理模块的接口编写及测试。

---
#### 四、E回声音乐APP个性化推荐系统  2017.03-2018.05     
***项目简介：*** 该项目为“大学生创新创业训练计划”，广东省，省级立项科研项目（已通过结题验收）。主要实现了类似网易云“每日推荐”的音乐推荐效果，载体为一个安卓APP。 推荐模型主要基于物品的协同过滤综合“歌词”、“歌手”、“歌名”三者权重搭建起来的综合模型。主要为JAVA实现，使用到了MySQL数据库、IK分词以及Mahout工具库。本人在其中主要担任算法开发、后端开发的角色。  
***本人职责：***
1.	完成个性化推荐系统基础知识储备，设计并实现推荐模型。
2.	完成后台音乐管理系统中音乐信息管理模块的接口编写及测试。
3.	编写项目文档，完成对负责模块的日常维护。

---
#### 五、学术论文《基于TF-IDF算法在协同过滤推荐算法的应用研究》  2018.11-2019.04    
***项目简介：*** 该论文为第十五届“挑战杯”广东大学生课外学术科技作品竞赛学术论文类三等奖作品。主要研究了个性化推荐系统中稀疏性问题，提出了从信息检索角度，计算目标用户的评分物品同时也“属于”其他用户的评分物品的可能性是多少，将可能性大的用户定义为目标用户的相似用户群，进而产生最后的推荐列表给目标用户的方案。并基于 MovieLens 数据集设计了对比实验。实验表明，本文提出的解决方案在 MRR 指标下的表现高于传统协同过滤算法在该指标中的表现。论文尚未发表，本人为论文第一作者。  
***本人职责：***
1.	查阅并研究相关文献、组织团队成员定期讨论。
2.	设计对比实验并进行代码实现。
3.	分析实验数据，与团队成员共同撰写论文。

---
#### 六、运用文本相似度实现（证券）智能客服系统  2018.12-2019.03   
***项目简介：*** 该项目主要完成了金融证券类客服的QA自动问答功能，当用户输入问题描述后，系统能识别到用户意图，并返回相关的标准问及标准答案链接列表给用户。此外，系统还拥有新闻资讯、企业介绍等功能。核心算法基于朴素贝叶斯模型搭建, 在其中，使用机器翻译等方式扩充了数据集，缓解了类不平衡的问题，模型最终F1值：0.85，项目部署于阿里云中。本人在其中主要担任算法开发、后端开发的角色。  
***本人职责：***
1.	完成核心算法的搭建及模型优化。
2.	完成服务端-算法模型-客户端三者之间的数据接口对接及调试。
3.	完成服务器的简单维护。

---
#### 七、智能型教育机器人——童乐  2019.03-2019.05    
***项目简介：*** 该项目为软硬件结合的NLP类项目，获得了第十六届“青牛杯”软件设计大赛二等奖。载体为一个卡通人物形象的公仔，具备与儿童聊天、背古诗、唱歌、讲故事的功能，可一定程度识别到儿童的语义并作出对应的回答。主要基于朴素贝叶斯模型综合余弦相似度，在进行文本清洗、向量化后计算出了QA对之间的相似度。本人在其中主要担任算法开发、后端开发的角色。  
***本人职责：***
1.	与队友共同完成数据清洗、算法设计、模型搭建。
2.	完成图灵机器人闲聊接口的接入。
3.	完成服务端-算法模型-客户端三者之间的数据接口对接及调试。
4.	完成服务器的简单维护。

---
#### 八、基于抽取式文本摘要提取的算法的新闻阅读系统  2019.02-2019.03  
***项目简介：*** 该项目为源于软件工程系学生党支部公众号开发需要。主要实现了国内外新闻模块的自动定时爬取，基于抽取式的摘要生成模块。首先对目标网页结构进行了分析，接着辅助以定时器使用BeautifulSoup工具库对新闻数据进行了爬取并定时更新，摘要提取算法基于MMR模型二次改造整合形成。呈现形式为公众号菜单点击跳转webAPP页面显示。系统前端为webAPP呈现，后端算法及爬虫为Python语言实现。本人在其中主要担任算法开发、后端开发的角色。  
***本人职责：***  
1.	完成了摘要生成算法的研究及整合实现。
2.	完成新闻爬虫的实现、维护。
3.	完成用户答题子模块的开发及维护。

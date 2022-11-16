## 设计框架  
<img src="https://cdn.jsdelivr.net/gh/zimaStrawer/doubleQ_Image/Elegami.png" width="80%">  

> ### 项目目的  

帮助K12群体学习电路知识
定位为交互立体书，每关教学一种电子元件，玩家通过与折纸机构交互解开谜题。
将电路中的元器件具象化为场景中的事物，依据教学的内容制定适合的场景。
（比如需要教“开关”—>桥和河流—>场景定义为“森林”）依次联想类推

> ### 背景设定  

主人公电次意外进入了一个异世界，当他解开所有的谜题，收集完钥匙碎片，才发现一切只是自己在科学课上做的一个梦。  

> ### 交互流程    

1. 玩家翻开一页立体书，关卡BGM启动（比如森林放莺啼燕语，工厂放机械轰鸣）
2. 在立体书上提示谜题所在处（以何种形式好？），玩家使用识别器识别，识别器播报谜题（比如“这里有一条河挡住了去路，该怎么办呢？”）
3. 玩家根据播报的谜题，开始解密
（解密卡住时，考虑下如何提示？）
4. 解密完成，解密成功音效启动，告诉玩家过关，最好有场景的互动（比如风车的旋转，灯塔的照明）  

> ### 技术细节  

1.翻开一页立体书——继续寻找关卡场景立体书展开方式；需要有背景音——BGM语音模组
2.识别器——已完成
3.玩家根据播报的谜题，开始解密——思考解密方式如何与所教学的元器件结合（重点）
4.解密成功音效启动——在每关下面嵌入主控，识别解密状态，控制场景互动  
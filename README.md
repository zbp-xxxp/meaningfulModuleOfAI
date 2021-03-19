# meaningfulModuleOfAI

Some AI projects based on paddlehub

## [驾驶员状态识别](https://github.com/zbp-xxxp/meaningfulModuleOfAI/tree/main/DriverStatusRecognition)

一般来讲，人在疲劳的时候会有比较典型的面部表情或动作特征，如较长的眨眼持续时间、较慢的眼睑运动、点头、打哈欠等。

基于摄像头的驾驶员监测方案正是利用这一点：首先挖掘出人在疲劳状态下的表情特征，然后将这些定性的表情特征进行量化，提取出面部特征点及特征指标作为判断依据，再结合实验数据总结出基于这些参数的识别方法，最后输入获取到的状态数据进行识别和判断。

根据CDC机动车安全部门的说法，五分之一的车祸 是由分心的驾驶员引起的。令人遗憾的是，每年因分心驾驶而导致的425,000人受伤和3,000人死亡。

希望能通过检测驾驶员的行为，从而改善上面这些令人震惊的统计数据，提醒驾驶员专心驾驶，减少交通事故的发生。

### 效果展示

#### 原图
<img src="/docs/imgs/Image_Classification_Drivers.png">

#### 输出结果
~~~
[{'category_id': 5, 'category': 'ch5', 'score': 0.47390476}]
[{'category_id': 2, 'category': 'ch2', 'score': 0.99997914}]
[{'category_id': 1, 'category': 'ch1', 'score': 0.99996376}]
~~~

## [海洋生物识别](https://github.com/zbp-xxxp/meaningfulModuleOfAI/tree/main/marine_biometrics)

海洋中的鱼类资源不仅有一定的食用价值，而且有很高的药用价值，近年来，世界各国对于海洋鱼类资源的重视程度与日俱增。在鱼类资源的开发利用中，必须对鱼类进行识别，从而了解其分布情况。但是由于鱼的种类繁多，形状大小相似，同时考虑到海底拍摄环境亮度低、场景模糊的实际情况，对鱼类资源的识别较为困难。

另一方面，全世界大约有两千万以观察海洋生物为目的的潜水者。在每次潜水结束后，大家谈论的主要话题总是观察到的动植物。但是像“刚才看见的那个叫什么？”这样的问题，答案总是无人知晓。因为在看到生物的那一刻，我们手边没有合适的工具帮助鉴别，而我们也没有扎实的生物和分类学知识基础。为弥补这一遗憾，海洋生物识别这一模型就应运而生了。

### 效果展示

#### 原图
<img src="/docs/imgs/Image_Classification_MarineBiometrics.png">

#### 输出结果
~~~
[{'category_id': 16, 'category': 'Plectroglyphidodon_dickii', 'score': 0.9932127}]
~~~

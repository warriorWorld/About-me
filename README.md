# About-me
An introduction about myself

Okay, in this repo, I will introduce my work experiences. For obvious reasons, my GitHub only includes my personal projects(I definitely cannot upload my companies' projects here, so all those projects I will not put project links here).

## Company projects
I've been working for three companies during my 8 years of working as an Android developer, I will describe them in an inverted order.

### 1, Roobo
![icon](https://zhengxin-pub.cdn.bcebos.com/brandpic/b8af51efce518f2745010d093f924f5d_fullsize.jpg?x-bce-process=image/resize,h_40,w_60)

This is an education company, it makes software for teaching children.

#### 1, Roobo AI teacher
This app is only available on specific devices, you can check it out by clicking [here](https://baijiahao.baidu.com/s?id=1756802320950561258&wfr=spider&for=pc).

This app is kind of like Siri, you can talk with it and it will answer you by voice. You can ask specific questions, such as how to write a Chinese word, and it will show you how by showing a gif, or you can ask the app to play a piece of music for you. Or you can just chat with it about everyday topics.

![AITeacher1](https://github.com/warriorWorld/About-me/blob/main/images/AITeacher1.jpg) ![AITeacher1](https://github.com/warriorWorld/About-me/blob/main/images/AITeacher2.jpg) ![AITeacher1](https://github.com/warriorWorld/About-me/blob/main/images/AITeacher3.jpg) 

##### Technical detail(if you are not interested, just ignore this part)
###### SDK Part
I developed an SDK for this app to use(we have other applications that also use this SDK which was developed by me), The SDK can deal with users' sound by using VAD(aka, Voice activity detection) technology to detect the active part of the sound, I denoise it, and then I call ASR(aka, Automatic Speech Recognition) interface in order to transfer the sound to text after I got the text, I send the text to our service, then our service will handle it with AI(chatGPT and my company's own AI, the service will determine use which one). And finally, the service will give me a response. And the SDK's job is done. (I developed all the parts of this SDK)
###### App Part
The app gets a response from the SDK and will handle the response according to specific rules because you know, there are several special feedbacks for users, just like the images showed, I handle this part by using RXJava. With a normal response, I just use the SDK to do TTS(aka, text to speech) for me and show the text to users(95% of this app's parts were developed by me).

#### 2, Roobo AI courses
This app is for children studying Chinese, English, art, mathematics, etc... You can learn more by clicking [here](http://activity.roobovip.com/#/mainEntry1).

This app actually has about a dozen types of little games built into it. Teachers can group videos and little games together in a console and they can configure those games according to courses. For example, they can configure a puzzle game in order to teach children art and configure a rhythm game in order to teach children music.

![AICourses](https://github.com/warriorWorld/About-me/blob/main/images/AICourses.webp)

##### Technical detail(if you are not interested, just ignore this part)
At first, we developed this app by using Flutter, but after the project became bigger and bigger. And also because the app mainly consisted of game-like features. As a result, we changed to Unity. I developed the video part and also developed several games for this project. For the video part, I used a third-party plugin for the video play, I mainly handled the gesture part of the video play. For the game part, I've developed a puzzle game, a rhythm game, a poem game, two exhibition games, a word pronunciation game, etc.

#### 3, Pudding robot
This is not an app but a robot, and it is based on Android. more info [here](https://baike.baidu.com/item/%E5%B8%83%E4%B8%81%E8%B1%86%E8%B1%86/20374641?fr=ge_ala)

I developed an SDK for other companies or whoever wants to control the robot, you can use the SDK to control the robot rotating, speaking, and sleeping. And you can use the SDK to manage the focus of the robot's hardware.
I also took the responsibility of maintaining several apps in that robot.

![Putting](https://github.com/warriorWorld/About-me/blob/main/images/Pudding.webp)


### 2, XianHuaHua(先花信息技术（北京）有限公司)

![icon](https://github.com/warriorWorld/About-me/blob/main/images/xianhuahua.png)

This company was a P2P company which means it provided loan and investment chances for users, and it has already gone broke.

#### 1, 先花一亿元（an app that you can borrow money from it）
I developed all the parts of this app(Android part), and this app had more than 10 million users.

![yyy](https://github.com/warriorWorld/About-me/blob/main/images/yyy.jpg)

#### 2, 花生米富（an app for lender to invest money）
I developed all the parts of this app(Android part),  and this app had more than hundreds of thousands of users.
![huashengmifu](https://github.com/warriorWorld/About-me/blob/main/images/huashengmifu1.jpg) ![huashengmifu](https://github.com/warriorWorld/About-me/blob/main/images/huashengmifu2.jpg) 


### 3, Kanglianda(康联达（北京）软件有限公司)

![icon](https://github.com/warriorWorld/About-me/blob/main/images/kanglianda.jpg)

This is a medical software company that mainly develops HIS(aka, Hospital Information System) applications.

#### 1, HIS(a medicine management application)

Hospitals use this application to manage their medicines and patients can also benefit from this, they can get their medicines more quickly and accurately. I developed this app all by myself(I mean during that time, I was still a novice and this app actually was very simple).

![medicine](https://github.com/warriorWorld/About-me/blob/main/images/medicine1.png) ![medicine](https://github.com/warriorWorld/About-me/blob/main/images/medicine2.png)


# About-me
An introduction about myself

Okay, in this repo, I will introduce my work experiences. For obvious reasons, my GitHub only includes my personal projects(I definitely cannot upload my companies' projects here, so all those company projects I will not put project links here).

## Company projects
I've been working for three companies during my 8 years of working as an Android developer, I will describe them in an inverted order.

### 1, Roobo
![icon](https://github.com/warriorWorld/About-me/blob/main/images/roobo.jpg)

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

![medicine](https://github.com/warriorWorld/About-me/blob/main/images/medicine1.jpg) ![medicine](https://github.com/warriorWorld/About-me/blob/main/images/medicine2.jpg)


## My Personal Projects

### 1, [Manga Reader](https://github.com/warriorWorld/MangaReader)
As the name suggested, it is an application for users to read mangas(in English), I developed this for myself to learn English, and it actually worked. Because of this, I expanded my vocabulary a lot.

![ss](https://github.com/warriorWorld/MangaReader/blob/master/app/screenshot/ss1.jpg) ![ss](https://github.com/warriorWorld/MangaReader/blob/master/app/screenshot/ss2.jpg) ![ss](https://github.com/warriorWorld/MangaReader/blob/master/app/screenshot/ss6.jpg)

##### Technical detail(if you are not interested, just ignore this part)
This app included a download feature, I used a thread pool to solve this. First, I would get all the image links, and then I would use a thread pool to execute the actual download threads. At every step, I would save its status, this guaranteed that if the process was interrupted, the app could still download the manga from the last point.

### 2, [To The Ground](https://github.com/warriorWorld/Shaft)
You can download this game on [Google Play](https://play.google.com/store/apps/details?id=com.harbinger.shaft)

I used Unity to develop this game, the game's target is to reach the final floor. In the game, it has 9 characters, all those characters have their own special ability. For example, the Spider can shoot a thread, the Time can stop time, and the Space can flash.

If you want to watch a [video](https://www.youtube.com/shorts/Tpv-56QXmFk) of this game, please click the image down here.

[![Watch the video](https://github.com/warriorWorld/Shaft/blob/master/screenshots/TTGSS1.jpg)](https://www.youtube.com/shorts/Tpv-56QXmFk)

When you arrive on the 100 floor, your character's ability will change permanently.

### 3, [Video Crawler](https://github.com/warriorWorld/VideoCrawler)
This is a video player, I created this app in order to learn English by watching videos, so, it makes sense that this app has a translation feature. In this app, I used Google's video player, I mainly handled the gestures of users, and I made the app very easy to use.

![github](https://github.com/warriorWorld/VideoCrawler/blob/master/app/screenshot/video.jpg) 

### 4, [A Keyboard](https://github.com/warriorWorld/StyleLibrary)
I developed this keyboard in order to use it on my "My Word" and "Manga Reader" projects. This keyboard will not guess what you want to input, it makes sense when you want a keyboard that will be used in a word cards application. In addition, this keyboard is very easy to use, you can slide your finger in order to select a letter. It has a vertical version and a horizontal version.

![ss](https://github.com/warriorWorld/MangaReader/blob/master/app/screenshot/ss5.jpg) 

On this vertical version of this keyboard, you select the letter by sliding your finger from 4 or 3 directions.

![github](https://github.com/warriorWorld/VideoCrawler/blob/master/app/screenshot/translate1.jpg) 

### 5, [Book Reader](https://github.com/warriorWorld/StrangerBookReader)
I developed this app for me to learn English(again) by you know, reading books. It supports TXT and PDF.

![ss](https://github.com/warriorWorld/StrangerBookReader/blob/master/app/screenshot/translate.jpg) ![ss](https://github.com/warriorWorld/StrangerBookReader/blob/master/app/screenshot/read.jpg)

### 6, [Puzzle](https://github.com/warriorWorld/Puzzle)
This is a puzzle game, I developed this while I was learning Unity. You can take a photo, and then my puzzle game can turn it into a puzzle.

### 7, [Parrot](https://github.com/warriorWorld/Parrot)
The Parrot is a parrot, it can repeat what you said, actually, it can detect your voice and then record it, and play it, that is all. I use this to improve my English speaking, you know, I can hear what I said and then I can correct myself.

### 8, [Word Cards](https://github.com/warriorWorld/MyWord)
I developed this for my TOEFL examination, it worked very well.

### 9, [A Browser](https://github.com/warriorWorld/ForeignNews)
This is a browser, just a browser, except you can translate a single word instead of the entire article. I also used this to learn English, you know, if you translated the entire article for yourself, it will not help you to improve your vocabulary.

### 10, [Touch Proof](https://github.com/warriorWorld/TouchProof)
Sometimes, you want to hear a video rather than watch a video, and you put your phone in your pocket, but this will produce some unexpected touches. That is why I developed this app(I know YouTube provides a service for this, but it charges me a fee).
I did this by covering the entire screen. First, you click the icon twice, it will cover your entire screen, and you have to click twice after a long touch on this screen in order to unlock the screen. This prevented those unexpected touches.

### 11, [Cover](https://github.com/warriorWorld/Cover)
In order to learn English, sometimes I need to block the video's subtitles. I developed this app for this purpose, you can adjust the cover's position and size, and it will remember your config.

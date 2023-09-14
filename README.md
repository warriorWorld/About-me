# About-me
An introduction about myself

Okay, in this repo, I will introduce my work experiences. For obvious reasons, my GitHub only includes my personal projects(I definitely cannot upload my companies' projects here, so all those projects I will not put project links here).

## Company projects
I've been working for three companies during my 8 years of working as an Android developer, I will describe them in an inverted order.

### Roobo 
![icon](https://zhengxin-pub.cdn.bcebos.com/brandpic/b8af51efce518f2745010d093f924f5d_fullsize.jpg?x-bce-process=image/resize,h_40,w_60)
#### Roobo AI teacher
This app is only available on specific devices, you can check it out by clicking [here](https://baijiahao.baidu.com/s?id=1756802320950561258&wfr=spider&for=pc).

This app is kind of like Siri, you can talk with it and it will answer you by voice. You can ask specific questions, such as how to write a Chinese word, and it will show you how by showing a gif, or you can ask the app to play a piece of music for you. Or you can just chat with it about everyday topics.

![AITeacher1](https://github.com/warriorWorld/About-me/blob/main/images/AITeacher1.jpg) ![AITeacher1](https://github.com/warriorWorld/About-me/blob/main/images/AITeacher2.jpg) ![AITeacher1](https://github.com/warriorWorld/About-me/blob/main/images/AITeacher3.jpg) 

##### Technical detail(if you are not interested, just ignore this part)
###### SDK Part
I developed an SDK for this app to use(we have other applications that also use this SDK which was developed by me), The SDK can deal with users' sound by using VAD(aka, Voice activity detection) technology to detect the active part of the sound, I denoise it, and then I call ASR(aka, Automatic Speech Recognition) interface in order to transfer the sound to text after I got the text, I send the text to our service, then our service will handle it with AI(chatGPT and my company's own AI, the service will determine use which one). And finally, the service will give me a response. And the SDK's job is done. (I developed all the parts of this SDK)
###### App Part
The app gets a response from the SDK and will handle the response according to specific rules because you know, there are several special feedbacks for users, just like the images showed, I handle this part by using RXJava. With a normal response, I just use the SDK to do TTS(aka, text to speech) for me and show the text to users(95% of this app's parts were developed by me).

#### Roobo AI courses
This app is for children studying Chinese, English, art, mathematics, etc... You can learn more by clicking [here](http://activity.roobovip.com/#/mainEntry1).

This app actually has about a dozen types of little games built into it. Teachers can group videos and little games together in a console and they can configure those games according to courses. For example, they can configure a puzzle game in order to teach children art and configure a rhythm game in order to teach children music.

![AICourses](https://github.com/warriorWorld/About-me/blob/main/images/AICourses.webp)

##### Technical detail(if you are not interested, just ignore this part)
At first, we developed this app by using Flutter, but after the project became bigger and bigger. And also because the app mainly consisted of game-like features. As a result, we changed to Unity. I developed the video part and also developed several games for this project. For the video part, I used a third-party plugin for the video play, I mainly handled the gesture part of the video play. For the game part, I've developed a puzzle game, a rhythm game, a poem game, two exhibition games, a word pronunciation game, etc.


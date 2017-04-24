---
title: CV
layout: resume
addr: cv.en
---

<!-- todo при составлении используй графы требования и плюсы с этих страниц -->
<!-- советы https://habrahabr.ru/post/184372/-->
<!-- советы https://habrahabr.ru/post/285608/-->

# Aleksey Titov
Computer Science, Math, Robotics & Game Development

## Contact information
**Email:** staffofmousecorp@gmail.com  
**Tel:** +7 961 685 82-18  
**Site:** [https://letsplaynow.github.io/](https://letsplaynow.github.io/)

## Education
I am on 4'th year undergraduate in [VSTU](http://www.vstu.ru/) in the direction "Informatics and Computer Science".

## Skills
### Machine Learning
Completed 2 courses of specialization "Machine Learning and Data Analisys" on Coursera:
* [Математика и Python для анализа данных](https://www.coursera.org/account/accomplishments/certificate/UKUZDXDD3BGK)
* [Обучение на размеченных данных](https://www.coursera.org/account/accomplishments/certificate/CXM3FL3SGHAK)

Familiar with basic models, methods и features of machine learning "with teacher".    
I work with Python & scikit-learn.

### Computer Vision
I Worked with the [Stereo Matching method](http://skillcounter.blogspot.ru/2015/08/point-cloud-from-pair-of-images-with.html).   
I came to the conclusion that, this method is quite demanding to cameras quality and environment.  
Now I am working for autonomous robot navigation based on SLAM algorithms and RGB-D camera. 

### Math & Algorithms
At a good level familiar with the basic sections of higher mathematics.  
At the moment I am improving my knowledge on the training list from [ШАД'а](https://cache-mskm906.cdn.yandex.net/download.cdn.yandex.net/shad/post_program_school.pdf).  
In my free time I solve olympiad problems.  
Also as far as I can take part in contests on [CodeForces](http://codeforces.com/profile/ResQ).

### Web
Well familiar with Ruby 2.2.4 & Rails 4.2.   
I wrote one big and very interesting project with Rails (check projects section).  
Also on the basic level is familiar with HTML5, CSS3 и JavaScript 5.

### System Programming
I work with 2 OS:  
**Windows 10**  
* From laboratory works some familiar with Win32 API.
* Wrote client-server apps.
* Wrote simple multithreaded (OpenMP) and multiprocess (MPI) applications.  

**Ubuntu 14.04**  
* On basic level familiar with Bash.
* I'm friends with the terminal.
* Wrote [my own sockets library](https://github.com/LetsPlayNow/TinySockets).

### Mobile apps programming
I have little experience of developing simple apps for Android with Java and for Windows Phone with C#.  

## Technical skills
### Languages
+ **C++**
  + **OpenCV**  
  Obtaining point clouds from one / two cameras using triangulation and optical flow.
  + **Point Cloud Library**  
  Point clouds processing. Mesh reconstruction from point cloud.
  + **ROS**  
  Developing of autonomous navigation system for anthropomorphic robot.    
  Planning of global trajectory for robot's movement using data from RGB-D sensor.
  + **OpenMP, MPI**  
  Familiar with basic parallelization methods using these frameworks.
  + **QT, STL**  
  I use it for GUI apps on C++ as needed.  
  The second one I use for solving olympic coding problems.
+ **Python**
  + **Numpy, matplotlib, skikit-learn, pandas**  
  Worked with them during the first 2 courses of specialization    
  "Machine Leaning And Data Analysis на Coursera"
  + **chatterbot, gTTS, SpeechRecognition**  
  I used these modules to write linguistic AI for robot (check projects section)

+ **Ruby 2.2.4**
  + **Rails 4.2.0**  
  I created Rails web app for competitions of a format Code Game Challenge (AI-Project).  
  Check details in a projects section below.
  
+ **JavaScript**
  + Familiar on basic level. I used this for visualization in AI-Project.
  
+ **Java, C#**
  + Familiar on basic level.
  Were used to write simple Android apps and GUI apps with WindowsForms library.
  
+ **C, ASM**
  + I use these two for programming STM32 & AVR controllers on laboratory works.  
  I enjoy electrical engineering with Arduino.
  
+ **Altera Quartus 9.1**
  + Was used on laboratory works to create logic schemes.    
  From the simplest to the most complex (my own CPU).     
  A bit familiar with VHDL. 

### Speach languages
**Русский** - my main language.  
**English** - I understand the text well, and use this language in my work, for writing articles & document code.
But my speech & listen skill are much lower. So I need some practice with them.  

## Some of my projects
You can see full list by [this link](https://github.com/LetsPlayNow?tab=repositories).
### AI - Project
![Game session](https://goo.gl/qDsgo2)

**Status:** partially finished  
**Technologies:** Ruby, Rails, HTML, CSS, JS   
**Description:** It is web app, which allows you to conquer in AI realization for your unit,   
who will fight with unit under control AI of your rival.  
Multiplayer with real players and solo game with bots are available.  
**Role in the project:** This project is completely designed and created by one person - me.  
At the beginning of this way, I know nothing about web development. Altrough I was very interested how other people make their cool and interesting web apps.  
In the process of project implementation I mastered Rails, HTML, CSS и JS & some web tricks.  
The project took a long time with all my perseverance.  
And in the end, I managed to bring it up to a decent view.   
**Links:**   
You can play by this link: [https://ai-project-new.herokuapp.com/](https://ai-project-new.herokuapp.com/)  
Code of this project is open and available by link: [https://github.com/LetsPlayNow/AI-Project](https://github.com/LetsPlayNow/AI-Project)


### Humanoid autonomous navigation
[![](https://habrastorage.org/files/922/ae4/9fe/922ae49fe1f24d779e5d5e116c24482a.png)](https://youtu.be/YXEq43HM_M8)

**Status:** in process  
**Technologies / skills:** ROS, C++, Research   
**Aim:** is to develop autonomous navigation system for anthropomorphic robot.     
**Description:** as SLAM-algorithm realization was choosed rtabmap on ROS and Kinect as data source.   
My own task is to process global trajectory for robot.   
I fixed bag in module footstrap_planner, which allow to build trajectory in form of sequence of foot steps of robot.   
And after I wrote additional module, I managed to run footstep planning based on obstacles map from rtabmap.  
Also sometimes I looking for good articles related with my work.   

### Speech for robot
**Status:** in process  
**Technologies:** Python  
**Aim:** is to create linguistic AI for robot.   
Robot must speak and more or less adequate to engage in dialogue.  
At this moment speech control for robot is done (commands "move", "stay", "silent" and others)  
Also robot can hold a simple conversation with someone.  
**Link:** [https://habrahabr.ru/post/323570/](https://habrahabr.ru/post/323570/)

## Interests
Lately, I decided to try TensorFlow and make some experiments with OpenCV 3 on Python 3.  
In my free time I solve olympic problems on CodeForces using Python or C++.  
I like implement complex algorithms.  
AI topic is close to me. I trying to find time to read book of Tim Jones "AI Application Programming".    

Also I like big 'must-have' books because of volume of qualitative knowledge I get from them.  
In my to-read list:
* Concrete mathematics
* Probabilistic Robotics
* Compilers: Principles, Techniques, and Tools aka 'Dragon book'
* Code complete (i have one at home)
* Cracking the code interview
* ∞

Also, whenever possible, I watch lectures and courses on topics of interest to me.  
For example, on Machine learning, Game Theory, Discrete Math and Linear Algebra.

And I try to find some time to make with my Orange PI,  
which is gathering dust in the closet, something interesting (first idea is "clever house").  

## Hobbies
I am advanced amateur bicyclist.

## Conferences
+ [XX Региональная конференция молодых исследователей Волгоградской области](http://www.vstu.ru/news/2015/12/22/nagrazhdenie-pobeditelei.html)
+ [Молодёжная  школа «Атмосфера:   встраиваемые системы и робототехника – 2015»](http://roboschool.org/participants) 
+ [V Московский международный форум «Открытые инновации»](https://forinnovations.ru/) 
  + [Статья на vstu.ru](http://www.vstu.ru/news/2016/10/26/tri-dnya-v-skolkovo.html)
+ [Skolkovo Robotics 2017](http://sk.ru/foundation/events/april2017/robotics/)
  + [Статья на vstu.ru](http://vstu.ru/university/press-center/news/nauka-i-innovatsii/shumnyy_uspekh_robota_iz_volggtu_v_skolkovo/)
  
<!-- TODO maybe bigger font -->
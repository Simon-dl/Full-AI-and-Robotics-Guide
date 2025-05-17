# Full-AI-and-Robotics-Guide
From no knowledge of math or programming to being able to do autonomous robots research

## Course path

This is mainly concerned with the software side of robotics with autonomous planning and control. I do not know of any mechatronics / mechanical engineer courses that can take people from no knowledge to very skilled, but I have not looked very hard either. If you make a path like this for the hardware side let me know and I can check it out and link it. This path is mainly for those that want to work on the intersection of robotics and AI.

This is what I believe to be the best path from knowing absolutely nothing other than grade school addition (and even that can be learned on khan academy) all the way up to research blending robotics and machine learning. 

While there is a lot of courses to potentially pick from the below is how to blend them all together into one cohesive path.   You should always do math + programming at the same time. Giving priority to math since that will be the main constraint on what you are able to study and understand. + means take concurrently.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### Start:

Do Khan Academy up through pre-calc, then move on. 

Start where you last remember being able to do math, when you get to high-school math do: algebra 1 -> geometry -> algebra 2 -> trig -> precalc


[Khan Academy](https://www.khanacademy.org/) + [Programming intro with Python](https://cs50.harvard.edu/python/2022/)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### Beginner

These courses will start to demand more of you, they are difficult and will ask you to tackle tough challenges. The most important thing you must learn when working on cognitively demanding tasks is to not give up, but to breathe and allow yourself time to think and understand the problem. If solutions are available the best way to learn is to do the problem all the way through until you get an answer you think is correct then to check the solution. if you got it correct thing about how you could have done it better / faster, if you got it wrong look for what caused you to follow incorrect logical paths or find the connections you missed.

Done in order.

[Calculus 1](https://math.berkeley.edu/~ogus/Math_1A/index.html) + [CS61A](https://cs61a.org/)

[Calculus 2](https://math.berkeley.edu/~hutching/teach/1b/) + [CS61B](https://sp25.datastructur.es/)

[Calculus 3](https://math.berkeley.edu/~pkoroteev/math53.html) + [CS61C](https://cs61c.org/sp25/)

Can get started in ros2 and play around with ros2 projects now. See ros2 projects section.

[Mechanical Physics](https://www.coursera.org/specializations/introduction-to-mechanics#courses) + [Linear Algebra](https://lin-lin.github.io/MATH54/)

[Differential Equations](https://www.coursera.org/learn/differential-equations-engineers) +

[CS70](https://www.eecs70.org/) + [Modern Robotics](https://www.coursera.org/specializations/modernrobotics#about)

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### Advanced

Even though the mathematics before were not easy this will still be a step up. Understand these concepts might take a while to set in and for concepts to become even harder to grasp and that’s okay. Perseverance is your best and most important friend here.

[Optimization 1](https://web.archive.org/web/20220818041300/https://stanford.edu/class/ee364a/index.html) + [C106A](https://ucb-ee106.github.io/eecs106a-fa23site/)  (Archived optimization course has homeworks)

[Optimization 2](https://stanford.edu/class/ee364b/index.html) + [C106B](https://pages.github.berkeley.edu/EECS-106/sp22-site/calendar/)

[Tao Analysis 1](https://www.amazon.com/Analysis-Third-Texts-Readings-Mathematics/dp/9380250649) + [Machine Learning](https://people.eecs.berkeley.edu/~jrs/189/)  (when you hit chapter 5 of Tao read Tao for the content but do the exercises of Rudin’s Principles of Mathematical Analysis, as those have solutions online)

[Tao Analysis 2](https://www.amazon.com/Analysis-2-Hindustan-Book-Agency/dp/8195196128/ref=sr_1_1?sr=8-1) + [Visual Navigation for Autonomous Vehicles](https://vnav.mit.edu/lectures.html)

[Tao Measure Theory](https://www.amazon.com/Introduction-Measure-Graduate-Studies-Mathematics/dp/1470466406/ref=sr_1_1?sr=8-1) + [Stanford Principles of Robot Autonomy 1](https://stanfordasl.github.io/PoRA-I/aa274a_aut2223/)

[Functional analysis](https://www.amazon.com/dp/8195196136)  + [Stanford Principles of Robot Autonomy 2](https://web.stanford.edu/class/cs237b/index.html)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### Very Advanced

[Theoretic probability theory primer](https://terrytao.wordpress.com/category/teaching/275a-probability-theory/)

[Theoretic probability theory](https://www.amazon.com/Probability-Martingales-Cambridge-Mathematical-Textbooks/dp/0521406056)  + [Berkeley Advanced Robotics](https://people.eecs.berkeley.edu/~pabbeel/cs287-fa19/)

[Stochastic Calculus 1](https://link.springer.com/book/10.1007/978-3-319-62226-2) + [University of Washington Autonomous Robotics](https://courses.cs.washington.edu/courses/cse478/24wi/)

[Stochastic Methods for Data Analysis](https://onefishy.github.io/am207/) + [Deep learning](https://web.archive.org/web/20240321011832/https://inst.eecs.berkeley.edu/~cs182/sp23/)

[Reinforcement Learning](https://courses.cs.washington.edu/courses/cse579/24au/) + [Deep unsupervised learning](https://sites.google.com/view/berkeley-cs294-158-sp24/home)

[Stochastic Calculus 2](https://www.amazon.com/Diffusions-Processes-Martingales-Cambridge-Mathematical/dp/0521775949/) + [Parallel Programming](https://youtu.be/F620ommtjqk)

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### Cutting Edge Research

Not putting anythign here since it is hard to know what will be relevant, but here are some robotics labs to keep an eye on. At this point you should be very much able to read and implement their research papers to test them out.

https://rl.uni-freiburg.de/publications

https://autonomousrobots.nl/research/

https://www.mmintlab.com/research/

https://robin-lab.cs.utexas.edu/publications/

https://www.physicalintelligence.company/

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### Ros2 and Robotics Projects

This is where the theory meets practice, over the course of your academic journey you should definitely be building robots and working on ros2 projects as some portion of your time. I really recommend working on them when you get burnt out doing academic exercises and want to work on something real and practical. Most of the coding will be done in C++ and Python, while I have no course on C++ you should be well equipt to find ways to fill in the gaps at this point. And remember just like learning anything getting comfortable with these projects and tools takes time and practice, but most importantly for these have fun and get creative.

Primer: 
https://youtu.be/8aoFndU7jos

**Getting started with ros2:**

I don’t really know of a good intro to ros2, so I would suggest dual booting ubuntu linux and doing the ros2 tutorial series, then doing the tutorial below.

https://github.com/henki-robotics/robotics_essentials_ros2?tab=readme-ov-file

From here pick a project and have fun, but I do highly recommend starting with articubot below


**More Beginner / Inexpensive**

Articubot
https://youtu.be/OWeLUSzxMsw

Robot arms
https://github.com/jess-moss/koch-v1-1

Two arms on a movable platform
https://github.com/Vector-Wangel/XLeRobot

**Advanced / More Expensive**

Robotic dog you can program
https://voltbro.gitbook.io/robot-sobaka-mors

Small humanoid robot, open source everything software and hardware.
https://lite.berkeley-humanoid.org/ 5k


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Wanted courses**

-A good intro to electronics course.
-A solid theoretic probability course with lectures.

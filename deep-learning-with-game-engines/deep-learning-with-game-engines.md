# Deep Learning with Game Engines: A Self-Driven Course
![Deep Learning with Game Engines: A Self-Driven Course](images/title-image.jpg)
*Last updated: Dec 13, 2018*

## Latest Video Update:
[![Deep Learning with Game Engines | Intro!](http://img.youtube.com/vi/WoP53JJxZNc/0.jpg)](http://www.youtube.com/watch?v=WoP53JJxZNc "Deep Learning with Game Engines | Intro!")  
![Play on YouTube](../common/images/youtube_indicator_banner.jpg)
<!-- Uncomment this iframe instead if the interpreter supports YouTube embedding.
<iframe width="560" height="315" src="https://www.youtube.com/embed/WoP53JJxZNc" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> -->

*Okay, on to the post...*

# My Inspiration
I kicked off this year with Udacity's Deep Learning Nanodegree and got a fantastic, comprehensive introduction to deep learning. While I was taking the class, I discovered Daniel Bourke's [Self-Created AI Masters Degree](https://hackernoon.com/my-self-created-ai-masters-degree-ddc7aae92d0e) which details the courses he's taking on his path to becoming a deep learning developer, one of which was the Deep Learning Nanodegree. I thought the idea to share his journey was brilliant. It holds him accountable and provides inspiration for others.

Rather than take the same path as him, I've decided to create my own course that pairs my long-standing interest in game development and 3d modeling with my newly found interest in artificial intelligence. If this branch of AI interests you too, I hope my path can inspire you to create your own self-driven education.

This post will be a work in progress toward understanding how 3d tools like Unity, Unreal Engine, and Blender can be used to train deep neural networks. I came into this course with a unique combo of skills, so I'll offer some suggestions for anyone who wants to follow along but doesn't have the same foundation.

# My Goals
1. Learn high level, cutting edge, practical deep learning skills and use game engine environments to train them  
    - My focus will be on utilizing and tweaking existing deep neural nets rather than inventing new ones. I'm not really interested in the underlying theory and math at this point, so I'm going to leave that to other researchers and hope they continue open-sourcing their work.
2. Spend more time on projects than courses
    - Practice is essential. I've found that projects solidify my knowledge and help me progress more quickly. Once I learn the fundamentals, I don't want to waste any more time taking redundant coursework.
3. Share and inspire others
    - I can't express how grateful I am to people who share their knowledge and experiences. By sharing my progress I can pay it forward and build proof of my experience. It's been said that GitHub is the new resume, and I think mine could use more work!

# Why Game Engines?
> "Training successful deep-learning algorithms requires computing power, technical talent, and lots of data. But of those three, it is the volume of data that will be the most important going forward." - **Kai-Fu Lee, AI Superpowers: China, Silicon Valley, and the New World Order**

If as Kai-Fu Lee says, data is the most important thing, we need a lot of it. Currently, most image and video datasets are annotated by hand. This process is tedious, expensive in large quantities, and error-prone. The most promising alternative is something I've blogged about: [Synthetic Datasets for Training AI](http://www.immersivelimit.com/blog/synthetic-datasets-for-training-ai). Put simply, we can create training data from 3d simulations.

Game engines like Unreal Engine and Unity are amazing tools for creating lifelike simulations of the real world. As opposed to the real world, they can allow neural networks to learn in cheap, safe, controllable, repeatable environments with infinite situations, impressive graphics, and realistic physics.

Autonomous cars are a great example: If a car crashes during training, it costs time, money, and potentially human lives. Even if crashes are avoided by human intervention, it's not possible to practice dangerous situations in a safe way for humans inside or outside of the vehicle. If a car crashes in simulation, it can either start over, or learn to safely pull the car off to the side of the road. It can also practice as many times as it needs to. Not surprisingly, the big players in autonomous vehicles (Tesla, GM, etc.) are hiring game engine developers to build realistic training simulations.

The CARLA simulator, built on Unreal Engine, is a great example of how a game engine can be used to teach cars to drive. Check out the video:  
[![CARLA: An Open Urban Driving Simulator](http://img.youtube.com/vi/Hp8Dz-Zek2E/0.jpg)](http://www.youtube.com/watch?v=Hp8Dz-Zek2E "CARLA: An Open Urban Driving Simulator")  
![Play on YouTube](../common/images/youtube_indicator_banner.jpg)
<!-- Uncomment this iframe instead if the interpreter supports YouTube embedding.
<iframe width="560" height="315" src="https://www.youtube.com/embed/Hp8Dz-Zek2E" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> -->

In addition to autonomous vehicles, game engines are being used to train robots and drones. Check out this video of Microsoft AirSim, which can simulate drone flight in Unreal Engine:  
[![AirSim Demo](http://img.youtube.com/vi/-WfTr1-OBGQ/0.jpg)](http://www.youtube.com/watch?v=-WfTr1-OBGQ "AirSim Demo")  
![Play on YouTube](../common/images/youtube_indicator_banner.jpg)
<!-- Uncomment this iframe instead if the interpreter supports YouTube embedding.
<iframe width="560" height="315" src="https://www.youtube.com/embed/-WfTr1-OBGQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> -->

I imagine in the near future, we will also see game engine applications in lifelike human simulation (for digital assistants, movies, and video games), [3d reconstructions of real places](https://ai.intel.com/fake-it-till-you-make-it-synthetic-datasets-assisting-machine-learning-in-data-scarce-environments/), augmented reality and mixed reality, intelligent adversaries in video games, and lots of other places.

Personally, I think the intersection of game engines and deep learning is going to be massive. These skills will be extremely valuable, so I'm trying to dive in early. It's also a ton of fun and very satisfying to build interactive virtual worlds with game engines. Have I sold you on this yet?! Join me and let me know how your learning is progressing!

# A Quick Bit About Me
I live in Austin, Texas with my wife. I enjoy eating Mexican food and drinking tequila with friends. I love video games, fantasy novels, board games, electronic dance music, and hot sunny weather.

Professionally, I'm a software engineer working primarily in AI and VR. CS degree from Michigan. Formerly worked at Microsoft, currently work at GM. If you want more detail, check out my [LinkedIn](https://www.linkedin.com/in/arkelly12).

I've found that throughout life, the times when I'm happiest are when I'm deliberately, voraciously, learning something new that I can do with my computer. I discovered as a teenager that I could learn without any formal instruction with a combination of free tutorials and self-directed projects. At the time, I just wanted to make trance music with FL Studio to become a famous DJ and later wanted to make 3d models with 3ds Max and become a Pixar animator. I'm glad I went with Computer Science instead. The power of creation it affords is about as close to being a wizard that humans can get. (I did mention I like fantasy novels…)

Starting in 2015 I used the same tutorials + projects approach to learn VR development in Unity and then at the beginning of 2018 I set out to do the same thing with Deep Learning.

# My Curriculum
Below are the courses I've taken or plan to take. I'll update the list with progress and new additions as I go.

*Note: I already knew a lot before starting this course, some from college, some from my job, some from personal interest. I was very capable in Unity, C#, and Blender, and had strong debugging and problem solving skills from years of programming. See the "Suggested Curriculum for Beginners" section below for my recommendations if you aren't coming in with some (or all) of these skills.*

## Deep Learning
**[Completed]** [Udacity - Deep Learning Nanodegree](https://www.udacity.com/course/deep-learning-nanodegree--nd101) [$$]  
This course was incredible. I've not seen another course that surpasses it in depth and breadth. Compare the syllabus to anything out there and you'll see what I mean. I was fortunate that my company paid for this because it was relevant to my job. This course was my first intro to Python programming. Fortunately, since I am an experienced developer, I was able to pick it up as I went along, but if you are new to development, I'd strongly suggest you take a Python course first.

**[Started]** [freeCodeCamp - Deep Reinforcement Learning Course](https://simoninithomas.github.io/Deep_reinforcement_learning_Course/) [Free]  
This free course looks really cool. You train deep reinforcement learning algorithms to play old-school video games.

[OpenAI - Spinning Up](http://spinningup.openai.com/en/latest/) [Free]  
This looks like a really deep, comprehensive overview of Reinforcement Learning. It also looks to be a great intro to OpenAI Gym, which is one of the projects I wanted to work on.

## Game Engines
**[Completed]** [Udemy - Unreal Engine C++ Developer Course](https://www.udemy.com/unrealcourse/) [$]  
This course did a good job of introducing me to Unreal. It's a bit messy in places, but overall it covers so much, so thoroughly, that it's easy to recommend.

## Programming
**[Completed]** [Pluralsight - Learn How to Program with C++](https://app.pluralsight.com/library/courses/learn-programming-cplusplus/table-of-contents) [$]  
**[Started]** [Pluralsight - C++ Fundamentals Including C++ 17](https://app.pluralsight.com/library/courses/cplusplus-fundamentals-c17/table-of-contents) [$]  
I was pretty rusty on C++, though I did learn it in college. These courses helped refresh me on the basics and get me up to speed on the more modern changes that happened to the language since I graduated. C++ is the language used by Unreal Engine, so I wanted to have a strong foundation.

## Robotics
**[Completed]** [ROS - Robot Operating System Tutorials](http://wiki.ros.org/ROS/Tutorials) [Free]  
I learned ROS for a project at work, but it's certainly relevant here. Robotics is already using 3d simulation for training purposes, in particular with Gazebo. It's a natural progression to use high powered game engines like Unreal Engine and Unity for training as these robots use more powerful computer vision.

## 3d Modeling
**[Started]** [Hard Surface Modeling in Blender](https://blendermarket.com/products/hard-surface-modeling-in-blender) [$]  
I started this fast-paced, advanced course more for fun than necessity, but I think it will really boost my 3d modeling skills. I spent a lot of time learning the basics of Blender on YouTube (years ago) before diving into this one.

# Suggested Curriculum for Beginners
## Mathematics
[Khan Academy - Math](https://www.khanacademy.org/math) [Free]  
My wife is currently learning to program for the first time. She quickly realized that her math skills were pretty rusty and that it was making the Python course she was taking extra difficult. Khan Academy has been a big help.

## Programming
[Udemy - Modern Python 3 Bootcamp](https://www.udemy.com/the-modern-python3-bootcamp/) [$]
This is the intro programming class my wife is taking. I picked it out because I liked the instructor and the syllabus.

[Microsoft Virtual Academy - C# Fundamentals for Absolute Beginners](https://mva.microsoft.com/en-us/training-courses/c-fundamentals-for-absolute-beginners-16169) [Free]  
[Microsoft Virtual Academy - Programming in C# Jump Start](https://mva.microsoft.com/en-US/training-courses/programming-in-c-jump-start-14254) [Free]  
These free courses appear to be a good intro to C#, which essential for Unity. I'd recommend you get comfortable with it so that you can write quality code.

## Game Engines
[Udemy - Complete C# Unity Developer 3D Course](https://www.udemy.com/unitycourse2/) [$]  
I started learning Unity from a book (that's out of date now) and YouTube tutorials, but this looks like a good intro course to get you up and running.

## 3d Modeling
[BlenderGuru - Blender Beginning Tutorial Series](https://www.youtube.com/watch?v=VT5oZndzj68&list=PLjEaoINr3zgHs8uzT3yqe4iHGfkCmMJ0P) [Free]  
[BlenderGuru - Intermediate Blender Tutorial Series](https://www.youtube.com/watch?v=yi87Dap_WOc&list=PLjEaoINr3zgHJVJF3T3CFUAZ6z11jKg6a) [Free]  
I've been playing around with Blender for 3d modeling for a couple years and I find it's almost as good as the applications that cost thousands of dollars, but is completely open source and free. If you are new to 3d modeling, there's a wealth of free material out there to learn on YouTube. The links above are from Andrew Price, aka BlenderGuru. I think he does a great job and am a big fan of his tutorials.

# Projects
Nothing beats practice to help solidify knowledge, stretch you beyond the learning material, and build confidence. Projects are a critical part of learning anything new and I intend to spend the majority of my time on them. Also, by sharing projects publicly, you can prove that you know what you're doing a hell of a lot better than most certificates. 

As part of my projects, I like to create tutorials for other people to follow in my footsteps. I believe teaching what I've learned really helps me lock in what I've learned. You can see what I've shared on the Tutorials section of my website:
[Immersive Limit - All Tutorials](http://www.immersivelimit.com/all-tutorials/)

## Projects Completed, Started, or Planned

### **[Completed]** [Mask R-CNN Cigarette Butt Detector](http://www.immersivelimit.com/blog/training-an-ai-to-recognize-cigarette-butts)
I trained a Mask R-CNN on a custom synthetic image dataset of cigarette butts. This didn't use any game engines, but it was a good intro to cutting edge image segmentation neural networks. It's not super practical to run these neural nets alongside game engines right now because of the sheer amount of graphics compute required, but I think we'll see a lot more of it in the coming years. I initially planned on using Blender to generate cigarette butt renders, but ended up using Python instead.

### **[Started]** Exploring Unity ML Agents
Unity has released an open source project called [ML Agents](https://github.com/Unity-Technologies/ml-agents), which is a framework for training Machine Learning agents (or characters) to navigate simple 3d worlds with neural networks. I'm currently working on training a pig agent to find truffles with stereo smell. Watching pigs spin and slide around has been pretty funny.

### Create a 2D Image Dataset with a Game Engine, then Train a CNN
There are some interesting examples of training image detection neural networks on rendered images. For example, [several research groups have used Grand Theft Auto 5](https://playing-for-benchmarks.org/overview/) to create training images. I'd like to create my own system to do this.

### Stream Live Video from a Game Engine to Real-time Deep Learning
Similar to the project above, but with imagery being processed in real time.

### Explore AirSim
Microsoft open sourced a project called [AirSim](https://github.com/Microsoft/AirSim) for training drones to fly and cars to drive with Unreal Engine. They have created several realistic environments for training and it even interfaces with flight controllers. I've fired it up to play with it, but haven't actually extended it with my own code yet.

### Explore OpenAI Gym
OpenAI has created [OpenAI Gym](https://gym.openai.com/) for training reinforcement learning algorithms and neural nets. I've had a little bit of exposure through the Udacity Deep Learning Nanodegree, but I want to explore it further.

### Explore OpenCV
[OpenCV](https://opencv.org/) continues to be the go-to framework for computer vision, especially on robots. Much of the library doesn't actually use deep learning, but it does have support for it. I've used it a bit and seen some neat projects done with it. I think that combining it with game engines would be a great experiment.

# Socialize
Another important aspect of becoming an expert in deep learning is getting involved with the community and meeting like minds. I've attended a couple local Austin AI meetups, joined some AI Facebook groups, and done a bit of reaching out through LinkedIn, but this is an area I need to put more effort into.

I probably need to tweet more.

Do you know of any great communities where people discuss deep learning? Let me know!

# Conclusion
This self-driven deep learning in game engines course is a work in progress and I hope it's helpful for others who want to go down a similar learning path. If you find any courses that you think I'd like, have other suggestions, or are just excited to follow along, please let me know! You can reach out to me at [@aktwelve on Twitter](https://twitter.com/aktwelve) or connect with me on [LinkedIn](https://www.linkedin.com/in/arkelly12).

## For future updates
- **Like** the [Immersive Limit Facebook Page](https://www.facebook.com/ImmersiveLimit/)
- **Subscribe** to the [Immersive Limit YouTube Channel](https://www.youtube.com/channel/UC1c0mDkk8R5sqhXO0mVJO3Q)
- **Follow** the [Immersive Limit Twitter](https://twitter.com/immersivelimit)  


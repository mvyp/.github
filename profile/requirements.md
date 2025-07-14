# 机器人技术入门与机器人中心考核要求

## 1 兴趣是最好的老师
大家可以都了解一下然后选择自己最感兴趣的方向。毕竟兴趣才是最好的老师。在如今人工智能为我们带来机器人技术的无限遐想，但机器人技术实际上遍布于各个领域，SLAM技术、机械臂抓取、人形与丝足、大模型赋予机器人的通用与泛化能力、无人机等等，建议大家先对上述各个技术进行了解。如下是一些在机器人入门阶段强烈建议阅读的指南、好文或者博客，相信在阅读过后，你会对机器人学有一个全新的认识。如果你发现你兴趣在此，你也必将成为未来真正赋予机器人实用性的工程师中的一份子。
* [机器人工程师学习计划](https://zhuanlan.zhihu.com/p/22266788)
* [具身智能：一场需要谦逊与耐心的科学远征](https://zhuanlan.zhihu.com/p/1909199500511260694)
* [Neal-博士前两年总结](https://www.bilibili.com/video/BV1neM1zKEmE/?spm_id_from=333.1387.homepage.video_card.click&vd_source=1f0d8e9830421a3c86871f4b5310f6f5)
* [具身智能入门指南](https://github.com/TianxingChen/Embodied-AI-Guide)
* [具身智能大模型简介]([https://zhuanlan.zhihu.com/p/22266788](https://www.bilibili.com/video/BV1QxB9YuERU?buvid=Y147691D6E19BBAC4CF391F1417ED53CA440&is_story_h5=false&mid=Y%2BfWEp2YxmLHi6nqBdFNdw%3D%3D&plat_id=116&share_from=ugc&share_medium=ipad&share_plat=ios&share_source=COPY&share_tag=s_i&timestamp=1733882221&unique_k=mKEvfgV&up_id=3493095748405551&vd_source=1f0d8e9830421a3c86871f4b5310f6f5))
* [机器人学习路线分享](https://www.bilibili.com/video/BV1eg411z7jM/?spm_id_from=333.337.search-card.all.click&vd_source=1f0d8e9830421a3c86871f4b5310f6f5)


## 2 考核方式
一份学习报告+视频+测试题
* 学习报告: 自己学习时的笔记，能够展示出学习后的水平。
* 视频: 你所完成的demo或者做过的小项目。
* 测试题: 请提供自己的答案和实现代码。
当然，因为学习时间有限，以上的内容哪怕第一项也不是那么轻松，不过我们仍希望大家能完成加粗的内容。

提交通道: 微信联系当届负责人


## 3 考核内容
ROS + 测试题 + 选其一: 导航/视觉/机械臂
### 2.1 ROS
ROS（Ubuntu 20.04）的安装、ROS 节点话题消息的理解、ROS 工作空间，功能包，launch 的使用等。

### 3.2 测试题
请在C++和Python 语言中任选一种语言作答</br>
**C++**:
* 指针的本质是什么？指针有何功能和优点？可以用代码片段或文字来解释。 
* “new”关键词的作用是什么，可以用代码片段或文字来解释。
* (编程题) 以下三题无标准答案，请尽量展示掌握的知识。请用C++代码实现以下题目：
    * 第一题: 首先输入一个整数n，然后输入 n 个整数，最后按照与输入相反的顺序输出这 n 个整数。
    * 第二题: 在 ROS 中实现 Subscriber 和 Publisher, 并实现 Subscriber 订阅 Publisher 的消息。请对其中的代码做注释。
    * 第三题: 实现一个“机器人"类，结合自己所学方向自行设计功能并展示。

**Python**:
* 在 Ubuntu 中使用 .py 文件第一行要加什么语句，为什么？
* 简述 Python 怎么实现并调用一个类。
* (编程题) 以下三题无标准答案，请尽量展示掌握的知识。请用Python代码实现以下题目：
    * 第一题: 首先输入一行字符串介绍一个人的名字和喜欢的饮料，请你输出人名字和饮料名字。例如输入一行字符串“My name is li hua and my favorite drink is orange juice.” 名字前会固定有一个"is"和"and"，饮料前后会固定有"is"和"."。 程序应能输出"li hua"和"orange juice"。
    * 第二题: 在 ROS 中实现 Subscriber 和 Publisher, 并实现 Subscriber 订阅 Publisher 的消息。请对其中的代码做注释。
    * 第三题: 实现一个“机器人"类，结合自己所学方向自行设计功能并展示。



### 3.3 导航/视觉/机械臂
* **导航**: 如 ROS 导航框架（move_base）和定位方法（amcl）的理解、***<u>在 Gazebo 中
进行小车导航的仿真</u>***、局部路径规划和全局路径规划的参数调整、规划方法的理解和代码的阅读。除此之外，机器人的导航与SLAM技术密不可分，针对于Robocup@Home比赛，可以优先了解Fast-lio激光lidar里程计算法，这或许会成为你阅读的第一篇论文。
* **视觉**: 如对机器视觉相关内容的掌握、***<u>YOLO/SAM/...</u>*** 的使用、训练数据集进行物体识别等。
* **机械臂**: ***<u>用 MoveIt 在仿真环境控制机械臂</u>***。建议实际操作Kinova 机械臂的仿真
[https://github.com/Kinovarobotics/kinova-ros.git](https://github.com/Kinovarobotics/kinova-ros.git)或者按照 MoveIt 官方教程[https://moveit.github.io/moveit_tutorials](https://moveit.github.io/moveit_tutorials/)在仿真中控制机械臂。



## 4 机器人技术路线补充
### 4.1 机器人学
上述中无论是ROS、Python亦或者其他，都是机器人中必不可少的工具链，掌握工具后的下一步便是通过对机器人理论的学习，了解必备的数学知识、控制原理，了解机器人的构建过程，涵盖感知、控制、建模，构建完整的感知-决策-控制闭环系统设计。
* [Modern Robotics](https://www.bilibili.com/video/BV1KV411Z7sC/?spm_id_from=333.1387.favlist.content.click&vd_source=1f0d8e9830421a3c86871f4b5310f6f5)
* [卡尔曼滤波器](https://www.bilibili.com/video/BV12D4y1S7fU/?spm_id_from=333.1387.favlist.content.click&vd_source=1f0d8e9830421a3c86871f4b5310f6f5)
* [自动控制原理](https://www.bilibili.com/video/BV1SE411Y7CK/?spm_id_from=333.1387.favlist.content.click&vd_source=1f0d8e9830421a3c86871f4b5310f6f5)
* [MPC控制原理](https://www.bilibili.com/video/BV1U54y1J7wh/?vd_source=1f0d8e9830421a3c86871f4b5310f6f5)
同时，**机器人仿真**也是必不可少的一部分，建议了解**Gazebo、Mujoco、Isaac**系列的仿真器和使用方法


### 4.2 神经网络在机器人中的应用
在如今AI赋予了人们极大期望的时代，神经网络在机器人领域迸发出极大的潜力，在上述的基础之外，对于AI在机器人当中的应用也显得格外重要和不可或缺。在第一部分兴趣中的**具身智能入门指南**里，提到了强化学习、模仿学习、Vision Language Model等等方面在机器人领域中的应用以及对应的推荐网站、教材，更多在此处就不多加复述了；pytorch暂时不是机器人中心考核的必备内容，但强烈建议你掌握它。并且可以尝试去复现一些基于强化学习的双足、四足机器人的仿真步态项目。


### 4.3 机械与嵌入式
上述的机器人理论更多依靠算法的支撑，除此之外，机器人是一门与世界物理交互的学科，因此机械和嵌入式也极为重要。我们中心也参与RoboMsater的比赛，机械和嵌入式更是RoboMaster比赛的核心。
* [RoboMaster电控入门](https://www.cnblogs.com/sasasatori/p/11582006.html)
* [RoboMaster电控教程](https://www.bilibili.com/video/BV1bz411e7RG/?vd_source=1f0d8e9830421a3c86871f4b5310f6f5)
* [DIJ RoboMaster社区](https://bbs.robomaster.com/)





# DHU-AILAB 自主飞行器项目组 暑期学习
---
### 2024/8/4更新
【中期项目】Projects  ddl:2024/8/18<br>
请各位同学在接下来2周内择一完成项目，有能力的同学可以都做一下。<br>
考虑到项目均有一定交叉，本次中期项目允许组队，每队1-2人。<br>
组队情况请于8月8日中午12:00前填写。<br>

![feec2cc52733c8ae80eea2f701621bbb](https://github.com/user-attachments/assets/2ae380b2-26ba-4379-9de2-6ecc18ca1536)

https://www.123pan.com/s/JMPqVv-rY6KA.html提取码:uwEi<br>
【中期项目】Projects.zip<br>
|<br>
├── 方向1<br>
│   ├── 2007.11898v2.pdf<br>
│   └── ORB_SLAM3-master.zip<br>
├── 方向2<br>
│   └── P2.zip<br>
└── 方向3<br>
    &emsp;&emsp;├── 20.04 仿真环境.docx<br>
    &emsp;&emsp;└── offboard.cpp<br>
<br>

### 2024/7/14更新
方向2 ROS补充资料

[【【古月居】古月·ROS入门21讲 | 一学就会的ROS机器人入门教程】]( https://www.bilibili.com/video/BV1zt411G7Vn/?share_source=copy_web&vd_source=0dcdde79b7dae0137ed24d4067111edf)


### 2024/7/9更新
1.资料下载链接可查看对应方向文件夹下txt<br><br>
2.请大家每周日晚24:00前提交周报到邮箱 --> hb.c678999@88.com<br>
邮件标题:22/23-[方向?]-[姓名]-第[?]周周报<br>
邮件内容：本周学习总结、代码运行截图、学习笔记等。。。内容格式均不限制<br>
注：7/8-7/14为第一周，以此类推。<br><br>
3.在学习过程中遇到任何问题，请在本仓库提交issues，我们会尽快解答的。<br><br>
4.需要注意的是，请每周按时提交周报。不接受补交，如有特殊情况在邮件中说明。

---
# 什么是自主飞行器：
[自主飞行器.pdf](自主飞行器简介.pdf) 
### 国内发展现状
[浙江大学 FAST-Lab 2021代表性研究成果](https://www.bilibili.com/video/BV1eq4y1F7EJ/?spm_id_from=333.999.0.0&vd_source=f85eb6ada6324b9c99a2057597d06c6b)<br>
[浙江大学 FAST-Lab 2022代表性研究成果](https://www.bilibili.com/video/BV1iY411X7ZC/?spm_id_from=333.999.0.0&vd_source=f85eb6ada6324b9c99a2057597d06c6b)<br>
[浙江大学 FAST-Lab FAR 课题组2023代表性研究成果](https://www.bilibili.com/video/av1900272364/?spm_id_from=333.999.0.0&vd_source=f85eb6ada6324b9c99a2057597d06c6b)<br>
[上海交大CIUS实验室 | 2021工作分享](https://www.bilibili.com/video/BV1CA411A7y2/?spm_id_from=333.999.0.0&vd_source=f85eb6ada6324b9c99a2057597d06c6b)<br>
[中山大学 STAR 课题组2023研究成果速览](https://www.bilibili.com/video/BV1CA4m1578H/?spm_id_from=333.337.search-card.all.click&vd_source=f85eb6ada6324b9c99a2057597d06c6b)<br>
[RACER: 多无人机协作快速探索 IEEE TRO Best Paper](https://www.bilibili.com/video/BV1ec411J7ps/?spm_id_from=333.337.search-card.all.click&vd_source=f85eb6ada6324b9c99a2057597d06c6b)
### 一些国内的比赛（大学生参加）
[大疆 无人飞行器智能感知技术竞赛｜2022 线下实体赛收官！](https://www.bilibili.com/video/BV1dg411J7Zb/?spm_id_from=333.337.search-card.all.click&vd_source=f85eb6ada6324b9c99a2057597d06c6b)<br>
[2023工程训练大赛智能无人机配送项目](https://www.bilibili.com/video/BV1K8411M7aV/?spm_id_from=333.337.search-card.all.click&vd_source=f85eb6ada6324b9c99a2057597d06c6b)<br>
[中国高校智能机器人创意大赛](https://www.bilibili.com/video/BV1q94y147PW/?spm_id_from=333.337.search-card.all.click&vd_source=f85eb6ada6324b9c99a2057597d06c6b)

# 目前成果：
### 部分视频
[自主定位+路径规划](https://www.bilibili.com/video/BV1pJ4m1T7uZ/?spm_id_from=333.999.0.0&vd_source=f85eb6ada6324b9c99a2057597d06c6b)<br>
[自主无人机投放](https://www.bilibili.com/video/BV16e4y1g7S4/?spm_id_from=333.999.0.0&vd_source=f85eb6ada6324b9c99a2057597d06c6b)
### 汇总：
- 学科竞赛获奖 国家级4项 上海市级3项 校级2项
- 大学生创新创业训练计划项目 国家级2项
- 国家发明专利 1项受理中
- EI会议论文 1篇发表
- 等等。。。

### 长远规划(TODO)
- [X] 激光雷达slam
- [X] 视觉slam
- [X] 路径规划
- [X] 无人机集群
- [X] 地空协同

# --------言归正传--------
## 学习方向（择一即可）
- [X] 方向1：视觉slam/激光雷达slam
- [X] 方向2：机器人操作系统ROS
- [X] 方向3：无人机动力系统及硬件电路
## 学习形式
以组长提供的学习资料自学为主。根据组长要求提交周报和参加假期结束后的项目验收，这些将同时作为人工智能创新实验室暑期招新的重要参考。
## 拟招收（专业不限）
- 22级 4人
- 23级 6人
- 24级 待定
## 前置基础（满足一项即可）
- 数学基础良好、认真踏实、持之以恒有上进心的同学优先考虑
- 掌握一门编程语言C、C++、Python
- 对嵌入式设备感兴趣（stm32、Arduino等等。。。）
以上条件适当放松
<br>
<br>
<br>
---
如有兴趣参加，请发邮件至 -->  haobin_chen@mail.dhu.edu.cn <br>
邮件标题：23/22-暑期学习-姓名-专业-方向X    例：22-暑期学习-张三-自动化-方向1,2<br>
邮件内容：个人介绍、个人特产、感兴趣的方向、有什么自己的想法... （请附上学期绩点）<br>
并扫码进群<br>


![alt text](QQ.jpg)


<br>
<br>
<br>
<br>

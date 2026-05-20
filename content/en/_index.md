---
# Leave the homepage title empty to use the site title
title:
type: home_index




# 实验室介绍
heroBlock:
  block: hero
  content:
    title: Autonomous Robots Lab@PKU <br> <br> 北京大学  自主机器人实验室
#   image:
#      filename: research_topic.jpg
    text: |

      **Welcome to the Autonomous Robots Lab (ARL) at Peking University, China.**

      **ARL** investigates problems related to the planning and perception of autonomous systems and intelligent robots. The lab combines expertise from robotics, control theory, machine learning, optimization, and cognitive science to develop theories and methodologies for single and multi-robot systems to reliably and efficiently operate in uncertain and dynamically changing environments.

      **Chang Liu** received the B.S. degrees in Electronic Information Science and Technology and in Mathematics and Applied Mathematics (double degree) from the Peking University, China, in 2011, and the M.S. degrees in Mechanical Engineering and in Computer Science, and the Ph.D. degree in Mechanical Engineering from the University of California, Berkeley, USA, in 2014, 2015, and 2017, respectively. He is currently an Assistant Professor with the School of Advanced Manufacturing and Robotics, Peking University. From 2017 to 2020, he was a Postdoctoral Associate with the Cornell University, USA. He has also worked for Ford Motor Company and NVIDIA Corporation on autonomous vehicles. His research interests include robot motion planning, active sensing, and multirobot collaboration.

      **刘畅**于 2011 年在北京大学获得电子信息科学与技术以及数学与应用数学双学士学位。随后，他分别于 2014 年、2015 年和 2017 年在美国加州大学伯克利分校获得机械工程和计算机科学硕士学位以及机械工程博士学位，2017 年至 2020 年，他担任美国康奈尔大学的博士后研究员，现于北京大学先进制造与机器人学院担任助理教授。他曾在福特汽车公司和英伟达公司从事自动驾驶相关工作。

      I am working on Motion Planning, Active Sensing, Distributed Filtering, and Human Robot Collaboration. I am recruiting Ph.D./Master Students and Research Assistants/Interns. If you are interested, please read the Recruiting page (top-right).

      实验室研究方向：**机器人运动规划、主动感知、分布式滤波和人机交互**。实验室常年招收硕博士生以及实习生，详情请阅读右上角招聘页面。

  



# 图片轮播  
heroSlideBlock:
  block: slider

  content:

    slides:

    - title:  ""
      content:  autonomous robots
      align: left
      background:
        image:
          filename: group_slides/s2.jpg
          filters:
            brightness: 1
        position: right
        color: '#666'  

    - title: ""
      content:  autonomous robots 2
      align: left
      background:
        image:
          filename: group_slides/s1.jpg
          filters:
            brightness: 1
        position: right
        color: '#666'  

  design:
    # Slide height is automatic unless you force a specific height (e.g. '400px')
    slide_height: '415px'
    is_fullscreen: false
    # Automatically transition through slides?
    loop: true
    # Duration of transition between slides (in ms)
    interval: 1000



# Recent works
recentWorksBlock:
  - img: recent_works/rw1.jpg
    desc: "The motivation of this work is to address the significant challenges of computationally demanding and safety-critical motion planning for large-scale robotic swarms navigating cluttered environments, which can be applied to missions including search and rescue, warehouse automation, and environmental exploration. "
    title: 
    link: recent-works/risk-aware
    
  - img: recent_works/rw2.jpg
    desc: "[CVPR'25 Oral] We propose Video-XL, a novel approach that leverages MLLMs’ inherent KV sparsification capacity to condense the visual input realizes outstanding cost-effectiveness, enabling high-quality processing of thousands of frames on a single A100 GPU."
    title: 
    link: 


  - img: recent_works/rw3.jpg
    desc: "[ICRA'25] We propose SpatialBot, a family of state-of-the-art VLMs, for effective depth understanding and thus precise robot manipulating in embodied AI by training on our constructed SpatialQA and SpatialQA-E datasets."
    title: 
    link: 

  - img: recent_works/rw4.jpg
    desc: "[ECCV'24] We introduces Omni6DPose, a substantial benchmark featured by its diversity in object categories, large scale, and variety in object materials, across 581 instances in 149 categories."
    title: 
    link: 

  - img: recent_works/rw5.jpg
    desc: "[NeurIPS'24 Spotlight] We propose a 3D foundation segmentation model, named SegVol, supporting universal and interactive volumetric medical image segmentation, supporting the segmentation of over 200 anatomical categories."
    title: 
    link: 

  - img: recent_works/rw6.jpg
    desc: "We introduce Emu3, a new suite of state-of-the-art multimodal models trained solely with next-token prediction. By tokenizing images, text, and videos into a discrete space, we train a single transformer from scratch on a mixture of multimodal sequences."
    title: 
    link: 







newsBlock:
  block: collection
  content:
    title: Latest News
    count: 5
    filters:
      author: ''
      category: ''
      exclude_featured: false
      publication_type: ''
      tag: ''
    offset: 0
    order: desc
    page_type: post
  design:
    view: card
    columns: '1'      




---  




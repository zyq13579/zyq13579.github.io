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

      **ARL** focuses on embodied AI and multi-robot collaboration in complex real-world environments. The lab develops intelligent decision-making and coordination algorithms that enable autonomous robots to robustly navigate, interact, and cooperate under uncertainty. Our research draws from robotics, machine learning, control theory, and optimization to advance embodied intelligence for both single-robot and multi-robot systems.

      Ph.D. and master’s students, as well as research assistants and interns, are being recruited. If you are interested, please read the Recruiting page (top-right).

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
  - img: recent_works/home-rw1.jpg
    desc: "[IEEE T-ASE’25]The motivation of this work is to address the significant challenges of computationally demanding and safety-critical motion planning for large-scale robotic swarms navigating cluttered environments, which can be applied to missions including search and rescue, warehouse automation, and environmental exploration. "
    title: 
    # link: recent-works/risk-aware
    link: https://ieeexplore.ieee.org/document/11313580
    
  - img: recent_works/home-rw2.png
    desc: "[IEEE TSMC: Systems’25] We propose ReSPIRe, which plans informative search-and-tracking trajectories by estimating belief-space information gain with sigma-point mutual-information approximation and accelerating online belief-tree search through hierarchical particles and reusable rollouts. "
    title: 
    link: https://ieeexplore.ieee.org/abstract/document/11293378


  - img: recent_works/home-rw3.png
    desc: "[IEEE RAM’25] We propose AINav, an LLM-based adaptive interactive navigation framework that combines primitive skill tree planning, RL-pretrained locomotion and interaction skills, and adaptive replanning to proactively modify cluttered environments and reach originally unreachable goals. "
    title: 
    link: https://ieeexplore.ieee.org/abstract/document/11313696

  - img: recent_works/home-rw4.png
    desc: "[ICML’24] VoroNav is a zero-shot object navigation (ZSON) framework that builds a Reduced Voronoi Graph from a real-time semantic map to extract traversable paths and intersection-based waypoints. It converts the topological structure into path descriptions and farsight descriptions (via BLIP image captioning), which an LLM (ChatGPT) uses with commonsense reasoning to select navigation waypoints. "
    title: 
    link: https://voro-nav.github.io/

  - img: recent_works/home-rw5.jpg
    desc: "[R-AL’24] We propose DOZE, a high-fidelity dataset for open-vocabulary zero-shot object navigation in dynamic environments, featuring 10 realistic 3D scenes and over 18K tasks. DOZE introduces moving humanoid obstacles, diverse open-vocabulary and attribute-varied target objects, scene-text hints, dynamic goal objects, and agent–moving-obstacle collision detection, enabling more realistic evaluation of navigation efficiency, safety, and object recognition in embodied AI."
    title: 
    link: https://doze-dataset.github.io/

  - img: recent_works/home-rw6.png
    desc: "[IROS’24] We propose SwarmPRM, a hierarchical, highly scalable, computationally efficient, and risk-aware sampling-based motion planning approach for swarm robots. At the macroscopic stage, the collective swarm is represented by a GMM. At the microscopic stage, individual robots track the GMM via a local tracking control law."
    title: 
    link: https://ieeexplore.ieee.org/document/10801905






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




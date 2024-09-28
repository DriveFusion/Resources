# Resources

Welcome to the **Resources** repository! This repository provides a curated collection of papers, datasets, tools, and notes, with a special focus on the integration of **Large Language Models (LLMs)** in autonomous driving systems.

## Contents

- **Papers**: Research papers on the application of LLMs in autonomous driving, as well as traditional topics like sensor fusion, object detection, trajectory prediction, and vehicle control.
  - Repo: [Awesome-LLM4AD](<https://github.com/Thinklab-SJTU/Awesome-LLM4AD>)
  - Repo: [End-to-end-Autonomous-Driving](<https://github.com/OpenDriveLab/End-to-end-Autonomous-Driving?tab=readme-ov-file>)
  - Repo: [Awesome-Multimodal-LLM-Autonomous-Driving](<https://github.com/IrohXu/Awesome-Multimodal-LLM-Autonomous-Driving>)
  - Repo: [Awesome-VLM-AD-ITS](<https://github.com/ge25nab/Awesome-VLM-AD-ITS?tab=readme-ov-file>)
  - Repo: [awesome-knowledge-driven-AD](<https://github.com/PJLab-ADG/awesome-knowledge-driven-AD?tab=readme-ov-file#dataset--benchmark>)
  - Repo: [Driving-with-LLMs](<https://github.com/wayveai/Driving-with-LLMs>)
  - Website (Contains Video): [DriveVLM](<https://tsinghua-mars-lab.github.io/DriveVLM/>)
  - Website: [Path planning algorithms in the autonomous driving system: A comprehensive review](<https://www.sciencedirect.com/science/article/pii/S0921889024000137>)
  - Masked Autoencoders (Lidar):
    - Repo: [Awesome-Masked-Autoencoders](<https://github.com/EdisonLeeeee/Awesome-Masked-Autoencoders?tab=readme-ov-file>)
- **Datasets**: A collection of datasets used for training models in areas such as perception, natural language understanding, and driving behavior prediction.
  - Repo: [Awesome-LLM4AD](<https://github.com/Thinklab-SJTU/Awesome-LLM4AD?tab=readme-ov-file#datasets>)
  - Repo: [awesome-autonomous-driving-datasets](<https://github.com/lhyfst/awesome-autonomous-driving-datasets>)
  - Repo: [Awesome-Multimodal-LLM-Autonomous-Driving](<https://github.com/IrohXu/Awesome-Multimodal-LLM-Autonomous-Driving?tab=readme-ov-file#datasets>)
  - Repo: [awesome-knowledge-driven-AD](<https://github.com/PJLab-ADG/awesome-knowledge-driven-AD?tab=readme-ov-file#dataset--benchmark>)
  - Repo: [Awesome-VLM-AD-ITS](<https://github.com/ge25nab/Awesome-VLM-AD-ITS?tab=readme-ov-file#-dataset>)
  - Website: [15-best-open-source-autonomous-driving-datasets](<https://medium.com/analytics-vidhya/15-best-open-source-autonomous-driving-datasets-34324676c8d7>)
  - Website: [Comprehensive Vision-Language-Action Dataset for Autonomous Driving](<https://arxiv.org/html/2408.10845v1>)
- **Tools & Techniques**: Software tools and frameworks to facilitate the use of LLMs.
- **Notes**: Summaries of research findings, insights on integrating LLMs into self-driving architectures, and discussions on the future of autonomous driving with AI.

## Project Plan

### There are 6 phases in this project:
1) Searching for datasets
2) Auto-labeling or manual labeling datasets **if needed**
3) Develop **`not from scratch`** and train MLLM model
    1) **Develop VLA model:** Make the LLM able to see general image, multi-image and videos (e.g. `SigLIP`, `SVFormer`)
    * In the next step we can add Lidar data to the model (e.g. `GD-MAE`)
    * Add Self-Discover method to make the model reason better
    2) **Perception and Understanding:** Make the model to be able to multi objects referring, 3D object detection and tracking
    3) **Navigation and Planning VLA model:** Make the model to be able to predict trajectory, motion planning and localization
    4) **Decision Making and Control:** Open-loop or Closed-loop decision making 
    5) **End-to-End Autonomous Driving:** Where the model can drive the car normaly
4) Integrating MLLM with existing autonomous driving system (e.g. Apollo, Autoware) **We may ignore this**
5) Testing and evaluating our system on simulators (e.g. CARLA)
6) Testing the system in real world



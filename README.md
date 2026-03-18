# Vision-Based-Autonomous-Cruise-Control-for-Unmanned-Vehicles
**Algorithm Elite Competition Project | Team Captain (Core Developer)**

Implemented a vision-based autonomous cruise system for unmanned vehicles. Integrated ROS framework, SLAM localization, TEB dynamic obstacle avoidance with Doubao large models for image feature extraction and speech synthesis, achieving high-precision path planning and intelligent autonomous navigation in competition scenarios.

---

## Project Highlights
- **Team Leadership**: As team captain, led a 3-member team in requirement analysis, task division, progress control, and technical decision-making, ensuring on-time project delivery.
- **Technical Innovation**: First introduced Doubao large models into UAV navigation system, enabling image semantic understanding and voice interaction to enhance system intelligence.
- **Performance Achievement**: Achieved over 95% positioning accuracy and 100% dynamic obstacle avoidance success rate in competition test scenarios, completing full autonomous cruise.
- **Full-stack Engineering**: Completed end-to-end development from algorithm simulation to real-device deployment, demonstrating comprehensive engineering practice capabilities.

## Core Technologies
- **Visual Perception**: Camera-based image acquisition for obstacle detection and scene semantic understanding.
- **Autonomous Localization**: SLAM technology for real-time UAV positioning and environment mapping.
- **Dynamic Obstacle Avoidance**: TEB (Timed Elastic Band) algorithm for real-time dynamic obstacle avoidance.
- **AI Interaction**: Doubao large models integration for image feature extraction and speech synthesis, supporting natural language command interaction.
- **System Framework**: ROS-based distributed architecture for modular decoupling and efficient communication.

## My Contributions
- **Team Management**: Coordinated project progress, divided modules (visual perception, localization navigation, AI interaction), and ensured cross-team collaboration.
- **Core Development**: Led implementation of SLAM localization and TEB obstacle avoidance algorithms, completed ROS core node development and system integration.
- **Technical Selection**: Decided to adopt Doubao large models, designed image extraction and speech synthesis interfaces to boost project competitiveness.
- **Competition Optimization**: Tuned algorithm parameters for competition scenarios, improved positioning accuracy and obstacle avoidance response speed.
- **Documentation & Presentation**: Prepared technical reports and demo documents, responsible for competition defense and result presentation.

## Run Instructions (Competition Version)
1. Environment Setup: Install ROS Noetic, OpenCV, and SLAM-related dependencies.
2. Project Deployment: Clone the repository into ROS workspace, run `catkin_make` for compilation.
3. Competition Launch: Execute `roslaunch competition main.launch` to load competition scene configuration.
4. Intelligent Interaction: Trigger cruise tasks via voice commands, system automatically completes path planning and obstacle avoidance.

## Project Value
This project validates the feasibility of combining visual navigation with large models in algorithm competition scenarios, demonstrating comprehensive abilities in **team management, algorithm design, system integration, and engineering deployment**, which can be directly applied to intelligent unmanned devices and autonomous driving fields.

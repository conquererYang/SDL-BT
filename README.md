# 🤖 Multi-Robot Coordination for Effective Anomaly Handling in Self-Driving Laboratories
## 🚀 Project Overview
<img width="475" height="288" alt="framework_high" src="https://github.com/user-attachments/assets/e173a318-d7fc-4f79-97f1-6f86fe57458a" />

In scientific laboratories, the complexity of experimental processes and high-precision equipment increase the likelihood of anomalies, which can compromise results and pose safety risks. This project addresses these challenges by implementing a **Multi-Robot Coordination Framework** specifically designed for effective anomaly handling in autonomous laboratory environments.

### 🔑 Key Contributions
- **Anomaly Detection and Handling Framework**: A comprehensive approach that emphasizes restoring standard workflows while maintaining reliability in laboratory settings.
- **Anomaly-Triggered Cross-Behavior Tree Extension Algorithm**: An innovative algorithm that activates upon detecting anomalies, which efficiently manages and localizes issues without extensive re-planning.
- **Comprehensive Experimentation and Validation**: Rigorous testing in both simulated and real environments demonstrates the framework's effectiveness in enhancing fault tolerance and flexibility during anomaly management.

### 📊 Anomaly Detection Data Set
Our framework is validated using our **Sdls Anomaly Detect** dataset（https://figshare.com/articles/dataset/sdls_anomaly_detect/29234663/1）, which includes a variety of scenarios and labeled anomalies commonly encountered in laboratory settings. For detailed methodologies and further reading, refer to the following foundational paper: 
- **Anomaly Detection in Robotics**: S. Lin, C. Wang, X. Ding, Y. Wang, B. Du, L. Song, C. Wang, and H. Liu, "A VLM-based Method for Visual Anomaly Detection in Robotic Scientific Laboratories," arXiv preprint arXiv:2506.05405, 2025.

### 🛠️ Methodology
Our framework leverages **Hierarchical Large Language Models (LLMs)** to facilitate intelligent task planning and actions, executing dynamic adjustments in real time. The **Cross-Behavior Tree Expansion Algorithm** effectively identifies and responds to common laboratory anomalies, thus ensuring smooth operation of multi-robot systems.
<img width="7680" height="4320" alt="Fig Methods" src="https://github.com/user-attachments/assets/d7f725b0-e733-4319-b315-076ba08b1a73" />

### 📹 Case Study Videos
Link: https://www.youtube.com/watch?v=OH60_Ew9avQ&list=PLIJnmuEVkn7JcBSICKHqBwTBSFjnzq4pN&pp=gAQB

We have conducted extensive case studies demonstrating the anomaly handling process through practical scenarios. The following videos display various anomaly situations encountered and how the framework responds:
- Video 1: Simulated silica gel 1 material shortage  
- Video 2: Simulated pigment shortages continue to increase
- Video 3: Cleaning robot cleans water stains
- Video 4: Simulated the test tube is missing, re-execute the action of taking the test tube
- Video 5: The test tube of the weighing instrument is missing and then put it back in 
- Video 6-1: Workbench robot0 straightens the mold on the mold plate
- Video 6-2: Workbench robot0 straightens the tray mold
- Video 6-3: Workbench robot0 re-rectifies the mold and puts it back on the tray
- Video 7: Workbench robot0 is interrupted when adding pigment to the test tube. Replace the test tube with a new one and add pigment again. 
### 📈 Conclusion
This research presents a novel framework for managing anomalies in multi-robot systems, paving the way for enhanced automation in scientific laboratories. Feel free to dive in, provide feedback, or contribute to enhancing anomaly handling strategies! 💡
### Authors
Yang Yang, Jiankun Yang, Haibo Lu, Ge Li, Huaping Liu, and Wen Gao, Fellow, IEEE

# GR56EC431-Proactive-Network-Congestion-Prediction-and-Mitigation-in-5G-Networks-using-Edge-AI

# Video Demonstration

Watch the demonstration here: [Proactive-Network-Congestion-Prediction-and-Mitigation-in-5G-Networks-using-Edge-AI](https://www.youtube.com/watch?v=yEhHeosH4YM&ab_channel=YASHKUMARSINGH)


## Overview
This project proposes a system for **proactive network congestion prediction and mitigation** in 5G networks, leveraging **Edge AI** for real-time analysis and decision-making. The approach addresses challenges in dynamic and complex 5G environments by predicting congestion events before they occur and taking preemptive measures to maintain optimal **Quality of Service (QoS)**.

### Key Features
- **Real-time Congestion Prediction**: Utilizes an LSTM-based model for analyzing traffic data and predicting potential congestion.
- **Edge AI Integration**: Enables low-latency decision-making at edge nodes.
- **Traffic Mitigation Strategies**: Includes dynamic resource allocation and traffic rerouting to reduce latency and enhance network reliability.
- **Simulation with NS-3**: Simulates 5G network metrics to validate the model’s effectiveness.

## Dataset and Analysis
The dataset consists of synthetic network traffic metrics, including:
- **Throughput**: Network throughput in Mbps.
- **Latency**: Round-trip time in milliseconds.
- **Packet Loss**: Percentage of lost packets.
- **Active Users**: Number of users on the network.
- **Bandwidth Utilization**: Percentage of bandwidth used.
- **Derived Features**: Moving averages and congestion labels.

### Dataset Insights
- **Latency Trends**: Increase during peak hours with a higher number of active users.
- **Throughput vs. Congestion**: Significant decline in throughput during congestion.
- **Packet Loss Correlation**: Strongly linked to bandwidth utilization.

## Methodology
1. **Network Simulation**: 
   - Simulated using NS-3 with metrics like throughput, latency, and packet loss.
2. **Machine Learning Model**:
   - A multi-layer LSTM model trained to predict congestion based on time-series data.
   - Validated using real-time simulated data.
3. **Traffic Mitigation**:
   - **Dynamic Resource Allocation**: Adjusts bandwidth and processing capacity based on predictions.
   - **Traffic Rerouting**: Redirects traffic to less congested paths.

## Evaluation
The system was evaluated using NS-3 simulations and the following performance metrics:
- **Latency**: Reduced by up to 30%.
- **Throughput**: Maintained within acceptable limits during high traffic conditions.
- **Stability**: Scalable and robust under varying network stress.

### Observations
- **Model Accuracy**: High prediction accuracy with effective generalization.
- **System Scalability**: Handles increased active users and traffic demand efficiently.

## Project Details
- **Authors**:
  - Dev Shrinivas Agrawal
  - Jigar Kanakhara
  - Phagun Gandhi
  - Shivam Kumar Pandey
  - Yash Singh
- **Institution**: IIIT Vadodara
- **Guide**: Dr. Bhupendra Kumar

## Links
- [Project Code on Colab](https://colab.research.google.com/drive/1JF28_Lvy3EvRCyGGLkUydMQll0_sVxBf)
- [Project Video](https://youtu.be/yEhHeosH4YM)

## Future Work
- Incorporating adaptive learning models for evolving traffic patterns.
- Integration with cloud-based platforms for enhanced scalability.
- Conducting real-world trials in live 5G environments.

## References
1. Tam, P., et al. "Enhancing QoS with LSTM-Based Prediction for Congestion-Aware Aggregation Scheduling." *Electronics*, 2023.
2. IEEE. "An Open Dataset for Beyond-5G Data-driven Network Automation Experiments," 2024.
3. Zhao, Q., Xie, L. "Real-Time Traffic Prediction and Optimization in 5G Mobile Networks Using AI and Edge Computing." *Journal of Communications and Networks*, 2023.

---

## Acknowledgments
Special thanks to Dr. Bhupendra Kumar for guidance and mentorship. We also extend our gratitude to IIIT Vadodara for providing the infrastructure and resources essential for the project’s success.

---

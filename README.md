# *Cesats*: A Non-Clairvoyant Distributed Traffic Scheduling Framework for SD-WANs

<div align="center">
  
[![Auth](https://img.shields.io/badge/Auth-DongYang_Yu-blue)](https://dyyuCS.github.io)  [![Paper](https://img.shields.io/badge/arXiV-TBD-blue)]() [![GitHub issues](https://img.shields.io/github/issues/dyyuCS/Cesats)]() [![GitHub license](https://img.shields.io/github/license/dyyuCS/Cesats)]() [![GitHub stars](https://img.shields.io/github/stars/dyyuCS/Cesats)]() [![GitHub forks](https://img.shields.io/github/forks/dyyuCS/Cesats)]() 
</div>

This repository contains the code and resources for the paper titled **"*Cesats*: A Non-Clairvoyant Distributed Traffic Scheduling Framework for SD-WANs"**. The framework, named ***Cesats***, introduces a novel distributed approach to optimize traffic scheduling under the P95 billing model, ensuring cost-efficiency and SLA compliance in large-scale SD-WAN environments.

# Overview

Software-Defined Wide Area Networks (SD-WANs) provide cost-effective solutions for enterprises by enabling dynamic bandwidth management across heterogeneous network links. However, the growing complexity of network traffic and the increasing scale of SD-WANs pose challenges in effectively managing network costs and ensuring compliance with Service Level Agreements (SLAs). 


In this paper, we propose **Cesats**, a robust and scalable traffic scheduling framework that utilizes distributed optimization techniques and novel forecasting mechanisms to manage network bandwidth efficiently under the **P95 billing model**. The framework tackles two main challenges:

1. **Uncertainty in traffic predictions**: Traditional traffic forecasting methods assume perfect knowledge of future traffic, which is often unrealistic. Cesats uses a stochastic LSTM-based approach to quantify and accommodate traffic prediction uncertainty.
2. **Scalability in large-scale networks**: Centralized scheduling methods face significant scalability limitations. Cesats employs a distributed architecture based on **Benders decomposition** to enable scalable optimization across multiple nodes.

Our extensive evaluations demonstrate that Cesats reduces bandwidth costs by up to **32%** compared to centralized scheduling, while maintaining robust SLA compliance (0.19% deadline misses) and enabling **148× speedup** in optimization time in large networks.


> [!NOTE]
> The manuscript for this project is currently **_<u>under review</u>_** and will be made publicly available upon the acceptance of the paper. Please check back after the review process is complete, or contact the corresponding author for any inquiries.


## License

This project is licensed under the MIT License.

## Contact

Dong-Yang Yu - A @ bupt.edu.cn (A<=>dyyu)


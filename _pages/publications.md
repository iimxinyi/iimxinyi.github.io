---
# =====================================================================
# PUBLICATION DATA (edit this file to manage your papers).
# This file renders no visible page — it only holds the list that the
# home page reads. To ADD A PAPER, copy one block below and edit it.
# The home page auto-sorts by year, draws the year divider, and handles
# the "Show All" collapse.
#   selected: true  -> always shown ; false -> hidden until "Show All"
#   authors : wrap your own name in <strong>..</strong>;
#             use <sup>&dagger;</sup> for co-first, * for corresponding
# =====================================================================
layout: none
sitemap: false
permalink: /publications-data/
publications:
  - title: "When AIGC meets MEC: A novel diffusion-based collaborative inference paradigm"
    authors: "H. Wu<sup>&dagger;</sup>, <strong>Xinyi Zhuang</strong><sup>&dagger;</sup>, J. Wu, L. Gao, D. Niyato, and T.-T. Chan"
    venue: "IEEE Communications Magazine, Early Access"
    year: 2026
    badge: "COMMAG"
    color: "#f39c12"
    link: "https://ieeexplore.ieee.org/document/11503883"
    role: "Co-First Author"
    tags: "SCI Q2 · JCR Q1"
    selected: true
    abstract: "Driven by rapid advancements in mobile edge computing and model compression technologies, generative diffusion models (GDMs) are increasingly being deployed at the edge to support a broad range of AI-generated content (AIGC) applications. However, delivering efficient and high-quality AIGC services remains a significant challenge due to the inherent limitations of edge resources and the growing diversity of personalized user demands. To address these challenges, collaborative inference has emerged as a promising paradigm. By partitioning model execution between edge servers and end devices, this approach effectively leverages the complementary strengths of both platforms in terms of scalability, computational efficiency, and personalization. In this article, we first provide a comprehensive overview of the paradigm evolution of collaborative inference tailored for GDMs, with a particular focus on how different paradigms trade off efficiency, reliability, and quality. Building upon this foundation, we propose a semantic-aware cross-task collaborative inference (SemCT) framework that examines how prompt semantic similarity and shared inference proportion affect content quality, and leverages these insights for more effective prompt clustering and denoising step allocation. We further present a case study to validate the effectiveness of SemCT and offer practical insights into efficient AIGC service delivery. Finally, we identify and discuss key challenges in this domain and outline promising directions for future research. In summary, this work aims to deepen the understanding of collaborative inference for GDMs, highlighting critical methodologies and open issues to guide further exploration."

  - title: "Joint communication and computation scheduling for MEC-enabled AIGC services: A game-theoretic stochastic learning approach"
    authors: "H. Liu, <strong>Xinyi Zhuang</strong>, J. Wu, Y. Luo, B. Cao, and L. Gao"
    venue: "IEEE Internet of Things Journal, Early Access"
    year: 2026
    badge: "IoTJ"
    color: "#c5ca30"
    link: "https://arxiv.org/abs/2605.22277"
    role: "Collaborative Author"
    tags: "CCF C · SCI Q1 · JCR Q1"
    selected: false
    abstract: "Artificial Intelligence Generated Content (AIGC) powered by Generative Diffusion Models (GDMs) has emerged as a transformative paradigm for automated content creation. To satisfy the stringent latency requirements of AIGC services in many edge intelligence scenarios (e.g., smart cities), Mobile Edge Computing (MEC) provides critical computational support by deploying GDMs at edge servers (ES) close to end users. This paper investigates an MEC-enabled AIGC network comprising multiple ES, wireless access points (APs), and mobile users (UEs) with heterogeneous latency and accuracy demands. We formulate a Joint Communication Association and Computation Offloading (JCACO) game, where each UE strategically selects its serving AP, ES, and inference steps to minimize the overall service completion time while meeting accuracy constraints. The problem is challenging due to the network dynamics and the incomplete information. We prove that the JCACO game is a potential game under both complete and stochastic information settings, ensuring the existence of Nash Equilibrium (NE) in both cases. To derive the NE efficiently, we develop a distributed Multi-Agent Stochastic Learning (MASL) algorithm that provably converges to the NE with strict performance guarantees. Unlike conventional best-response schemes, MASL requires neither the knowledge of other players' strategies nor global network information, making it fully distributed and adaptive to dynamic environments. We further provide a strict theoretical convergence analysis for MASL by using Ordinary Differential Equations (ODEs). Simulation results demonstrate that MASL significantly reduces service completion time compared with benchmark methods while satisfying accuracy constraints, confirming its effectiveness and practicality for real-world MEC-enabled AIGC networks."

  - title: "Joint optimization of offloading, scheduling, and inferencing for MEC-empowered AIGC services"
    authors: "X. Guo, C. Zhang, X. Chen, D. Zhao, <strong>Xinyi Zhuang</strong>*, J. Wu*, H. Liu, and L. Gao*"
    venue: "IEEE Global Communications Conference, Taipei, Taiwan, Dec. 2025, pp. 823-828"
    year: 2025
    badge: "GLOBECOM"
    color: "#27ae60"
    link: "https://ieeexplore.ieee.org/document/11431795"
    role: "Corresponding Author"
    tags: "CCF C"
    selected: true
    abstract: "Generative Diffusion Model (GDM)-based AI-Generated Content (AIGC) services are rapidly emerging as powerful solutions for creating high-quality, personalized content across various domains, playing an essential role in shaping the future network landscapes. However, the traditional cloud-based implementation of AIGC services faces substantial challenges due to the heterogeneity of GDMs as well as their computation-intensive nature and the low-latency requirement. In this work, we investigate a Mobile Edge Computing (MEC)-empowered heterogeneous AIGC service scenario, where User Equipments (UEs) and Base Stations (BSs) deploy lightweight and heavyweight GDMs, respectively, to deliver different levels of AIGC services at the network edge. Specifically, when initiating an AIGC task, each UE can choose to process the task locally using lightweight GDMs, or offload and process the task on a BS using heavyweight GDMs. In such a scenario, we focus on the joint optimization of offloading, scheduling, and inferencing, aiming to minimize task delay and energy consumption, while maximizing content quality. To address the problem in an online and decentralized manner, we develop a Multi-Agent Proximal Policy Optimization (MAPPO)-based deep reinforcement learning algorithm in a centralized training and decentralized execution framework. Simulation results show that our proposed algorithm outperforms existing intelligent benchmarks, with the performance gains ranging from 5.1% to 13.9%."

  - title: "QoS-driven hybrid inference scheme for generative diffusion models in MEC-enabled AI-generated content networks"
    authors: "<strong>Xinyi Zhuang</strong>, J. Wu, H. Wu, M. Tang, and L. Gao"
    venue: "IEEE International Conference on Communications, Montreal, QC, Canada, Jun. 2025, pp. 1151-1156"
    year: 2025
    badge: "ICC"
    color: "#27ae60"
    link: "https://ieeexplore.ieee.org/document/11161497"
    role: "First Author"
    tags: "CCF C"
    selected: true
    abstract: "AI-Generated Content (AIGC) based on Generative Diffusion Models (GDMs) is revolutionizing content creation and promoting substantial advancements in domains like autonomous driving and robotics. Leveraging progress in Mobile Edge Computing (MEC) and model compression techniques, GDMs are increasingly being deployed on Edge Servers (ESs) and User Equipments (UEs), which typically face resource limitations. In such MEC-enabled scenarios, designing an efficient inference scheme for GDMs still remains a significant challenge, due to the resource constraints on ESs and UEs as well as the personalized demands of AIGC users. In this work, we propose a novel hybrid inference scheme, which consists of two stages: public prompt generation and common-to-personalized inference. In the first stage, a Large Language Model (LLM) is adopted to generate public prompts derived from the common features of users' personal prompts. In the second stage, a common inference phase based on public prompts is first executed for all users (to produce common intermediate results), and then a personalized inference phase based on each user's personal prompts is performed for each individual user (to generate final contents). Clearly, by introducing the common inference phase, the total inference steps can be significantly reduced. In such a scheme, we further study a hybrid inference optimization problem to optimize both common and personalized inference steps, aiming to maximize the total Quality of Service (QoS), while minimizing delay and energy consumption. Simulation results show that our proposed scheme significantly outperforms existing benchmarks, with the performance gains ranging from 12.6% to 102.2%."

  - title: "Joint optimization of model inferencing and task offloading for MEC-empowered large vision model services"
    authors: "<strong>Xinyi Zhuang</strong>, J. Wu, H. Wu, T. Zhang, and L. Gao"
    venue: "IEEE International Conference on Computer Communications, London, United Kingdom, May 2025"
    year: 2025
    badge: "INFOCOM"
    color: "#e74c3c"
    link: "https://ieeexplore.ieee.org/document/11044689"
    role: "First Author"
    tags: "CCF A"
    selected: true
    abstract: "With the rapid advancement of Large Vision Models (LVMs) such as Sora, the initial comprehension of physical laws by large AI models has garnered significant attention, which enables them to interpret and apply physical principles with increasing accuracy and sophistication. Nevertheless, due to resource limitations and delay constraints, traditional cloud-based LVM services often fail to meet the diverse needs of users, particularly in scenarios requiring real-time responsiveness. In this work, we explore the scenario of Mobile Edge Computing (MEC)-empowered LVM services in wireless networks, where heterogeneous LVMs are deployed on both cloud and edge servers, and LVM Users (LUs) can offload computation task to edge servers to reduce delay and energy consumption. In such a scenario, we focus on the joint optimization of model inferencing and task offloading for LUs, aiming to maximize the total service utility, while minimizing delay and energy consumption. First, to characterize the utility of LVM services, we propose a multi-dimensional video quality metric based on real measurements, which incorporates both the prompt-video alignment and the classic video quality indicators. Then, to solve the problem in a decentralized manner, we propose a two-stage solution based on both learning and optimization techniques. In the first stage, we design a reinforcement learning-based Multi-Agent Proximal Policy Optimization (MAPPO) approach to make the real-time model inferencing and task offloading decisions. In the second stage, we employ the optimization-based Sequential Least Squares Programming (SLSQP) to make the efficient resource allocation decisions. Simulation results show that our proposed solution outperforms other benchmarks, and can reduce delay and energy consumption by up to 17.2% and 21.7%, respectively, while increasing service utility by up to 3%."

  - title: "QoE-aware offloading and resource allocation for MEC-empowered AIGC services"
    authors: "J. Wu, <strong>Xinyi Zhuang</strong>, M. Tang, and L. Gao"
    venue: "IEEE Transactions on Mobile Computing, vol. 24, no. 10, pp. 9664-9682, Oct. 2025"
    year: 2025
    badge: "TMC"
    color: "#e74c3c"
    link: "https://ieeexplore.ieee.org/document/10972066"
    role: "Collaborative Author"
    tags: "CCF A · SCI Q1 · JCR Q1"
    selected: false
    abstract: "Artificial Intelligence-Generated Content (AIGC) has emerged as a transformative paradigm, enabling the autonomous creation of diverse content. By offloading model inference tasks to the network edge that is closer to mobile users (MUs), Mobile Edge Computing (MEC) has the potential to significantly enhance the performance of AIGC services. In practice, however, it is challenging to optimally manage MEC-empowered AIGC services, due to the lack of well-defined AIGC-specific metrics, as well as the dynamic workload and computation-intensive nature of AIGC services. In this paper, we first define a novel AIGC metric based on extensive real data experiments, and then study the joint task offloading and resource allocation problem in a generic MEC-empowered AIGC network, where MUs can offload model inference tasks to local or remote Base Stations (BSs), aiming at maximizing their Quality of Experience (QoE). The problem is challenging due to the fast and randomly changing of environments, as well as the necessity for real-time, asynchronous decision-making. To tackle these challenges, we propose two deep reinforcement learning algorithms based on the Proximal Policy Optimization (PPO) framework: Single-Layer PPO (SL-PPO) and Multi-Layer PPO (ML-PPO), designed for slow-changing and fast-changing environments, respectively. In the SL-PPO algorithm, both task offloading and resource allocation decisions are made simultaneously when tasks arrive. In the ML-PPO algorithm, the task offloading decision is made immediately when tasks arrive, while the resource allocation decision is deferred until tasks are scheduled for processing or transmission in the corresponding queues. Simulation results show that (i) both algorithms outperform existing methods in the literature, and can increase the average utility by up to 47% and 48.8%; (ii) both algorithms can effectively manage the trade-off between latency and energy consumption."

  - title: "Joint communication and computation scheduling for MEC-enabled AIGC services based on generative diffusion model"
    authors: "H. Liu, J. Wu, <strong>Xinyi Zhuang</strong>, H. Wu, and L. Gao"
    venue: "International Symposium on Modeling and Optimization in Mobile, Ad Hoc, and Wireless Networks, Seoul, Republic of Korea, Oct. 2024, pp. 345-352"
    year: 2024
    badge: "WiOpt"
    color: "#3498db"
    link: "https://ieeexplore.ieee.org/document/10778362"
    role: "Collaborative Author"
    tags: ""
    selected: false
    abstract: "Artificial Intelligence-Generated Content (AIGC) based on Generative Diffusion Model (GDM) has emerged as a promising paradigm of content generation, revolutionizing the creation of diverse contents and driving significant technological advancements. Due to the low latency requirements of AIGC services, mobile edge computing (MEC) has become a crucial enabling technology for these services. In this work, we consider an MEC-enabled GDM-based AIGC network, which consists of multiple GDMs with varying sizes and capabilities deployed on edge computing servers (ES), and multiple mobile users (UEs) with diverse latency and accuracy requirements requesting AIGC services from ES through wireless access points (APs). In such a scenario, we are interested in the joint communication and computation scheduling problem for UEs, which involves selecting the appropriate APs (along with the communication bandwidth allocation) and the appropriate ES (together with the computation resource allocation and model inference optimization) for UEs, considering both the UEs' heterogeneous requirements and the GDMs' heterogeneous capabilities. To address the problem in a practical scenario with decentralized, autonomous, and self-interested UEs, we formulate a non-cooperative game, called the Joint User Association and Computation Offloading (JUACO) game, where each UE acts as a game player, selecting the best AP (for communication) as well as the best ES and the best GDM model inference step (for computation), aiming to minimize the inference time while meeting the specified inference accuracy requirement. We prove that the proposed JUACO game is a potential game, thus guaranteeing the existence of Nash equilibrium (NE) and the convergence of simple best response-based distributed algorithms to NE. Simulation results demonstrate that the proposed JDACO game approach significantly reduces the inference time and meets the required accuracy compared to traditional methods, validating the effectiveness and practicality of the game-theoretic approach in real-world scenarios."
---

# 面部和生理信号历年的疼痛识别论文

## 2023

### 论文
Pain Recognition Differences between Female and Male Subjects: An Analysis based on the Physiological Signals of the X-ITE Pain Database女性与男性受试者疼痛识别差异：基于X-ITE疼痛数据库生理信号的分析

https://dl.acm.org/doi/10.1145/3610661.3617131

出版机构：ICMI(CCFC)

研究机构：德国乌尔姆大学 Ulm University, Germany

摘要：在本研究中，我们研究了人类对热和电疼痛刺激的适应和习惯，重点关注女性和男性受试者之间的差异。我们评估了两种疼痛识别场景，无痛与最低疼痛水平以及无痛与最高疼痛水平。此外，实验结合了两种刺激持续时间，即短期和长期，从而产生了八项不同的任务。请注意，在这项工作中，我们的目的不是提出任何新的分类方法。根据我们的结果，我们能够观察到女性受试者对某些生理信号的热刺激和电刺激的适应和习惯随时间的变化。然而，长期刺激的长度为 60 秒，这可能会限制这些观察结果对于长期疼痛（例如慢性疼痛）的有效性。此外，我们观察到在特定情况下，仅使用特定于女性或男性受试者的数据可能有利于相应的分类性能。

## 2024
### 开源
### 论文
Unraveling Pain Levels: A Data-Uncertainty Guided Approach for Effective Pain Assessment

https://ojs.aaai.org/index.php/AAAI/article/view/30221

出版机构：AAAI

研究机构：悉尼大学 The University of Sydney 

抽象：

疼痛是寻求医疗帮助的主要原因，需要进行必要的疼痛评估才能有效管理。研究已经认识到皮肤电活动 (EDA) 信号在自动疼痛评估方面的潜力，但传统算法通常会忽略疼痛数据中固有的噪音和不确定性。为了解决这个问题，我们提出了一个基于数据不确定性的学习框架，引入了两种形式：a) 受试者水平的刺激-反应漂移；b) 自我报告分数的模糊性。我们使用心率变异性 (HRV) 特征制定不确定性评估，以指导响应性疼痛概况的选择，并根据自我报告数据的模糊性重新加权子任务的重要性。这些方法集成在端到端神经网络学习范式中，将检测器的重点放在不确定性领域内更准确的洞察上。对公开的 biovid 数据集和专有的 Apon 数据集进行的大量实验证明了我们方法的有效性。在 biovid 数据集中，我们比最先进的方法提高了 6%，而在 Apon 数据集上，我们的方法比基线方法提高了 20% 以上。

### 会议
The Fourth International Workshop on Automated Assessment of Pain (AAP 2024)第四届国际疼痛自动评估研讨会（AAP 2024）

http://aap-workshop.net/
### 挑战赛
First Multimodal Sensing Grand Challenge for Next-Gen Pain Assessment (AI4Pain)首个针对下一代疼痛评估的多模式传感大挑战（AI4Pain）（正在尝试获取数据）

https://sites.google.com/view/ai4pain/home

### 数据集
AI4PAIN

AI4PAIN 数据集包含从澳大利亚堪培拉大学人机交互实验室的 51 名参与者（20 名女性，31 名男性）收集的数据。使用经皮电神经刺激机（TENS）在右臂的两个位置（手和前臂）施加疼痛刺激。这两个解剖位置用于探索在未来研究中识别疼痛来源的可能性。疼痛刺激的位置和强度得到平衡，以避免对重复的实验疼痛产生习惯，并避免由于顺序效应而产生的混杂因素。参与者坐在桌子前的椅子上，使用采样率为 30Hz 的 Logitech StreamCam 捕捉面部视频数据。在每次实验开始时，记录一个 60 秒的基线期。这个基线期作为实验设置中的无痛条件。对每个刺激记录了六次重复，每次持续 10 秒。数据集的每个视频都包含每个疼痛刺激 10 秒的持续时间。AI4PAIN 数据集包括 577 个高痛视频、571 个低痛视频和 51 个基线（即无痛）视频。

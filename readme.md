# 面部和生理信号历年的疼痛识别论文

## 2024
### 论文
1. Unraveling Pain Levels: A Data-Uncertainty Guided Approach for Effective Pain Assessment

https://ojs.aaai.org/index.php/AAAI/article/view/30221

出版机构：AAAI

研究机构：悉尼大学 The University of Sydney 

使用数据：biovid，私有数据

抽象：

疼痛是寻求医疗帮助的主要原因，需要进行必要的疼痛评估才能有效管理。研究已经认识到皮肤电活动 (EDA) 信号在自动疼痛评估方面的潜力，但传统算法通常会忽略疼痛数据中固有的噪音和不确定性。为了解决这个问题，我们提出了一个基于数据不确定性的学习框架，引入了两种形式：a) 受试者水平的刺激-反应漂移；b) 自我报告分数的模糊性。我们使用心率变异性 (HRV) 特征制定不确定性评估，以指导响应性疼痛概况的选择，并根据自我报告数据的模糊性重新加权子任务的重要性。这些方法集成在端到端神经网络学习范式中，将检测器的重点放在不确定性领域内更准确的洞察上。对公开的 biovid 数据集和专有的 Apon 数据集进行的大量实验证明了我们方法的有效性。在 biovid 数据集中，我们比最先进的方法提高了 6%，而在 Apon 数据集上，我们的方法比基线方法提高了 20% 以上。

2.Automatic Pain Assessment Based on Physiological Signals: Application of Multi-Scale Networks and Cross-Attention Cross-Attention基于生理信号的自动疼痛评估：多尺度网络和交叉注意的应用

https://dl.acm.org/doi/10.1145/3704198.3704212

出版机构：ICBBS: International Conference on Bioinformatics and Biomedical Science

研究机构：暨南大学
使用数据：biovid

抽象：

疼痛是一种与生理和心理紧密相连的主观感受，当疼痛发生时会引起人们对身体威胁的注意，与疾病和生存息息相关。评估疼痛最常见的方法是自我报告。然而，在患者无法交流的情况下，自我评估疼痛是不可行的，必须依靠观察者报告。由于观察者的主观偏见和认知差异，观察者对疼痛的报告可能不准确。此外，通过自我报告和观察者报告进行持续监测是不切实际的。因此，自动疼痛评估技术可用于协助人类护理人员并补充他们的服务，从而提高疼痛管理的质量。在本研究中，我们设计并实现了一个创新的疼痛评估模型，我们称之为EDAPainNet。该模型使用皮肤电信号（EDA）进行疼痛评估。模型结构包括多尺寸窗口维度卷积网络（MSWDCN）、激活通道特征网络（ACFN）和时间卷积交叉注意网络（TCCAN），旨在从EDA信号中提取和优化关键特征并确保特征表示的准确性。我们在公开数据集BioVid上对模型进行了验证，实验表明，我们的模型可以比现有方法更准确地输出疼痛等级，为疼痛评估提供了一种高效可靠的自动化解决方案。BioVid疼痛数据集评估表明，我们的方法优于现有方法，在区分无痛和疼痛状态的识别准确率达到81.25％。在对比实验中，我们的方法在性能上表现出超过2％的显著提升。



### 会议
The Fourth International Workshop on Automated Assessment of Pain (AAP 2024)第四届国际疼痛自动评估研讨会（AAP 2024）

http://aap-workshop.net/
### 挑战赛
First Multimodal Sensing Grand Challenge for Next-Gen Pain Assessment (AI4Pain)首个针对下一代疼痛评估的多模式传感大挑战（AI4Pain）（正在尝试获取数据）

https://sites.google.com/view/ai4pain/home

### 数据集
AI4PAIN

AI4PAIN 数据集包含从澳大利亚堪培拉大学人机交互实验室的 51 名参与者（20 名女性，31 名男性）收集的数据。使用经皮电神经刺激机（TENS）在右臂的两个位置（手和前臂）施加疼痛刺激。这两个解剖位置用于探索在未来研究中识别疼痛来源的可能性。疼痛刺激的位置和强度得到平衡，以避免对重复的实验疼痛产生习惯，并避免由于顺序效应而产生的混杂因素。参与者坐在桌子前的椅子上，使用采样率为 30Hz 的 Logitech StreamCam 捕捉面部视频数据。在每次实验开始时，记录一个 60 秒的基线期。这个基线期作为实验设置中的无痛条件。对每个刺激记录了六次重复，每次持续 10 秒。数据集的每个视频都包含每个疼痛刺激 10 秒的持续时间。AI4PAIN 数据集包括 577 个高痛视频、571 个低痛视频和 51 个基线（即无痛）视频。

## 2023

### 论文
1. Pain Recognition Differences between Female and Male Subjects: An Analysis based on the Physiological Signals of the X-ITE Pain Database女性与男性受试者疼痛识别差异：基于X-ITE疼痛数据库生理信号的分析

https://dl.acm.org/doi/10.1145/3610661.3617131

出版机构：ICMI(CCFC)

研究机构：德国乌尔姆大学 Ulm University, Germany

数据：X-ITE不开源

摘要：在本研究中，我们研究了人类对热和电疼痛刺激的适应和习惯，重点关注女性和男性受试者之间的差异。我们评估了两种疼痛识别场景，无痛与最低疼痛水平以及无痛与最高疼痛水平。此外，实验结合了两种刺激持续时间，即短期和长期，从而产生了八项不同的任务。请注意，在这项工作中，我们的目的不是提出任何新的分类方法。根据我们的结果，我们能够观察到女性受试者对某些生理信号的热刺激和电刺激的适应和习惯随时间的变化。然而，长期刺激的长度为 60 秒，这可能会限制这些观察结果对于长期疼痛（例如慢性疼痛）的有效性。此外，我们观察到在特定情况下，仅使用特定于女性或男性受试者的数据可能有利于相应的分类性能。

2.Transformer encoder with multiscale deep learning for pain classification using physiological signals具有多尺度深度学习的 Transformer 编码器，用于使用生理信号进行疼痛分类

https://www.frontiersin.org/journals/physiology/articles/10.3389/fphys.2023.1294577/full

github: https://github.com/zhenyuanlu/PainAttnNet

出版机构：Frontiers in Physiology (SCI3区)

研究机构：美国马萨诸塞州波士顿东北大学机械与工业工程系

数据：Biovid

疼痛是一种普遍存在的全球健康问题，影响着全球很大一部分人口。由于传统自我报告量表的局限性，准确的疼痛评估仍然是一项挑战，这些量表通常会产生不一致的结果并且容易产生偏见。认识到这一差距，我们的研究引入了 PainAttnNet，这是一种新型深度学习模型，旨在使用生理信号对疼痛强度进行精确分类。我们研究了 PainAttnNet 在捕捉时间依赖性方面是否会优于现有模型。该模型集成了多尺度卷积网络、压缩和激励残差网络和变压器编码器块。这种集成对于在多个时间窗口中提取稳健特征、强调特征相互依赖性和增强时间依赖性分析至关重要。在 BioVid 热痛数据集上对 PainAttnNet 的评估证实了该模型优于现有模型的性能。结果证实 PainAttnNet 是一种有前途的自动化和细化疼痛评估的工具。我们的研究不仅引入了一种新颖的计算方法，而且为未来更加个性化和准确的疼痛评估和管理奠定了基础。

3.Occluded Facial Pain Assessment in the ICU Using Action Units Guided Network 使用动作单元引导网络进行 ICU 中的阻塞性面部疼痛评估

[https://dl.acm.org/doi/10.1145/3704198.3704212](https://ieeexplore.ieee.org/document/10327783)

出版机构： IEEE Journal of Biomedical and Health Informatics 

研究机构：合肥工业大学
使用数据：肩痛数据集

危重患者疼痛未得到治疗会导致免疫抑制和代谢活动增加，并导致呼吸急促和谵妄等严重临床后果。由于护理人员短缺和重症监护病房 (ICU) 工作量大，持续疼痛评估具有挑战性。机械通气设备掩盖了 ICU 中许多患者的面部特征，使得以前基于全脸图像的面部疼痛检测方法不再适用。本文提出了一种针对遮挡面部的面部动作单元 (AU) 引导疼痛评估网络。该网络由 AU 引导 (AUG) 模块、纹理特征提取 (TFE) 模块和疼痛评估 (PA) 模块组成。AUG 模块自动检测面部非遮挡区域中的 AU。相比之下，TFE 模块会检测面部特征点并裁剪先验知识块、随机探索块和全局特征块。然后，这些块被输入到两个卷积网络中以提取纹理特征。随后，将设计的 AU 引导和纹理特征融合到 PA 模块中以评估疼痛状态。对公共数据集和本文创建的两个数据集进行了广泛的验证。所提出的网络架构在二分类、四分类和强度回归任务中实现了卓越的性能。此外，我们已成功将网络应用于实验室环境中收集的实际数据，并取得了优异的结果。



## 2021
### 论文
1.Spatio-Temporal Pain Estimation Network With Measuring Pseudo Heart Rate Gain带测量伪心率增益的时空疼痛估计网络

https://ieeexplore.ieee.org/document/9479776

出版机构：IEEE Transactions on Multimedia （SCI1区）

研究机构：西北工业大学电子信息学院

数据：biovid,mintpain

没代码，不开源

抽象的：
疼痛是表明人们正在遭受不适体验的重要指标，近年来，疼痛的自动估计引起了人们的极大兴趣。最近，大多数估计方法旨在从视觉信号中捕捉动态疼痛信息，而一些基于生理信号的方法可以提供额外的潜在线索来更准确地分析疼痛。然而，捕捉患者的生理数据仍然具有挑战性，因为它需要接触设备和患者的配合。在本文中，我们提出利用伪生理信息，从原始视觉视频中生成新的模态数据，并通过端到端网络联合估计疼痛。为了从双模态数据中提取表示，我们设计了一个时空疼痛估计网络，该网络采用双分支框架分别提取疼痛感知的视觉和伪生理特征，并以概率方式融合这些特征。来自伪生理信息的固有生命体征，即心率增益 (HRG)，可用作辅助信号并与视觉疼痛估计框架相结合。此外，我们采用专门设计的 3D 卷积滤波器和注意结构来提取两个分支的时空特征。为了将 HRG 作为疼痛估计的辅助方法，我们提出了一个概率推理模型，该模型同时考虑了视觉分支和生理分支，使我们的模型能够全面估计疼痛。在两个公开可用的数据集上进行的实验证明了引入伪模态的有效性，并且所提出的方法可以胜过最先进的方法。

2.Automatic Detection of Pain from Facial Expressions: A Survey根据面部表情自动检测疼痛：一项调查

https://ieeexplore.ieee.org/document/8928510

出版机构：IEEE Transactions on Pattern Analysis and Machine Intelligence (SCI1区)

研究机构：德国埃尔兰根 弗劳恩霍夫研究院（欧洲最大的应用科学研究机构）


抽象的：
疼痛感对于生存至关重要，因为它能引起人们对身体受到的物理威胁的注意。疼痛评估通常通过自我报告进行。然而，对于无法交流的患者，无法进行疼痛的自我评估，因此应依赖观察者的报告。由于观察者的主观偏见，观察者对疼痛的报告可能容易出错。此外，人类的持续监测是不切实际的。因此，可以部署自动疼痛检测技术来协助人类护理人员并补充他们的服务，从而提高疼痛管理的质量，特别是对于无法交流的患者。面部表情是疼痛的可靠指标，并用于所有基于观察者的疼痛评估工具。随着自动面部表情分析的进步，计算机视觉研究人员试图利用这项技术开发自动从面部表情检测疼痛的方法。本文调查了过去十年该领域发表的文献，对其进行了分类，并确定了未来的研究方向。该调查涵盖了所审查文献中使用的疼痛数据集、方法针对的学习任务、从图像和图像序列中提取的用于表示疼痛相关信息的特征，以及最后使用的机器学习方法。

## 2018
### 论文

Automatic Recognition Methods Supporting Pain Assessment: A Survey 支持疼痛评估的自动识别方法：一项调查

https://ieeexplore.ieee.org/document/8865626

出版机构：IEEE Transactions on Affective Computing (SCI2区)

研究机构：神经信息技术组 奥托·冯·格里克大学 德国马格德堡

抽象的：
疼痛是一种复杂的现象，涉及感觉和情感体验，人们对此往往知之甚少，尤其是在婴儿、麻醉患者和其他无法说话的人中。支持疼痛评估的技术有可能帮助减轻痛苦；然而，在临床应用之前，还需要取得进展。这篇综述论文评估了最先进的技术，并为研究人员提供了帮助取得此类进展的指导。首先，我们概述了疼痛的生物机制、生理和行为反应、情感成分以及临床常用的评估方法。接下来，我们讨论了阻碍疼痛识别技术开发和验证的挑战，并调查了现有的数据集和评估方法。然后，我们概述了 Web of Science 中索引的所有自动疼痛识别出版物以及生物医学信息学和人工智能主要会议的论文集，以了解目前取得的进展。我们重点介绍了非接触式和接触式方法的进展、使用面部、语音、生理和多模态信息的工具、背景的重要性，并讨论了存在的挑战，包括识别基本事实。最后，我们确定了慢性疼痛和治疗之间的联系等尚未充分探索的领域，并描述了继续取得进展的有希望的机会。

## 2013
### 数据集
Biovid

数据集项目页面

https://www.nit.ovgu.de/BioVid.html#PubICPR14

90 名参与者接受了四种强度的实验引起的热痛。为了补偿不同的热痛敏感性，根据受试者特定的疼痛阈值和疼痛耐受性调整刺激温度。对四个疼痛水平中的每一个水平都按随机顺序刺激 20 次。对于每个刺激，最高温度保持 4 秒。刺激之间的停顿随机在8至12秒之间。疼痛刺激实验进行了两次：一次采用未遮挡面部，一次采用面部肌电图传感器。

关于数据集的介绍：

biovid 热痛数据库数据用于自动疼痛识别系统的开发和系统验证

https://ieeexplore.ieee.org/document/6617456

实验诱发热痛时的面部表情分析

https://ieeexplore.ieee.org/document/8272610


## 2012
### 数据集
UNBC Mcmaster

PAINFUL DATA: The UNBC-McMaster Shoulder Pain Expression Archive Database 疼痛数据：UNBC-McMaster 肩痛表达档案数据库

https://sites.pitt.edu/~emotion/fulltext/2011/Painful_Data.pdf

现在这个数据集已经不能访问了

资源页面：

https://www.jeffcohn.net/Resources/

这位作者的出版物：

https://www.jeffcohn.net/publications/

动作编码系统介绍

https://sites.pitt.edu/~jeffcohn/FACSmodule.html

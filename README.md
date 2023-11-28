## 11月

| &nbsp;Date&nbsp; | Paper | Links & Summary |
| --- | --- | --- |
| <span style='display: inline-block; width: 42px;'>11-23</span> | **GAIA: a benchmark for General AI Assistants** - GAIA 是一项针对通用人工智能助理的基准测试，其目的在于提出真实世界的挑战性问题，并避开传统 LLMs 评价中的许多陷阱。该基准测试强调任务对人类简单而对AI难度较大，以此来评估AI的执行复杂行动序列的准确能力，这些任务在设计上无法简单地通过暴力方法得以解决。GAIA 还考虑了如何扩展基准测试，并探讨了一些最先进的助理的成功与短板，展示了增强 LLMs 的潜力。最终，文章旨在设立一个开发者问题集，为人工智能研究提供一个可扩展的基准测试平台。</div>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2311.12983v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2023-11/2311.12983.md)  |
| <span style='display: inline-block; width: 42px;'>11-23</span> | **LucidDreamer: Domain-free Generation of 3D Gaussian Splatting Scenes** - LucidDreamer是一个能够用于生成逼真而且分辨率更高的3D场景的模型。它优于现有的场景生成模型，因为它不依赖特定的训练数据集，并能够适应多种输入样式。LucidDreamer通过约束点云的移动和使用插值算法，克服了形状扭曲和点云与图像错位的问题，从而在操纵3D空间中的点云时保持了场景的真实感和一致性。在实验中明显展示了其优越性和高泛化能力。</div>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2311.13384v2)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2023-11/2311.13384.md)  |
| <span style='display: inline-block; width: 42px;'>11-23</span> | **Diffusion Model Alignment Using Direct Preference Optimization** - 本文提出了一个名为Diffusion-DPO的方法，其通过直接优化基于人类比较数据的模型来实现对扩散模型与人类偏好的对齐。此外，文章也探索了基于AI反馈的训练，取得了与基于人类偏好训练相媲美的成绩。这明显提升了模型在视觉吸引力和文本对齐方面的性能，为利用AI反馈扩展扩散模型对齐方法提供了新的途径。</div>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2311.12908v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2023-11/2311.12908.md)  |
| <span style='display: inline-block; width: 42px;'>11-23</span> | **ZipLoRA: Any Subject in Any Style by Effectively Merging LoRAs** - 文章提出了一种名为ZipLoRA的新策略，旨在通过一个优化过程有效地合并独立训练的主题和风格LoRAs，从而能够生成任何用户提供的主题风格的组合。ZipLoRA对生成任何特定主题和风格的图像这一开放性研究问题提供了创新的解决方案，且由于其无需手动超参数调整，使用起来更加简便高效。实验证明该方法在保持主题和风格真实性的同时，相比于现有方法和其他基本方法而言，具有更好的生成质量和鲁棒性。</div>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2311.13600v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2023-11/2311.136.md)  |
| <span style='display: inline-block; width: 42px;'>11-23</span> | **FusionFrames: Efficient Architectural Aspects for Text-to-Video Generation Pipeline** - 总体而言，该论文提出了一个新型两阶段潜在扩散的文本到视频生成架构，解决了关键帧合成和插值帧生成中存在的问题，通过使用独立的时域块和有效的插值架构，减少了计算成本，并在多个质量指标上取得了优于现有技术的表现。此外，论文还针对视频解码器设计了不同的架构选项，进一步优化了视频的一致性和整体质量。</div>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2311.13073v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2023-11/2311.13073.md)  |
| <span style='display: inline-block; width: 42px;'>11-22</span> | **LIMIT: Less Is More for Instruction Tuning Across Evaluation Paradigms** - 本论文的主要贡献包括：在开源模型上微调不同大小和风格的指令数据集，评估微调模型在不同的评估范式下的表现，并且发现较少的样本（特别是当这些样本结合了不同来源和风格时）足以在不同类型的评估中获得良好的性能。这表明在培养LLMs的指令遵从能力时，“少即是多”，且通过精心选择微调样本，可以使模型在执行指令能力上得到显著提升。这一发现对于如何有效地微调LLMs以及如何评估它们的实用性具有重要意义。</div>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2311.13133v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2023-11/2311.13133.md)  |
| <span style='display: inline-block; width: 42px;'>11-22</span> | **XAGen: 3D Expressive Human Avatars Generation** - 研究提出了XAGen模型，它是首个能够生成全面可控3D人类化身的GAN模型。XAGen在细粒度属性控制上具有独立的能力，并通过多尺度和多部分的3D表示与渲染技术提升了面部和手部的生成质量。实验结果证明XAGen在外观质量、控制能力和数据利用率方面都超过了现有最先进的方法，推进了3D虚拟化身生成技术的发展。</div>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2311.13574v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2023-11/2311.13574.md)  |
| <span style='display: inline-block; width: 42px;'>11-21</span> | **Oasis: Data Curation and Assessment System for Pretraining of Large Language Models** - 本文提出的Oasis系统是针对大型语言模型预训练的数据整理和评估问题的解决方案。Oasis通过其交互式的自定义数据整理模块、针对偏差的模型过滤器和全面的数据评估系统，旨在提高数据集的质量和多样性，同时降低内存需求和资源消耗。系统的实现立足于提升数据处理的灵活性和评估的准确性，填补了现有工作在全面性和多维度评估方面的空白。通过综合使用人类评估、启发式度量和最新的大型语言模型如GPT-4进行质量评估，Oasis展现了对预训练数据集进行全方位优化的能力。</div>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2311.12537v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2023-11/2311.12537.md)  |
| <span style='display: inline-block; width: 42px;'>11-21</span> | **Mechanistically analyzing the effects of fine-tuning on procedurally defined tasks** - 本文针对微调对预定义能力的影响开展了一项全面的分析和评估。通过Tracr编译式的能力设计和基于PCFG的学习式能力设计，文章详细探讨了微调过程中嵌入特征的相关性，提出了reFT来强化分析微调影响的深度。本研究的发现改进了对微调影响机理的理解，并为后续的模型设计和微调策略提供了实证支持。</div>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2311.12786v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2023-11/2311.12786.md)  |
| <span style='display: inline-block; width: 42px;'>11-21</span> | **How Capable Can a Transformer Become? A Study on Synthetic, Interpretable Tasks** - 本文通过设计合成数据生成过程和系统性实验，以评估和理解自回归Transformer模型在组合其原始能力方面的潜力。研究结果突显了模型学习组合结构的能力，揭示了训练数据对此能力的影响以及模型内部注意力层在组合学习过程中的重要性。这或许为评估和提高现代神经网络对真实世界数据的理解和应用，特别是在其可能面临前所未见的任务时，提供了新的见解。</div>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2311.12997v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2023-11/2311.12997.md)  |
| <span style='display: inline-block; width: 42px;'>11-21</span> | **Latent Lab: Large Language Models for Knowledge Exploration** - Latent Lab作为一种探索大型数据集中相互联系关系的创新和强大工具，通过利用LLMs和视觉引人注目的接口，它超越了常规搜索的局限性，提供了一个语义上有意义和情境感知的体验。强调探索的价值和迭代设计，在直观地访问大量相互连接的信息方面实现了信息技术专家的长期追求，并通过AI辅助探索将这一愿景变为现实，为未来人工智能共创系统的发展奠定了基础，并促进了更直观和高效的合作，有能力产生新颖和有影响力的创造物。</div>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2311.13051v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2023-11/2311.13051.md)  |
| <span style='display: inline-block; width: 42px;'>11-21</span> | **A Survey on Multimodal Large Language Models for Autonomous Driving** - 该论文全面回顾了MLLMs在自动驾驶领域的应用，表明MLLMs具备解析非文本数据和融合多种模态（如视觉、语言）的能力，这些能力对于行为预测和动作规划尤为重要。通过在不同的自动驾驶环节中部署MLLMs（如理解交通场景、规划控制、模式生成），可以改善决策流程，并实现类似人类的驾驶直觉和决策模式，同时提高车辆导航和规划的效率和安全性。此外，模型通过为多个任务的预训练提供了一种新的可能性，这可能会推动把智能系统推向人工普遍智能（AGI）的发展路径。</div>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2311.12320v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2023-11/2311.1232.md)  |
| <span style='display: inline-block; width: 42px;'>11-21</span> | **Do Smaller Language Models Answer Contextualised Questions Through Memorisation Or Generalisation?** - 本论文提出了一种新方法以评价小型语言模型在问答任务中答案的生成是否为记忆或概括能力的结果。通过语义相似度分析，确定了不太可能被模型记住答案的评估样本，并用增加额外训练数据集的方式，针对特定评估子集进行了模型性能的优化。最终，研究结果显示增加了数据集的模型在特定评估数据集上有了显著提升，并推断这种改善与模型的泛化能力有关。</div>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2311.12337v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2023-11/2311.12337.md)  |
| <span style='display: inline-block; width: 42px;'>11-21</span> | **AcademicGPT: Empowering Academic Research** - AcademicGPT针对学术研究的特定需求进行了优化，通过结合针对性强的训练数据和多方面的应用开发，为学术领域提供了实质性的支持和工具。它标志着大型语言模型个性化与专业化发展的一个重要步骤，并有望对学术社区产生深远的影响。</div>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2311.12315v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2023-11/2311.12315.md)  |
| <span style='display: inline-block; width: 42px;'>11-21</span> | **Advancing Transformer Architecture in Long-Context Large Language Models: A Comprehensive Survey** - 文章为了解决LLMs在应对长上下文时的挑战，提出了一系列方法和综合分类体系，提高了LLMs在注意力机制、记忆效率和最大长度处理上的性能。通过综合回顾和分类学界最近的进展，本文为未来的LLMs架构设计和优化提供了清晰的指导方向。。</div>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2311.12351v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2023-11/2311.12351.md) <div style='min-width:85px;'>[![GitHub](https://img.shields.io/badge/GitHub-View-brightgreen?logo=github)](https://github.com/Strivin0311/long-llms-learning)</div> |
| <span style='display: inline-block; width: 42px;'>11-20</span> | **Continual Learning: Applications and the Road Forward** - 论文综述了当前的持续学习研究现状，指出了其在记忆限制条件下研究较多而忽视计算成本的问题，并提出了四个有前途的研究方向。这些方向包括：1) 真实世界数据处理的挑战，2) 计算成本的考虑，以及其他如何获取数据和理论理解方面的关注点。论文主张未来的CL算法应在减少对完全标记和封闭世界假设的依赖上做出实质性的进展，以使CL成为解决实际机器学习问题的一个有效工具。</div>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2311.11908v2)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2023-11/2311.11908.md)  |
| <span style='display: inline-block; width: 42px;'>11-20</span> | **Igniting Language Intelligence: The Hitchhiker's Guide From Chain-of-Thought Reasoning to Language Agents** - 本文作为首篇系统性探讨CoT基步机制、范式转变，以及CoT与代理间复杂交互的工作，提供了一些关键见解。文章揭示了CoT在特定条件下显示出的有效性，指出了使CoT工作的多个条件，以及理论和实证研究为其成功提供了何种解释。文章还对CoT理论进行了深入分析，提出了CoT对于LLMs在多个领域的优化和革新可能具有重要的贡献，并指出尽管LLMs、CoT推理和语言代理快速发展，但仍存在未解决的挑战，如对未见领域的泛化、提高交互效率、代理定制化、代理扩展及代理安全性等【10†源】。</div>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2311.11797v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2023-11/2311.11797.md) <div style='min-width:85px;'>[![GitHub](https://img.shields.io/badge/GitHub-View-brightgreen?logo=github)](https://github.com/Zoeyyao27/CoT-Igniting-Agent)</div> |
| <span style='display: inline-block; width: 42px;'>11-20</span> | **Assessing Prompt Injection Risks in 200+ Custom GPTs** - 该论文着重研究了自定义GPT模型中的安全风险，尤其是提示注入攻击。研究者们提出了一个包含扫描、注入敌意提示和提取目标信息三个步骤的攻击方法，并通过实施评估发现自定义GPT模型存在严重的系统提示提取和文件泄露漏洞。这些发现突出了自定义GPT模型中的关键安全缺陷，并指出了提升这些模型安全性结构的必要性。此外，红队评估清楚地显示出，现有防护措施并不足够强大，甚至有时候明确指出不应该分享的信息也能被提取出来，这表明亟需进一步加强对抗提示注入攻击的防御机制。</div>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2311.11538v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2023-11/2311.11538.md)  |
| <span style='display: inline-block; width: 42px;'>11-18</span> | **Orca 2: Teaching Small Language Models How to Reason** - 文章通过介绍一个新的小型语言模型Orca 2，并展示其在多种推理任务上能够与更大的模型相匹敌或超越它们的性能，对当前小型语言模型在复杂推理任务中表现不佳的问题提出了有效的解决方案。Orca 2的开发依赖于对训练数据和训练策略的精心设计，证明了即使是小型模型，也可以通过改进训练方法来增强其理解和推理能力。文章还提供了Orca 2在各种标准测试中的卓越性能结果，验证了其方法论在实际应用中的有效性。</div>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2311.11045v2)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2023-11/2311.11045.md)  |
| <span style='display: inline-block; width: 42px;'>11-18</span> | **RecExplainer: Aligning Large Language Models for Recommendation Model Interpretability** - 文章针对推荐模型解释性的研究提出了一种新型的方法，即通过大型语言模型进行对齐，以提高解释的质量和准确性。文章介绍了三种不同的对齐方法，并通过一系列任务训练LLM以模仿推荐模型的逻辑。论文采用了多种评估策略和评分体系，包括使用最新的GPT-4模型和人类评分来验证所提出方法的有效性，并在三个不同的数据集上进行了测试，显示出其在提高推荐模型解释性方面的潜力。</div>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2311.10947v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2023-11/2311.10947.md)  |
| <span style='display: inline-block; width: 42px;'>11-18</span> | **An Embodied Generalist Agent in 3D World** - LEO是一个新型的身体化、多模态、多任务的通用型智能体，专注于在3D世界中的感知、基础、推理、规划和行动。通过对3D视觉-语言对齐和视觉-语言-动作指令调优的训练，LEO能在3D世界中执行一系列任务。文章通过一系列严格实验和消融实验的结果，证实了LEO在一系列任务上的高效性能，并为未来身体化通用型智能体的发展提供了宝贵洞见。</div>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2311.12871v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2023-11/2311.12871.md)  |
| <span style='display: inline-block; width: 42px;'>11-17</span> | **Exploring the Relationship between In-Context Learning and Instruction Tuning** - 论文提供了ICL与IT之间密切相关的实证证据，即使ICL中不更改模型参数，二者所使用的指令和示例都驱动模型朝着收敛的隐藏状态前进。这一发现对于如何设计高效的数据集和任务以推进基础模型在下游应用的发展和对齐具有启示作用。研究结果还可以帮助理解示例在ICL和IT中的作用，以及如何利用这些见解来设计有效的示例任务和数据集，从而提升LLM的性能。论文中申明将会提供实验代码以供复现。</div>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2311.10367v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2023-11/2311.10367.md)  |
| <span style='display: inline-block; width: 42px;'>11-17</span> | **Camels in a Changing Climate: Enhancing LM Adaptation with Tulu 2** - TÜLU 2通过采用新的基础模型和调整策略，在多个性能指标上实现了突破，对进一步理解和改进预训练语言模型的适配具有重要意义。通过引入新的数据混合物和先进的训练方法（如DPO），TÜLU 2提高了模型在各种推理和知识探测任务上的性能，并在开放式生成指标上取得了显著的提升。此外，研究者们通过公开相关模型、数据和代码，推动了语言模型适配方法的开放研究和发展。</div>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2311.10702v2)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2023-11/2311.10702.md)  |
| <span style='display: inline-block; width: 42px;'>11-16</span> | **Automatic Engineering of Long Prompts** - 本文针对语言模型长指令工程中存在的问题，提出了一种新的算法框架，并解决了贪婪算法易陷入局部最优和遗传算法初期收敛慢的问题。通过对指令的每个句子进行语义保持重述，并利用波束搜索来维护和优化候选指令集合，使算法在有限训练数据上表现出良好的性能和较快的收敛速度。</div>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2311.10117v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2023-11/2311.10117.md)  |
| <span style='display: inline-block; width: 42px;'>11-16</span> | **Predictive Minds: LLMs As Atypical Active Inference Agents** - 本论文将活动推断的概念应用于大型语言模型（LLMs），从一个新的视角分析了LLMs的行为和学习机制。论文提出，尽管LLMs在物理上无法直接与环境互动，但它们通过生成文本在虚拟环境中的“行动”间接影响世界，并有可能将这些影响反馈到模型的训练中。研究指出，增强LLMs与用户交互的反馈循环，将有助于提升模型的自我意识，让其更好地适应和响应环境变化，这将带来重大的社会影响和潜在的风险。论文为理解和改进LLMs在实际部署时的行为提供了重要的理论基础，预测了这些系统未来可能的发展方向。</div>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2311.10215v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2023-11/2311.10215.md)  |
| <span style='display: inline-block; width: 42px;'>11-16</span> | **Crafting In-context Examples according to LMs' Parametric Knowledge** - 本文的重点研究是如何根据LM的参数知识有效地创建上下文示例：选择最优的示例（已知与未知的比较）以及在上下文示例中如何排序答案。实验结果支持了半已知示例的有效性以及基于参数知识的答案排序方法，这些发现为提高大型语言模型在多答案生成任务中的性能提供了可行的技术途径。</div>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2311.09579v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2023-11/2311.09579.md)  |
| <span style='display: inline-block; width: 42px;'>11-16</span> | **MacGyver: Are Large Language Models Creative Problem Solvers?** - 本研究通过创造MACGYVER数据集，探索了LLMs在解决非传统问题上的能力，并通过人类评估员对GPT-4的表现进行了评价。研究结果展示了LLMs在这类任务上的局限性，同时提出了提高其表现的新方法。研究强调了创造性问题解决能力在日常生活中的重要性，并尝试通过LLMs补充人类的创造性思维，以期提高解决问题的能力和效率。</div>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2311.09682v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2023-11/2311.09682.md)  |
| <span style='display: inline-block; width: 42px;'>11-15</span> | **Chain-of-Note: Enhancing Robustness in Retrieval-Augmented Language Models** - 论文提出的CHAIN-OF-NOTE（CON）框架旨在提高RALMs的鲁棒性，主要通过引入结构化的阅读笔记过程来批判性地评估检索到的文档。实验结果表明，该框架提高了模型在噪声数据和未知情况下的健壮性，改善了整体QA性能，并在检索文档失败还是成功时均提高了模型的性能。CON框架通过生成读取笔记和最终回答，提高了模型对噪声的鲁棒性，并在缺乏信息时能够给出“未知”的回答，增强了模型的适应性和可靠性。</div>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2311.09210v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2023-11/2311.0921.md)  |
| <span style='display: inline-block; width: 42px;'>11-15</span> | **Contrastive Chain-of-Thought Prompting** - 本论文提出了对比式链式思维方法，以解决传统链式思维中存在的问题，即缺乏对错误避免的指导以及实现推理效果的不确定性。通过提供有效和无效的推理示例，新方法旨在引导模型减少推理错误并一步步推理，同时该方法提供了自动化构建对比示例的技术以便泛化到各种任务。实验结果证实，该方法能够作为一种通用增强手段，显著提升链式思维的性能。</div>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2311.09277v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2023-11/2311.09277.md)  |
| <span style='display: inline-block; width: 42px;'>11-15</span> | **Memory Augmented Language Models through Mixture of Word Experts** - 本论文提出了一个称为MoWE的新型架构，它通过融合稀疏模型的效率和大型语言模型的性能，出色地处理了性能与计算成本之间的平衡。通过采取创新的设计原则，并且在NLP多种任务中验证了其超越传统模型如T5和MoE的性能，MoWE展示了在学术和实际应用领域的潜力，尤其是在处理知识密集型任务时。</div>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2311.10768v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2023-11/2311.10768.md)  |
| <span style='display: inline-block; width: 42px;'>11-14</span> | **KTRL+F: Knowledge-Augmented In-Document Search** - 文章提出了一个新的问题——KTRL+F，以解决文献搜索中的实时、准确性、引入外部知识的需求。通过分析现有基线，文章发现它们存在局限性，在此基础上提出了Knowledge-Augmented Phrase Retrieval模型。该模型有效地在短语检索中整合了外部知识，通过简单的扩展保持了快速响应，无需额外训练。通过用户研究，证明了该模型能够提升用户搜索体验，减少搜索时间和外部信息检索量。作者鼓励研究社区关注KTRL+F这一独特挑战，提高文献信息访问的效率和效果。</div>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2311.08329v3)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2023-11/2311.08329.md)  |
| <span style='display: inline-block; width: 42px;'>11-14</span> | **Learning to Filter Context for Retrieval-Augmented Generation** - 本文提出的FILCO方法针对开放领域问答和事实验证等知识密集型任务，通过改善提供给生成模型的上下文质量来解决生成输出时面临的问题。通过结合词汇和信息论方法来识别有用上下文，并训练模型以在测试时过滤检索上下文，很好地解决了以前方法的局限性。实验结果显示，相比传统方法，FILCO在多个知识密集型任务上都取得了显著的性能改进，并且在上下文过滤训练上显示出其有效性。</div>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2311.08377v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2023-11/2311.08377.md)  |
| <span style='display: inline-block; width: 42px;'>11-14</span> | **Instruction-Following Evaluation for Large Language Models** - 本文提出了一种评估大型语言模型的指令遵循能力的新方法——IFEval，它通过合成逻辑一致的指令和计算指令遵循准确性的新准则来解决评估过程中的挑战。此方法为自动化且无偏见，它通过多步骤过程避免指令间的潜在冲突，并引入了严格和宽松的准确性评价标准来减少误判，同时认为未来可以通过增加多样化和使用多模态指令来改进该方法。</div>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2311.07911v1)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2023-11/2311.07911.md) <div style='min-width:85px;'>[![GitHub](https://img.shields.io/badge/GitHub-View-brightgreen?logo=github)](https://github.com/google-research/google-research/tree/master/instruction_following_eval)</div> |
| <span style='display: inline-block; width: 42px;'>11-11</span> | **In-context Vectors: Making In Context Learning More Effective and Controllable Through Latent Space Steering** - 本论文提出的ICV方法为大型语言模型的上下文学习提供了一种新颖且更加有效的替代方案。通过将演示示例的关键信息集成到一个可以控制的向量中，ICV方法提高了任务指导的精确度和效果，并显著优于现有的方法。实验结果表明，ICV在多项任务中展现了较高的性能，包括在不同的LLMs上进行语言模型解毒、风格转换和角色扮演。ICV方法的计算开销低，并且易于控制，有助于提升语言模型在实际应用中的适用性和弹性。</div>| <div style='min-width:85px;'>[![arXiv](https://img.shields.io/badge/arXiv-Paper-%23D2691E?logo=arxiv)](http://arxiv.org/pdf/2311.06668v2)</div><div style='min-width:85px;'>[![Summary](https://img.shields.io/badge/Sum.-Read-blue?logo=dependabot)](summary/2023-11/2311.06668.md)  |

---


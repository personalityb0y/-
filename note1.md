#  一、书生·浦语大模型全链路开源体系
大模型已经成为了发展通用人工智能的重要途径，从从前的一个任务一个专用模型逐渐向能够同时解决多模态任务的通用大模型演变。

## Model Zoo

| Model                       | Transformers(HF)                          | ModelScope(HF)                           | OpenXLab(HF)                           | OpenXLab(Origin)                           | Release Date |
| --------------------------- | ----------------------------------------- | ---------------------------------------- | -------------------------------------- | ------------------------------------------ | ------------ |
| **InternLM2-1.8B**          | [🤗internlm2-1.8b](https://huggingface.co/internlm/internlm2-1_8b) | [<img src="./assets/modelscope_logo.png" width="20px" /> internlm2-1.8b](https://www.modelscope.cn/models/Shanghai_AI_Laboratory/internlm2-1_8b/summary) | [![Open in OpenXLab](https://cdn-static.openxlab.org.cn/header/openxlab_models.svg)](https://openxlab.org.cn/models/detail/OpenLMLab/internlm2-base-1.8b) | [![Open in OpenXLab](https://cdn-static.openxlab.org.cn/header/openxlab_models.svg)](https://openxlab.org.cn/models/detail/OpenLMLab/internlm2-base-1.8b-original) | 2024-01-31   |
| **InternLM2-Chat-1.8B-SFT** | [🤗internlm2-chat-1.8b-sft](https://huggingface.co/internlm/internlm2-chat-1_8b-sft) | [<img src="./assets/modelscope_logo.png" width="20px" /> internlm2-chat-1.8b-sft](https://www.modelscope.cn/models/Shanghai_AI_Laboratory/internlm2-chat-1_8b-sft/summary) | [![Open in OpenXLab](https://cdn-static.openxlab.org.cn/header/openxlab_models.svg)](https://openxlab.org.cn/models/detail/OpenLMLab/internlm2-chat-1.8b-sft) | [![Open in OpenXLab](https://cdn-static.openxlab.org.cn/header/openxlab_models.svg)](https://openxlab.org.cn/models/detail/OpenLMLab/internlm2-chat-1.8b-sft-original) | 2024-01-31   |
| **InternLM2-Chat-1.8B**     | [🤗internlm2-chat-1.8b](https://huggingface.co/internlm/internlm2-chat-1_8b) | [<img src="./assets/modelscope_logo.png" width="20px" /> internlm2-chat-1.8b](https://www.modelscope.cn/models/Shanghai_AI_Laboratory/internlm2-chat-1_8b/summary) | [![Open in OpenXLab](https://cdn-static.openxlab.org.cn/header/openxlab_models.svg)](https://openxlab.org.cn/models/detail/OpenLMLab/internlm2-chat-1.8b) | [![Open in OpenXLab](https://cdn-static.openxlab.org.cn/header/openxlab_models.svg)](https://openxlab.org.cn/models/detail/OpenLMLab/internlm2-chat-1.8b-original) | 2024-02-19   |
| **InternLM2-Base-7B**       | [🤗internlm2-base-7b](https://huggingface.co/internlm/internlm2-base-7b) | [<img src="./assets/modelscope_logo.png" width="20px" /> internlm2-base-7b](https://modelscope.cn/models/Shanghai_AI_Laboratory/internlm2-base-7b/summary) | [![Open in OpenXLab](https://cdn-static.openxlab.org.cn/header/openxlab_models.svg)](https://openxlab.org.cn/models/detail/OpenLMLab/internlm2-base-7b) | [![Open in OpenXLab](https://cdn-static.openxlab.org.cn/header/openxlab_models.svg)](https://openxlab.org.cn/models/detail/OpenLMLab/internlm2-base-7b-original) | 2024-01-17   |
| **InternLM2-7B**            | [🤗internlm2-7b](https://huggingface.co/internlm/internlm2-7b) | [<img src="./assets/modelscope_logo.png" width="20px" /> internlm2-7b](https://modelscope.cn/models/Shanghai_AI_Laboratory/internlm2-7b/summary) | [![Open in OpenXLab](https://cdn-static.openxlab.org.cn/header/openxlab_models.svg)](https://openxlab.org.cn/models/detail/OpenLMLab/internlm2-7b) | [![Open in OpenXLab](https://cdn-static.openxlab.org.cn/header/openxlab_models.svg)](https://openxlab.org.cn/models/detail/OpenLMLab/internlm2-7b-original) | 2024-01-17   |
| **InternLM2-Chat-7B-SFT**   | [🤗internlm2-chat-7b-sft](https://huggingface.co/internlm/internlm2-chat-7b-sft) | [<img src="./assets/modelscope_logo.png" width="20px" /> internlm2-chat-7b-sft](https://modelscope.cn/models/Shanghai_AI_Laboratory/internlm2-chat-7b-sft/summary) | [![Open in OpenXLab](https://cdn-static.openxlab.org.cn/header/openxlab_models.svg)](https://openxlab.org.cn/models/detail/OpenLMLab/internlm2-chat-7b-sft) | [![Open in OpenXLab](https://cdn-static.openxlab.org.cn/header/openxlab_models.svg)](https://openxlab.org.cn/models/detail/OpenLMLab/internlm2-chat-7b-sft-original) | 2024-01-17   |
| **InternLM2-Chat-7B**       | [🤗internlm2-chat-7b](https://huggingface.co/internlm/internlm2-chat-7b) | [<img src="./assets/modelscope_logo.png" width="20px" /> internlm2-chat-7b](https://modelscope.cn/models/Shanghai_AI_Laboratory/internlm2-chat-7b/summary) | [![Open in OpenXLab](https://cdn-static.openxlab.org.cn/header/openxlab_models.svg)](https://openxlab.org.cn/models/detail/OpenLMLab/internlm2-chat-7b) | [![Open in OpenXLab](https://cdn-static.openxlab.org.cn/header/openxlab_models.svg)](https://openxlab.org.cn/models/detail/OpenLMLab/internlm2-chat-7b-original) | 2024-01-17   |
| **InternLM2-Base-20B**      | [🤗internlm2-base-20b](https://huggingface.co/internlm/internlm2-base-20b) | [<img src="./assets/modelscope_logo.png" width="20px" /> internlm2-base-20b](https://modelscope.cn/models/Shanghai_AI_Laboratory/internlm2-base-20b/summary) | [![Open in OpenXLab](https://cdn-static.openxlab.org.cn/header/openxlab_models.svg)](https://openxlab.org.cn/models/detail/OpenLMLab/internlm2-base-20b) | [![Open in OpenXLab](https://cdn-static.openxlab.org.cn/header/openxlab_models.svg)](https://openxlab.org.cn/models/detail/OpenLMLab/internlm2-base-20b-original) | 2024-01-17   |
| **InternLM2-20B**           | [🤗internlm2-20b](https://huggingface.co/internlm/internlm2-20b) | [<img src="./assets/modelscope_logo.png" width="20px" /> internlm2-20b](https://modelscope.cn/models/Shanghai_AI_Laboratory/internlm2-20b/summary) | [![Open in OpenXLab](https://cdn-static.openxlab.org.cn/header/openxlab_models.svg)](https://openxlab.org.cn/models/detail/OpenLMLab/internlm2-20b) | [![Open in OpenXLab](https://cdn-static.openxlab.org.cn/header/openxlab_models.svg)](https://openxlab.org.cn/models/detail/OpenLMLab/internlm2-20b-original) | 2024-01-17   |
| **InternLM2-Chat-20B-SFT**  | [🤗internlm2-chat-20b-sft](https://huggingface.co/internlm/internlm2-chat-20b-sft) | [<img src="./assets/modelscope_logo.png" width="20px" /> internlm2-chat-20b-sft](https://modelscope.cn/models/Shanghai_AI_Laboratory/internlm2-chat-20b-sft/summary) | [![Open in OpenXLab](https://cdn-static.openxlab.org.cn/header/openxlab_models.svg)](https://openxlab.org.cn/models/detail/OpenLMLab/internlm2-chat-20b-sft) | [![Open in OpenXLab](https://cdn-static.openxlab.org.cn/header/openxlab_models.svg)](https://openxlab.org.cn/models/detail/OpenLMLab/internlm2-chat-20b-sft-original) | 2024-01-17   |
| **InternLM2-Chat-20B**      | [🤗internlm2-chat-20b](https://huggingface.co/internlm/internlm2-chat-20b) | [<img src="./assets/modelscope_logo.png" width="20px" /> internlm2-chat-20b](https://modelscope.cn/models/Shanghai_AI_Laboratory/internlm2-chat-20b/summary) | [![Open in OpenXLab](https://cdn-static.openxlab.org.cn/header/openxlab_models.svg)](https://openxlab.org.cn/models/detail/OpenLMLab/internlm2-chat-20b) | [![Open in OpenXLab](https://cdn-static.openxlab.org.cn/header/openxlab_models.svg)](https://openxlab.org.cn/models/detail/OpenLMLab/internlm2-chat-20b-original) | 2024-01-17   |

**模型说明：**

在此次发布中，InternLM2 包含两种模型规格：7B 和 20B。7B 为轻量级的研究和应用提供了一个轻便但性能不俗的模型，20B 模型的综合性能更为强劲，可以有效支持更加复杂的实用场景。每个规格不同模型关系如下图所示：
补充： 新增1.8B 依然很棒

![](https://internlm.oss-cn-shanghai.aliyuncs.com/series.png)

书生浦语全链条开放体系提供了数据、预训练、微调、部署、评测和应用的一条龙服务框架

## 全链路开源

数据 -> 预训练 -> 微调 ->  部署 -> 评测 -> 应用

### 数据  
开放高质量数据集，数据集获取：https://opendatalab.org.cn/


#  二、InternLM2技术报告
综述
该报告详细阐述了InternLM2的基础设施、模型结构、预训练数据、预训练设置、预训练阶段、对齐策略、评估和分析等内容。该模型在多个维度和基准测试中展现出了超越先前方法的能力。特别介绍了通过创新的预训练和优化技术，使得该模型在长序列建模和开放性主观评估方面表现得更加突出。

主要贡献
模型开源与发布： InternLM2以不同规模（18亿、70亿和200亿参数）的模型形式公开发布，这些模型在主观和客观评估中都展现出了卓越的性能。 报告还发布了不同训练阶段的模型，以便社区能够分析监督微调（SFT）和基于人类反馈的条件在线强化学习（Conditional Online RLHF）训练后的模型变化。

长序列处理能力： InternLM2设计了具有200k上下文窗口的能力，使其在长序列任务中表现出色。特别是在“大海捞针”实验中，使用200k上下文几乎完美地识别出所有目标。 报告分享了在整个训练过程中（预训练、SFT和RLHF）训练长序列语言模型的经验和策略。

数据准备指南： 报告详细阐述了数据准备的各个环节，包括预训练数据、领域特定增强数据、SFT数据和RLHF数据的收集、处理和使用。 这些详细的数据准备指南将有助于社区更好地理解和训练LLMs，提高模型性能和泛化能力。

创新的RLHF训练技术：

报告引入了条件在线RLHF（COOL RLHF）方法，用于协调不同的偏好，从而显著提高了InternLM2在各种主观对话评估中的性能。 报告还进行了初步的主观和客观RLHF结果的分析和比较，为社区提供了对RLHF技术的深入理解。

训练框架
InternEvo作为训练框架，在预训练、SFT和RLHF阶段展现了高效性和扩展性，通过数据并行等技术优化训练效率，支持灵活微调，并整合人类反馈优化模型表现，为大型语言模型的开发提供了坚实基础。

模型架构
该模型架构基于LLaMA的设计原则，不仅继承了RMSNorm和SwiGLU激活函数的优点，还在权重矩阵和注意力机制方面进行了创新。具体来说，模型对权重矩阵Wk、Wq、Wv进行了精心调整，以更好地支持不同的张量并行转换，从而显著提高了训练速度。这一改进使得模型在处理大规模数据时能够更加高效。

为了支持长上下文的处理，模型引入了分组查询注意力（GQA）结构。这种结构使得模型在处理非常长的上下文时能够保持高速运算和低GPU显存消耗，从而扩展了模型的应用范围。GQA结构通过分组处理查询向量，有效降低了计算复杂度和内存需求，使得模型在处理长文本时更加高效稳定。



预训练数据
预训练数据是构建大型语言模型（LLM）的基石，对于模型的性能至关重要。在本项目中，使用了海量的文本数据作为预训练数据，这些数据涵盖了多个领域，包括新闻、科技、文学、社交媒体等。通过收集这些多样化的数据，确保了模型能够从多个角度学习语言的规律和结构。

在数据预处理阶段，对原始数据进行了清洗和过滤，去除了重复、低质量和与任务不相关的内容。同时，还进行了分词、词频统计等处理，以便模型更好地理解和处理文本数据。

预训练设置
在预训练阶段，采用了多机多卡的方式进行分布式训练，以充分利用计算资源。具体来说，我们使用了数百个GPU进行并行训练，以加速模型的收敛速度。

在模型设置方面，采用了LLaMA的结构设计原则，并在此基础上进行了一些改进。使用了RMSNorm作为归一化方法，并采用了SwiGLU作为激活函数。这些选择有助于提高模型的稳定性和性能。

此外，还对模型的超参数进行了精心调整，包括学习率、批处理大小、训练轮数等。通过多次实验和调优，找到了一组适合本项目的超参数设置。

预训练阶段
预训练阶段是整个模型构建过程中最为耗时的部分。在这个阶段，模型通过无监督学习的方式从预训练数据中学习语言的规律和结构。采用了大规模并行化的训练策略，以加快训练速度。

在训练过程中，使用了梯度下降等优化算法来更新模型的参数。同时，还采用了学习率衰减、梯度裁剪等技术来防止模型过拟合和梯度爆炸等问题。

随着训练的进行，模型的性能逐渐提升，能够更好地理解和生成自然语言文本。

对齐策略
在对齐策略方面，采用了对齐损失函数来确保模型在生成文本时能够保持与原始文本的一致性。具体来说，计算了生成文本与原始文本之间的相似度或距离，并将其作为损失函数的一部分进行优化。

通过优化对齐损失函数，能够使模型在生成文本时更好地保留原始文本的信息和意图，提高生成文本的质量和相关性。



评估和分析
为了评估模型的性能，采用了多种评估指标，包括困惑度（Perplexity）、BLEU分数、ROUGE分数等。这些指标能够从不同角度评估模型在文本生成和理解方面的能力。

通过对模型在不同数据集和任务上的评估，发现模型在多个方面都取得了显著的性能提升。同时，还对模型的内部表示进行了可视化分析，以更好地理解其工作原理和性能瓶颈。

总结
通过模型开发的一系列创新细节处理，使得Internlm2模型在多个领域都展现出了良好的性能。同时开发了一整条开发项目的进展框架，能够针对每一个步骤进行专门的处理，能够使大家很好的学习相关的开发流程和知识，推流llm领域的发展。

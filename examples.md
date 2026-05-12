# 输入输出示例

本文件提供完整的输入输出示例，供 agent 参考改写风格和输出格式。

---

## 示例 1：中文纯文本 - AIGC降率模式

### 用户输入

> 帮我降AIGC
>
> 随着人工智能技术的快速发展，深度学习已经成为计算机视觉领域的核心技术。卷积神经网络通过多层特征提取，能够自动学习图像中的层次化表示。首先，浅层网络提取边缘和纹理等低级特征；其次，中间层网络捕获形状和部件等中级特征；最后，深层网络学习语义级别的高级特征。因此，深度学习模型能够在图像分类、目标检测和语义分割等任务中取得优异的性能。然而，深度学习模型通常需要大量标注数据进行训练，这在一定程度上限制了其在数据稀缺场景下的应用。

### 输出

## 改写结果

人工智能技术近年来发展迅速，深度学习已逐步成为计算机视觉领域中较为核心的技术手段。卷积神经网络的基本机制在于通过多层特征提取，使模型能够自动习得图像中不同层次的表示。就网络结构而言，浅层部分主要负责提取边缘与纹理等低级特征；中间层则进一步捕获形状及部件等具有一定抽象性的中级特征；深层网络在此基础上学习语义级别的高级特征。正是由于具备这种层次化的特征学习能力，深度学习模型在图像分类、目标检测、语义分割等任务中均取得了较为突出的性能表现。但需要指出的是，此类模型通常依赖大量标注数据进行训练，这在一定程度上制约了其在数据稀缺场景下的推广应用。

## 修改说明

- 第1句：将"随着...的快速发展"改为"近年来发展迅速"，消除 AI 典型的"随着"开头句式
- 第2句：将"通过...能够..."改为"基本机制在于..."的解释性句式，调整了语序
- 第3-5句：去掉"首先、其次、最后"的 AI 典型排列，改为"就...而言""则进一步""在此基础上"等更多样的学术过渡
- 第6句：将"因此"替换为"正是由于"，调整句式结构
- 第7句：将"然而"替换为"但需要指出的是"，使用学术性的限定表达

---

## 示例 2：中文 LaTeX - AIGC降率模式

### 用户输入

> 帮我降AIGC
>
> ```latex
> 近年来，深度学习技术在自然语言处理领域取得了显著进展\cite{devlin2019bert}。
> 预训练语言模型通过在大规模语料库上进行无监督学习，能够捕获丰富的语言知识。
> 其中，\textbf{BERT}模型采用了Transformer编码器架构，
> 通过掩码语言模型（Masked Language Model）和下一句预测（Next Sentence Prediction）
> 两个预训练任务来学习双向上下文表示\cite{vaswani2017attention}。
> 实验结果表明，BERT在多项自然语言理解基准测试中均取得了当时最优的性能，
> 如表\ref{tab:bert_results}所示。
> ```

### 输出

## 改写结果（LaTeX）

```latex
深度学习技术在自然语言处理领域的发展近些年较为迅速，已取得了一系列值得关注的成果\cite{devlin2019bert}。
预训练语言模型的核心思路在于借助大规模语料库开展无监督学习，
使模型能够获取较为丰富的语言知识。
\textbf{BERT}作为其中具有代表性的模型之一，
其架构基于Transformer编码器，
预训练阶段采用了掩码语言模型（Masked Language Model）与下一句预测（Next Sentence Prediction）
两项任务，以此习得双向上下文表示\cite{vaswani2017attention}。
从实验结果来看，BERT在多项自然语言理解基准测试中均达到了当时的最优水平，
相关数据详见表\ref{tab:bert_results}。
```

## 改写结果（纯文本预览）

深度学习技术在自然语言处理领域的发展近些年较为迅速，已取得了一系列值得关注的成果。预训练语言模型的核心思路在于借助大规模语料库开展无监督学习，使模型能够获取较为丰富的语言知识。BERT作为其中具有代表性的模型之一，其架构基于Transformer编码器，预训练阶段采用了掩码语言模型（Masked Language Model）与下一句预测（Next Sentence Prediction）两项任务，以此习得双向上下文表示。从实验结果来看，BERT在多项自然语言理解基准测试中均达到了当时的最优水平，相关数据详见表。

## 修改说明

- 第1句：将"近年来...取得了显著进展"重组为"发展近些年较为迅速，已取得了..."，打破 AI 典型的"近年来"开头
- 第2句：将"通过...能够捕获"改为"核心思路在于借助...使模型能够获取"，调整句式结构
- 第3句：将"其中...采用了"改为"作为其中具有代表性的模型之一，其架构..."，调整主语引入方式
- 第4句：将"实验结果表明"改为"从实验结果来看"，将"如表X所示"改为"相关数据详见表"
- 所有 `\cite{}`、`\ref{}`、`\textbf{}` 标记完整保留

---

## 示例 3：英文摘要 - AIGC降率模式

### 用户输入

> Help me reduce AIGC detection rate
>
> This paper presents a comprehensive study on the application of deep learning techniques in medical image analysis. We propose a novel convolutional neural network architecture that effectively addresses the challenges of limited training data in medical imaging. Our experimental results demonstrate that the proposed method achieves state-of-the-art performance on three benchmark datasets, with significant improvements in accuracy and robustness compared to existing approaches.

### 输出

## 改写结果

This paper investigates the application of deep learning techniques to medical image analysis, a field that has attracted considerable research interest. A convolutional neural network architecture is proposed in this work, with the specific aim of addressing the challenge posed by limited training data in the medical imaging domain. Evaluation on three benchmark datasets indicates that the proposed method attains state-of-the-art performance, yielding notable improvements in both accuracy and robustness relative to several existing approaches.

## 修改说明

- Sentence 1: Replaced "presents a comprehensive study on" with "investigates the application of...to", restructured the clause order
- Sentence 2: Changed from "We propose" to passive voice "is proposed in this work", replaced "effectively addresses" with "addressing the challenge posed by"
- Sentence 3: Replaced "Our experimental results demonstrate that" with "Evaluation on...indicates that", changed "significant improvements" to "notable improvements", replaced "compared to" with "relative to"

---

## 示例 4：中文纯文本 - 传统降重模式

### 用户输入

> 帮我降重
>
> 随机森林算法是一种基于集成学习的分类方法，它通过构建多棵决策树并将它们的预测结果进行投票来得到最终的分类结果。每棵决策树在训练时使用的是原始数据集的一个随机子集，同时在每个节点分裂时也只考虑特征的一个随机子集。这种随机性使得各棵树之间具有较大的差异性，从而有效降低了模型的过拟合风险。

### 输出

## 改写结果

随机森林是一种以集成学习为基础的分类手段，其核心思路是建立若干棵决策树，再将各棵树的预测输出通过投票机制汇总，得出最终的分类判定。在训练阶段，每棵决策树所使用的并非完整的原始数据集，而是从中随机抽取的一个子集；与此同时，节点进行分裂时也仅从特征空间中随机选取部分特征加以考量。上述随机化处理带来了各棵树之间较为明显的个体差异，进而在一定程度上抑制了模型的过拟合现象。

## 修改说明

- 第1句：将"基于集成学习的分类方法"改为"以集成学习为基础的分类手段"；将"构建多棵决策树并将它们的预测结果进行投票"重组为"建立若干棵决策树，再将各棵树的预测输出通过投票机制汇总"
- 第2句：将"使用的是"改为"所使用的并非...而是..."的否定-肯定句式；将"只考虑特征的一个随机子集"改为"仅从特征空间中随机选取部分特征加以考量"
- 第3句：将"这种随机性"改为"上述随机化处理"；将"具有较大的差异性"改为"较为明显的个体差异"；将"有效降低了...过拟合风险"改为"在一定程度上抑制了...过拟合现象"

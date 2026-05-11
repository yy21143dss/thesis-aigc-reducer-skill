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

人工智能技术这几年发展得很快，深度学习也因此在计算机视觉领域占据了比较核心的位置。拿卷积神经网络来说，它的工作方式是通过多层特征提取，让模型自己去学习图像中不同层次的表示——这一点其实挺关键的。具体而言，网络浅层主要负责提取边缘、纹理这类偏底层的特征；到了中间层，网络开始捕获一些更抽象的东西，比如形状和物体的局部结构；而深层网络则进一步学习到语义层面的高级特征。正因为有这样的层次化学习能力，深度学习在图像分类、目标检测、语义分割等任务上，表现确实不错。不过话说回来，这类模型对标注数据的需求量很大，一旦数据不够充足，应用起来就会受到不少限制。

## 修改说明

- 第1句：将"随着...的快速发展"改为更口语化的"这几年发展得很快"，去除 AI 典型的"随着"句式
- 第2句：加入"拿...来说"的个人化引入方式，插入破折号补充说明
- 第3-5句：去掉"首先、其次、最后"的 AI 典型排列，改为"具体而言""到了中间层""而深层"的自然过渡
- 第6句：将"因此"替换为"正因为"，用逗号衔接而非另起一句
- 第7句：将"然而"替换为"不过话说回来"，更口语化；重组句式

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
深度学习技术在自然语言处理这一领域的进展，近些年可以说是相当明显的\cite{devlin2019bert}。
预训练语言模型的基本思路是在大规模语料库上做无监督学习，
从而让模型获得比较丰富的语言知识——这也是目前主流方法的核心所在。
在众多模型中，\textbf{BERT}算是比较有代表性的一个，
它的底层架构基于Transformer编码器，
训练过程中主要依赖两个任务：一个是掩码语言模型（Masked Language Model），
另一个是下一句预测（Next Sentence Prediction），
目的是学习双向的上下文表示\cite{vaswani2017attention}。
从实验数据来看，BERT在好几项自然语言理解基准测试上都拿到了当时的最好成绩，
具体数据见表\ref{tab:bert_results}。
```

## 改写结果（纯文本预览）

深度学习技术在自然语言处理这一领域的进展，近些年可以说是相当明显的。预训练语言模型的基本思路是在大规模语料库上做无监督学习，从而让模型获得比较丰富的语言知识——这也是目前主流方法的核心所在。在众多模型中，BERT算是比较有代表性的一个，它的底层架构基于Transformer编码器，训练过程中主要依赖两个任务：一个是掩码语言模型（Masked Language Model），另一个是下一句预测（Next Sentence Prediction），目的是学习双向的上下文表示。从实验数据来看，BERT在好几项自然语言理解基准测试上都拿到了当时的最好成绩，具体数据见表。

## 修改说明

- 第1句：将"近年来...取得了显著进展"倒装为"进展...近些年可以说是相当明显的"，打破 AI 典型的"近年来"开头
- 第2句：改为"基本思路是..."的解释性句式，加入破折号插入语
- 第3句：加入"算是比较有代表性的一个"这类个人化表达，将并列描述改为口语化的"一个是...另一个是..."
- 第4句：将"实验结果表明"改为"从实验数据来看"，将"如表X所示"改为"具体数据见表"
- 所有 `\cite{}`、`\ref{}`、`\textbf{}` 标记完整保留

---

## 示例 3：英文摘要 - AIGC降率模式

### 用户输入

> Help me reduce AIGC detection rate
>
> This paper presents a comprehensive study on the application of deep learning techniques in medical image analysis. We propose a novel convolutional neural network architecture that effectively addresses the challenges of limited training data in medical imaging. Our experimental results demonstrate that the proposed method achieves state-of-the-art performance on three benchmark datasets, with significant improvements in accuracy and robustness compared to existing approaches.

### 输出

## 改写结果

In this paper, we look into how deep learning techniques can be applied to medical image analysis — a topic that has drawn quite a bit of attention in recent years. The main contribution here is a new convolutional neural network architecture, designed with the specific goal of tackling the limited training data problem that medical imaging often faces. We tested the proposed method on three benchmark datasets, and the results turned out to be fairly encouraging: it achieved what can be considered state-of-the-art performance, showing notable gains in both accuracy and robustness over several existing approaches.

## 修改说明

- Sentence 1: Replaced "presents a comprehensive study" with the more conversational "we look into", added a dash-separated aside
- Sentence 2: Restructured from passive to active voice, added "designed with the specific goal of" for a more personal tone
- Sentence 3: Broke the formal "Our experimental results demonstrate that" into a more narrative flow with "We tested...and the results turned out to be", softened "significant improvements" to "notable gains"

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

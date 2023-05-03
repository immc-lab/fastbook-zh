# **The Fastai Book**——你的中文快速AI上手指南🧭

<a href="https://creativecommons.org/licenses/by/4.0/">[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg "title")](https://colab.research.google.com/github/immc-lab/fastbook-zh/blob/main/)<img src="https://img.shields.io/github/stars/immc-lab/fastbook-zh.svg"><img src="https://img.shields.io/github/watchers/immc-lab/fastbook-zh.svg"></a>

### 注意：

- **为了方便国内读者阅读，本书主要对[fastai](https://github.com/fastai/fastai)进行翻译，同时保留原英语原文，以便读者对比学习。**在翻译的过程中，我们也对文本进行了润色和校对，以确保翻译的准确性和流畅性。
- 如果您发现任何错误、不适当或过时的内容，请考虑打开一个问题(issue)或一个拉取请求(PR)。我们非常感谢您为这个库做出的贡献！
- **如果你觉的有用，请点亮一个🌟吧！**



### 简介与声明：

这些notebook包含了对深度学习，[fastai](https://docs.fast.ai/)，以及[PyTorch](https://pytorch.org/)的介绍。fastai是一个用于深度学习的分层API；要了解更多信息，请阅读[the fastai paper](https://www.mdpi.com/2078-2489/11/2/108)论文。本repo的所有内容的版权都属于Jeremy Howard和Sylvain Gugger，自2020年起。

这些notebook被用于[一个MOOC课程](https://course.fast.ai/)，并且是[这本书](https://www.amazon.com/Deep-Learning-Coders-fastai-PyTorch/dp/1492045527)（目前可供购买）的基础。书籍并没有本稿的GPL限制。

notebook 里的代码以及 python 的 `.py` 文件受到 GPL v3 开源协议的保护；更多详情请查看 LICENSE 文件。

其余部分（包括 notebook 里的 markdown 单元以及其他文字内容）可以用于重新发布，调整格式或者载体。你可以复制这里的 notebook 或者 fork 本 repo 用于个人目的。但是任何商业传播行为都是不被允许的。我们制作这些资料是用来帮助你学习深度学习的，所以请遵守我们的版权以及上述限制.

如果你在别的地方发现任何人持有这些资料的副本，请告诉他们，他们的行为是不被允许的，并可能导致法律措施被采取。而且，他们可能会对社区造成伤害。这是因为如果人们忽视我们的版权，我们可能不会再像这样发布新的资料。

这些资料还属于初稿阶段。如果你在运行这些 notebook 时遇到困难，请尝试在[fastai-dev forum](https://forums.fast.ai/c/fastai-users/fastai-dev/)搜索或者寻求帮助。请不要因为运行 notebook 中遇到的问题而使用 GitHub issues。



### 在Colab平台进行学习

您可以使用[Google Colab](https://research.google.com/colaboratory/)来阅读和处理笔记本，而不是克隆此仓库并在本地打开。这是给初学者推荐的方法——无需在您自己的计算机上设置Python开发环境，因为您可以直接在网络浏览器中进行工作。

您可以通过单击以下链接之一在 Colab 中打开本书的任何章节：

[第一章：介绍](https://colab.research.google.com/github/immc-lab/fastbook-zh/blob/main/01_intro.ipynb) 

[第二章：生产](https://colab.research.google.com/github/immc-lab/fastbook-zh/blob/main/02_production.ipynb) 

[第三章：道德问题](https://colab.research.google.com/github/immc-lab/fastbook-zh/blob/main/03_ethics.ipynb) 

[第四章：MNIST基础](https://colab.research.google.com/github/immc-lab/fastbook-zh/blob/main/04_mnist_basics.ipynb) 

[第五章：宠物品种](https://colab.research.google.com/github/immc-lab/fastbook-zh/blob/main/05_pet_breeds.ipynb) 

[第六章：多类别分类](https://colab.research.google.com/github/immc-lab/fastbook-zh/blob/main/06_multicat.ipynb) 

[第七章：模型大小和TTA](https://colab.research.google.com/github/immc-lab/fastbook-zh/blob/main/07_sizing_and_tta.ipynb) 

[第八章：协同过滤](https://colab.research.google.com/github/immc-lab/fastbook-zh/blob/main/08_collab.ipynb) 

[第九章：表格数据](https://colab.research.google.com/github/immc-lab/fastbook-zh/blob/main/09_tabular_ipynb.ipynb) 

[第十章：NLP](https://colab.research.google.com/github/immc-lab/fastbook-zh/blob/main/10_nlp.ipynb) 

[第十一章：中级API](https://colab.research.google.com/github/immc-lab/fastbook-zh/blob/main/11_midlevel_data.ipynb) 

[第十二章：深入探讨自然语言处理](https://colab.research.google.com/github/immc-lab/fastbook-zh/blob/main/12_nlp_dive.ipynb) 

[第十三章：卷积](https://colab.research.google.com/github/immc-lab/fastbook-zh/blob/main/13_convolutions.ipynb) 

[第十四章：Resnet](https://colab.research.google.com/github/immc-lab/fastbook-zh/blob/main/14_resnet.ipynb) 

[第十五章：架构细节](https://colab.research.google.com/github/immc-lab/fastbook-zh/blob/main/15_arch_details.ipynb) 

[第十六章：优化器和回调函数](https://colab.research.google.com/github/immc-lab/fastbook-zh/blob/main/16_accel_sgd.ipynb) 

[第十七章，基础知识](hhttps://colab.research.google.com/github/immc-lab/fastbook-zh/blob/main/17_foundations.ipynb) 

[第十八章：GradCAM](https://colab.research.google.com/github/immc-lab/fastbook-zh/blob/main/18_CAM.ipynb) 

[第十九章：一个AI学者](https://colab.research.google.com/github/immc-lab/fastbook-zh/blob/main/19_learner.ipynb) 

[第二十章：结论](https://colab.research.google.com/github/immc-lab/fastbook-zh/blob/main/20_conclusion.ipynb)



### Contributors 

<p align="center"><a href="https://github.com/huaiwen"><img src="https://avatars.githubusercontent.com/u/3187529?v=4" width="50px" alt="robinicus" /></a>&nbsp;&nbsp;<a href="https://github.com/YangYang"><img src="https://avatars.githubusercontent.com/u/17808880?v=4" width="50px" alt="0xmatchmaker" /></a>&nbsp;&nbsp;<a href="https://github.com/guozihang"><img src="https://avatars.githubusercontent.com/u/17142416?v=4" width="50px" alt="0xmatchmaker" /></a>&nbsp;&nbsp;<a href="https://github.com/LeeRoc-China"><img src="https://avatars.githubusercontent.com/u/59104898?s=400&u=c225a082a6a410e3d7c84ca29a07d723d7308dca&v=4" width="50px" alt="0xmatchmaker" /></a>&nbsp;&nbsp;<a href="https://github.com/baiw123"><img src="https://avatars.githubusercontent.com/u/106874386?v=4" width="50px" alt="0xmatchmaker" /></a>&nbsp;&nbsp;<a href="https://github.com/zhangziyi1670"><img src="https://avatars.githubusercontent.com/u/75550266?v=4" width="50px" alt="0xmatchmaker" /></a>&nbsp;&nbsp;<a href="https://github.com/yangqqq-yq"><img src="https://avatars.githubusercontent.com/u/37734579?v=4" width="50px" alt="0xmatchmaker" /></a>&nbsp;&nbsp;<a href="https://github.com/ASHES-G"><img src="https://avatars.githubusercontent.com/u/106022375?v=4" width="50px" alt="0xmatchmaker" /></a>&nbsp;&nbsp;<a href="https://github.com/yannaixin001"><img src="https://avatars.githubusercontent.com/u/106919860?v=4" width="50px" alt="0xmatchmaker" /></a>&nbsp;&nbsp;</p>

该项目遵循全贡献者规范(all-contributors specification)。

欢迎任何形式的贡献！


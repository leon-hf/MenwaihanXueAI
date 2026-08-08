# 门外汉学 AI，不用怕！

> 最通俗的讲AI，最硬核的算法，文科生都能听懂的AI！

从零开始，用最通俗的方式讲透 AI 核心技术。共 58 篇文章，覆盖 7 大系列，配 255 张图解。

## 两种阅读方式

### 方式一：在线阅读（GitHub Pages）

直接访问 GitHub Pages 在线阅读，支持精美排版、公式渲染、代码高亮：

- 首页目录：`https://<你的用户名>.github.io/<仓库名>/`
- 每篇文章：`https://<你的用户名>.github.io/<仓库名>/sample_第XX篇.html`

### 方式二：离线 Markdown

仓库根目录下的 `.md` 文件即为 Markdown 源文件，可下载到本地用任意 Markdown 编辑器阅读，也可用 Typora、Obsidian 等工具导出为 PDF / EPUB。

## 目录结构

```
.
├── index.html                # 在线目录页
├── sample_第01篇.html        # 第01篇 HTML（mdnice 风格）
├── sample_第02篇.html
├── ...
├── sample_第58篇.html
├── 门外汉学 AI，不用怕！（1）... .md   # 第01篇 Markdown 源文件
├── 门外汉学 AI，不用怕！（2）... .md
├── ...
├── images/                   # 图片资源
│   ├── 第05篇/               # 公共资源（封面、H2图标）
│   ├── 第01篇/
│   ├── ...
│   └── 第58篇/
├── .nojekyll                 # 禁用 Jekyll（GitHub Pages 必需）
└── README.md                 # 本文件
```

## 内容概览

| 系列 | 篇号 | 篇数 | 简介 |
|------|:---:|:---:|------|
| 基础入门 | 1-7 | 7 | AI 基本概念、模型/参数、机器学习核心思想 |
| 深度学习与ML算法 | 8-22 | 15 | 训练/损失/前向反向传播、逻辑回归/决策树/SVM/朴素贝叶斯/KNN/聚类/PCA/SVD、CNN |
| NLP 系列技术 | 23-36 | 14 | Word2vec → RNN → Seq2Seq → Attention → Transformer（六讲） |
| DeepSeek 系列 | 37-39 | 3 | MoE / MLA / MTP / RoPE / RMSNorm 等核心技术创新 |
| 大模型评估 | 40 | 1 | MMLU / GSM8K / HumanEval / Chatbot Arena 等评测体系 |
| 多模态大模型 | 41-46 | 6 | CLIP → Flamingo → BLIP-2 → LLaVA → Stable Diffusion |
| 强化学习 | 47-58 | 12 | MDP → 贝尔曼方程 → SARSA/Q-Learning → DQN → 策略梯度 → PPO/DPO/GRPO |

## 部署到 GitHub Pages

```bash
# 1. 创建 GitHub 仓库（假设名为 ai-book）

# 2. 初始化并推送
cd 门外汉学AI\(第三稿\)
git init
git add .
git commit -m "门外汉学AI 全58篇"
git branch -M main
git remote add origin https://github.com/<你的用户名>/ai-book.git
git push -u origin main

# 3. 开启 GitHub Pages
#    进入仓库 Settings → Pages
#    Source 选 Deploy from a branch
#    Branch 选 main / (root)
#    保存后等待 1-2 分钟即可访问
```

## License

本项目内容版权归原作者所有。

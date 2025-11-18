<div align=center>
  <h1>Applications</h1>
  <p><a href="./README.md">View English</a></p>
</div>

本仓库提供了系列精心整理的基于 MindSpore 实现的应用案例，覆盖计算机视觉、自然语言处理、生成对抗网络、扩散模型、大语言模型、检索增强生成及智能体等领域。所有案例按领域和模型分类归档，为各类代表性任务提供可复用的实践方案。

## 📢 最新消息

- 2025-11-18 [功能优化]：重构仓库结构以优化应用导航体验；新增Issue与PR模板，让贡献流程更标准化。

## 前置知识

在学习本门课程之前，您需要掌握：

- Python基础
- Linux命令基础
- Jupyter基础
- Docker镜像使用

您可以通过前置学习考试进行自检。

## 环境准备

为确保项目仓中实践代码可正常运行，推荐以下环境准备方式。更多详细的环境准备指南详见[Wiki](https://github.com/mindspore-courses/applications/wiki/Set-Up-Development-Environment)。

### 直接安装依赖

请先确保 Python 版本符合[课程要求](#版本维护)后，进入仓库根目录，执行：

```bash
pip install requirements.txt
```

### 使用Docker镜像

为方便开发者更加便捷地进行代码实践，节约环境准备的时间，我们提供了预装好的基础Dockerfile文件。课程的所有镜像可从[dockerfile](./dockerfile/)获取。本课程镜像文件信息如下，开发者可根据实际需求进行拉取：

| 硬件平台 | 镜像名称        | 标签      |  说明                     | Dockerfile文件 |
| :------ | :-------------- | :------- | :------------------------ | :------------- |
| CPU     | xxx             | xxx      | xxx                       | xxx            |
| GPU     | xxx             | xxx      | xxx                       | xxx            |
| NPU     | xxx             | xxx      | xxx                       | xxx            |

镜像基础使用教程详见环境准备Wiki中的[Docker镜像使用](https://github.com/mindspore-courses/applications/wiki/Set-Up-Development-Environment)部分。

## 案例清单

| 序号 | 领域 |
| :-- | :----- |
| 1   | [CV](./cv/) |
| 2   | [NLP](./nlp/) |
| 3   | [GAN](./gan/) |
| 4   | [Diffusion](./diffusion) |
| 5   | [LLM](./cv/) |
| 6   | [Multi-Modal](./multi-modal/) |
| 7   | [OrangePi](https://github.com/mindspore-courses/orange-pi-mindspore) |
| 8   | [RAG](./rag/) |
| 9   | [Agent](./agent/) |

## 版本维护

项目随昇思MindSpore及昇思MindSpore NLP套件迭代同步发布版本。

| 版本名  | Python | MindSpore | MindSpore NLP |
| :----- | :----- |:------ |:------ |
| dev   | >=3.9, <=3.11 | 2.7.1    | 0.5.1    |

## 常见问题（FAQ）

详见Wiki中[FAQ](https://github.com/mindspore-courses/applications/wiki/Developer-FAQ)。

## 贡献与反馈

欢迎各位开发者通过 [Issue](https://github.com/mindspore-courses/applications/issues) 提交建议或 bug 反馈，也可直接发起 [PR](https://github.com/mindspore-courses/applications/pulls) 进行Bug修复或代码贡献（提交前请参考提交规范，由Committer @xing-yiren 及另一位committer 完成评审合入），你的每一份参与都能让本项目更加完善。

### 提交规范

详见WIKI：[Issue与PR提交规范](https://github.com/mindspore-courses/applications/wiki/Contributing-Guidelines)

### 贡献者展示

向本项目的贡献者们致以最诚挚的感谢！

<div align=center style="margin-top: 30px;">
  <a href="https://github.com/mindspore-courses/applications/graphs/contributors">
    <img src="https://contrib.rocks/image?repo=mindspore-courses/applications" />
  </a>
</div>

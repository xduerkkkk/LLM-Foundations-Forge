# LLM Foundations Forge (大语言模型基础锻造厂)

欢迎来到【LLM基础锻造厂】。

在这个项目中，我们的使命只有一个：**将构建大语言模型所需的核心“知识原子”，一块一块地锻造成逻辑清晰、洞见深刻、可供实践的“基石”。**

我们相信，理解一个复杂系统的最好方式，就是亲手重建它的地基。

---

## ✨ 项目理念

*   **第一性原理:** 我们不满足于“调用API”，而是致力于“打开黑箱”，探究每个核心组件背后的数学与设计哲学。
*   **文码结合:** 每一篇深度解析文章，都配有可运行、可复现的Jupyter Notebook，实现理论与实践的无缝对接。
*   **叙事驱动:** 我们将沿着技术的演进脉络，讲述从简单到复杂的故事，揭示每个思想诞生的历史必然性。

---

## 🗺️ 当前锻造系列：解构Transformer (Deconstructing Transformer)

这是我们进入LLM世界的第一站，也是最重要的一站。我们将分三步，彻底解构这个革命性的架构。

### **第一部：变革前夜 —— RNN的瓶颈与Attention的曙光**

*   **📖 文章 :** 
     *   [**[中文原文]**](./articles/01_Why_Transformer.md) 
    *   [**[博客发布版]**](https://blog.csdn.net/xuderkk/article/details/153396195?spm=1001.2014.3001.5502) 
    *   **状态:** ✅ **已发布**
*   **💻 配套代码:**
    *   `notebooks/01_The_Sequence_Problem_and_RNN_Solution_Demo.ipynb`
    *   **核心内容:** 通过代码实验，生动复现静态词向量的“语序丢失”问题，并展示RNN如何从机制上解决它。包含一个【选读】部分，从零实现一个基础RNN。
    *   **状态:** ✅ **已发布**

### **第二部：核心引擎 —— 深入理解Self-Attention与Multi-Head Attention**

*   **📖 文章:** 
    *   [**[中文原文]**](./articles/02_对Attention机制的深度可视化解剖.md)
    *   [**[博客发布版]**](https://blog.csdn.net/xuderkk/article/details/153882923?spm=1001.2014.3001.5501) 
    *   **状态:** ✅ **已发布**
*   **💻 配套代码:**
    *   `notebooks/02a_Visualizing_the_Attention_Mechanism.ipynb`
    *   **核心内容:** 通过代码实验，生动可视化attention、crossattention、multiheadattention、位置编码
    *   **状态:** ✅ **已发布*

### **第三部：宏伟蓝图 —— 组装完整的Transformer**

*   **📖 文章:** *(规划中...)*
    *   **状态:** 🗓️ **规划中**

---

## 🚀 如何开始 (Getting Started)

1.  **克隆本仓库:**
    ```bash
    git clone https://github.com/your_username/LLM-Foundations-Forge.git
    cd LLM-Foundations-Forge
    ```

2.  **创建并激活Conda环境:**
    ```bash
    # (推荐) 按照我们在第一篇文章配套代码中所经历的流程，创建一个干净的环境。
    # 我们推荐使用 conda 来处理复杂的依赖。
    ```

3.  **安装依赖:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **启动Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
    现在，你可以开始探索 `notebooks` 文件夹中的内容了！

---

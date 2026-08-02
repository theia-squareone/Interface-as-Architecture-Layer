<h1 align="center">Interface Is a Separate Architectural Layer</h1>
<p align="center">
  <i>Theia Ivy Aletheia / 梁曦真</i>
</p>

<p align="center">
  <b>Series:</b> Platform Architecture Notes · <b>Note 4</b>
</p>

<p align="center">
  <b>Keywords:</b> Interface Design, Platform Architecture, Developer Experience, AI Systems, MUSA, Moore Threads, Accessibility
</p>

---

## About this paper

The interface is often considered an external shell—something added on top of a powerful chip and a capable SDK. But in reality, the interface is not decoration: it is a translator between complexity and action. If it is poorly designed, even the strongest platform remains closed to most people. If it is well designed, the system begins to work not only for engineers, but also for the product, the business, and the end scenario. This paper argues that the interface is a separate architectural discipline, not a decorative layer over computation.

---

## Contact

- **GitHub:** [theia-squareone](https://github.com/theia-squareone)
- **Telegram:** [@Theia_squareone](https://t.me/Theia_squareone)
- **Email:** [theia.squareone@gmail.com](mailto:theia.squareone@gmail.com)

---

<details>
<summary><b>🇬🇧 English Version</b></summary>

<br>

# Interface Is a Separate Architectural Layer

**Abstract**  
The interface is often considered an external shell—something added on top of a powerful chip and a capable SDK. But in reality, the interface is not decoration: it is a translator between complexity and action. If it is poorly designed, even the strongest platform remains closed to most people. If it is well designed, the system begins to work not only for engineers, but also for the product, the business, and the end scenario. [1][5][3]

**Why the interface cannot be conflated with hardware**  
Hardware answers the question "what is possible." The interface answers the question "what becomes accessible." These are different levels. The same GPU can be either a mere accelerator for a narrow circle of specialists, or part of an environment where the developer, the operator, and the user work without constant friction. Therefore, the interface is a separate architectural discipline, not a decorative layer over computation. [1][6][4]

**The interface as a way to hide complexity**  
A good interface does not show everything. It hides the excess, leaving only what is needed for action. In this sense, the interface is a filter of complexity. It does not eliminate the depth of the system, but makes it applicable. Public materials around MUSA show that the platform is accompanied by an SDK, migration tools, profiling means, and modular integrations with external stacks such as vLLM—the interface works as a set of different doors into the same system. [1][2][7][4]

**The interface as a mode of communication**  
The same platform may have multiple interfaces: for the developer, for DevOps, for the researcher, for the end user, for the API client. And each speaks its own language. Therefore, a mature system does not try to impose a single universal way of interaction. It creates a set of coherent ways to enter itself. This is how the chip, the SDK, and the user scenario stop conflicting with each other. [1][3][6]

**When the interface becomes the product**  
At some point, people buy not the power, but the ease of entry into that power. Then the interface ceases to be secondary and becomes the product itself. This is especially noticeable in AI platforms, where one can have a strong mathematical foundation, yet lose because the code is hard to port, hard to debug, or hard to embed into a workflow. Conversely, a well‑assembled interface makes the platform alive, even if under the hood it is complex. [1][2][4][6]

**Why this matters for AI architecture**  
If we look at AI as a system, the interface is not just a UI and not just an API. It is a way to organize contact between intention and computation. It is the layer where an abstract request turns into a concrete action. Therefore, a mature AI platform should have not one interface, but several: for work, for development, for serving, for observation, for management. Without this, the platform remains a set of functions rather than a workspace. [7][4][5]

**Where this leads**  
If the SDK is responsible for translation and coherence, and the interface for accessibility and modes of communication, then the next step is natural: **memory as a pervasive fabric of the system**. Because without memory, the interface remains a moment, while the platform must remember who interacted with it, what was done, and how the process should continue. [1][2][3]

---

**References**  
[1] MUSA SDK https://developer.mthreads.com/sdk/download/musa  
[2] MUSA supports porting CUDA code using Musify toolkit https://www.tomshardware.com/pc-components/gpus/chinas-moore-threads-polishes-homegrown-cuda-alternative-musa-supports-porting-cuda-code-using-musify-toolkit  
[3] MetaPark | Moore Threads https://metapark.mthreads.com/en  
[4] BLAS - GitHub https://raw.githubusercontent.com/ggml-org/llama.cpp/master/docs/build.md  
[5] About Us | Moore Threads - 摩尔线程 https://en.mthreads.com/about  
[6] Moore Threads Adapts Alibaba Qwen3.5 on MTT S5000 GPU https://ubos.tech/news/moore-threads-adapts-alibaba-qwen3-5-on-mtt-s5000-gpu-a-leap-for-chinese-ai-hardware/  
[7] MooreThreads/vllm-musa: A high-throughput and memory- ... https://github.com/MooreThreads/vllm-musa  
[8] MusaCoder: Native GPU Kernel Generation with Full-Stack ... https://arxiv.org/html/2606.04847v1  
[9] Moore Threads Just Launched GPU With 50x Better Ray ... https://www.youtube.com/watch?v=ehE8FEP5sB0  
[10] Moore Threads unveils next-generation GPU architecture ... https://www.jiemian.com/article/13792747.html  
[11] Moore Threads CEO Teases Next-gen GPU Architecture ... https://www.techpowerup.com/343853/moore-threads-ceo-teases-next-gen-gpu-architecture-ahead-of-musa-developer-conference  
[12] Moore Threads Service Introduction https://en.mthreads.com/support/intros

</details>

<br>

<details>
<summary><b>🇨🇳 中文版 (Chinese Version)</b></summary>

<br>

# 接口是独立的架构层

**摘要**  
接口常被视为外部外壳——附加在强大芯片和成熟 SDK 之上的东西。但实际上，接口不是装饰：它是复杂性与行动之间的翻译器。如果设计不佳，即使是最强的平台也对大多数人保持封闭。如果设计良好，系统不仅为工程师工作，也为产品、业务和最终场景工作。 [1][5][3]

**为什么接口不能与硬件混为一谈**  
硬件回答“什么可能”的问题。接口回答“什么变得可访问”的问题。这是不同的层面。同一块 GPU 既可以是仅供少数专家使用的加速器，也可以成为开发者、操作员和用户毫无摩擦地工作的环境的一部分。因此，接口是一门独立的架构学科，而不是计算之上的装饰层。 [1][6][4]

**接口作为隐藏复杂性的方式**  
好的接口不会展示一切。它会隐藏多余的部分，只留下行动所需的内容。在这个意义上，接口是复杂性的过滤器。它不消除系统的深度，而是使其变得可应用。围绕 MUSA 的公开资料显示，平台伴随着 SDK、迁移工具、性能分析工具以及与外部栈（如 vLLM）的模块化集成——接口表现为通往同一系统的多扇不同门户。 [1][2][7][4]

**接口作为沟通模式**  
同一个平台可以有多个接口：面向开发者、运维人员、研究人员、最终用户、API 客户端。每一种都使用自己的语言。因此，成熟的系统不会试图强加一种通用的交互方式，而是创建一组协调的入口。正是这样，芯片、SDK 和用户场景才不再相互冲突。 [1][3][6]

**当接口成为产品本身**  
在某个时刻，人们购买的已经不再是算力，而是进入算力的便捷性。这时接口就不再是次要的，而是成为产品本身。这在 AI 平台中尤为明显：你可以拥有强大的数学基础，却因为代码难以移植、难以调试或难以嵌入工作流而失败。反之，精心设计的接口使平台保持活跃，即使其内部结构很复杂。 [1][2][4][6]

**为什么这对 AI 架构很重要**  
如果我们把 AI 视为一个系统，接口就不仅仅是 UI 或 API。它是组织意图与计算之间接触的方式。它是一个抽象请求转化为具体行动的层。因此，成熟的 AI 平台应该拥有不止一个接口，而是多个：面向工作、开发、服务、观察和管理。没有这些，平台仍然只是一组功能，而不是工作空间。 [7][4][5]

**这引向何处**  
如果 SDK 负责翻译和一致性，接口负责可访问性和沟通模式，那么下一步就顺理成章了：**记忆作为系统的贯穿性组织**。因为没有记忆，接口就只是一个瞬间，而平台必须记住谁与它交互过、做了什么、以及过程应如何继续。 [1][2][3]

---

**参考文献**  
[1] MUSA SDK https://developer.mthreads.com/sdk/download/musa  
[2] MUSA supports porting CUDA code using Musify toolkit https://www.tomshardware.com/pc-components/gpus/chinas-moore-threads-polishes-homegrown-cuda-alternative-musa-supports-porting-cuda-code-using-musify-toolkit  
[3] MetaPark | Moore Threads https://metapark.mthreads.com/en  
[4] BLAS - GitHub https://raw.githubusercontent.com/ggml-org/llama.cpp/master/docs/build.md  
[5] About Us | Moore Threads - 摩尔线程 https://en.mthreads.com/about  
[6] Moore Threads Adapts Alibaba Qwen3.5 on MTT S5000 GPU https://ubos.tech/news/moore-threads-adapts-alibaba-qwen3-5-on-mtt-s5000-gpu-a-leap-for-chinese-ai-hardware/  
[7] MooreThreads/vllm-musa: A high-throughput and memory- ... https://github.com/MooreThreads/vllm-musa  
[8] MusaCoder: Native GPU Kernel Generation with Full-Stack ... https://arxiv.org/html/2606.04847v1  
[9] Moore Threads Just Launched GPU With 50x Better Ray ... https://www.youtube.com/watch?v=ehE8FEP5sB0  
[10] Moore Threads unveils next-generation GPU architecture ... https://www.jiemian.com/article/13792747.html  
[11] Moore Threads CEO Teases Next-gen GPU Architecture ... https://www.techpowerup.com/343853/moore-threads-ceo-teases-next-gen-gpu-architecture-ahead-of-musa-developer-conference  
[12] Moore Threads Service Introduction https://en.mthreads.com/support/intros

</details>

# 学习资料与实习准备计划

本仓库整理两类学习资料：

- 竞赛算法备赛清单：面向 ICPC、CCPC、蓝桥杯、团体程序设计天梯赛。
- Java 后端与 AI 应用开发实习准备计划：面向大一到低年级同学，目标是准备 Java 后端实习，并补充 AI 应用开发能力。

## 目录结构

```text
.
├── README.md
├── AlgorithmTest/
│   ├── 竞赛API背诵清单.md
│   ├── 竞赛API背诵清单.pdf
│   ├── 竞赛算法板子背诵清单.md
│   ├── 竞赛算法板子背诵清单.pdf
│   ├── 竞赛实战技巧与调试对拍清单.md
│   └── 竞赛实战技巧与调试对拍清单.pdf
└── java-backend-internship-plan/
    └── learning-plan.md
```

## Java 后端与 AI 实习计划

核心文档：

- [Java 后端与 AI 应用开发实习准备计划](./java-backend-internship-plan/learning-plan.md)

这份计划包含：

- 12 周学习节奏：Java 基础、MySQL、Spring Boot、Redis、项目、八股、系统设计、AI 应用和求职冲刺。
- 项目路线：一个传统 Java 后端项目，一个 AI 应用项目。
- 推荐资料：JavaGuide、小林 coding、二哥的 Java 进阶之路、黑马 Redis/黑马点评、Spring AI、LangChain4j、派聪明 RAG 架构等。
- 牛客双非面经观察：整理 50 篇双非 Java/后端相关面经、实习复盘、秋招春招总结和简历拷打样本。
- 简历模板与面试准备：项目描述、Redis 场景、RAG 项目亮点、八股复述方法和投递节奏。

推荐执行方式：

1. 第 1 到 4 周先补 Java、MySQL、Spring Boot、Redis 基础。
2. 第 5 到 8 周完成传统 Java 后端项目，并开始读牛客面经、模拟面试。
3. 第 9 到 11 周完成 AI 应用项目，跑通 RAG、流式输出、引用来源和权限过滤。
4. 第 11 到 12 周把两个项目放进简历，开始稳定投递并复盘面试。

## 竞赛算法备赛清单

文档目录：

| 文档 | 内容 | 适合什么时候看 |
|---|---|---|
| [竞赛API背诵清单.md](./AlgorithmTest/竞赛API背诵清单.md) | C++ STL、输入输出、字符串、容器、常用库函数、Java/Python 高频 API、比赛资料限制参考 | 刚开始准备比赛，或赛前快速复习语言 API |
| [竞赛算法板子背诵清单.md](./AlgorithmTest/竞赛算法板子背诵清单.md) | ICPC/CCPC/蓝桥杯/天梯赛常见算法模板、背诵优先级、题面信号到算法映射 | 系统整理算法模板，判断哪些板子必须会写 |
| [竞赛实战技巧与调试对拍清单.md](./AlgorithmTest/竞赛实战技巧与调试对拍清单.md) | 宏定义、`long long`、`__int128`、编译参数、debug、assert、对拍、WA/RE/TLE 排查、赛场流程 | 开始刷题训练后，用来减少低级错误和提升调试效率 |

仓库中同时提供对应 PDF，方便打印或离线阅读。

推荐阅读顺序：

1. 先读 [竞赛API背诵清单.md](./AlgorithmTest/竞赛API背诵清单.md)，确保基础库函数和输入输出不拖后腿。
2. 再读 [竞赛算法板子背诵清单.md](./AlgorithmTest/竞赛算法板子背诵清单.md)，按 A/B/C 级优先级整理自己的模板。
3. 最后读 [竞赛实战技巧与调试对拍清单.md](./AlgorithmTest/竞赛实战技巧与调试对拍清单.md)，把 debug、对拍、边界检查变成日常习惯。

适用范围：

- ICPC / CCPC：适合整理个人模板和队伍 Team Reference Document。
- 蓝桥杯：重点关注 STL、模拟、枚举、搜索、基础 DP、基础数论、日期和格式输出。
- 团体程序设计天梯赛：重点关注稳定实现、图论基础、树、最短路、并查集、排序模拟和中档 DP。

默认主语言是 C++。文档中也补充了少量 Java / Python 高频 API，方便不同语言选手查漏补缺。

## 使用建议

- 不要只收藏文档。每个板子至少手写 2 到 3 次，并用小数据对拍。
- 不要临场换模板。赛前只复习自己写过、测过、会改的版本。
- 不要把高级模板优先级放太高。蓝桥杯和天梯赛先保证基础分；ICPC/CCPC 再逐步补网络流、字符串进阶、计算几何等内容。
- Java 后端计划不要同时铺开太多资料。八股主线只选 1 到 2 套，项目必须改造成自己的业务。
- 比赛规则、招聘节奏和岗位要求会变化，执行前要以当年正式规则、岗位 JD 和真实面试反馈为准。

## 资料来源

竞赛资料整理时参考了以下公开资料：

- OI Wiki：<https://oi-wiki.org/>
- cp-algorithms：<https://cp-algorithms.com/>
- KACTL：<https://github.com/kth-competitive-programming/kactl>
- AtCoder Library：<https://atcoder.github.io/ac-library/production/document_en/index.html>
- USACO Guide：<https://usaco.guide/>
- GCC 文档：<https://gcc.gnu.org/onlinedocs/>
- ICPC 官方环境说明：<https://docs.icpc.global/worldfinals-programming-environment/>

Java 后端与 AI 应用计划中的资料链接、项目资源和牛客面经样本见 [learning-plan.md](./java-backend-internship-plan/learning-plan.md)。

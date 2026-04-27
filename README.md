# 竞赛备赛清单

面向 ICPC、CCPC、蓝桥杯、团体程序设计天梯赛的 C++ 竞赛备赛资料整理。

本仓库把备赛内容拆成三类：API、算法板子、实战技巧。目标是帮助训练时明确“要背什么、什么时候用、怎么写稳、怎么调试”。

## 文档目录

| 文档 | 内容 | 适合什么时候看 |
|---|---|---|
| [竞赛API背诵清单.md](./竞赛API背诵清单.md) | C++ STL、输入输出、字符串、容器、常用库函数、Java/Python 高频 API、比赛资料限制参考 | 刚开始准备比赛，或赛前快速复习语言 API |
| [竞赛算法板子背诵清单.md](./竞赛算法板子背诵清单.md) | ICPC/CCPC/蓝桥杯/天梯赛常见算法模板、背诵优先级、题面信号到算法映射 | 系统整理算法模板，判断哪些板子必须会写 |
| [竞赛实战技巧与调试对拍清单.md](./竞赛实战技巧与调试对拍清单.md) | 宏定义、`long long`、`__int128`、编译参数、debug、assert、对拍、WA/RE/TLE 排查、赛场流程 | 开始刷题训练后，用来减少低级错误和提升调试效率 |

仓库中同时提供对应 PDF，方便打印或离线阅读。

## 推荐阅读顺序

1. 先读 [竞赛API背诵清单.md](./竞赛API背诵清单.md)，确保基础库函数和输入输出不拖后腿。
2. 再读 [竞赛算法板子背诵清单.md](./竞赛算法板子背诵清单.md)，按 A/B/C 级优先级整理自己的模板。
3. 最后读 [竞赛实战技巧与调试对拍清单.md](./竞赛实战技巧与调试对拍清单.md)，把 debug、对拍、边界检查变成日常习惯。

## 适用范围

- ICPC / CCPC：适合整理个人模板和队伍 Team Reference Document。
- 蓝桥杯：重点关注 STL、模拟、枚举、搜索、基础 DP、基础数论、日期和格式输出。
- 团体程序设计天梯赛：重点关注稳定实现、图论基础、树、最短路、并查集、排序模拟和中档 DP。

默认主语言是 C++。文档中也补充了少量 Java / Python 高频 API，方便不同语言选手查漏补缺。

## 使用建议

- 不要只收藏文档。每个板子至少手写 2-3 次，并用小数据对拍。
- 不要临场换模板。赛前只复习自己写过、测过、会改的版本。
- 不要把高级模板优先级放太高。蓝桥杯和天梯赛先保证基础分；ICPC/CCPC 再逐步补网络流、字符串进阶、计算几何等内容。
- 比赛规则每年、每站可能不同，赛前必须核对当届正式规则，尤其是是否允许纸质资料、电子文档、网络访问和本地文件。

## 资料来源

文档整理时参考了以下公开资料：

- OI Wiki：<https://oi-wiki.org/>
- cp-algorithms：<https://cp-algorithms.com/>
- KACTL：<https://github.com/kth-competitive-programming/kactl>
- AtCoder Library：<https://atcoder.github.io/ac-library/production/document_en/index.html>
- USACO Guide：<https://usaco.guide/>
- GCC 文档：<https://gcc.gnu.org/onlinedocs/>
- ICPC 官方环境说明：<https://docs.icpc.global/worldfinals-programming-environment/>

## 当前文件

```text
.
├── README.md
├── 竞赛API背诵清单.md
├── 竞赛API背诵清单.pdf
├── 竞赛算法板子背诵清单.md
├── 竞赛算法板子背诵清单.pdf
├── 竞赛实战技巧与调试对拍清单.md
└── 竞赛实战技巧与调试对拍清单.pdf
```

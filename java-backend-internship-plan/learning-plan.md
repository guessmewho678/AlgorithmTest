# Java 后端与 AI 应用开发实习准备计划

更新时间：2026-04-27

适用对象：大一新生，目标是准备 Java 后端开发实习，同时补充 AI 应用开发能力。

## 总体路线

建议路线是：先把传统 Java 后端基础打稳，再做一个 AI 应用项目作为差异化。不要一开始只背八股，也不要只跟项目视频敲代码。

核心目标：

- 掌握 Java 后端实习常见八股：Java 基础、集合、JVM、并发、Spring、MySQL、Redis、网络、操作系统、简单分布式。
- 至少完成 2 个可写进简历的项目：一个传统 Java 后端项目，一个 AI 应用项目。
- 每个项目都能讲清楚业务背景、技术选型、数据库设计、接口设计、难点、优化和部署。
- 第 7 周开始持续刷牛客面经和模拟面试，第 9 周以后根据项目完成度开始小规模投递。

## 推荐资料

使用原则：

- 八股主线只选 JavaGuide、小林 coding、二哥的 Java 进阶之路中的 1 到 2 个，不要三套同时全量推进。
- 项目视频只作为业务和技术场景参考，必须改造成自己的校园或个人业务。
- 牛客面经从第 7 周开始固定输入，每周读 10 篇并沉淀到八股卡片和项目 README。
- AI 资料从第 9 周开始集中使用，先跑通 Spring AI 或 LangChain4j 的最小 RAG 链路。

### 免费八股资料

1. [JavaGuide](https://javaguide.cn/)

   Java 面试和后端通用面试指南，覆盖计算机基础、数据库、分布式、高并发、系统设计与 AI 应用开发。适合作为八股主目录。

   重点看：

   - Java 基础常见面试题
   - Java 集合常见面试题
   - JVM 常见面试题
   - MySQL 常见面试题
   - Redis 常见面试题
   - 分布式高频面试题
   - AI 应用开发、RAG、Agent、MCP 相关内容

2. [小林 coding](https://www.xiaolincoding.com/)

   图解网络、操作系统、MySQL、Redis 很适合初学者理解。它也有 Java 后端面试题、Agent/RAG 面试题和 AI 项目资料。

   重点看：

   - 图解网络
   - 图解系统
   - 图解 MySQL
   - 图解 Redis
   - Java 后端面试题
   - Agent 面试题
   - RAG 面试题

3. [Doocs advanced-java](https://java.doocs.org/)

   适合进阶补高并发、分布式、高可用、微服务、海量数据处理。

   建议在第 7 周以后看，不建议一开始就啃。大一阶段先以实习高频基础为主。

4. [二哥的 Java 进阶之路](https://javabetter.cn/)

   适合作为 Java 学习路线、面试复习和项目表达的补充资料。重点看 Java 基础、集合、并发、JVM、Spring、MySQL、Redis，以及“面渣逆袭”系列。

   使用方式：

   - 不要和 JavaGuide、小林 coding 同时全量铺开。
   - 某个模块看不懂时，用它做第二份解释材料。
   - 面试前按专题查漏补缺，整理成自己的口述稿。

5. [牛客 Java 面经](https://www.nowcoder.com/experience/639)

   用来观察真实面试问法。第 7 周以后开始看，每周挑 10 篇，整理高频问题。

6. [牛客 Java 岗位面试真题宝典](https://www.nowcoder.com/tutorial/10070/index)

   适合查漏补缺。不要从第一页硬刷到最后，优先按自己薄弱模块查。

### 免费项目和视频

1. [黑马程序员 Java 项目实战《苍穹外卖》](https://www.bilibili.com/video/BV1TP411v7v6/)

   适合第一个 Java 后端项目，能练需求分析、接口设计、编码、调试、文档阅读。

   注意：简历不要原样写“苍穹外卖”。可以改造成自己的业务，比如：

   - 校园点餐系统
   - 校园预约系统
   - 社团活动报名系统
   - 校园二手交易管理系统

2. [黑马程序员 Redis 入门到实战教程 + 黑马点评项目](https://www.bilibili.com/video/BV1cr4y1671t/)

   适合放在第 4 周 Redis 入门和第 6 周项目强化阶段。第 4 周只学 Redis 基础和 1 到 2 个核心场景，第 6 周再把这些场景迁移到自己的校园业务项目。不要把“黑马点评”原样写进简历。

   重点练：

   - Redis 登录态和共享 Session
   - 缓存穿透、缓存击穿、缓存雪崩
   - 分布式锁和 Lua 脚本
   - 优惠券秒杀、库存扣减、重复下单控制
   - Redis Stream 异步下单
   - 热点数据缓存和缓存一致性

3. [RuoYi-Vue 文档](https://doc.ruoyi.vip/ruoyi-vue/)

   适合学习后台管理系统、RBAC 权限、JWT、代码生成、前后端分离工程结构。

   重点看：

   - 用户、角色、菜单权限
   - 数据权限
   - 日志管理
   - 代码生成器
   - 前后端分离项目结构

4. [mall 学习教程](https://www.macrozheng.com/)

   适合后期学习电商业务、Redis、RabbitMQ、Elasticsearch、Docker。

   大一找实习阶段不建议完整啃完 mall，优先读架构篇和业务篇，借鉴项目表达。

5. [mall-swarm 微服务项目](https://github.com/macrozheng/mall-swarm)

   适合第 8 周以后了解微服务、网关、注册中心、监控中心、搜索、缓存、消息队列。

   对实习来说，知道架构和核心组件即可，不要求完全掌握。

### AI 应用开发资料

1. [Spring AI 官方文档](https://docs.spring.io/spring-ai/reference/)

   Java 做 AI 应用的官方路线，支持模型调用、Embedding、向量库、Tool Calling、RAG、Chat Memory。

   重点看：

   - Chat Client API
   - Chat Memory
   - Tool Calling
   - Retrieval Augmented Generation
   - Vector Databases

2. [LangChain4j 官方文档](https://docs.langchain4j.dev/)

   Java 生态里做 RAG、Agent、Tool Calling 很合适。

   重点看：

   - AI Services
   - Tools
   - RAG
   - Spring Boot Integration
   - MCP

3. [LangChain4j RAG 文档](https://docs.langchain4j.dev/tutorials/rag/)

   重点理解三种 RAG：

   - Easy RAG：适合快速上手
   - Naive RAG：基础向量检索
   - Advanced RAG：支持查询改写、多路召回、重排序等扩展

4. [Dify](https://dify.ai/)

   适合快速理解 AI 工作流、RAG Pipeline、Agent 工具调用。可以作为原型工具，但简历项目最好有自己写的 Java 后端代码。

5. [Dify Agent 文档](https://docs.dify.ai/en/guides/workflow/node/agent)

   适合理解 Agent 如何决定调用哪些工具，以及 Function Calling 和 ReAct 的区别。

6. [黑马 SpringAI + DeepSeek 大模型应用开发实战](https://www.bilibili.com/video/BV1MtZnYtEB3)

   适合 Java 项目 AI 化入门，讲 Spring AI、大模型应用开发。

7. [派聪明 RAG 知识库技术架构](https://javabetter.cn/zhishixingqiu/paismart.html#%E4%B8%89%E3%80%81%E6%B4%BE%E8%81%AA%E6%98%8E%E7%9A%84%E6%8A%80%E6%9C%AF%E6%9E%B6%E6%9E%84)

   适合作为 AI 应用项目的架构参考，重点看 RAG 链路、文档解析、分块、Embedding、向量检索、权限过滤、流式回答、Redis/MinIO/Kafka/Elasticsearch 的工程化组合。

   使用方式：

   - 先照着理解链路，不要一上来追全量企业级技术栈。
   - 自己的项目可以缩小为“文档上传 + 向量检索 + 流式问答 + 引用来源”。
   - 简历表达时重点讲自己实现的链路和取舍，不要写成“学习过派聪明”。

### 付费可选资料

1. [极客时间 MySQL 实战 45 讲](https://time.geekbang.org/column/intro/139)

   适合系统补 MySQL 原理和面试高频点，比如索引、事务、锁、日志、慢 SQL。

2. [极客时间 Java 并发编程实战](https://time.geekbang.org/column/intro/159)

   适合把 JMM、线程池、锁、并发工具系统化。

3. [极客时间 Redis 核心技术与实战](https://time.geekbang.org/course/intro/101061904)

   适合补 Redis 底层结构、网络模型、最佳实践和场景实战。

4. JavaGuide《Java 面试指北》、小林训练营、牛客专刊

   如果预算足够，并且你自学容易失去节奏，可以考虑。不要把付费课当主线，主线必须是代码、复述、项目和面试反馈。

## 项目建议

简历上建议放 2 个项目。

### 项目一：传统 Java 后端项目

推荐选题：

- 校园预约系统
- 校园二手交易系统
- 社团活动报名系统
- 课程资料管理系统
- 校园点餐系统

推荐技术栈：

- Spring Boot
- MyBatis 或 MyBatis-Plus
- MySQL
- Redis
- JWT
- Spring Security 或 Sa-Token
- Knife4j 或 Swagger
- Docker

必须做出的能力点：

- 用户登录、注册、鉴权
- RBAC 权限控制
- 核心业务 CRUD
- 复杂条件分页查询
- Redis 缓存
- Redis 分布式锁或 Lua 原子扣减
- 幂等处理
- 事务处理
- 操作日志
- 接口文档
- Docker 部署

建议把黑马点评里的 Redis 场景改造到自己的业务里。例如校园预约系统可以做“热门场地预约”，校园二手交易系统可以做“限时抢购”，社团活动报名系统可以做“名额秒杀”。核心是讲清楚并发下如何防重复报名、如何扣减名额、如何异步落库，而不是照搬点评业务。

可以写进简历的亮点：

- 使用 Redis 缓存热点数据，降低数据库重复查询。
- 使用 Redis + Lua 实现名额或库存原子扣减，避免并发超卖。
- 使用 Redis Stream 或消息队列异步处理预约、报名或订单创建，削峰并提升接口响应速度。
- 使用唯一业务号和状态机保证订单、预约或报名流程幂等。
- 使用统一异常处理和参数校验提升接口稳定性。
- 使用 RBAC 模型实现菜单权限和按钮权限控制。
- 使用 Docker 编排 MySQL、Redis 和后端服务，降低部署成本。

### 项目二：AI 应用项目

推荐选题：

- 课程资料 RAG 问答系统
- AI 简历分析系统
- AI 模拟面试平台
- 校园智能问答助手
- 个人知识库问答系统

推荐技术栈：

- Spring Boot
- Spring AI 或 LangChain4j
- MySQL
- Redis
- PostgreSQL + pgvector，或 Milvus、Qdrant
- SSE 流式输出
- Docker

必须做出的能力点：

- 文档上传
- 文档解析
- 文本切分
- Embedding 生成
- 向量入库
- 用户问题检索
- 权限过滤
- Prompt 组装
- 流式回答
- 引用来源返回
- 简单对话记忆

架构可以参考派聪明，但自己的第一版要收敛：先完成单用户知识库，再补登录权限；先用 pgvector 或轻量向量库跑通，再考虑 Elasticsearch 混合检索；先用本地文件存储，再升级 MinIO。

可以写进简历的亮点：

- 基于 RAG 实现课程资料问答，回答时返回引用片段，降低幻觉。
- 使用文档切分、向量检索和 Prompt 模板组合构建问答链路。
- 在检索阶段按用户或知识库权限过滤文档，避免越权访问。
- 使用 SSE 实现大模型回答流式返回，提升用户体验。
- 使用 Redis 缓存会话上下文和限流信息。
- 对比不同 chunk size、topK 和相似度阈值对回答质量的影响。

## 每日固定时间安排

假设平日每天 3 小时，周末每天 5 小时。

平日：

| 时间 | 内容 |
| --- | --- |
| 早上 30 分钟 | 复述八股或 Anki，不看答案说出来 |
| 晚上 50 分钟 | 看文档或视频 |
| 晚上 80 分钟 | 写代码 |
| 晚上 30 分钟 | 1 道算法或 SQL + 当日总结 |

周末：

| 时间 | 内容 |
| --- | --- |
| 上午 2 小时 | 写项目核心功能 |
| 下午 2 小时 | 补文档、调试、重构、部署 |
| 晚上 1 小时 | 写 README、画架构图、录一次项目讲解 |

每天必须输出：

- 1 次 Git 提交
- 1 条学习笔记
- 1 个可复述的问题
- 1 个待解决问题

## 12 周学习计划

计划周期：2026-04-27 到 2026-07-19。

| 周次 | 周一 | 周二 | 周三 | 周四 | 周五 | 周六 | 周日交付 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 第 1 周：Java 基础 | OOP、异常 | 集合 | 泛型、IO | Stream、Lambda | Git、Maven | 小 CLI 项目 | 20 道基础题 + Java 笔记 |
| 第 2 周：MySQL | SQL CRUD | 表设计 | 索引 | 事务、锁 | explain | 设计 5 张业务表 | MySQL 八股卡片 |
| 第 3 周：Spring Boot | MVC、REST | MyBatis | 参数校验、异常 | 日志、Swagger | JWT 入门 | CRUD 后台 | 接口文档 + 代码提交 |
| 第 4 周：Redis | 数据类型 | 缓存穿透、击穿、雪崩 | 分布式锁 | 黑马点评核心场景 | Redis Stream 入门 | 项目接 Redis | 压测和问题记录 |
| 第 5 周：项目一启动 | 选题和需求 | 数据库设计 | 登录、RBAC | 核心 CRUD | 订单、预约或报名流程 | 文件上传、日志 | README 初版 |
| 第 6 周：项目一强化 | 事务 | 幂等 | 缓存一致性 | 统计接口 | Docker | 部署 | 简历项目描述 |
| 第 7 周：八股一轮 | Java 基础 | 集合、JVM | 并发 | Spring | MySQL、Redis | 牛客双非 Java 面经 | 模拟面试 1 次 |
| 第 8 周：系统设计入门 | HTTP、TCP | OS、Linux | Docker | MQ | 分布式锁、Session | 读 mall-swarm 架构 | 画项目架构图 |
| 第 9 周：AI 入门 | LLM API | Prompt | Spring AI | LangChain4j | Tool Calling | 简单聊天后端 | AI 笔记 + Demo |
| 第 10 周：RAG 项目 | 需求设计 | 文档上传 | 切分、Embedding | 向量检索 | 问答接口 | SSE + 架构图 | AI 项目可演示 |
| 第 11 周：AI 项目强化 | 对话记忆 | 权限过滤 | Dify 工作流对照 | 幻觉规避 | 日志、评估 | 部署 | AI 项目 README |
| 第 12 周：求职冲刺 | 简历 | 项目问答 | 牛客面经 | 算法复盘 | 模拟面试 | 投递 | 复盘和补弱清单 |

## 八股复习优先级

### 第一优先级

- Java 基础
- 集合
- JVM
- 并发
- Spring Boot
- MySQL
- Redis

### 第二优先级

- 计算机网络
- 操作系统
- Linux
- 消息队列
- Docker
- 设计模式

### 第三优先级

- Spring Cloud
- 分布式事务
- Elasticsearch
- 系统设计
- 微服务治理

### AI 应用方向额外补充

- LLM 基础概念
- Prompt
- Function Calling
- Tool Calling
- RAG
- Embedding
- 向量数据库
- Agent
- MCP
- 幻觉规避
- 流式输出

## 每周复盘模板

每周日晚上写一次复盘。

```markdown
## 第 X 周复盘

### 本周完成

- 

### 本周没完成

- 

### 卡住的问题

- 

### 下周优先级

1. 
2. 
3. 

### 本周可复述的问题

1. 
2. 
3. 

### 项目进展

- 新增功能：
- 修复问题：
- README 更新：
- Git 提交次数：
```

## 简历项目描述模板

### 传统 Java 后端项目模板

```text
项目名称：校园预约管理系统

项目简介：
面向校内活动室、实验室或社团资源预约场景，提供用户登录、资源管理、预约审批、通知提醒、权限管理和后台统计能力。

技术栈：
Spring Boot、MyBatis 或 MyBatis-Plus、MySQL、Redis、Sa-Token 或 JWT、Knife4j、Docker

个人职责：
1. 负责用户认证、RBAC 权限、资源预约、审批流等核心模块开发。
2. 设计资源、预约、审批记录、用户角色等核心表结构。
3. 使用 Redis 缓存资源状态和热点查询，减少数据库重复访问。
4. 使用 Redis + Lua 或分布式锁控制热门资源预约名额，避免并发超约。
5. 通过唯一预约号和状态流转控制重复提交，保证业务幂等。
6. 使用 Docker 部署 MySQL、Redis 和后端服务，并编写接口文档和部署文档。
```

### AI 应用项目模板

```text
项目名称：课程资料 RAG 智能问答系统

项目简介：
面向课程 PDF、Markdown 和笔记资料，提供文档上传、知识库构建、语义检索和流式问答能力，回答时返回引用来源。

技术栈：
Spring Boot、Spring AI 或 LangChain4j、PostgreSQL + pgvector、Redis、SSE、Docker

个人职责：
1. 负责文档上传、文本解析、分块、Embedding 生成和向量入库流程。
2. 基于用户问题进行向量召回，组装 Prompt 并调用大模型生成回答。
3. 使用 SSE 实现回答流式输出，提升交互体验。
4. 返回引用片段和来源文件，降低大模型幻觉风险。
5. 按用户或知识库维度过滤检索结果，避免越权访问非授权文档。
6. 调整 chunk size、topK 和相似度阈值，优化回答相关性。
```

## 面试准备方式

### 八股不要只背结论

每个知识点按这个结构准备：

1. 是什么
2. 为什么需要
3. 底层原理
4. 项目里怎么用
5. 有什么坑
6. 如何优化

示例：Redis 缓存穿透

- 是什么：查询不存在的数据，导致请求绕过缓存打到数据库。
- 为什么危险：高并发下会压垮数据库。
- 解决方式：缓存空值、布隆过滤器、参数校验。
- 项目里怎么用：对不存在的资源 ID 缓存短 TTL 空值。
- 坑：空值缓存太久会影响新增数据可见性。
- 优化：短 TTL + 主动删除 + 布隆过滤器。

### 项目必须能讲 10 分钟

准备以下问题：

- 你的项目解决什么问题？
- 为什么选这个技术栈？
- 数据库怎么设计？
- 登录鉴权怎么做？
- Redis 用在哪里？
- 哪些地方用了事务？
- 如何防止重复提交？
- 线上接口慢怎么排查？
- 项目最大的难点是什么？
- 如果用户量扩大 10 倍怎么优化？
- AI 项目中 RAG 为什么能降低幻觉？
- 向量检索 topK 和相似度阈值怎么选？

## 牛客双非面经观察

这些帖子不要当成功学看，要当作求职风险清单和行动样本看。重点不是“别人上岸了”，而是他们如何补学校劣势、如何制造项目亮点、如何复盘面试。

推荐阅读样本（50 篇）：

### 秋招、春招和中大厂复盘

1. [Java 双非选手无实习秋招进大厂的感慨](https://www.nowcoder.com/discuss/573446967632695296)：重点看如何用笔记、架构图、源码理解和真诚表达制造差异化。
2. [双非本 Java 成功拿下字节 offer，求职、学习经验分享](https://www.nowcoder.com/discuss/544583036730454016)：重点看从 0 基础到秋招的八股、算法、项目和面试复盘框架。
3. [双非本 java 选手的秋招总结](https://www.nowcoder.com/discuss/705897452397760512)：重点看实习、项目、投递渠道和 Hot 100 复盘对秋招机会的影响。
4. [双非秋招总结](https://www.nowcoder.com/discuss/681607381058416640)：重点看高强度投递、Boss 沟通和面试记录如何形成数据化复盘。
5. [双非本的后端秋招总结](https://www.nowcoder.com/discuss/697798154430799872)：重点看海投规模、笔试面试密度和中小厂 offer 兜底策略。
6. [双非计算机秋招总结，附带一些个人建议](https://www.nowcoder.com/discuss/1603749)：重点看大厂后端实习、简历项目写法和面试范围分布。
7. [26 届双非硕 Java 秋招总结](https://www.nowcoder.com/discuss/1603801)：重点看提前投递、官网和 Boss 双渠道，以及中厂、制造业、国企机会。
8. [双非本秋招总结](https://www.nowcoder.com/discuss/835468485693079552)：重点看投晚后的被动局面，以及中后期如何靠 Boss 和补录找机会。
9. [双非春招及补录总结](https://www.nowcoder.com/discuss/752210314401189888)：重点看秋招之后如何继续春招、补录和线下面试。
10. [双非本 211 硕的秋招总结](https://www.nowcoder.com/discuss/425770987733458944)：重点看一面八股、二面项目设计、三面综合面的常见分工。
11. [秋招总结(Java 后端)](https://www.nowcoder.com/discuss/339726)：重点看基础、项目、算法三条线如何同时准备。
12. [渣硕 Java 后端秋招面试总结](https://www.nowcoder.com/discuss/575911)：重点看非科班背景下如何靠实习、系统学习和实践补短板。
13. [双非本的秋招总结](https://www.nowcoder.com/discuss/353159140006633472)：重点看开源影响力、项目辨识度和“显而易见的成就”。
14. [双非菜鸡进大厂的秋招总结](https://www.nowcoder.com/discuss/439766367613575168)：重点看信息渠道、内推、基础、RPC/MQ 项目和 ACM 模式笔试。
15. [双非菜鸡回馈牛客](https://www.nowcoder.com/discuss/403103)：重点看书单、算法分类、面试复盘和长期海投心态。
16. [双非秋招全记录](https://www.nowcoder.com/discuss/419160826785918976)：重点看按公司、时间、流程记录投递，适合模仿做自己的求职表。
17. [双非机械转码春招之路](https://www.nowcoder.com/discuss/927821)：重点看转码背景、项目兜底和春招开始较晚时的取舍。
18. [双非 Java 面试中小厂面经](https://www.nowcoder.com/discuss/353159627141488640)：重点看中小厂 Java 面试高频基础题和转 Java 的路径。
19. [双非的秋招，感谢牛客](https://www.nowcoder.com/discuss/142181)：重点看腾讯 Java 面试中 JVM、集合、并发、网络、Linux、SQL、手写题覆盖面。
20. [25 校招 双非 拿下大厂](https://www.nowcoder.com/discuss/760975601057476608)：重点看实习数量、八股、算法、项目量化和方向选择建议。
21. [一个双非拿到 SSP 的秋招总结](https://www.nowcoder.com/discuss/755483099097497600)：重点看 Java、Redis、MySQL、网络、分布式、操作系统的面试框架。
22. [24 届秋招心得总结（双非本 c9 硕）](https://www.nowcoder.com/discuss/584896596123435008)：重点看地域选择、实习经历和后端岗位竞争差异。
23. [双非本 Golang 选手秋招经验分享](https://www.nowcoder.com/discuss/1228765)：重点看后端通用的校招节奏、简历、投递、笔试和项目准备。
24. [双非硕 后端开发投递更新 ing](https://www.nowcoder.com/discuss/602963110089031680)：重点看后端投递过程中的持续记录和 0 offer 阶段心态管理。

### 实习、暑期和真实面经

25. [双非后端 从秋招到春招 从 0 offer 到大结局](https://www.nowcoder.com/feed/main/detail/babf5598e82249c09699ccd13549386b)：重点看投递过晚、缺少实习和项目“玩具化”的风险。
26. [双非鼠暑期面经（已 oc 字节）](https://www.nowcoder.com/feed/main/detail/953c04d065524ca1abe227d831dbcd7e)：重点看字节、腾讯暑期面试中的项目深挖、系统基础、算法和 HR 面。
27. [双非暑期五轮面试上岸字节](https://www.nowcoder.com/feed/main/detail/f5055354a2c3448d83341a3ef6b043fd)：重点看短链接项目、布隆过滤器、限流、索引和实习经历拷打。
28. [28 届双非 Java 后端实习面经](https://www.nowcoder.com/feed/main/detail/95647376ad31433e826762a1ca2e776c)：重点看低年级 Java 实习中基础、SQL、Redis、接口文档和 AI 工具问题。
29. [28 届双非 JAVA 后端开发实习面经](https://www.nowcoder.com/feed/main/detail/b4b73f276cf149d69d435d74e32ec13f)：重点看 Java 实习面试里 RAG、MCP、AI 工具和并发基础的结合。
30. [双非 北京用友 java 实习后端（视频面试 40min）](https://www.nowcoder.com/feed/main/detail/2a0c4c50297a4eab8ffa171742626481)：重点看集合、并发、JVM、Spring、事务、慢查询和设计模式。
31. [Java 后端实习](https://www.nowcoder.com/feed/main/detail/fa453300808948fbbe078d997ba523d1?toCommentId=22185793)：重点看大规模投递后如何继续找中小厂实习，以及项目拷打强度。
32. [双非二本 26 届 润和的 Java 后端实习](https://www.nowcoder.com/feed/main/detail/c67f281128a94af4ab71e0a88bfccd85)：重点看第一段实习选择和“先有真实经历”的价值。
33. [四非非科班 26 后端找实习](https://www.nowcoder.com/feed/main/detail/614fee51895c45eb819d6f35972ba320)：重点看多家公司一面挂的原因：项目讲不清、Linux 场景题、系统设计和算法速度。
34. [双非本科历经一年半终上岸春招腾讯后端](https://www.nowcoder.com/feed/main/detail/ad928a4c83b14263ae6f3adeb4fe14e6)：重点看一年半内实习、秋招、春招、38 场技术面的连续复盘。
35. [双非本后端秋招进度](https://www.nowcoder.com/feed/main/detail/bccf482db8c74d5084271b891501eac1?toCommentId=22212940)：重点看中大厂密集流程、反复捞面和多个 offer/OC 的进度管理。
36. [26 届双非本秋招总结](https://www.nowcoder.com/feed/main/detail/6a720cdeb4a7456392e491a4cab596da)：重点看后端面试中实习真实性、业务价值、系统流程图和算法短板。
37. [双非硕 java 秋招历程](https://www.nowcoder.com/feed/main/detail/f97be5e68b194f50a74ce98a24410e50)：重点看本硕普通双非、Java 岗位投递、笔试和少量面试机会。
38. [双非鼠鼠终于结束秋招了](https://www.nowcoder.com/feed/main/detail/fbbf13340a7848bda6738850b0ee562f?sourceSSR=dynamic)：重点看无实习 Java 双非硕如何用成都中小厂投递和面经做兜底。

### 简历、投递计划和低年级准备

39. [27 届双非本科 java 实习简历锐评](https://www.nowcoder.com/feed/main/detail/0b7b78e56656486e822149e965cd92c8)：重点看黑马点评包装、简历模板、项目稚嫩感和第一份实习准备。
40. [27 届双非本 Java 日常实习 - 简历 v2 拷打](https://www.nowcoder.com/feed/main/detail/63f84813ed7e4b8886ab9c052017505b)：重点看微服务项目、八股、Hot 100、CodeTop 和投递时间点。
41. [双非 28 届 Java 后端，想在暑假找到实习](https://www.nowcoder.com/feed/main/detail/f4046f973e7e4be48250c1e447e68345)：重点看 JavaWeb、MySQL、Redis、SpringAI、JVM、JUC 的学习顺序和项目亮点不足。
42. [双非本 9 硕 JAVA 日常实习 0 约面](https://www.nowcoder.com/feed/main/detail/a0731f3f2890466f99c8dec2a918cba1)：重点看日常实习简历被挂时如何排查项目、技能和岗位匹配。
43. [26 届双非本 Java 后端求职情况](https://www.nowcoder.com/feed/main/detail/4eb9a209e58b4aca82f38c7dda5e9ebb)：重点看三段实习后仍然面临大厂困难，说明实习质量和岗位匹配同样重要。
44. [26 届 双非 准备找下一段实习](https://www.nowcoder.com/feed/main/detail/a61bb7da896543d2a1aabd886b2f32f0)：重点看有一段经历后，是否需要第二页简历和第二个项目。
45. [27 届双非本实习简历，大佬们帮忙看看](https://www.nowcoder.com/feed/main/detail/c2f8ae76277d48779f9196151b730760)：重点看 0 实习时技能栏、项目亮点和主修课程的取舍。
46. [28 届双非实习简历求拷打](https://www.nowcoder.com/feed/main/detail/1b79556b6a954071a3c5313e1d434e2f)：重点看低年级找实习时项目背景、压测数据和 STAR 表达。
47. [双非二六届](https://www.nowcoder.com/feed/main/detail/2f36f61020ba4712be940f3cdd999712)：重点看 0 offer、0 实习时继续投实习还是准备春招的选择。
48. [很想找 java 后端实习](https://www.nowcoder.com/feed/main/detail/b9087400d97b4b7393ef4a2e4efa2544)：重点看民办二本背景下本地和跨城市投递反馈，以及学历弱势下如何补实习经历。
49. [双非 建议不要 All in Java 岗](https://www.nowcoder.com/feed/main/detail/3598f1715d194c008eb489f2211b4a69)：重点看方向选择风险，提醒不要只盯 Java 后端，也要观察测开、客户端、Go、数据等备选。
50. [双非后端之路](https://www.nowcoder.com/feed/main/detail/9fdfed8b96be45edb8cca5baa95be084?sourceSSR=dynamic)：重点看从不知道计算机学什么，到 Java、项目、八股、力扣和信息差补课的完整路径。

共性结论：

- 双非背景更需要“可验证亮点”：项目压测数据、架构图、源码理解、博客笔记、实习产出、开源 PR，都比空泛自夸有用。
- 项目不能只写功能列表，要写场景、动作、结果。例如“用 Redis 缓存热点数据”不如写清楚缓存对象、更新策略、并发风险和压测结果。
- 八股要能串线表达。Java、MySQL、Redis、网络、操作系统不要只背结论，要能画流程图、讲调用链、讲项目落地。
- 算法不能完全放弃。至少把 Hot 100 刷熟，再按二叉树、链表、哈希、栈队列、动态规划、贪心、图论做二轮复盘。
- 投递要尽早、要记录。牛客样本里很多人都是官网、Boss、内推、线下招聘会一起推进，靠持续复盘换来更多面试机会。
- 中小厂实习也有价值。大一到大二阶段先争取任何真实后端开发机会，实习产出比“又跟完一个视频项目”更有区分度。

第 7 周开始执行：

- 先按上面的 50 篇样本每周读 10 篇，5 周读完；之后再继续搜索“双非 Java 后端 实习 / 春招 / 秋招 / 中厂 / 大厂”相关帖子。
- 每篇只提取 5 个字段：背景、项目、八股高频、算法题型、上岸或挂掉原因。
- 每周把高频问题合并到自己的八股卡片，把项目追问合并到 README。
- 每周至少改 1 次简历项目描述，优先改成“场景 + 技术动作 + 量化结果”。
- 每次面试或模拟面试后，当天补齐不会的问题，第二天用 5 分钟复述。

## 投递节奏

具体岗位线索、投递记录模板，以及日常实习、转正实习、秋招春招分别推荐使用的招聘软件，见：[日常实习机会搜索清单（2026-04-27）](./internship-opportunities-2026-04-27.md)。

第 1 到 4 周：

- 不急着投递，先补基础。
- 可以关注实习岗位 JD，记录要求。

第 5 到 8 周：

- 开始写简历初版。
- 第 7 周开始每周读 10 篇牛客双非 Java 面经样本。
- 第 7 周开始每周模拟面试 1 次。

第 9 到 10 周：

- AI 项目还没有完全成型时，简历先主打传统 Java 后端项目。
- 小规模投递日常实习、内推和本地中小厂岗位，每天 2 到 5 个。
- AI 项目能演示后，再把它加入简历作为第二项目。

第 11 到 12 周：

- 简历放 2 个项目：传统 Java 后端项目 + AI 应用项目。
- 每天投 5 到 10 个岗位，优先投 Java 后端实习，同时保留 AI 应用开发、测开、后端相关岗位作为备选。
- 每次面试后当天复盘。
- 遇到不会的问题，24 小时内补齐。

## 最重要的执行标准

- 资料只选 1 到 2 个主线，不要同时打开 10 套课。
- 项目必须自己改业务，不能原样复制视频项目。
- 每天要写代码，哪怕只有 1 小时。
- 八股必须复述，不要只划线。
- 简历上的每一句话都必须能展开讲。
- 第 7 周后开始模拟面试，越早暴露问题越好。

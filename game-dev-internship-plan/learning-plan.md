# 游戏开发实习准备计划

更新时间：2026-04-27

适用对象：大一或低年级本科生，目标是准备游戏开发相关实习，优先方向是 Unity/C# 游戏客户端开发，同时保留 Unreal/C++、游戏工具、VR/交互开发和游戏后端作为备选。

## 总体路线

建议路线是：先用 Unity 做出能玩的作品，再补 C#、数据结构、游戏数学、图形学和性能优化。游戏开发实习最怕简历上只有“学过 Unity”，没有可试玩 Demo、演示视频、代码仓库和能讲清楚的技术点。

核心目标：

- 掌握游戏客户端实习常见基础：C# 或 C++、数据结构与算法、面向对象、Unity 生命周期、物理、动画、UI、输入、资源加载、对象池、状态机、简单 AI、性能分析。
- 至少完成 2 个可写进简历的作品：一个完整 2D 小游戏，一个 3D Gameplay Demo 或带网络/工具/图形亮点的项目。
- 每个作品都能提供：可执行包或 WebGL 试玩、30 到 90 秒演示视频、GitHub/Gitee 仓库、README、核心代码说明、性能优化记录。
- 第 7 周开始补游戏客户端面经，第 9 周以后根据作品完成度开始小规模投递，不要等所有知识学完再投。

## 方向选择

### 首选：Unity/C# 游戏客户端

适合第一份实习。原因是学习曲线相对友好，资料多，能快速做出可玩的作品，国内实习岗位里 Unity、U3D、C#、Lua、小游戏、手游、VR/AR、交互开发的需求也更容易作为低年级切入口。

你应该重点练：

- C# 基础、集合、委托、事件、协程、泛型、LINQ 基础、GC 与装箱拆箱。
- Unity 场景、Prefab、MonoBehaviour 生命周期、物理碰撞、动画状态机、UGUI、Input System、ScriptableObject。
- 游戏常用结构：状态机、对象池、事件总线、配置表、存档、红点系统、技能系统、简单背包系统。
- 性能：Profiler、GC Alloc、Draw Call、合批、资源加载、对象复用、移动端帧率。

### 进阶：Unreal/C++ 客户端

适合 C++ 基础较强，目标是 3D、动作、开放世界、主机/PC 或引擎向岗位的同学。第一阶段不要 Unity 和 Unreal 同时全量学。可以先用 Unity 做作品，第 8 周以后再补 Unreal Gameplay Framework；或者一开始就坚定 Unreal，但要接受 C++、编译、反射系统、编辑器工作流的学习成本。

你应该重点练：

- C++ 基础、指针/引用、RAII、智能指针、虚函数、内存布局、模板、STL。
- Unreal Actor、Pawn、Character、Controller、GameMode、Component、UObject、UPROPERTY、UFUNCTION、反射和蓝图协作。
- 一个小型 C++ Gameplay Demo，而不是只拖蓝图节点。

### 备选：游戏后端或工具开发

如果你已经在学 Java 后端，可以走“游戏后端/平台后端/运营工具”路线。它和传统后端重合度更高，适合把 Spring Boot、MySQL、Redis、WebSocket、排行榜、房间匹配、登录支付、活动配置平台做成游戏场景项目。

但如果目标岗位写的是“游戏客户端开发”，只会后端不够，必须至少有一个客户端 Demo。

## 推荐资料

使用原则：

- Unity 主线优先看官方 Learn 和官方文档，不要从一堆零散视频开始。
- 图形学先学能服务面试和项目的部分：向量、矩阵、MVP、光栅化、渲染管线、Shader 基础、透明、阴影、深度测试。
- 面经从第 7 周开始看，重点提炼高频问题，不要用面经替代项目。
- 项目视频可以跟，但必须改玩法、改代码结构、写 README，不能把教程项目原样放简历。

### 免费入门资料

1. [Unity Getting Started](https://unity.com/learn/get-started)

   Unity 官方入门入口，适合安装 Unity Hub、理解编辑器、选择学习路径。

   重点看：

   - Unity Hub 和 Editor 安装
   - Unity Essentials
   - 2D/3D 基础工作流
   - 官方学习路径

2. [Unity Create with Code](https://learn.unity.com/course/create-with-code)

   官方 C# 游戏编程入门课，适合作为第 1 到 3 周主线。它不是只教按钮在哪里，而是用多个小原型练 Player Control、Gameplay、音效、UI 和项目计划。

   重点练：

   - Player Control
   - Basic Gameplay
   - Sound and Effects
   - Gameplay Mechanics
   - User Interface
   - 自己扩展一个个人项目

3. [Unity Documentation](https://docs.unity.com/)

   Unity 官方文档入口。遇到 API 和组件问题，优先查文档，不要只搜博客。

   重点查：

   - Scripting API
   - Transform、Instantiate、Physics.Raycast、Vector3、Quaternion
   - Animation、Audio、UI、Physics
   - Input System、URP、Addressables、Profiler

4. [Microsoft C# 文档](https://learn.microsoft.com/en-us/dotnet/csharp/)

   C# 官方文档。Unity 面试会问值类型/引用类型、委托事件、泛型、GC、异步、LINQ、装箱拆箱等，不要只会写 MonoBehaviour。

   重点看：

   - Type system
   - Object oriented programming
   - Exceptions
   - Generics
   - Delegates and events
   - Async programming
   - LINQ 基础

5. [Catlike Coding Unity Tutorials](https://catlikecoding.com/unity/tutorials/)

   适合 Unity 进阶，尤其是程序化网格、渲染、运动、数学和代码结构。不要一开始全刷，项目遇到图形和系统问题时按专题看。

6. [Game Programming Patterns](https://gameprogrammingpatterns.com/)

   游戏编程模式经典资料。重点不是背设计模式名字，而是把它们用到项目里。

   重点看：

   - State：角色状态机、敌人状态机、技能状态。
   - Observer：事件系统、成就、任务、UI 刷新。
   - Object Pool：子弹、特效、敌人、伤害数字。
   - Component：实体能力拆分。
   - Data Locality：性能优化意识。

7. [GAMES101 现代计算机图形学入门](https://games-cn.org/intro-graphics/)

   图形学基础课，适合第 7 周以后系统补。课程偏原理，不教 Unity 或 OpenGL API，但能让你理解渲染管线、光栅化、着色、几何和光线追踪。

   重点看：

   - 向量与线性代数
   - MVP 变换
   - 光栅化与深度测试
   - 着色模型
   - 纹理映射
   - 阴影和反走样

8. [GAMES101 B 站视频](https://www.bilibili.com/video/BV1X7411F744/)

   中文视频版，适合配合笔记学习。不要第 1 周就啃完整门课，先做游戏，再补原理。

9. [LearnOpenGL](https://learnopengl.com/)

   适合想深入渲染或未来做引擎/TA/图形方向的同学。Unity 客户端实习不要求你完整学完 OpenGL，但理解坐标变换、纹理、光照和 Shader 会明显加分。

10. [The Book of Shaders](https://thebookofshaders.com/)

    适合 Shader 入门，重点练颜色、插值、噪声、距离场、简单特效。项目里做一个受击闪白、溶解、描边、水波或扫描线效果，比简历上写“了解 Shader”更有说服力。

11. [Unreal Engine C++ Documentation](https://dev.epicgames.com/documentation/en-us/unreal-engine/programming-with-cplusplus-in-unreal-engine)

    如果走 Unreal/C++，从官方 C++ 编程文档开始。重点理解 Gameplay Architecture、Actor/Object、反射宏、委托和 C++ 与蓝图协作。

12. [Godot 官方文档](https://docs.godotengine.org/en/stable/)

    Godot 适合个人兴趣和独立游戏，但国内客户端实习岗位通常 Unity/Unreal 更多。可以作为低成本做作品的备选，不建议作为第一份实习的唯一主线。

### 付费可选资料

1. Unity 官方认证课程或平台课

   如果自学节奏差，可以买一门项目制课程，但不要把课程项目原样写进简历。付费课的价值是帮你过入门期，不是替你做作品集。

2. 极客时间、技术美术、图形学专题课程

   适合第 8 周以后补渲染、Shader、性能优化。大一阶段优先做可玩的作品，不要上来追完整渲染管线源码。

3. 游戏开发训练营

   谨慎选择。凡是承诺包就业、要求贷款、押证件、先交高额培训费的直接排除。游戏开发能不能过筛，最终看作品、代码、基础和面试表达。

## 项目建议

简历上建议放 2 个作品，作品集里可以再放 1 个小 Demo。

### 项目一：完整 2D 小游戏

推荐选题：

- 2D 平台跳跃
- 俯视角 Roguelike 小游戏
- 弹幕射击
- 塔防小游戏
- 解谜闯关
- 卡牌战斗 Demo

推荐技术栈：

- Unity
- C#
- UGUI 或 UI Toolkit
- Input System
- ScriptableObject
- Tilemap 或简单关卡编辑
- JSON 存档
- WebGL 或 Windows 打包

必须做出的能力点：

- 主菜单、暂停、失败、结算流程
- 角色移动、攻击、受击、死亡
- 敌人 AI 或刷怪系统
- 状态机
- 对象池
- 碰撞检测
- UI 血条、技能冷却、分数或金币
- 音效和基础特效
- 存档或关卡进度
- 可执行包和演示视频

可以写进简历的亮点：

- 使用状态机管理玩家和敌人的移动、攻击、受击、死亡状态，避免动画和逻辑互相打架。
- 使用对象池复用子弹、特效和伤害数字，减少频繁 Instantiate/Destroy 带来的 GC 和卡顿。
- 使用 ScriptableObject 配置角色、敌人、武器和关卡参数，降低硬编码。
- 使用事件系统解耦战斗逻辑和 UI 刷新。
- 使用 Profiler 定位 GC Alloc 和帧率波动，并针对对象生成、UI 刷新和资源加载做优化。

### 项目二：3D Gameplay Demo

推荐选题：

- 第三人称动作 Demo
- 第一人称解谜探索
- 3D 跑酷/竞速
- 小型 Boss 战
- 小型生存建造 Demo
- 多人房间或局域网对战 Demo

推荐技术栈：

- Unity URP
- Cinemachine
- Input System
- Animator
- NavMesh
- Timeline 可选
- Addressables 可选
- Mirror、Netcode for GameObjects 或 WebSocket 可选

必须做出的能力点：

- 角色控制器
- 相机跟随和碰撞处理
- 动画状态机
- 基础战斗或交互
- 敌人寻路或行为树/状态机
- 场景加载
- 配置化数据
- 简单性能优化
- 打包发布

可以写进简历的亮点：

- 基于 Cinemachine 实现第三人称相机，处理遮挡、锁定和镜头跟随。
- 使用 NavMesh 实现敌人巡逻、追击和攻击状态切换。
- 使用动画事件或状态机回调控制攻击判定窗口，减少动画和判定错位。
- 用配置表驱动技能、怪物和关卡数据，方便快速调参。
- 对 Draw Call、贴图尺寸、粒子数量和 GC Alloc 做基础优化，保证目标帧率。

### 项目三：小而尖的加分 Demo

从下面选一个，不要贪多：

- Shader 特效：描边、溶解、受击闪白、水面、扫描线。
- A* 寻路可视化：网格、障碍、启发函数、路径回放。
- 背包和道具系统：配置表、拖拽、堆叠、装备栏、存档。
- 技能系统：冷却、消耗、Buff、命中判定、配置化。
- 简单网络同步：房间、移动同步、聊天、排行榜。
- Unity 编辑器工具：批量检查资源命名、生成配置、关卡刷怪点编辑器。

这个项目不一定要很大，但必须把一个点做深，适合面试时展示“我不只是拖组件，我能解决一个工程问题”。

## 每日固定时间安排

假设平日每天 3 小时，周末每天 5 小时。

平日：

| 时间 | 内容 |
| --- | --- |
| 早上 30 分钟 | 复述 C#/Unity/数学或算法卡片 |
| 晚上 50 分钟 | 看官方文档、课程或面经 |
| 晚上 80 分钟 | 写项目功能 |
| 晚上 30 分钟 | 1 道算法或 1 个小实验 + 当日总结 |

周末：

| 时间 | 内容 |
| --- | --- |
| 上午 2 小时 | 写项目核心玩法 |
| 下午 2 小时 | 调试、优化、打包、修 Bug |
| 晚上 1 小时 | 更新 README、录演示、整理面试问答 |

每天必须输出：

- 1 次 Git 提交
- 1 条开发日志
- 1 个可复述问题
- 1 个可展示的小变化，比如一个新技能、一个 UI、一个敌人行为、一次优化截图

## 12 周学习计划

计划周期：2026-04-27 到 2026-07-19。

| 周次 | 周一 | 周二 | 周三 | 周四 | 周五 | 周六 | 周日交付 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 第 1 周：C# 和 Unity 入门 | C# 基础 | OOP、集合 | Unity Editor | Transform、Prefab | MonoBehaviour 生命周期 | Create with Code 原型 | 3 个小场景 + C# 笔记 |
| 第 2 周：Unity 核心组件 | 输入系统 | 物理碰撞 | 动画基础 | UGUI | 音效和粒子 | 小玩法原型 | 可玩的 1 分钟 Demo |
| 第 3 周：项目一启动 | 选题和核心循环 | 角色控制 | 敌人和碰撞 | UI 和结算 | 对象池 | 关卡 1 | README 初版 |
| 第 4 周：项目一强化 | 状态机 | 配置表 | 存档 | 音效特效 | Profiler 入门 | 打包发布 | 2D 小游戏可试玩 |
| 第 5 周：3D 基础 | 3D 数学 | Character Controller | Cinemachine | Animator | 物理射线 | 3D 交互原型 | 第三人称控制 Demo |
| 第 6 周：项目二启动 | 选题和场景 | 相机和移动 | 战斗或交互 | NavMesh AI | UI 和配置 | Boss 或关卡 | 3D Demo 核心玩法 |
| 第 7 周：基础补强 | 数据结构 | 算法 Hot 题 | C# GC | C++ 高频基础 | 游戏数学 | 读 5 篇面经 | 高频题卡片 |
| 第 8 周：图形和性能 | 渲染管线 | Shader 基础 | Draw Call | 资源加载 | GC 优化 | 做一个 Shader Demo | 优化记录 + 截图 |
| 第 9 周：工程化 | 事件系统 | 配置系统 | 编辑器工具 | Addressables 入门 | 网络/排行榜选学 | 项目二补完整流程 | 作品集页面初版 |
| 第 10 周：项目打磨 | 手感优化 | 关卡节奏 | Bug 修复 | 打包 WebGL/PC | 演示视频 | 代码整理 | 两个作品可展示 |
| 第 11 周：求职准备 | 简历 | 项目问答 | 牛客面经 | 算法复盘 | 模拟面试 | 小规模投递 | 简历 v1 + 投递表 |
| 第 12 周：投递冲刺 | JD 复盘 | 简历迭代 | 面试补弱 | 作品集完善 | 模拟面试 | 稳定投递 | 复盘和补弱清单 |

## 八股复习优先级

### 第一优先级

- C# 基础：值类型/引用类型、委托、事件、泛型、接口、装箱拆箱、GC、协程。
- Unity 基础：生命周期、Prefab、Scene、Transform、Physics、Collider/Trigger、UGUI、Animator、Input。
- 数据结构与算法：数组、链表、栈队列、哈希、树、堆、图、排序、搜索、动态规划基础。
- 游戏数学：向量、点乘、叉乘、插值、矩阵、欧拉角、四元数、坐标空间转换。
- 游戏架构：状态机、对象池、事件系统、配置表、组件化、存档。

### 第二优先级

- 性能优化：Profiler、GC Alloc、Draw Call、合批、资源加载、贴图和粒子优化。
- 图形学基础：渲染管线、MVP、光栅化、深度测试、透明混合、阴影、抗锯齿、Shader。
- 网络基础：TCP/UDP、WebSocket、帧同步/状态同步概念、延迟和预测概念。
- C++ 基础：虚函数、智能指针、内存管理、STL、构造析构、引用和指针。
- Lua 基础：表、闭包、元表、热更新概念。

### 第三优先级

- Unreal Gameplay Framework
- ECS/DOTS
- Addressables 深入
- 热更新框架
- 引擎源码
- 渲染管线源码
- 技术美术工作流

## 面试准备方式

### 不要只说“我做了一个小游戏”

每个项目按这个结构准备：

1. 游戏是什么，核心玩法是什么。
2. 你负责哪些模块。
3. 你为什么这样拆代码。
4. 哪些地方用了状态机、对象池、事件、配置表。
5. 遇到什么 Bug 或性能问题。
6. 怎么定位，怎么修。
7. 如果做成商业项目，下一步怎么扩展。

示例：对象池

- 是什么：预先创建一组可复用对象，运行时反复取出和归还。
- 为什么需要：子弹、特效、伤害数字频繁创建销毁，会带来 GC 和卡顿。
- 项目里怎么用：给子弹和伤害数字做对象池，死亡或播放结束后回收。
- 坑：回收时要重置状态，比如速度、父节点、事件订阅、粒子播放状态。
- 优化：按对象类型分池，启动时预热，池满时限制生成或扩容。

### 项目必须能讲 10 分钟

准备以下问题：

- 你的游戏核心循环是什么？
- 玩家输入到角色移动，中间发生了什么？
- Unity 的 Update、FixedUpdate、LateUpdate 分别适合放什么？
- Collider 和 Trigger 的区别是什么？
- Animator 和代码状态机如何配合？
- 为什么需要对象池？
- 你的敌人 AI 怎么实现？
- 你的 UI 怎么和战斗逻辑解耦？
- 你的项目如何存档？
- Profiler 看过哪些指标？
- 出现卡顿你怎么排查？
- 你做过什么 Shader 或图形效果？
- 如果加入 100 个敌人，项目会哪里先出问题？
- 如果让你加一个新角色或新技能，要改哪些地方？

## 牛客游戏客户端面经观察

这些帖子和岗位样本不要当标准答案看，要当作求职风险清单。游戏客户端面试比普通前端/后端更看作品真实性，项目追问会具体到输入、UI、AI、动画、资源、性能和数学。

推荐阅读样本：

1. [2025 暑期实习游戏开发/Unity 开发/VR 开发面经总结](https://www.nowcoder.com/discuss/1495985)：重点看 C++、Unity、图形学、算法和项目问题如何分类复盘。
2. [游戏客户端面经及经历分享](https://www.nowcoder.com/discuss/860341579272212480)：重点看 C++、图形学、算法、Unity 和 UE 高频问题。
3. [游戏客户端面经](https://www.nowcoder.com/discuss/720516)：重点看 Unity、数学、渲染和业务题。
4. [23 届游戏开发/游戏客户端开发岗位个人秋招全记录](https://www.nowcoder.com/discuss/1103114)：重点看项目、实习、笔试和 Gameplay 经验不足带来的风险。
5. [Unity 客户端实习生（游戏开发）岗位样本](https://www.nowcoder.com/jobs/detail/335349)：重点看 JD 对 Unity Demo、数据结构算法、C++/C#、性能优化和协作能力的要求。
6. [游戏客户端开发实习生（26 届）岗位样本](https://www.nowcoder.com/jobs/detail/371573)：重点看 Unity、C++/C#、Lua、数学、网络、图形学和到岗时间要求。
7. [游戏客户端开发实习生（可转正）岗位样本](https://www.nowcoder.com/jobs/detail/309347)：重点看 Unity/Cocos、C/C++/C#/Lua 和“热爱游戏”的表达方式。
8. [UE 客户端开发实习生岗位样本](https://www.nowcoder.com/jobs/detail/411156)：重点看 Unreal/Unity、C++、算法和玩法实现能力。

共性结论：

- 游戏开发简历必须有可打开的作品。只有截图和课程描述不够。
- Unity 岗也经常问 C++、数据结构、算法、数学和图形学。
- 项目要讲“实现细节”，比如状态机怎么转移、AI 怎么寻路、对象池怎么回收、UI 怎么刷新。
- 图形学不用一开始很深，但渲染管线、MVP、深度测试、透明混合、阴影、抗锯齿要能说清。
- 游戏公司很看实习到岗时间。大一阶段可以先找中小团队、VR/交互/工具开发、校园项目和比赛作品积累经历。
- 作品集质量比“学了多少课”重要。一个完整、手感好、代码清楚的小作品，比三个半成品更有价值。

第 7 周开始执行：

- 每周读 5 篇游戏客户端面经。
- 每篇只提取 5 个字段：问了什么基础、问了什么项目、问了什么算法、岗位要求什么作品、自己缺什么。
- 每周至少录一次 5 分钟项目讲解。
- 每周至少改一次 README，把功能列表改成“问题 + 方案 + 结果”。

## 投递节奏

具体岗位搜索词、平台、城市、沟通话术和投递记录模板，见：[游戏开发实习机会搜索清单（2026-04-27）](./internship-opportunities-2026-04-27.md)。

第 1 到 4 周：

- 不急着投游戏公司，先做出第一个可玩的 2D Demo。
- 可以收藏 JD，记录高频要求。
- 不要把“学习中”写进简历当项目。

第 5 到 8 周：

- 第一个作品能打包后，开始写简历初版。
- 每周读面经和 JD，补 C#、Unity、算法、数学。
- 找老师、同学或社群做一次作品试玩反馈。

第 9 到 10 周：

- 第二个作品有核心玩法后，小规模投递 Unity/游戏客户端/VR/交互开发实习。
- 每天投 2 到 5 个，优先投不限制高年级、接受长期实习、要求有 Demo 的岗位。
- 简历里放作品集链接和演示视频。

第 11 到 12 周：

- 简历放 2 个作品：完整 2D 小游戏 + 3D Gameplay Demo 或小而尖加分 Demo。
- 每天投 5 到 10 个岗位，同时保留 Unity 交互开发、VR 开发、游戏工具开发、游戏后端作为备选。
- 每次面试或笔试后当天复盘，第二天补齐不会的问题。

## 简历项目描述模板

### 2D 小游戏模板

```text
项目名称：2D 俯视角 Roguelike 小游戏

项目简介：
基于 Unity 实现的 2D 俯视角动作 Roguelike Demo，包含角色移动、怪物追击、武器攻击、随机房间、掉落奖励、UI 结算和本地存档。项目提供 Windows 可执行包、WebGL 试玩和演示视频。

技术栈：
Unity、C#、UGUI、Input System、ScriptableObject、JSON、Profiler

个人职责：
1. 负责角色控制、敌人 AI、武器攻击、受击反馈、UI 和结算流程开发。
2. 使用状态机管理玩家和敌人的移动、攻击、受击、死亡等状态。
3. 使用对象池复用子弹、特效和伤害数字，降低运行时 GC 和卡顿。
4. 使用 ScriptableObject 配置武器、敌人和房间参数，支持快速调参。
5. 使用事件系统解耦战斗逻辑与 UI 刷新，降低模块耦合。
6. 使用 Profiler 定位 GC Alloc 和帧率波动，并完成对象生成和 UI 刷新的优化。
```

### 3D Gameplay Demo 模板

```text
项目名称：第三人称动作战斗 Demo

项目简介：
基于 Unity URP 实现的第三人称动作 Demo，包含角色移动、相机跟随、锁定敌人、连击、受击、敌人巡逻追击、Boss 战和关卡结算。

技术栈：
Unity、C#、URP、Cinemachine、Animator、NavMesh、Input System、Profiler

个人职责：
1. 负责第三人称角色控制、镜头跟随、战斗判定、敌人 AI 和关卡流程开发。
2. 基于 Cinemachine 实现跟随、锁定和碰撞避让相机。
3. 使用动画状态机和动画事件控制攻击判定窗口，保证动作和伤害同步。
4. 使用 NavMesh 实现敌人巡逻、追击、攻击和返回逻辑。
5. 使用配置表管理角色、敌人、技能和关卡参数。
6. 对粒子数量、Draw Call、GC Alloc 和资源加载做基础优化，稳定目标帧率。
```

### 小而尖 Demo 模板

```text
项目名称：Unity A* 寻路可视化工具

项目简介：
基于 Unity 实现的 A* 寻路可视化 Demo，支持网格编辑、障碍绘制、起点终点设置、路径回放和启发函数切换，用于展示寻路算法和调试过程。

技术栈：
Unity、C#、UGUI、Tilemap 或自定义 Grid、A*、Gizmos

个人职责：
1. 实现 A* 寻路核心逻辑，支持开放列表、关闭列表和路径回溯可视化。
2. 支持 Manhattan、Euclidean 等启发函数切换，并比较不同路径结果。
3. 使用 Gizmos 和 UI 展示节点代价、搜索过程和最终路径。
4. 封装 Grid 和 Node 数据结构，方便扩展到项目中的敌人寻路。
```

## 作品集要求

每个作品至少包含：

- README：玩法介绍、技术栈、核心功能、技术亮点、运行方式、截图。
- 演示视频：30 到 90 秒，展示完整流程，不要只展示编辑器。
- 可执行包：Windows、WebGL 或 Android APK 至少一种。
- 代码仓库：提交记录清晰，不要所有代码一次性上传。
- 技术复盘：写清楚 3 个问题和解决方案。

作品集页面建议结构：

| 作品 | 类型 | 可试玩 | 视频 | 技术亮点 |
| --- | --- | --- | --- | --- |
| 2D Roguelike | Unity 2D | 链接 | 链接 | 状态机、对象池、配置表、Profiler |
| 第三人称动作 Demo | Unity 3D | 链接 | 链接 | Cinemachine、Animator、NavMesh、战斗判定 |
| A* 可视化 | 算法 Demo | 链接 | 链接 | A*、启发函数、搜索过程可视化 |

## 最重要的执行标准

- 先做出可玩的作品，再补理论。
- 每个作品都要能打包、能演示、能讲代码。
- 不要同时学 Unity、Unreal、Godot、Cocos，第一阶段选一个主线。
- 不要只收藏教程。每周必须有可运行增量。
- 面试不是让你背“Unity 生命周期”定义，而是让你解释为什么某段逻辑放在 Update、FixedUpdate 或 LateUpdate。
- 简历上的每一句项目描述，都必须能打开代码讲 3 分钟。
- 第 7 周后开始模拟面试，越早暴露问题越好。

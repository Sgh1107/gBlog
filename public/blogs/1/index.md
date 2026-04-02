> + _**<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">题号范围</font>**__<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">：</font>__**<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">第 15～30 题左右</font>**__<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">（不绝对固定，但集中在中前段）</font>_
> + _**<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">软件工程整体</font>**__<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">：</font>__**<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">10～13 题 ≈ 10～13 分</font>**_
> + _**<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">结构化开发（结构化分析 / 设计、DFD、耦合内聚、瀑布模型等）</font>**__<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">：</font>_
>     - _**<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">2～4 题 ≈ 2～4 分</font>**__<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">（属于软件工程下的子考点）</font>_
> + _<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">软件工程整体：</font>__**<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">约 13%～17%</font>**_
> + _<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">结构化开发：</font>__**<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">约 3%～5%</font>**_
>

---

# 软件过程CMM与CMMI
## CMM
| 等级 | 级别名称 | 核心特征（高频考点） | 关键产出 / 重点 |
| --- | --- | --- | --- |
| 1 级 | **初始级**(Initial) | 无序、混乱，靠个人英雄主义；过程不可预测 | 无标准流程，质量 / 进度难管控 |
| 2 级 | **可重复级**(Repeatable) | 项目级管理，基本项目管理；同类项目可重复成功 | 需求管理、项目策划、配置管理、质量保证 |
| 3 级 | **已定义级**(Defined) | **组织级标准过程**，全公司统一裁剪使用；文档标准化 | 培训体系、组织过程定义、集成工程 |
| 4 级 | **已管理级**(Managed) | 量化管理，数据度量；过程 / 质量可定量控制 | 统计过程控制、量化目标、数据分析 |
| 5 级 | **优化级**(Optimizing) | 持续主动优化，缺陷预防、技术革新；闭环改进 | 缺陷预防、过程革新、新技术推广 |


## CMMI
| CMMI 等级 | 成熟度名称 | 核心高频考点（软考单选 / 填空） |
| --- | --- | --- |
| 1 | **初始级** | 过程混乱、即兴而为，依赖个人能力，风险高 |
| 2 | **可重复级** | 建立基础项目管理，过程可复用，管控项目基本要素 |
| 3 | **已定义级** | 组织统一标准过程，过程裁剪、文档规范、跨项目协同 |
| 4 | **量化管理级** | 量化数据度量，定量管控质量与绩效，预测过程偏差 |
| 5 | **持续优化级** | 主动过程改进、缺陷预防、新技术导入，持续降本提质 |


| 等级 | 中文名称 | 核心含义（软考常考） |
| --- | --- | --- |
| **CL0** | **未完成级 / 不完整级** | 过程没做，或目标没达成 |
| **CL1** | **已执行级** | 基本完成工作，有输入输出 |
| **CL2** | **已管理级** | 过程有计划、被监控（同阶段式 ML2） |
| **CL3** | **已定义级** | 组织级标准化（同阶段式 ML3） |
| **CL4** | **量化管理级** | 量化控制（同阶段式 ML4） |
| **CL5** | **优化级** | 持续优化（同阶段式 ML5） |


# 软件过程模型
![画板](https://cdn.nlark.com/yuque/0/2026/jpeg/32399360/1774684767106-5b08b046-5ed1-4480-8b7e-e3c2d9a2468f.jpeg)

+ 演化模型是一个迭代的过程模型，常常用于多变化的场景（需求不太明确，先开发大致框架），商业和产品需求经常发生变化，对软件需求缺乏准确认知，是一种用于专门应对不断变化的软件产品的过程模型。

## 🔥各模型历年考点总结
### 瀑布模型
> 简单总结就是：**<font style="color:#601BDE;">开发一个之前开发过的/之前有过经验的新系统！</font>**
>

![画板](https://cdn.nlark.com/yuque/0/2026/jpeg/32399360/1774681760538-26f62488-b674-40bd-99f6-7bab1d1085d8.jpeg)

### 增量模型
> 总结：**<font style="color:#601BDE;">适合是商业产品的开发，可以快速构造出核心产品！</font>**
>

![画板](https://cdn.nlark.com/yuque/0/2026/jpeg/32399360/1774688015112-65444778-43f6-4969-9612-fbe258e4b7f5.jpeg)

### 演化模型
![画板](https://cdn.nlark.com/yuque/0/2026/jpeg/32399360/1774684060648-40358b81-b5b1-4367-9d73-c452e978c95e.jpeg)

# 敏捷方法（小组织适用）
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/32399360/1774687815536-320fd9f0-c3d4-4251-a8b1-1b887ed92c7c.png)

| 敏捷方法 | 高频特点 & 软考考点 | 关键词 |
| --- | --- | --- |
| **Scrum** | ✅ 固定迭代、时间盒<br/>✅ 自组织团队、跨职能<br/>✅ SM 负责移除障碍、不做任务分配<br/>✅ 三大会议 + 两大待办列表 | "30天作为一个**<font style="color:#DF2A3F;">冲刺</font>**" |
| **XP 极限编程** | ✅ 四大价值观：沟通、简单、反馈、勇气<br/>✅ 核心实践：结对编程、持续集成、<font style="color:#DF2A3F;background-color:#FBDE28;">测试先行 TDD</font>、重构、小型发布<br/>✅ **客户现场参与**是特色 | "编码速度慢"<br/>"有非正式的code review"<br/>**<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">持续集成、小步发布</font>**，可以按日甚至按小时版本   |
| **Crystal 水晶法** | ✅ 核心：**人本主义**，重视人员协作<br/>✅ 分多个等级 (Clear/Yellow/Orange/Red)<br/>✅ 文档最少化，适合不同规模项目 |  |


# 软件测试
在软件开发过程中，系统测试阶段的测试目标来自于`**<font style="color:#DF2A3F;">需求分析阶段</font>**`！

软件测试活动应该遍布开发过程的每个阶段，没有说一定要从哪个阶段开始！！测试过程中存在的错误数量是不能确定的，所以下述这种说法是错误的！

```plain
[×] 在一个被测程序中，已发现的错误越多则残存的错误越少
```

软件测试方法分为动态测试和静态测试两种，其中静态测试是指使用`人工检测和计算机辅助静态工具`的方法进行测试，相反的，动态测试则是通过运行程序发现错误，静态测试没考过... 动态测试主要考的是黑盒和白盒测试两种方法。

+ 测试类中定义的每个方法属于 **<font style="color:#601BDE;">算法层</font>****<font style="color:#000000;"></font>**
+ 对类中定义的每个方法进行测试属于 

## 单元测试


## 系统测试
系统测试的目的主要是为了发现 **需求分析** 阶段的问题。测试计划也应在 **需求分析** 阶段撰写。

## 集成测试
集成测试是最适合发现 模块之间 的接口问题。

## 回归测试
回归测试总结下来简单来说就是当修改当前系统存在的问题1时，可能会引起之前的程序出现问题，所以要进行回归测试（重新测试之前程序的功能）。

## 黑盒和白盒测试
+ 白盒测试更关注的是程序你内部的逻辑和路径覆盖，不会去关注输入的数据是否合理。合理与不合理的输入应当再黑盒测试中进行。

### ⚠️白盒测试（考点很多）
![画板](https://cdn.nlark.com/yuque/0/2026/jpeg/32399360/1774677290787-8612838d-4ee7-4750-8a11-e2f6b0953fff.jpeg)

从上至下覆盖强度由低到高！

![画板](https://cdn.nlark.com/yuque/0/2026/jpeg/32399360/1774679797489-f605cd60-41d7-4b79-ab8c-0455c00702b2.jpeg)

# 耦合类型和内聚类型
| **<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">耦合类型</font>** | **<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">核心判定关键词</font>** | **<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">考场秒选特征</font>** |
| --- | --- | --- |
| **<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">无直接耦合</font>** | <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">模块间</font>**<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">无任何调用、无数据传递</font>** | <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">完全独立，互不来往</font> |
| **<font style="color:#601BDE;background-color:rgba(0, 0, 0, 0);">数据耦合</font>** | <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">传递</font>**<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">简单参数、基本数据类型</font>**<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">，只传值</font> | <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">常规函数传普通参数，最推荐</font> |
| **<font style="color:#601BDE;background-color:rgba(0, 0, 0, 0);">标记耦合 (特征耦合)</font>** | <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">传递</font>**<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">复合数据 / 结构体 / 对象</font>**<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">，共用数据结构</font> | <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">传结构体、数组、类对象</font> |
| **<font style="color:#601BDE;background-color:rgba(0, 0, 0, 0);">控制耦合</font>** | <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">传递</font>**<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">控制信号 / 标志位 / 开关量</font>**<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">，决定内部逻辑分支</font> | <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">传 flag、状态码、控制跳转、if 分支控制</font> |
| **<font style="color:#601BDE;background-color:rgba(0, 0, 0, 0);">外部耦合</font>** | <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">依赖</font>**<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">外部环境、全局 I/O、硬件、通信协议</font>** | <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">共用外设、接口协议、固定外部端口</font> |
| **<font style="color:#601BDE;background-color:rgba(0, 0, 0, 0);">公共耦合</font>** | <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">共享</font>**<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">全局数据区、公共变量、公共存储区</font>** | <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">全局变量、公共数据库全局表、共享内存区</font> |
| **<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">内容耦合</font>** | <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">一个模块</font>**<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">直接修改 / 访问另一模块内部代码、数据、跳转</font>** | <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">侵入内部、改别人代码、 goto 跨模块、读内部私有数据</font> |


<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">💡</font><font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);"> 高频易错：</font>

+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">传简单值 → 数据耦合</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">传结构体 / 对象 → 标记耦合</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">传控制 flag → 控制耦合</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">全局变量 → 公共耦合</font>
+ <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">改别人内部数据 → 内容耦合（最垃圾）</font>

---

| **<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">内聚类型</font>** | **<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">核心判定关键词</font>** | **<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">考场秒选特征</font>** |
| --- | --- | --- |
| **<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">功能内聚</font>** | **<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">单一完整功能、只做一件事</font>** | <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">一个模块只完成一个明确核心功能</font> |
| **<font style="color:#601BDE;background-color:rgba(0, 0, 0, 0);">顺序内聚</font>** | <font style="color:#601BDE;background-color:rgba(0, 0, 0, 0);">处理步骤</font>**<font style="color:#601BDE;background-color:rgba(0, 0, 0, 0);">按顺序、前输出是后输入   </font>****<font style="color:#601BDE;background-color:rgba(0, 0, 0, 0);">前一步输出 = 后一步输入</font>** | <font style="color:#601BDE;background-color:rgba(0, 0, 0, 0);">A 结果→传给 B 当输入，流水线顺序执行</font> |
| **<font style="color:#601BDE;background-color:rgba(0, 0, 0, 0);">通信内聚</font>** | <font style="color:#601BDE;background-color:rgba(0, 0, 0, 0);">同一批</font>**<font style="color:#601BDE;background-color:rgba(0, 0, 0, 0);">输入 / 输出数据</font>**<font style="color:#601BDE;background-color:rgba(0, 0, 0, 0);">，共享数据加工   </font><font style="color:#601BDE;background-color:rgba(0, 0, 0, 0);">在</font>**<font style="color:#601BDE;background-color:rgba(0, 0, 0, 0);">同一数据结构</font>**<font style="color:#601BDE;background-color:rgba(0, 0, 0, 0);">上操作</font> | <font style="color:#601BDE;background-color:rgba(0, 0, 0, 0);">多个操作围绕同一数据加工、读写同一文件</font> |
| **<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">过程内聚</font>** | <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">代码</font>**<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">按流程步骤编排，无共享数据</font>** | <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">只为执行流程顺序，数据不互通</font> |
| **<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">时间内聚 (经典必考)</font>** | **<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">同一时间段、初始化 / 收尾</font>**<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">一批操作</font> | <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">初始化所有变量、关闭所有资源、启动就绪一组动作</font> |
| **<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">逻辑内聚</font>** | <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">功能</font>**<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">逻辑相似、打包在一起</font>**<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">，靠参数选执行</font> | <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">多个同类功能放一个模块，传参数决定用哪个</font> |


<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">💡</font><font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);"> 内聚考场秒杀：</font>

1. <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">只干一件完整事 → </font>**<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">功能内聚</font>**
2. <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">前一步输出 = 后一步输入 → </font>**<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">顺序内聚</font>**
3. <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">共用同一数据加工 → </font>**<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">通信内聚</font>**
4. <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">同一时刻一起做（初始化）→ </font>**<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">时间内聚</font>**
5. <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">参数选相似功能 → </font>**<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">逻辑内聚</font>**
6. <font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">乱七八糟凑一起 → </font>**<font style="color:rgb(0, 0, 0);background-color:rgba(0, 0, 0, 0);">偶然内聚</font>**

# McCabe度量法
考点基本就固定的这一个：计算有向图`G`的环路复杂性即环路个数`V(G)`

$ V(G) = m-n+2 $亦可以写为 $ V(G)=闭合区域数量+1 $

+ `m`代表有向图中边的个数
+ `n` 代表有向图中点的个数

# 软件维护
<font style="color:rgb(0, 0, 0);">软件可维护性评价指标通常涵盖</font>**<font style="color:rgb(0, 0, 0);">易于理解、诊断、修改的特性</font>**<font style="color:rgb(0, 0, 0);">。根据ISO/IEC 25010标准，可维护性包括</font><font style="color:#601BDE;">模块化、可重用性、可分析性、可修改性、可测试性</font><font style="color:rgb(0, 0, 0);">等维度。</font>

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/32399360/1774707125193-4c712694-de07-46ef-9101-000bb807db9c.png)

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/32399360/1774771034808-61fa3156-d519-4ff4-a820-8459116d3aaa.png)

+ 可靠性：$ MTTF/(1+MTTF) $		【**<font style="color:#DF2A3F;">可靠性和故障时间挂钩</font>**】
+ 可用性：$ MTBF/(1+MTBF) $		【**<font style="color:#DF2A3F;">可用性和修复时间挂钩</font>**】
+ 可维护性：$ 1/(1+MTTR) $			**【可维护性一般最小】**

# 📋补充内容
<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/32399360/1774688352131-90c29919-dcc0-4951-9fa9-33a7ed60603f.png)



<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/32399360/1774707459542-5cdf7c76-a06d-4a95-a6e0-536c48ff4cef.png)



<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/32399360/1774707518744-c9dcde42-747a-444e-8aaa-b7e79114822f.png)

## Pert图
<font style="color:rgb(0, 0, 0);">PERT图是一种用于表示项目进度和关键任务的图表，使用</font>**<font style="color:#DF2A3F;">网络模型</font>**<font style="color:rgb(0, 0, 0);">描述任务与任务之间的关系，PERT图不仅给出了每个任务的开始时间、结束时间和完成该任务所需的时间，还给出了任务之间的关系，即哪些任务完成之后才能开始另外的一些任务，以及如期完成整个工程的关键路径。</font>

<font style="color:rgb(0, 0, 0);">但是，</font>**<font style="color:#601BDE;">PERT图并不能直接反映出项目的实际进度情况。</font>**

## <font style="color:rgb(0, 0, 0);">甘特图</font>
<font style="color:rgb(0, 0, 0);">甘特图是一种进度管理的工具，以日历为基准，用</font>**<font style="color:#DF2A3F;">水平条状图</font>**<font style="color:rgb(0, 0, 0);">描述；</font>**<font style="color:#601BDE;">易于看出每个子任务的持续时间和目前项目的实际进度情况</font>**<font style="color:rgb(0, 0, 0);">，还能看出任务的进展情况以及各个任务之间的并行性。</font>

<font style="color:rgb(0, 0, 0);">但是子任务之间的</font>**<font style="color:rgb(0, 0, 0);">衔接关系，不能在甘特图中看出</font>**<font style="color:rgb(0, 0, 0);">；不能清晰地反映出各任务之间的依赖关系，难以确定整个项目的关键所在，也不能反映计划中有潜力的部分。</font>

## <font style="color:rgb(0, 0, 0);">配置管理</font>
配置管理包括版本控制、变更管理、配置状态报告和配置审计四部分，风险管理并不属于配置管理！


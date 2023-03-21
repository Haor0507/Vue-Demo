近四十年来

摩尔定律一直是引领计算机行业动态发展的重要规律

而计算机行业又影响着各行各业的发展

在成本和功耗不变的情况下
性能的指数级增长已经放缓

然而，计算技术的发展日新月异

曲速引擎是加速计算，动力来源就是 AI

各行各业正在应对

可持续发展、生成式 AI

和数字化等强大的动态挑战

因此加速计算和 AI 的到来

恰逢其时

如果没有摩尔定律，随着计算量的激增
数据中心的能耗飙升

企业将难以实现净零排放

生成式 AI 的非凡能力

使得企业产生了紧迫感，他们需要重新构思他们的产品和商业模式

产业内各企业正在竞相实现数字化转型，成为软件驱动的科技公司

要成为颠覆者

而不是被颠覆者

今天，我们将讨论加速计算和 AI 如何成为强大的工具，帮人们应对这些挑战

和把握未来的巨大机遇

我们将分享 NVIDIA 的数据中心级全栈加速计算平台的新进展

我们将展示新的芯片和系统、加速库、云服务、AI 服务

以及助力我们拓展新市场的合作伙伴关系

欢迎来到 GTC 大会！

GTC 是我们面向开发者的一场盛会

这个全球 NVIDIA 生态系统涵盖 400 万开发者
4 万家公司

和 1.4 万家初创公司

感谢我们的钻石赞助商，他们为我们提供大力支持
并助力 2023 年 GTC 大会取得巨大成功

我们非常高兴地欢迎超过 25 万人
参加我们的大会

GTC 大会的发展令人难以置信

就在四年前，我们的线下 GTC 大会
还只有 8000 名与会者

在 2023 年 GTC 大会上
我们将向 DeepMind 的 Demis Hassabis

阿贡实验室的 Valeri Taylor

Adobe 的 Scott Belsky

Netflix 的 Paul Debevec

苏黎世联邦理工学院的 Thomas Schulthess 等领导者学习

并且我还将与创造出 ChatGPT 的 OpenAI 公司的联合创始人 Ilya Sutskever

进行一场特别的炉边谈话

来自学术界和全球大型行业的精英将带来 650 场精彩演讲：

仅与生成式 AI 相关的演讲就超过 70 场

其他精彩演讲，例如适用于机器人开发的预训练多任务模型

还有推进 AI 发展的重要方法 —— 合成数据生成的演讲

包括如何使用 Isaac Sim 生成
基于物理性质的激光雷达点云

还有一系列关于数字孪生的演讲
从使用 AI 拓展未来的虚拟工厂

到重现遗失了的古罗马马赛克艺术作品，内容多种多样

有关于计算仪器的酷炫演讲，包括巨型光学望远镜和光子计数 CT

以及用于碳捕获和太阳能电池的材料科学

以及气候科学的讨论，及我们在 Earth-2 上所做的工作

NVIDIA 研究团队也将带来的重要演讲
探讨关于值得信赖的 AI 和 AV 安全等议题

还有从微芯片的计算光刻技术 ，到制造最小的机器

再到将 AI 应用在大型强子对撞机中以解释宇宙的议题

大会汇集了全球最重要的公司和企业，包括汽车和交通运输业

医疗健康业、制造业、金融服务业

零售业、服装业、媒体和娱乐业、电信业

以及全球顶尖的 AI 公司

GTC 大会的宗旨是激励全世界，告诉大家，加速计算是可以实践的

并为科学家和研究人员
通过利用该技术取得的成就喝彩

我是一名翻译

将文本转化为创造性发现

将动作转化为动画

将指令转化为行动

我是一名治疗师

探索让人类与众不同的组成基础

在新威胁发生之前进行建模

并寻找治疗方法以防止入侵

我是一名梦想家

致力创造新的医学奇迹

让人们以全新视角了解太阳

确保我们在地球上安全无虞

我是一名导航者

在海量内容中探索独特片刻

为一个个故事打造理想的背景

我是一名创造者

通过快照构建 3D 体验

并将虚拟自我提升至更高的现实水平

我是一名好帮手

将头脑风暴变为现实

分享 100 万程序员的智慧

并将想法转化为虚拟世界

“建造北方森林”

我还帮助编写了这支短片的脚本

给文字注入生命

并为其谱写旋律

我是 AI

NVIDIA、深度学习以及无所不在的人类智慧
将我融入每个人的生活

NVIDIA 率先推出加速计算，着力解决普通计算机
无法解决的问题

加速计算并非易事

它需要从芯片、系统、网络、加速库

到重构应用的全栈发明

从图形、成像、粒子或流体动力学、量子物理学

到数据处理和机器学习

每个经过优化的堆栈都会加速对应应用领域

加速后，应用可以获得令人难以置信的速度，还可以扩展到许多台计算机

在过去十年中，加速和纵向扩展的结合

使我们能够为许多应用

实现百万倍的性能提升

进而有助于解决以前无法解决的问题

虽然存在很多示例

但最著名的一个是深度学习

2012 年，Alex Kerchevsky、Ilya Suskever 和 Geoff Hinton
需要一台速度超快的计算机

来训练 AlexNet 计算机视觉模型

研究人员在 GeForce GTX 580 上
使用 1400 万张图像训练了 AlexNet

可处理 262 千万亿次浮点运算

经过训练的模型以压倒性优势赢得了 ImageNet 挑战赛，并触发了 AI 的大爆炸

十年后，Transformer 模型面世了

现在任职于 OpenAI 的 Ilya
训练了 GPT-3 大型语言模型来预测下一个单词

训练 GPT-3 需要进行 323 x 10e21 次浮点运算

浮点运算量比训练 AlexNet
多一百万倍

结果创造出了 ChatGPT，这个震惊全世界的 AI

崭新的计算平台已经诞生

AI 的 “iPhone 时刻” 已经到来

加速计算和 AI 技术已经走进现实

加速库是加速计算的核心

这些加速库连接到了各种应用中，进而再连接到遍布世界的各行各业，形成了网络中的网络

经过 30 年的开发，已经有数千款应用被 NVIDIA 的库加速

几乎涉及科学和工业的每个领域

所有 NVIDIA GPU 都兼容 CUDA，为开发者提供了庞大的安装基础和广泛的覆盖范围

大量加速应用吸引了终端用户，这为云服务提供商和计算机制造商

创造了一个庞大的市场

这个市场大到足以投入数十亿的研发费用来推动其增长

NVIDIA 建立了加速计算的良性循环

在涵盖光线追踪和神经渲染、物理、地球和生命科学
量子物理学和化学、计算机视觉

数据处理、机器学习和 AI 的
 300 个加速库和 400 个 AI 模型中

我们今年更新了其中的 100 个

让所有正在使用中的用户享受到更高的性能
更多的功能

下面，我来重点介绍一些可以解决新挑战、开辟新市场的加速库

汽车和航空航天行业使用 CFD 进行湍流
和空气动力学仿真

电子行业使用 CFD 进行热管理设计

这是 Cadence 的幻灯片，展示了
由 CUDA 加速的新 CFD 求解器

在同等系统成本下，NVIDIA A100 的吞吐量
是 CPU 服务器的 9 倍

或者，在同等仿真吞吐量下，NVIDIA 的成本降低了 9 倍
能耗降低了 17 倍

Ansys、Siemens、Cadence 和其他先进的 CFD 求解器
现已采用 CUDA 加速

在全球范围内，工业 CAE 每年使用
近 1000 亿 CPU 核心小时

加速计算是减少功耗、实现可持续发展和净零排放的最好方式

NVIDIA 正在与全球量子计算
研究社区合作

NVIDIA Quantum 平台由库和系统组成，可供研究人员推进量子编程模型

系统架构和算法

cuQuantum 是用于量子电路仿真的
加速库

IBM Qiskit、Google Cirq、百度量易伏、QMWare、QuEra、Xanadu Pennylane、Agnostiq 和 AWS Bracket

已将 cuQuantum 集成到他们的仿真框架中

Open Quantum CUDA 是我们的混合 GPU-Quantum
编程模型

IonQ、ORCA Computing、Atom、QuEra、Oxford Quantum Circuits、IQM、Pasqal、Quantum Brilliance、Quantinuum、Rigetti

Xanadu 和 Anyon 已经集成 Open Quantum CUDA

要从量子噪声和退相干中恢复数据，需要对大量量子比特进行纠错

今天，我们宣布推出一个量子控制链路，这是与 Quantum Machines 合作开发的

它可将 NVIDIA GPU 连接到量子计算机
以极快的速度进行纠错

虽然商用量子计算机还有十到二十年的时间才能实现，
但我们很高兴能通过 NVIDIA Quantum

为这个充满活力的大型研究社区提供支持

全球企业使用 Apache Spark
处理数据湖和仓库

SQL 查询、图分析和推荐系统

Spark-RAPIDS 是 NVIDIA 加速的 Apache Spark
数据处理引擎

数据处理是全球 5000 亿美元云计算支出的
主要工作负载

现在，Spark-RAPIDS 可加速主要云数据处理平台，包括 GCP Dataproc

Amazon EMR、Databricks 和 Cloudera

推荐系统使用向量数据库来存储、索引、搜索和检索非结构化数据的大型数据集

向量数据库的一个新型重要用例是大型语言模型，在文本生成过程中

可用于检索领域特定事实或专有事实

我们将推出一个新的库，即 RAFT

用于加速索引、数据加载和近邻检索

我们正在将 RAFT 的加速引入到 Meta 的开源 FAISS AI 相似性搜索，超过 1000 家组织使用的

Milvus 开源向量数据库
以及 Docker 镜像下载次数超过 40 亿次的 Redis

对于构建专有大型语言模型的组织而言，向量数据库至关重要

22 年前，运筹学研究科学家 Li 和 Lim 发布了一系列具有挑战性的拣取和配送问题 (PDP)

PDP 出现在制造、运输
零售和物流， 甚至救灾领域

PDP 是旅行商问题的泛化
同时也是 NP-hard 问题

这意味着不存在有效算法来找到精确解

随着问题规模的增加，求解时间会呈阶乘增长

NVIDIA cuOpt 使用进化算法和加速计算
每秒分析 300 亿次动作

打破了世界纪录，并为 Li 和 Lim 的挑战
找到了合适的解决方案

AT&T 定期派遣 3 万名技术人员为 700 个地理区域的 1300 万客户提供服务

如今，如果在 CPU 上运行，AT&T 的调度优化
需要一整夜的时间

AT&T 希望找到一个实时调度解决方案， 能不断优化紧急客户需求

和整体客户满意度， 同时能
针对延误和出现的新事件进行调整

借助 cuOpt，AT&T 可以将查找解决方案的速度加快 100 倍
并实时更新其调度方案

AT&T 已采用全套 NVIDIA AI 库

除了 Spark-RAPIDS 和 cuOPT 之外，他们还将 Riva 用于对话式 AI，
并将 Omniverse 用于数字人

AT&T 正在利用 NVIDIA 加速计算和 AI
来实现高可持续性、成本节约和新的服务

cuOpt 还可以优化物流服务, 每年有  4000 亿个包裹
被投递到 3770 亿个站点

德勤、Capgemini、Softserve、埃森哲和 Quantiphi 正在使用 
NVIDIA cuOpt 来帮助客户优化运营

NVIDIA 的推理平台由三个软件 SDK 组成

NVIDIA TensorRT 用于推理运行时
针对指定 GPU 进行性能优化

NVIDIA Triton 用于数据中心的推理服务，支持多种深度学习框架，支持 GPU 和 CPU

TensorRT 和 Triton 已有 4 万余客户
其中包括 Microsoft Office 和 Teams

Amazon、美国运通和美国邮政署

Uber 使用 Triton 每秒为数十万车辆
预测到达时间

Roblox 拥有超 6000 万的日活用户，它使用 Triton 来部署包括游戏推荐

构建虚拟形象、审核内容和市场广告的模型

我们将发布一些强大的新功能：支持集成模型的模型分析器、并发多模型服务

以及适用于 GPT-3 大语言模型的
多 GPU、多节点推理

NVIDIA Triton Management Service 是我们的新软件，可在整个数据中心

自动扩展和编排 Triton 推理实例

Triton Management Service 将帮助您提高部署模型的吞吐量和成本效率

50%-80% 的云视频管线运行在 CPU 上

这增加了功耗和成本，并增加了延迟

用于计算机视觉的 CV-CUDA 和用于视频处理的 VPF 是新的云规模加速库

CV-CUDA 包括 30 个计算机视觉算子，可用于检测、分割和分类

VPF 是一个 Python 视频编解码加速库

腾讯使用 CV-CUDA 和 VPF
每天处理 30 万个视频

Microsoft 使用 CV-CUDA 和 VPF 来处理视觉搜索

超级酷的 Runway 公司使用 CV-CUDA 和 VPF

为其云生成式 AI 视频编辑服务处理视频

视频已经占据了 80% 的互联网流量

用户生成的视频内容正在显著增长，并消耗大量能源

我们应该加速所有视频处理服务并减少能源消耗

CV-CUDA 和 VPF 处于抢先体验阶段

NVIDIA 加速计算帮助
基因组学实现了里程碑式发展

现在医生可以在同一次就诊中抽取患者的血液
并对其 DNA 进行测序

另一个里程碑是，使用 NVIDIA 助力的仪器设备，
将整个基因组测序的成本降低至仅需 100 美元

基因组学是合成生物学的重要工具
从药物研发、农业到能源生产

其应用范围非常广泛

NVIDIA Parabricks 是一套 AI 加速库，可用于云端或仪器设备内的端到端基因组分析

NVIDIA Parabricks 适用于各种公有云和基因组学平台（例如 Terra、DNAnexus 和 FormBio）

今天，我们宣布推出 Parabricks 4.1，并将会在 PacBio、Oxford Nanopore、Ultima

Singular、BioNano 和 Nanostring 的
第四代 NVIDIA 加速基因组学设备上运行

全球价值 2500 亿美元的医疗设备市场
正在发生变革

医疗设备将由软件定义，并且由 AI 进行赋能

NVIDIA Holoscan 是一个适用于
实时传感器处理系统的软件库

超过 75 家公司正在通过 Holoscan
开发医疗设备

今天我们宣布，全球医疗设备行业领导者 Medtronic 将与 NVIDIA 携手

为软件定义的医疗设备构建其 AI 平台

此次合作将为 Medtronic 系统打造一个通用平台，从手术导航到机器人辅助手术

皆包含在内

今天，Medtronic 宣布基于 NVIDIA Holoscan 构建新一代 GI Genius 系统

将 AI 用于早期检测结肠癌并将于今年年底推出

芯片行业几乎是各行各业的基础

芯片制造要求极高的精确度，生产出的特征比细菌小 1000 倍

大小约为一个金原子或一条人类 DNA 链的尺寸

光刻，即在晶圆上创建图案的过程，是芯片制造过程的起始阶段

包括两个阶段 - 光掩模制作和图案投影

从根本上来说，这是一个物理极限下的成像问题

光掩模如同芯片中的模板光线被阻挡或穿过掩模

到达晶片以形成图案

光线由 ASML EUV
极紫外线光刻系统产生

每个系统的价值超过 2.5 亿美元

ASML EUV 采用一种颠覆性的方式来制造光线

激光脉冲每秒向一滴锡发射 5 万次，使其汽化，产生一种能发射 13.5 纳米 EUV 光的等离子体

几乎是 X 射线

随后，多层镜面引导光线至光掩膜

光掩膜板中的多层反射器利用 13.5 纳米光的干涉图案

实现更精细特征，精细度可达到 3 纳米

很神奇

晶圆的定位精度达到四分之一纳米，并且每秒对准 2 万次以消除任何振动的影响

光刻之前的步骤同样令人不可思议

计算光刻应用逆物理算法
来预测掩膜板上的图案

以便在晶圆上生成最终图案

事实上，掩膜上的图案与最终特征完全不相似

计算光刻模拟了光通过光学元件
并与光刻胶相互作用时的行为

这些行为是根据麦克斯韦方程描述的

计算光刻是芯片设计和制造领域中
最大的计算工作负载

每年消耗数百亿 CPU 小时

大型数据中心 24x7 全天候运行
以便创建用于光刻系统的掩膜板

这些数据中心是芯片制造商每年投资近 2000 亿美元的资本支出的一部分

随着算法越来越复杂
计算光刻技术也在快速发展

使整个行业能够达到 2 纳米及以上

NVIDIA 今天宣布推出 cuLitho —— 一个计算光刻库

cuLitho 是一项历时近四年的庞大任务，我们与台积电、ASML 和 Synopsys 密切合作

将计算光刻加速了 40 倍以上

NVIDIA H100 需要 89 块掩膜板

在 CPU 上运行时，处理单个掩膜板
当前需要两周时间

如果在 GPU 上运行 cuLitho
只需 8 小时即可处理完一个掩膜板

台积电可以通过在 500 个 DGX H100 系统上使用 cuLitho 加速，将功率从 35MW 降至 5MW

从而替代用于计算光刻的 4 万台 CPU 服务器

借助 cuLitho，台积电可以缩短原型周期时间
提高产量

减少制造过程中的碳足迹
并为 2 纳米及以上的生产做好准备

台积电将于 6 月开始对 cuLitho 进行生产资格认证

所有行业都需要加速各种工作负载，以便我们能减少功耗，达到事半功倍的效果

在过去十年中，云计算每年增长 20%，成为了价值 1 万亿美元的巨大行业

大约 3000 万台 CPU 服务器完成大部分处理工作

而挑战即将到来

随着摩尔定律的终结，CPU 性能的提高也会伴随着功耗的增加

另外，减少碳排放这一任务从根本上与增加数据中心的需求相悖

云计算的发展受功耗限制

首要的，数据中心必须加速各种工作负载

加速将会减少功耗

节省的能源可以促进新的增长

未经过加速的工作负载都将会在 CPU 上进行处理

加速云数据中心的 CPU
侧重点与过去有着根本性的不同

在 AI 和云服务中，加速计算卸载可并行的工作负载，而 CPU 可处理其他工作负载

比如 Web RPC 和数据库查询

我们为 AI 和云优先的行业设计了 Grace CPU
其中 AI 工作负载由 GPU 加速

单线程执行和内存处理
则是 Grace 的擅长之处

但这不仅仅是 CPU 芯片的问题, 数据中心管理员负责
对整个数据中心的吞吐量和 TCO 进行优化

为了在云数据中心规模下实现高能效
我们设计了 Grace

Grace 包含 72 个 Arm 核心，由超高速片内可扩展的、缓存一致的网络连接，
可提供 3.2 TB/s 的截面带宽

Grace Superchip 通过 900 GB/s 的低功耗芯片到芯片缓存一致接口，
连接两个 CPU 芯片之间的 144 个核

内存系统由 LPDDR 低功耗内存构成（与手机上使用的相似），
我们专门对此进行了增强，以便在数据中心中使用

它提供 1 TB/s 的带宽，是目前系统的 2.5 倍
而功耗只是其 1/8

整个 144 核 Grace Superchip 模组的大小
仅为 5x8 英寸，而内存高达 1TB

该模组的功耗超低，风冷即可

这是带有被动冷却功能的计算模组

两台 Grace Superchip 计算机可以
安装进一台 1U 风冷服务器即可正常运行

Grace 的性能和能效非常适合云计算应用和科学计算应用

我们使用热门的 Google 基准测试（测试云微服务的通信速度）

和 Hi-Bench 套件（测试 Apache Spark 内存密集型数据处理）
测试了 Grace

此类工作负载是云数据中心的基础

在微服务方面，Grace 的速度比
最新一代 x86 CPU 的平均速度快 1.3 倍

而在数据处理中则快 1.2 倍

而达到如此高性能，整机功耗仅为原来服务器的 60%

云服务提供商可以为功率受限的数据中心配备超过 1.7 倍的 Grace 服务器，
每台服务器的吞吐量提高 25%

在功耗相同的情况下，Grace 使云服务提供商获得了两倍的增长机会

Grace 正在进行样品调测

华硕、Atos、GB、HPE、QCT
Supermicro、Wistron 和 ZT 目前正在构建系统

在现代软件定义的数据中心中，操作系统在执行虚拟化、网络、存储和安全任务时

会消耗近一半的数据中心 CPU 核心
和相关功耗

数据中心必须加速每个工作负载，从而降低功耗并释放 CPU 给可创造收入的工作负载

NVIDIA BlueField 卸载并加速数据中心操作系统和基础设施软件

Check Point、思科、DDN、Dell EMC、
Juniper、Palo Alto Networks

Red Hat 和 VMWare 等超过二十个生态系统合作伙伴

使用 BlueField 的数据中心加速技术来更高效地运行其软件平台

BlueField-3 已投入生产，并被领先的云服务提供商所采用以加速其云计算平台，
比如百度、CoreWeave

京东、Microsoft Azure、Oracle OCI 和腾讯游戏

NVIDIA 加速计算始于 DGX（AI 超级计算机）

这是大语言模型实现突破背后的引擎

我亲手将全球首款 DGX 交给了 OpenAI

自此之后，《财富》100 强企业中有一半
安装了 DGX AI 超级计算机

DGX 已成为 AI 领域的必备工具

DGX 配有 8 个 H100 GPU 模组

H100 配有 Transformer 引擎，旨在处理
类似令人惊叹的 ChatGPT 模型

ChatGPT 是生成式预训练 Transformer 模型的代表

这 8 个 H100 模组通过 NVLINK Switch 彼此相连，以实现全面无阻塞通信

8 个 H100 协同工作，就像一个巨型 GPU

计算网络是 AI 超级计算机的
重要系统之一

400 Gbps 超低延迟的 NVIDIA Quantum InfiniBand

具有网络内计算功能

可将成千上万个 DGX 节点连接成

一台 AI 超级计算机

NVIDIA DGX H100 是全球客户
构建 AI 基础设施的蓝图

现在已全面投入生产

令我倍感激动的是，微软宣布 Azure 将向其 H100 AI 超级计算机开放私人预览版

Atos、AWS、Cirrascale、CoreWeave、戴尔、Gigabyte、谷歌、HPE、
Lambda Labs、联想、Oracle、Quanta

和 SuperMicro 也将很快开放系统和云服务

DGX AI 超级计算机的市场获得了显著增长

从最初被用作 AI 研究工具，DGX AI 超级计算机正在不断扩展其应用范围

能够全天候运行以优化数据和处理 AI

DGX 超级计算机是现代 AI 工厂

我们正处于 AI 的“iPhone 时刻”

初创公司竞相构建具有颠覆性的产品和商业模式，而老牌公司则在寻求应对之法

生成式 AI 引发了全球企业制定 AI 战略的紧迫感

客户需要更简单快捷地访问 NVIDIA AI

我们宣布推出 NVIDIA DGX Cloud，通过与 Microsoft Azure、Google GCP 和 Oracle OCI 合作

通过一个浏览器就可以将 NVIDIA DGX AI 超级计算机即时地接入每家公司

DGX Cloud 经过优化，可运行 NVIDIA AI Enterprise，这是一款全球领先的加速库套件

用于 AI 端到端开发和部署

DGX Cloud 为客户提供出色的 NVIDIA AI 以及全球主要的云服务提供商

这一合作将 NVIDIA 的生态系统引入到了云服务提供商
NVIDIA 触及的范围得以扩展

这种双赢的合作伙伴关系为迫切需要使用生成式 AI 的客户
提供了在全球云端即时访问 NVIDIA AI 的机会

我们很高兴我们的业务模式以这种速度、规模和覆盖范围在云上扩展

Oracle Cloud Infrastructure (OCI)
将成为首个 NVIDIA DGX Cloud

OCI 具有出色的性能它拥有两层
计算网络和管理网络

具有业界最佳 RDMA 功能的 NVIDIA CX-7
提供了计算网络

而 BlueField-3 将成为管理网络的
基础设施处理器

这种组合是一款先进的 DGX AI 超级计算机，可提供多租户云服务

我们拥有 50 家 EA 企业客户，涵盖消费互联网和软件、医疗健康

媒体和娱乐以及金融服务

ChatGPT、Stable Diffusion、DALL-E 和 Midjourney 唤醒了世界对生成式 AI 的 认知

这些应用的易用性和令人印象深刻的功能，短短几个月内就吸引了超过一亿的用户

ChatGPT 是迄今历史上用户数量增长最快的应用

无需训练只需给这些模型下指令即可

您可以使用精确提示，也可以使用模糊提示如果提示不够清晰

ChatGPT 会根据对话了解您的意图

生成的文本令人赞叹

ChatGPT可以撰写备忘录和诗歌，改写研究论文，解决数学问题

突出合同的关键点, 甚至编写软件程序

ChatGPT 是一台计算机，它不仅可以
运行软件，还能编写软件

众多突破性成果造就了生成式 AI

Transformer 能以大规模并行的方式，从数据的关系和依赖性中学习上下文和含义

这使得大型语言模型能够利用海量数据进行学习

他们可以在没有明确训练的情况下执行下游任务

受物理学启发的扩散模型通过无监督学习
来生成图像

在短短十几年的时间里，我们经历了
从试图识别猫到生成穿着太空服

在月球上行走的

的逼真猫图像的过程

生成式 AI 是一种新型计算机，一种我们可以用人类语言进行编程的计算机

这种能力影响深远每个人都可以命令计算机来解决问题

而之前这是只有计算机程序员才能接触的领域

现在每个人都可以是程序员

生成式 AI 是一种新型计算平台，
与 PC、互联网、移动设备和云类似

与之前的计算时代类似
先行者正在打造新的应用

并成立新公司，以利用
生成式 AI 的自动化和协同创作能力

借助 Debuild，用户只需说明自己想要的内容
即可设计和部署 Web 应用

Grammarly 是一款可以结合上下文的写作助手

Tabnine 可帮助开发者编写代码

Omnekey 可生成定制广告和文案

Kore.ai 是虚拟客服

Jasper 可生成营销材料Jasper 已经
编写了近 50 亿字

将初稿生成时间缩短了 80%

Insilico 利用 AI 加速药物设计

Absci 正在使用 AI 预测治疗抗体

生成式 AI 将重塑几乎所有行业

许多公司都可以使用某个即将上市的
超赞的生成式 AI API

一些专业领域的公司需要使用其专有数据来构建定制模型

他们需要制定使用规范
并优化模型，以契合

公司的安全、隐私和安保要求

这个行业需要一个类似台积电的
代工厂，来构建自定义的大型语言模型

今天，我们宣布推出 NVIDIA AI Foundations

这是一项云服务，面向需要构建、优化和运营

定制 LLM（大型语言模型）和生成式 AI

使用其专有数据进行训练

用于处理特定领域的任务

NVIDIA AI Foundations 包括语言

视觉和生物学模型制作服务

NVIDIA Nemo 用于构建定制的语言文本转文本

生成式模型

客户可以引入自己的模型，或从 Nemo 涵盖了 GPT-8、GPT-43 到 GPT-530 等数十亿参数的

预训练模型入手

从创建专有模型到运营，NVIDIA AI 专家将全程与您合作

我们一起来看一下

生成式模型，比如 NVIDIA 的 43B 基础模型，
通过基于数十亿个句子和数万亿个单词进行训练来学习

随着模型的收敛，它开始理解单词与其基本概念之间的关系

这些关系通过模型嵌入空间中的权重进行捕获

Transformer 模型使用一种名为自注意力的技术：一种旨在学习一系列单词中的依赖性

和关系的机制

其结果是得到一种模型，该模型可为类似 ChatGPT 的体验奠定基础

这些生成式模型需要大量数据

数据处理和分布式训练方面深厚的 AI 专业知识

以及大规模计算，以跟上创新的步伐
进行训练、部署和维护

企业可以通过在 NVIDIA DGX Cloud 上的 NVIDIA NeMo 服务

快速采用生成式 AI

最快捷的方法是从 NVIDIA 的某项先进

预训练基础模型开始入手

借助 NeMo 服务，人们可以轻松自定义一个模型

并进行参数调优，以教授其专业技能

比如汇总财务文档

创建特定品牌的内容

以及以个性化的写作风格撰写电子邮件

将模型连接到专有知识库

可确保响应是准确的、最新的

并为其业务所引用

接下来，他们可以通过添加逻辑

以及监控输入、输出、毒性和偏差阈值来提供防护栏

以便模型在指定的领域内运行

并防止出现意外响应

模型投入使用后，可以根据

用户交互通过强化学习不断改进

在迁移到云 API 进行更大规模的
评估和应用集成之前

可以使用 NeMo 进行快速原型设计

立即注册以获取 NVIDIA NeMo 服务

将您的企业知识编入个性化的

由您控制的 AI 模型

Picasso 是一项视觉语言模型制作服务，面向希望使用许可内容或专有内容

来训练自定义模型的客户

我们一起来看一下

生成式 AI 正在改变视觉内容的创建方式

但要充分发挥其潜力，企业需要大量版权许可的数据、AI 专家和 AI 超级计算机

NVIDIA Picasso 是一项云服务，用于构建和部署

生成式 AI 赋能的图像、视频和 3D 应用

借助此服务，企业、ISV 和服务提供商

可以部署自己的模型

我们正在与主要合作伙伴合作

力求为各行各业提供生成式 AI 功能

另外，人们还可以从 NVIDIA Edify 模型入手

使用自己的数据训练这些模型，以创建产品或服务

这些模型可生成图像、视频和 3D 素材

要访问生成式 AI 模型

应用需向 Picasso 发送带有文本提示

和元数据的 API 调用

Picasso 使用在 NVIDIA DGX Cloud 上运行的适当模型

将生成的素材发送回应用

这些素材可以是逼真的图像、高分辨率视频
或详细的 3D 几何图形

可将生成的素材导入编辑工具或 NVIDIA Omniverse，以构建逼真的虚拟世界

元宇宙应用和数字孪生仿真

借助在 NVIDIA DGX Cloud 上运行的 NVIDIA Picasso 服务

您可以简化构建自定义生成式 AI 应用所需的

训练、优化和推理

了解 NVIDIA Picasso 如何为您的应用带来变革性的生成式 AI 功能

我们很高兴 Getty Images 将使用 Picasso 服务构建 Edify 图片和 Edify 视频生成式模型

这些模型以其丰富的内容库为基础进行训练，
其中包含大量以负责任授权的方式获得许可的专业图像和视频素材

企业将能够使用简单的文本或图像提示
创建自定义的图像和视频

Shutterstock 正在开发一款以其专业的图像、3D 和视频素材库

进行训练的 Edify-3D 生成式模型

Shutterstock 将帮助简化用于创意制作、数字孪生和虚拟协作的 3D 素材的创建过程

使企业能够更快
更轻松地实现这些工作流

我很高兴地宣布，我们与 Adobe 之间的长期合作
将迎来重要扩展

我们将共同构建一系列新一代 AI 功能
打造创意领域的未来

将生成式 AI 融入营销人员和创意专业人士的
日常工作流

新的生成式 AI 模型将

针对图像、视频、3D 和动画制作进行优化

为了保护艺术家的权利，Adobe 正在开发以商业可行性和正确内容归属为重点的方案

该方案由 Adobe 的 “内容真实性倡议” 提供支持

我们的第三个语言领域是生物学

药物研发是一个价值近 2 万亿美元的行业

研发投入高达 2500 亿美元

NVIDIA Clara 是一款医疗健康应用框架，用于影像

仪器、基因组学分析和药物研发

目前，该行业正在转向利用生成式 AI
来发现疾病靶因

设计新型分子或蛋白质类药物，以及预测药物对机体的作用

数百家新型 AI 药物研发初创公司相继涌现，
Insilico Medicine、Exscientia、Absci 和 Evozyme 就是位列其中

有些公司已经发现了新型靶标或候选药物，并开始了人体临床试验

BioNeMo 可帮助研究人员

使用专有数据创建、微调和提供自定义模型

我们一起来看一下

药物研发包括 3 个关键阶段

发现引发疾病的机理

设计新分子——无论是小分子、蛋白质还是抗体

以及最后就这些分子之间相互作用的方式进行筛选

如今，生成式 AI 正在改变药物研发过程的每一步

NVIDIA BioNeMo 服务提供先进的

用于药物研发的生成式 AI 模型

它可作为云服务提供，让用户即时轻松地访问加速的药物研发工作流

BioNeMo 包括 AlphaFold、ESMFold 和 OpenFold 等

用于三维蛋白质结构预测的模型

ProtGPT 用于蛋白质生成

ESM1 和 ESM2 用于蛋白质特性预测

MegaMolBART 和 MoFlow 用于分子生成

DiffDock 则用于分子对接

药物研发团队可以通过 BioNeMo 的 Web 界面
或云 API

使用这些模型

以下是一个使用 NVIDIA BioNeMo

进行药物研发虚拟筛选的示例

现在，生成式模型可以读取蛋白质氨基酸序列

并在几秒钟内准确预测目标蛋白质的结构

它们还可生成具有理想 ADME 特性的分子，从而优化药物在体内的作用方式

生成式模型甚至可以预测蛋白质和分子的
三维相互作用

加速最佳候选药物的研发

借助 NVIDIA DGX Cloud，BioNeMo 还可提供按需超级计算基础设施，
以进一步优化和训练模型

进而为团队节省宝贵的时间和资金，使其专注于研发挽救生命的药物

新的 AI 药物研发流程已经面世

敬请注册以获取 NVIDIA BioNeMo 服务

我们将继续与业界合作
将模型纳入 BioNemo

其中包含药物研发和虚拟筛选的
端到端工作流

Amgen、AstraZeneca、Insilico Medicine、Evozyne、Innophore 和 Alchemab Therapeutics 是 BioNeMo 的早期体验用户

NVIDIA AI Foundations 是一个云服务和代工厂，用于构建自定义语言模型和生成式 AI

自十年前 AlexNet 面市以来，深度学习就开辟了巨大的新市场，
包括自动驾驶、机器人、智能音箱

并重塑了我们购物、了解新闻和享受音乐的方式

这只是冰山一角

随着生成式 AI 掀起新一波机遇浪潮，AI 正处于转折点，
使得推理工作负载呈阶梯函数式增长

AI 现在可以生成多种数据，从语音、文本、图像、视频和 3D 图形，
到蛋白质和化学物质，不一而足

设计一个云数据中心
来处理生成式 AI 是一项巨大挑战

一方面，理想情况下最好使用一种加速器，
因为这可以使得数据中心具有弹性

能够应对不可预测的流量峰值和低谷

但另一方面，没有一个加速器能以最优的方式处理在算法、模型、
数据类型和数据大小方面的多样性

NVIDIA 的 One Architecture 平台
兼具加速功能和弹性

今天，我们宣布推出我们全新的推理平台：
四种配置 —— 一个体系架构 —— 一个软件栈

每种配置都针对某一类工作负载进行了优化

针对 AI 视频工作负载，我们推出了 L4，它针对以下方面进行了优化：
视频解码和转码、视频内容审核

以及视频通话功能，例如背景替换、重新打光、眼神交流

转录和实时翻译

如今，大多数云端视频都在 CPU 上处理

一台 8-GPU L4 服务器将取代一百多台用于处理 AI 视频的双插槽 CPU 服务器

Snap 是 NVIDIA AI 在计算机视觉
和推荐系统领域领先的用户

Snap 将会把 L4 用于 AV1 视频处理
生成式 AI 和增强现实

Snapchat 用户每天上传数亿个视频

Google 今天宣布在其 GCP上提供 NVIDIA L4

NVIDIA 和 Google Cloud 正在努力
加速在 L4 上部署主要工作负载

我来重点介绍一下其中五个工作负载

首先，我们正在加速针对 Wombo 和 Descript 等云服务的生成式 AI 模型的推理

其次，我们会将 Triton 推理服务器与 Google Kubernetes Engine 和 VertexAI 集成

第三，我们将使用 NVIDIA Spark-RAPIDS
加速 Google Dataproc

第四，我们将加速 AlphaFold
UL2 和 T5 大型语言模型

第五，我们将加速 Google Cloud 的沉浸式流，以渲染 3D 和 AR 体验

通过此次合作，Google GCP 成为了首款 NVIDIA AI 云

我们期待尽快向您详细介绍
我们的合作

针对 Omniverse、 图形渲染以及文本转图像和文本转视频等生成式 AI，我们宣布推出 L40

L40 的性能是 NVIDIA 最受欢迎的
云推理 GPU T4 的 10 倍

Runway 是生成式 AI 领域的先驱

他们的研究团队是 Stable Diffusion 及其前身
Latent Diffusion 的主要创造者

Runway 正在发明用于创作和编辑内容的
生成式 AI 模型

借助 30 多种来自云端的 AI Magic Tools，他们的服务将彻底改变创作过程

我们一起来看一下

Runway 正在打造令人惊叹的可供所有人使用的 AI 赋能视频编辑和图像创建工具

在本地或云端运行的最新一代 NVIDIA GPU 的助力下，Runway 让用户

只需简单几笔即可从视频中移除一个对象

或仅使用一个输入图像就可以对视频应用不同的样式

或更改视频的背景或前景

过去使用传统工具需要数小时才能完成的工作，现在只需短短几分钟就可以获得

专业广播级质量的结果

在实现这一点的过程中，Runway 采用了 CV-CUDA，它是一个开源项目，使开发者能够构建

GPU 加速的高效计算机视觉工作负载预处理和后处理流程，并将其扩展到云

借助 NVIDIA 技术，Runway 得以行不可能之事，让内容创作者获得最佳体验

以前受限的专业工作现在可以由您来完成

事实上，Runway 在奥斯卡提名的好莱坞电影中得到了应用，而我们正在致力将这项技术

提供给全世界的创作者

ChatGPT 等大型语言模型
是一个新出现的重要的推理工作负载

GPT 模型是内存和计算密集型模型

此外，推理是一种高容量、外扩型工作负载，需要标准的商用服务器

针对 ChatGPT 等大型语言模型的推理，
我们宣布推出一款新的 Hopper GPU——配备双 GPU NVLINK 的 PCIE H100

这一款 H100 配备 94GB HBM3 显存

H100 可以处理拥有 1750 亿参数的 GPT-3

同时还可支持商用 PCIE 服务器轻松扩展

目前在云上唯一可以实际处理 ChatGPT 的 GPU 是 HGX A100

与适用于 GPT-3 处理的 HGX A100 相比，
一台搭载四对 H100 及双 GPU NVLINK 的标准服务器的速度

要快 10 倍

H100 可将大型语言模型的处理成本
降低一个数量级

Grace Hopper 是我们的新的超级芯片，通过 900 GB/秒的高速一致性芯片到芯片接口

连接 Grace CPU 和 Hopper GPU

Grace Hopper 非常适合处理大型数据集，
例如适用于推荐系统和大型语言模型的 AI 数据库

如今，利用大容量内存，CPU 会存储和查询巨型嵌入表，
然后将结果传输到 GPU 进行推理

借助 Grace-Hopper，Grace 可以查询嵌入表，并将结果直接传输到 Hopper

速度比 PCIE 快 7 倍

客户希望构建规模大几个数量级的 AI 数据库

Grace-Hopper 是理想的引擎

以上就是 NVIDIA 的推理平台
一个为适用于多种 AI 负载

最大化的数据中心加速和弹性而设计的架构

全球最大的工业产业都生产实体产品
但他们也希望实现数字化生产方式

Omniverse 是一个工业数字化平台
旨在搭建数字化和物理实体之间的桥梁

该平台让各个行业先以数字方式设计、构建、运营和优化实体产品和工厂

然后再投入实际生产

数字化提高了效率和速度，并节省了资金

Omniverse 其中一个用途是以虚拟方式构建工厂，
在真正的实体工厂建成之前，以数字方式整合

工厂的所有机械设备

这样可以减少在最后时刻出现意外、变更订单
和工厂延迟开工等情况

虚拟工厂整合可以为全球工厂节省数十亿美元

半导体行业正在投资 5000 亿美元
来建造 84 个新晶圆厂

到 2030 年，汽车制造商将建造 300 家工厂
生产 2 亿辆电动汽车

电池制造商正在建造 100 多家特大型工厂

数字化也在改变物流行业，
在全球数十亿平方英尺的仓库之间辗转运输货物

我们来看看 Amazon 如何使用 Omniverse 自动化、优化和规划其自动仓库

Amazon Robotics 制造并部署了非常庞大的移动工业机器人机群

此机器人机群的最新成员是 Proteus，这是 Amazon 首个完全自主的仓库机器人

Proteus 可利用先进的安全、感知和导航技术在我们的设施中移动

我们来看看基于 Omniverse 构建的 NVIDIA Isaac Sim 如何创建物理精准的逼真仿真

从而帮助加快 Proteus 部署

Proteus 具有多个传感器，其中包括摄像头
激光雷达和超声传感器

用于为其自主软件系统提供支持

Proteus 团队需要提高神经网络的性能，该神经网络能够读取基准标记并帮助机器人

确定其在地图上的位置

训练由机器人传感器输入驱动的 ML 模型需要大量正确的数据

通过 Isaac Sim 中的 Omniverse Replicator，
Amazon Robotics 成功生成了大型逼真合成数据集

将标记检测成功率从 88.6% 提高到了 98%

此外，使用 Omniverse Replicator 生成的合成数据还加快了开发速度，
将所需时间从几个月缩短到了几天

因为与仅使用真实数据相比，我们能够以更快的速度
迭代测试和训练模型

为了给不断壮大的 Proteus 机器机群提供新的自主功能，Amazon Robotics 正在努力

缩小仿真与现实之间的差距，构建大规模的多传感器、多机器人仿真

借助 Omniverse，Amazon Robotics 将通过全保真仓库数字孪生优化运营

无论是生成合成数据还是开发更高水平的自主功能，基于 Omniverse 的 Isaac Sim

都可帮助 Amazon Robotics 团队在设施中部署 Proteus 之时节省时间和资金

Omniverse 具备独特的数字化技术

Omniverse 是 USD 的首要开发平台，它是一种通用语言，帮助团队协作

创建虚拟世界和数字孪生

Omniverse 基于物理性质，反映物理定律

它可以连接到机器人系统，并使用环路中的硬件进行操作

它采用生成式 AI 来加速创建虚拟世界

Omniverse 可以管理大型数据集

我们在每个领域都对 Omniverse 进行了重大更新

我们一起来看一下

已有近 30 万名创作者和设计师
下载了 Omniverse

Omniverse 不是一种工具，而是一个 USD 网络和共享数据库

也是一种与各行各业使用的设计工具相连接的基础结构

它可以连接、合成和模拟
使用行业领先工具创建的 3D 资产

我们很高兴看到 Omniverse 生态连接的发展壮大

每个连接都会将一个平台的生态系统与所有其他平台的生态系统连接到一起

Omniverse 网络中的网络正在呈指数级增长

现已连接 Bentley Systems LumenRT

还连接了 Siemens Teamcenter、NX 和 Process Simulate、
Rockwell Automation Emulate 3D、Cesium、Unity 等许多应用

我们来看看价值 3 万亿美元的汽车行业的数字化

了解汽车公司如何
在其工作流中评估 Omniverse

沃尔沃汽车公司和通用汽车使用 Omniverse USD Composer
连接和统一其资产工作流

通用汽车使用 Alias、Siemens NX、Unreal、Maya 和 3ds Max 将设计师、
雕塑家和艺术家连接到一起

并将汽车零部件在虚拟环境中
组装成数字孪生汽车

在工程和仿真中，他们在 Omniverse 中将 Powerflow 空气动力学可视化

对于新一代梅赛德斯-奔驰和捷豹路虎汽车，工程师在 Omniverse 中使用 Drive Sim 生成

合成数据来训练 AI 模型，通过虚拟 NCAP 驾驶测试验证主动安全系统

并模拟真实驾驶场景

Omniverse 的生成式 AI 将以前驾驶的路线
重构为 3D

以便重现或修改过去的体验

借助 Idealworks，宝马在 Omniverse 中
使用 Isaac Sim 生成合成数据

和场景，用来训练工厂机器人

Lotus 正在使用 Omniverse，以虚拟方式组装焊接站

丰田公司正在使用 Omniverse 构建自己工厂的数字孪生

梅赛德斯-奔驰使用 Omniverse 为新车型构建、优化和规划组装流水线

Rimac 和 Lucid Motors 使用 Omniverse 根据真实的设计数据构建数字商店，
这些数据准确地反映他们的汽车的状况

宝马正在使用 Omniverse 规划全球近三十家工厂的运营

在实际工厂开业两年之前，他们会在 Omniverse 中完整建造一间新的电动汽车工厂

让我们来观摩一下

全球各行各业都在加速数字化发展，未来三年，该领域的投资金额将超过 3.4 万亿美元

宝马努力在汽车数字化领域处于领先地位

借助 NVIDIA Omniverse 和 AI，我们能够更快地建立新工厂，并更高效地进行生产

这会为我们节省大量成本

这一切都要从规划开始， 这是一个复杂的过程
在此过程中，我们需要将许多工具

数据集和遍布全球的专家串联起来

传统上，我们受到限制，因为数据在各种系统和工具中单独管理

如今，这种局面已经实现了全方位的改变

我们正在开发自定义 Omniverse 应用，以将现有的工具、专门知识和团队联系在一起

使其处在统一视图中

Omniverse 是云原生同时不限平台，可让团队随时随地在我们的虚拟工厂中开展协作

我即将参加一场虚拟规划会议，会议关乎将于 2025 年开幕的匈牙利德布勒森工厂，这是我们新的 EV 工厂

我们开始吧

规划师 1：喔，Milan 也加入了

Milan：大家好！

规划师 1：您好，Milan，很高兴见到您，我们正为车身车间执行优化循环

您想看看吗？

Milan：谢谢，我非常感兴趣我想邀请一位朋友

规划师 1：当然没问题

黄仁勋：Milan，您好！很高兴见到您

Milan：黄先生，欢迎参加我们的虚拟规划会议

黄仁勋：很高兴来到这里我们在看什么内容？

Milan：这是我们的全球规划团队，他们正在研究德布勒森工厂数字孪生中的机器人单元

Matthias，给我们介绍一下发生了什么情况吧……

Matthias：我们刚刚了解到
生产理念需要进行一些更改

现在，我们正在重新配置布局，以便在单元中添加一个新的机器人

规划师 2：好的，但如果我们在物流方面添加一个新机器人，则需要移动存储容器

规划师 3：好的，让我们把这个新机器人放进去

Matthias：太完美了但是，我们来仔细检查一下
我们能运行这个单元吗？

非常好

黄仁勋：Milan，真是不可思议！

虚拟工厂集成对于各行各业来说都是必不可少的

看到我们的团队合作完成的成果，我感到非常自豪恭喜！

Milan：我们正在全球范围内开展工作，努力实现本地优化

在规划之后，成功运营才是王道，而我们已经开始！

为了庆祝我们虚拟工厂的启动，我想邀请您和我一起为第一家数字工厂揭幕

黄仁勋：我很荣幸我们开始吧！

汽车公司雇佣了近 1400 万名员工

数字化将提高整个行业的
效率、生产力和速度

Omniverse 是实现工业数字化的
数字到物理操作系统

今天，我们要宣布推出三款
专为运行 Omniverse 而设计的系统

首先，我们将推出由 NVIDIA Ada RTX GPU 和
英特尔的最新款 CPU 提供动力支持的新一代工作站

这款新工作站非常适合用于光线追踪、物理仿真、神经图形和生成式 AI

从 3 月开始，Boxx、戴尔、惠普
和联想将提供这款工作站

其次，针对 Omniverse 优化的新型 NVIDIA OVX 服务器

OVX 由服务器 GPU Ada RTX L40
和我们的新款 BlueField-3 组成

OVX 服务器将由戴尔、HPE、Quanta、技嘉、联想和 Supermicro 提供

每一层 Omniverse 的堆栈包括芯片、系统、网络和软件在内都是新发明

构建和操作 Omniverse 计算机
需要一个成熟的 IT 团队

我们将快速轻松地
扩展和运用 Omniverse

我们一起来看一下

全球大型行业竞相
实现其物理流程的数字化

目前，这是一项复杂的任务

NVIDIA Omniverse Cloud 是一种平台即服务，
支持即时安全地访问托管的 Omniverse Cloud API

工作流，以及在 NVIDIA OVX 上运行的可定制应用

企业团队通过 Web 浏览器 Omniverse Launcher 或通过自定义集成

访问托管服务套件

进入 Omniverse Cloud 后，企业团队可以立即访问、扩展和发布基础应用

和工作流，以组装和构建虚拟世界

生成用于训练感知 AI 的数据

测试和验证自动驾驶汽车

或模拟自主机器人

从而访问共享数据，并将其发布到 Omniverse Nucleus

设计师和工程师在 RTX 工作站上使用他们惯用的
第三方设计工具

并行发布对 Nucleus 的编辑

然后，当准备好在 Omniverse 中迭代或查看
其集成模型时

只需打开 Web 浏览器并登录即可

随着项目和团队规模的扩大，Omniverse Cloud 可帮助

根据需要调配计算资源和许可证，从而优化成本

新的服务和升级会自动
获得实时更新

借助 Omniverse Cloud，企业可以在主要的工业工作流中

快速实现统一的数字化和协作、提高效率
降低成本和减少浪费

加速实现创新

Omniverse 中见！

今天，我们宣布推出 NVIDIA Omniverse Cloud
这是一种完全托管的云服务

我们正在与 Microsoft 合作，将 Omniverse Cloud 引入全球各个行业

我们将在 Azure 中托管它，并通过 Microsoft 丰富的存储、安全性、应用和服务组合受益

我们正在将 Omniverse Cloud 连接到 Microsoft 365 生产力套件，
其中包括 Teams、OneDrive、SharePoint

和 Azure IoT Digital Twins 服务

Microsoft 和 NVIDIA 正在将 Omniverse 带给数以亿计的 Microsoft 365 和 Azure 用户

加速计算和 AI 技术已经走进现实

开发者使用 NVIDIA 来提速和扩大规模，从而解决之前无法解决的问题

净零排放是一项艰巨的挑战,
每家公司都必须加速所有工作负载以减少功耗

加速计算是一项全栈的
数据中心级计算挑战

Grace、Grace-Hopper 和 BlueField-3 是适用于超级节能加速数据中心的新芯片

加速库可解决新挑战，开辟新市场

我们更新了 100 个加速库，包括用于量子计算的 cuQuantum、用于组合优化的 cuOpt

以及用于计算光刻的 cuLitho

我们很高兴能与台积电、ASML 和 Synopsys 合作
达到 2 纳米及更高精度制程

NVIDIA DGX AI 超级计算机是生成式大型语言模型取得突破的引擎

DGX H100 AI 超级计算机正在生产中，并即将通过

全球不断扩大的 OEM 和云服务合作伙伴网络面世

DGX 超级计算机没有止步于
研究，正在成为现代化的 AI 工厂

每家公司都将会制造智能

我们通过与 Microsoft Azure、Google GCP 和 Oracle OCI 合作，
借此扩展 NVIDIA DGX Cloud 的业务模式

通过一个浏览器就可以将 NVIDIA DGX AI 超级计算机即时地接入每家公司

DGX Cloud 为客户提供
在 NVIDIA 和全球范围内都出类拔萃的 CSP

我们正处于 AI 的“iPhone 时刻”

生成式 AI 推理工作负载已进入超速运行状态

我们推出了新的推理平台：
四种配置，一个体系架构

适用于 AI 视频的 L4

适用于 Omniverse 和图形渲染的 L40

适用于扩展 LLM 推理的 H100 PCIE

适用于推荐系统和向量数据库的 Grace-Hopper

NVIDIA 推理平台可最大化提高
数据中心加速和弹性

NVIDIA 和 Google Cloud 正在合作部署广泛的推理工作负载

通过此次合作，Google GCP 成为了首款 NVIDIA AI 云

NVIDIA AI Foundations 是一个云服务和代工厂，
用于构建自定义语言模型和生成式 AI

NVIDIA AI Foundations 包括语言
视觉和生物学模型制作服务

Getty Images 和 Shutterstock 正在
构建自定义视觉语言模型

我们正与 Adobe 合作，为创造性的未来构建一系列新一代 AI 功能

Omniverse 是实现工业数字化的
数字到物理操作系统

Omniverse 可以统一端到端工作流，并将价值 3 万亿美元，
拥有 1400 万员工的汽车行业数字化

Omniverse 正在跃上云端

我们在 Azure 上进行托管，与 Microsoft 合作，将 Omniverse Cloud 引入全球各个行业

感谢我们的系统、云和软件合作伙伴
研究人员、科学家

尤其是我们优秀的员工

他们为构建 NVIDIA 加速计算生态系统付出了很大努力

我们正在携手帮助世界实现不可能的事情

祝各位有一个愉快的 GTC！


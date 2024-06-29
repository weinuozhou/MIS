# 管理信息系统

## 信息的概念

* 狭义：**可通信**并有关联性和目的性的结构化、组织化的客观事实
* 广义：凡是在一种情况下能**减少不确定性**的任何事物都可称为信息

## 信息和数据的区别

* 数据（Data）又称资料，是记录客观事物的、可鉴别的符号。这些符号不仅包括数字，还包括字符、文字、图形、图像、语音等
* **数据经过处理仍然是数据**。处理数据是为了便于更好地解释。只有经过解释，数据才有意义，才成为信息。可以说信息是经过加工后，对客观世界产生影响的数据

## 信息的作用

* 信息量的大小取决于信息内容消除人们知识的**不确定性程度**
* 如果事先就确切地知道消息的内容，那么消息中所包含的信息量就等于零

> 信息系统的发展

<div style="text-align: center;"><img alt='202406291328958' src='https://cdn.jsdelivr.net/gh/weno861/image@main/img/202406291328958.png' > </div>

## 管理信息系统的特点

* 它是一个为管理决策服务的信息系统
* 它是一个对组织乃至整个供应链进行**全面管理**的综合系统
* 它是一个**人机结合**的系统
* 它是一个需要与先进的管理方法和手段相结合的信息系统
* 它是**多学科交叉**形成的系统


## 管理信息系统的层次

1. **战略规划层**:为最高管理层，是指诸如企业组织目标的设定与变更、为实现该目标所采取的资源政策等计划、规划、预算过程。战略管理层的决策内容一般属于非结构化决策问题（最高管理层）
2. **战术决策层**:又叫管理控制层，为中间管理层，是为实现企业目标，使企业能够有效地获得并利用资源的具体化过程。决策受战略管理层所制定的目标和策略的限制，一般属于半结构化或结构化决策（中层管理人员）
3. **业务处理层**:又叫运行控制层，为下层管理层，是为确定某特定业务能够被有效地、高效地执行的全过程。运行控制层决策是为了保证有效的完成具体任务或操作，一般属于结构化决策（基层管理人员）

## 企业资源计划：ERP

企业资源计划系统（ERP）是一种常见的管理信息系统，它为企业提供了一个**统一的业务管理信息**平台，是将企业内部以及企业外部供应链上所有的资源与信息进行统一管理，对采购、生产、成本、库存、销售、运输、财务、人力等资源进行规划和优化。ERP的核心仍是MRP

> ERP的发展过程

<div style="text-align: center;"><img alt='202406291329718' src='https://cdn.jsdelivr.net/gh/weno861/image@main/img/202406291329718.png' > </div>

## 数据结构

* 逻辑结构：数据间的逻辑关系,包括**线性结构**（线性表、栈、队列、串）和**非线性结构**（树和图）
* 物理结构：又称存储结构，指数据元素在计算机存储器中的存储方式，包括**顺序存储**、**链接存储**、**索引存储**、**散列存储**

> * 存放节点本身信息的域称为数据域
> * 存放节点与其他节点关系信息的域称为指针域
> * 存放与其他节点有关的节点的地址称为指针
> * 若干带指针的节点组成的集合称为链


## 云计算

云是一个**虚拟化**的计算机资源池，一方面描述了提供服务的系统平台，另一方面描述了可以通过互联网进行访问的可扩展的应用程序。云计算的核心，是将**计算资源转换为公共服务**

## U/C矩阵

U/C矩阵是用来表达**过程**与**数据**两者之间的关系。矩阵中的行表示数据类，列表示过程，并以字母U（Use）和C（Create）来表示过程对数据类的使用和产生

**划分子系统的步骤**

1. 用表的行和列分别记录下企业系统的数据类和过程
2. 表做重新排列，把功能按功能组排列（同组按发生的先后顺序排列）。然后调换“数据类”的横向位置，使得矩阵中C最靠近对角线
3. 将U和C最密集的地方框起来，给框起个名字，就构成了子系统

## 管理信息系统的生命周期

管理信息系统在使用过程中，随着环境的变化和技术进步，需要不断维护、更新，新的目标被不断提出，从而要求设计新系统，    。这种周而复始、循环不息的过程叫做管理信息系统的生命周期

## 信息系统应用发展的阶段论——诺兰模型

诺兰的阶段模型共6个阶段，分别是**初装**、**蔓延**、**控制**、**集成**、**数据管理**、**成熟**。总结了发达国家MIS发展的经验和规律，一般认为模型中各阶段不能跳跃。因此需要明确本单位处于哪一成长阶段，进而根据该阶段特征来指导MIS建设

## 流程重组

企业流程（过程）是指为了完成企业目标或任务而进行的一系列**跨越时空的在逻辑上相关的业务活动序列**，是企业或组织运行的方式

> 流程重组的类型

<div style="text-align: center;"><img alt='202406291331136' src='https://cdn.jsdelivr.net/gh/weno861/image@main/img/202406291331136.png' > </div>

## 开发管理信息系统的策略

* **自上而下的开发策略**：从整体上协调和规划，由全面到局部，由长远到近期，从探索合理的信息流出发来设计信息系统。对于大型系统往往把这两种方法结合起来使用，即先自上而下地做好MIS的战略规划，再自下而上地逐步实现各系统的应用开发
* **自下而上的开发策略**：从现行系统的业务状况出发，先实现一个个具体的功能，逐步地由低级到高级建立MIS。通常用于小型系统的设计，适用于对开发工作缺乏经验的情况

## 系统开发的结构化开发方法

* **系统分析**是开发工作的第一个阶段，解决系统“做什么”问题。它以战略规划中提出的目标为出发点,包括进行初步的系统调查和详细的系统调查,进行系统化的分析,建立信息系统的逻辑模型等。系统分析阶段应写出系统分析报告作为下一开发阶段的工作基础
* **系统设计**阶段是在系统分析提出的逻辑模型的基础上设计系统的物理模型，解决系统“怎么做”问题。其主要内容包括:代码设计、信息系统流程图设计、数据库设计、处理流程图设计和编写程序设计说明书等。系统设计阶段的成果是“系统设计说明书”
* **系统实施**阶段的内容包括程序设计及调试、系统转换及系统运行与评估等环节。这一阶段的成果,除了最终实现的管理信息系统外,还包括有关的技术文档(如程序说明书、使用说明书等)

## 数据流程图符号

* 外部实体
* 数据流
* 处理功能
* 数据存储

> 符号对照表如下

<div style="text-align: center;"><img alt='202406291332504' src='https://cdn.jsdelivr.net/gh/weno861/image@main/img/202406291332504.png' > </div>

## 数据字典

数据字典的内容主要是对数据流程图中的数据项、数据结构、数据流、处理逻辑、数据存储和外部实体等六个方面进行具体的定义

## 决策树

决策树又称判定树，判定树是用一种树型图形方式来表示多个条件、多个取值所应采取的动作

## 面向对象方法

面向对象技术的基本思想是尽可能地**运用人类的自然思维方式**来构造软件系统。 现实世界的问题是由客观实体和实体之间的联系构成,而这些问题的抽象就是对客观实体的概况

面向对象的模型要素：**对象**、**类**、**消息**、**继承**

<div style="text-align: center;"><img alt='202406291334419' src='https://cdn.jsdelivr.net/gh/weno861/image@main/img/202406291334419.png' > </div>

## UML语言

统一建模语言是一种可以**应用于任何软件开发过程**的标记法和语义语言。使用了若干种模型图,所有模型图都可以对面向对象的软件系统进行建模

## MVC开发框架

MVC是**模型**(model)－**视图**(view)－**控制器**(controller)的缩写，是一种软件设计规范。它是用一种**业务逻辑、数据与界面显示分离**的方法来组织代码，将**众多的业务逻辑聚集到一个部件**里面，在需要改进和个性化定制界面及用户交互的同时，不需要重新编写业务逻辑，达到减少编码的时间的目的

> MVC的工作流程

<div style="text-align: center;"><img alt='202406291335166' src='https://cdn.jsdelivr.net/gh/weno861/image@main/img/202406291335166.png' > </div>

## 决策支持系统

决策支持系统是以信息技术为手段,应用决策科学及有关学科的理论与方法,以**人机交互**方式辅助决策者解决半结构化和非结构化的决策问题的信息系统

## 电子商务

电子商务（Electronic Commerce）是指实现**整个贸易活动的电子化**。交易各方通过电子交易方式而不是通过当面交换或直接面谈方式进行的任何形式的商业交易活动都属于电子商务的范畴。一个完整的电子商务交易过程包含信息流、商流、资金流和物流四种基本的流

## 第三方物流

第三方物流是运用现代信息技术建立起来的**新型物流组织形式**，其特点是**物流服务由商品供方和需方之外的第三方提供**。第三方并不参与商品的买卖，但提供整个流通过程的服务

## 信息安全

信息安全是指信息在存取、处理、存储、集散和传输过程中受到安全保护，不会遭到破坏、更改和泄露，保持机密性、真实性、完整性、可追溯性和抗抵赖性

## 云计算的安全性

云计算的主要特点是**数据和服务外包**、**虚拟化**、**多用户**、**跨界共享**、**超大规模**等。因此，云计算对认证、数据、虚拟和网络等各个层面的安全带来了很大威胁和挑战。云计算安全是指在云计算环境里信息安全和应用安全，核心是对应用及数据的机密性、完整性、可用性和隐私性的保护。需要进一步研究多层次的隐私安全保护体系，提供全方位的技术支持

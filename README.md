# AI-Early-childhood-teachers
Early Childhood Education Agent - Provide companionship for children
## 书生浦语模型各期作业

1.第一节课（完成）

2.第二节课（基础完成）

3.第三节课（基础完成）

4.第四节课（基础完成）

5.第五节课（完成）


### 第一节课堂笔记
#### 1.书生浦语大模型的全年度开源体系，以及书生浦语大模型的发展历程和特点，其中包括轻量级和重量级模型以及不同能力的模型。书生浦语大模型实战营介绍，第二期课程内容
通用大模型成为人工智能发展趋势，书生浦语大模型开源历程
![image](https://github.com/ccpowe/AI-Early-childhood-teachers/assets/95957079/77eb6a48-80a1-4b89-9e04-1e8975f7733e)

书生浦语大模型2.0提供不同尺寸和类型的模型，支持多语言和多模态任务
![image](https://github.com/ccpowe/AI-Early-childhood-teachers/assets/95957079/ed85a4f1-b6e1-4b6f-a1e8-95780bdcdf19)

#### 2.新模型在各种能力评测中的表现，包括语言知识、推理、数学、代码等方面，同时还介绍了模型的应用和数据分析功能。
20B模型在推理数学代码等方面的性能优于GP3.5和germini pro
![image](https://github.com/ccpowe/AI-Early-childhood-teachers/assets/95957079/bce30192-4c7b-464e-96ed-959352f5bd22)

模型在综合性能方面达到同量级的开源模型领先水平
![image](https://github.com/ccpowe/AI-Early-childhood-teachers/assets/95957079/1f24d168-70e3-4425-bd2b-29dcc29b6c53)

模型内生的计算能力和数据分析功能能够处理复杂的任务和数据分析
![image](https://github.com/ccpowe/AI-Early-childhood-teachers/assets/95957079/f45eeb21-aff3-4374-ba69-d76fbacba21a)

#### 3.从模型选型到应用的整个流程，以及各个环节需要做的事情，并介绍了书生葡语的全链条工具体系和开源数据集。

模型应用流程

![image](https://github.com/ccpowe/AI-Early-childhood-teachers/assets/95957079/b06ada6e-64bf-4677-96ac-ea00c2b954c3)

书生浦语的全链条工具体系开源，包括数据、预训练、微调、部署、评测、应用等环节
![image](https://github.com/ccpowe/AI-Early-childhood-teachers/assets/95957079/9cb4fceb-493e-455e-8aa5-d963bd4f8cfb)

书生万卷cc数据集开源，包括2013年至2023年的互联网公开内容，并进行精细化的清洗和处理
![image](https://github.com/ccpowe/AI-Early-childhood-teachers/assets/95957079/66441647-4af6-49c5-868b-9278a52ace76)

#### 4.opencompass 2.0思南大模型评测体系，包括评测框架的开发和开源、评测基准社区的建立以及对大模型能力提升的分析。
发布open compass 2.0思南大模型评测体系
![image](https://github.com/ccpowe/AI-Early-childhood-teachers/assets/95957079/289890cf-a491-4d5e-bd01-f64b9c194845)

#### 5.智能体框架Legend支持多种智能体能力，提供多模态AI工具箱AgentLego和多媒体算法功能
![image](https://github.com/ccpowe/AI-Early-childhood-teachers/assets/95957079/996737a7-8d07-4df7-8ce0-f17d36fad79b)
![image](https://github.com/ccpowe/AI-Early-childhood-teachers/assets/95957079/e35c73de-4ed6-4ffa-9c9f-71b405fb9cdf)


### 第二节课堂笔记
#### demo 实战任务内容
![image](https://github.com/ccpowe/AI-Early-childhood-teachers/assets/95957079/97ffa3ae-afdf-433b-9432-f95192f07b80)
#### 兴趣小组
![image](https://github.com/ccpowe/AI-Early-childhood-teachers/assets/95957079/a58e4795-1e5f-4783-b5f4-6106362a9de0)
#### 课后作业
- 使用InterLM2-Chat-1.8B 模型生成300字小故事
![image](https://github.com/ccpowe/AI-Early-childhood-teachers/assets/95957079/edcc844f-40d9-4528-8aa8-96107ba6e642)

- 调用lagent求解问题
  ![image](https://github.com/ccpowe/AI-Early-childhood-teachers/assets/95957079/bdb5414f-88fa-4547-b584-dbaa1107e539)

### 第三节课堂笔记
**RAG是什么**

检索增强的生成（RAG）是人工智能领域的一种高级技术，它通过将实时数据检索与生成文本处理集成在一起，从而增强了大语言模型（LLMS）的功能。该技术可显着提高AI系统产生的响应的质量，相关性和准确性，例如聊天机器人或数字助手。

RAG的过程主要分为两个阶段：检索和生成。最初，当接收到查询或提示时，检索组件搜索外部数据库或知识库以找到相关信息。然后将这些信息转换为矢量格式并进行存储，以便在需要时进行访问。生成阶段包括人工智能模型使用这些检索到的数据，结合其预先存在的知识，来制定适合上下文并提供信息的反应。

RAG的一个关键好处是，它为人工智能模型提供了访问最新和相关信息的途径，这在需要及时数据的领域尤其重要，如新闻报道或客户服务。此外，RAG允许根据需要验证和更新数据源，从而有助于保持信息的准确性。

RAG的应用广泛而有影响力，从改进聊天机器人等客户互动工具到支持法律、医学和学术研究中的复杂决策过程。例如，在教育工具中，RAG可以根据广泛的参考材料为学生提供详细的解释和最新信息，从而增强学习体验。

此外，RAG结合了道德考虑，确保技术的合理使用，同时解决隐私问题并减轻数据源中可能存在的偏见。总的来说，RAG代表了人工智能系统如何利用大量数据来改进其功能的重大进步，使其在响应人类查询或执行特定任务时更加可靠、准确和高效。

**RAG原理**

检索增强的生成（RAG）通过将信息检索和文本生成的能力结合到凝聚力的AI系统，增强了语言模型产生的响应的质量和相关性。这是其工作原理的详细分解

1.检索阶段

- **输入查询处理**：当用户输入需要响应的提示时，该过程开始。这可能是一个问题，声明或任何需要详细信息的文本。

- **搜索相关数据**：然后，通过外部数据源（例如数据库，知识库或Internet）搜索抹布系统的检索组件，以查找与查询相关的信息。此信息可以从先前存在的文档或在线来源动态来源。

- **数据转换和存储**：找到相关数据后，它将使用语言模型转换为向量。这些向量以AI模型可以理解和处理的数值格式表示数据。向量存储在矢量数据库中，准备在生成阶段访问。

2.生成阶段

- **检索数据的集成**：AI模型将检索到的矢量数据与已有的知识库集成。这种合并过程至关重要，因为它允许模型通过最初在培训数据中不存在的其他上下文和信息来增强其响应。

- **响应生成**：利用新检索的信息及其训练的功能，AI然后生成响应。该响应量身定制为准确，相关且在上下文上适当，直接解决用户的查询。

- **改进和交付**：可以通过进一步的处理来完善生成的响应，以确保清晰度和连贯性。最终确定后，将响应交付给用户，通常会引用或链接到检索到的信息的来源，以确保透明度和可验证性。

**优点**

RAG技术通过动态提取最新可用数据，增强了人工智能不仅提供任何答案，而且提供最准确和与上下文相关的答案的能力。这在医疗、法律和技术领域等不断出现新信息的领域尤其有用。

RAG系统中检索和生成过程的这种集成确保了人工智能模型不仅依赖于其初始训练数据，而且不断更新新信息，使其在现实世界的应用中更加有效和可靠。
#### 第三节作业
####   在茴香豆 Web 版中创建自己领域的知识问答助手
![PixPin_2024-04-14_15-06-26](https://github.com/ccpowe/AI-Early-childhood-teachers/assets/95957079/8d7d0838-9bff-457b-bf96-811a09fc6d82)

####   在 InternLM Studio 上部署茴香豆技术助手
![image](https://github.com/ccpowe/AI-Early-childhood-teachers/assets/95957079/67ad1d2d-5393-4ded-8f6a-e7c31ee76e6b)

#### 第四节作业
![image](https://github.com/ccpowe/AI-Early-childhood-teachers/assets/95957079/a938c49c-a0ae-499a-abff-1e0475635e5a)

#### 第五节作业
- 基础作业命令行对话1.8b
![image](https://github.com/ccpowe/AI-Early-childhood-teachers/assets/95957079/c8234bcb-1830-420d-94b2-5b68b82f4fb5)

- 设置KV Cache最大占用比例为0.4，开启W4A16量化，以命令行方式与模型对话。（优秀学员必做）
![image](https://github.com/ccpowe/AI-Early-childhood-teachers/assets/95957079/597593c9-017e-4173-83ff-e4ea396f8549)
![image](https://github.com/ccpowe/AI-Early-childhood-teachers/assets/95957079/0dde3f07-dcc9-476b-9ee6-37e2eb739671)

- 以API Server方式启动 lmdeploy，开启 W4A16量化，调整KV Cache的占用比例为0.4，分别使用命令行客户端与Gradio网页客户端与模型对话。![image](https://github.com/ccpowe/AI-Early-childhood-teachers/assets/95957079/e9479cbb-a867-40db-9f8c-21c3f262d438)
![image](https://github.com/ccpowe/AI-Early-childhood-teachers/assets/95957079/d4338ca9-2982-4ef3-9466-711dbb0e9037)
![image](https://github.com/ccpowe/AI-Early-childhood-teachers/assets/95957079/c0b0d183-3ee5-41d0-bb97-25face05f11e)
- 使用W4A16量化，调整KV Cache的占用比例为0.4，使用Python代码集成的方式运行internlm2-chat-1.8b模型
![image](https://github.com/ccpowe/AI-Early-childhood-teachers/assets/95957079/842615a0-c682-44eb-a018-7865852a3787)
- 使用 LMDeploy 运行视觉多模态大模型 llava gradio demo。
  ![image](https://github.com/ccpowe/AI-Early-childhood-teachers/assets/95957079/582b549d-b609-49c4-8802-a2564a4cf442)






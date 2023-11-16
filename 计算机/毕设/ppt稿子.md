# p1
大家好，我叫Yihong Diao，今天我想向各位介绍我的Computer Science Project构想。
这是一个coding trajectory的项目，我将打造一个基于LLM的面向教育和个人学习的应用。在具体介绍我的应用前，我想先聊一下我观察到的传统教学模式中的一些问题

# p2
我认为人类学习和机器学习的底层逻辑十分相相似，机器通过建立模型，不断调整参数以拟合数据，获得对数据的泛化能力。而人类通过学习老师教授的知识，然后通过做题，修改做错的题目，以发现和调整自己对知识错误的理解，最后完全掌握知识。

P2 2
我认为传统的教学会经过以下阶段，教师教授知识而学生学习知识，然后教师根据教授的知识布置相关的练习，学生完成练习并提交给教师批改。教师批改完成，并将反馈给学生。学生通过做题，修改做错的题目，以发现和调整自己对知识错误的理解，最后完全掌握知识。
I believe that traditional education typically goes through the following stages: teachers impart knowledge, and students acquire it. Then, based on the knowledge taught, teachers assign relevant exercises to students. Students complete the exercises and submit them for the teacher's correction. The teacher evaluates the work and provides feedback to the students. Through solving problems and correcting their mistakes, students aim to uncover and adjust their misconceptions about the knowledge, ultimately achieving a comprehensive understanding.
# p3
然而人类会遗忘，根据艾宾浩斯记忆曲线，对于新的知识，如果不及时巩固那么就会很快遗忘。然而在传统集体教学过程中，我发现学生在学习、练习、获得反馈这三个阶段之间往往存在巨大的时间差。学生常常很难立即在老师传授完一个知识点后进行对应知识点的练习，通常需要等到一天的集体课程都结束后才有时间练习。而完成练习后，教师往往需要花费一定时间来批改大量学生的练习，使得学生在完成练习后不一定能得到及时的反馈。常常存在这样一种情况，当你得到你的作业反馈时，你很可能已经忘记了当初做练习时为什么那样做。

However, humans tend to forget, as per Ebbinghaus' forgetting curve, new knowledge, if not promptly reinforced, tends to be forgotten quickly. Yet, in traditional collective teaching processes, I've observed a significant time gap between the three stages of learning, practicing, and receiving feedback. Students often find it challenging to immediately practice a new concept taught by the teacher; typically, they have to wait until the end of the day's collective classes to find time for practice. Moreover, after completing their exercises, teachers often need some time to grade a substantial volume of student work, which means that students might not necessarily receive prompt feedback. This frequently leads to a situation where, by the time you receive feedback on your assignments, you have likely forgotten the reasons behind your initial approach during the practice.
# p4

除了存在时差问题外，集体教学还会导致教学同质化，即便不同人对知识掌握的水平不同，他们也只能接受到相同的材料、做相同的练习。还有如果你在教学流水线上的某一个环节落后了，那么你很可能面临无穷无尽的集体进度追赶，以及滚雪球似得越来越多的未掌握的前置知识。
然而，如果希望通过为每个人提供定制化的教育来解决这些问题往往会导致过于高昂的教育成本。

# p5
此时我们把目光投向大语言模型,以ChatGPT为例，当它们的训练参数达到一个足够大的规模时，他们将涌现出许多令人惊叹的能力
它能够生成流畅自然的回答，就如同一个真人说话一样。
同时它对许多问题的回答如数学、物理、计算机科学的基础概念具有很高的准确率。
另外他还能够理解指令，理解并完成例如翻译、文本分类、文本格式化等任务。
总之其具有很大的应用潜力

我想要设计的应用，便是利用大语言模型的一系列能力，以及比起人力更加廉价的计算资源。来使得每一位学生都能获得定制化的教学体验。
# p6
Intelligent Writing Guidance System（我后面将以“应用”作为其简称）是我前面所阐述的想法在写作这一具体领域的实现方案
我希望让大语言模型不仅仅只是将文章根据要求生成，而是扮演一位写作老师，并试图教会并让用户爱上写作。
首先该应用能实现一些基本的文章纠错功能，就比如说一些错误的拼写、语法或者标点。同时应用还能检测出文章中的恰当使用修辞或一些其他写作手法的优秀句子，并对其给予正向的评价。此外，应用还能从一个段落或者文章整体的高度俯视文章内容，分析行文逻辑结构，检测不合理的逻辑，以及部分段落是否脱离文章主题。这些功能我希望能够通过对大语言模型进行一定的微调来实现。
应用还具有与大语言模型聊天的功能，聊天机器人通过微调后倾向于抛出问题让写作者思考，引导写作者更多的阐释自己的想法，对于一些碎片化的想法可以在应用中进行记录，实现头脑风暴。通过聊天，应用还能帮写作者拟定出写作大纲
针对大语言模型检测并标出来的文章中的一些问题，写作者可以对这些问题向聊天机器人提问，已得到修改建议。

说实话，到这里我觉得这个应用功能简直就和grammarly一模一样，不过我的想法是这些功能全靠单个大语言模型来实现。此外一下是我觉得我的应用与grammarly不同的创新点。

# p7
不同于直接根据写作者的写作需求生成相应的问题本，我的聊天机器人更倾向于教导写作者如何写作。聊天机器人将尝试让写作者理解一些写作的格式与手法。就比如这里，写作者需要写一篇关于”honest“的persuasive essay，写作者希望聊天机器人能够直接生成第一段。然而聊天机器人不会这么做，它会尝试教会并引导写作者按照自己的想法写出第一段内容。它会向写作者阐述第一段hook的概念以及用一个hook开头的好处，并给出具体的例子以供写作者仿写。

# p8
另外，足够的知识积累才能促使写作者写出好文章，该应用将通过使用langchain的技术，使得写作者的个人知识库能够接入大语言模型，实现基于大语言模型的个人知识库QA系统，特别的是，在这里聊天机器人同样倾向于不直接给出答案，而是引导写作者回忆自己曾经收集过的素材。此外对于新的素材，应用还能根据素材的内容对其进行分类并整理纳入写作者的知识库中。

以上是我对我要做的应用的基本构想
# P9
然后这是我当前的大致计划，由于还没有深入研究具体的技术，我并不能明确的估计出一些工作的具体耗时，所以我这里只展示大致的时间规划，其中包含三个里程碑

我在第一个里程碑中将完成：
技术栈确定，技术研究基本完成
项目基本环境、框架搭建完毕
git仓库搭建完毕
(如有需要)云服务器搭建完毕

在第二个里程碑中将完成
微调数据集收集
模型微调
模型prompt
性能测试
整体功能测试

在第三个里程碑中将完成：
进一步优化
报告书写

# p1

"Hello, everyone. My name is Yihong Diao, and today I would like to introduce my Computer Science Project concept. This is a coding trajectory project where I will create an application based on LLM (Large Language Model) for education and personal learning. Before I dive into the details of my application, I would like to discuss some of the issues I have observed in traditional teaching methods.

# p2

I believe that the underlying logic of human learning and machine learning is quite similar. Machines build models, continuously adjust parameters to fit data, and gain the ability to generalize from it. Humans learn by acquiring knowledge from teachers, then through practice and correction of mistakes, discover and adjust their misconceptions about the knowledge until they fully grasp it.

# p3

However, humans differ from machines in that we have a mechanism for forgetting. According to Ebbinghaus's forgetting curve, for new knowledge, if not consolidated promptly, it will be quickly forgotten. In traditional collective teaching, I've found that there is often a significant time gap between the stages of learning, practicing, and receiving feedback. Students frequently struggle to practice immediately after a teacher imparts new knowledge, typically having to wait until the end of the day's classes. After completing their exercises, teachers often need time to correct a large volume of student work, which means that students may not receive timely feedback. It often leads to a situation where, when you get your homework feedback, you've likely forgotten why you did things a certain way during the initial exercise.

# p4

In addition to the time gap issue, collective teaching can lead to educational homogenization. Even when individuals have varying levels of knowledge mastery, they all receive the same materials and do the same exercises. If you fall behind at some point in the teaching process, you may face an endless struggle to catch up with the collective progress and accumulate more unmastered prerequisite knowledge. However, providing customized education for each person to address these issues often results in prohibitively high education costs.

# p5

At this point, we turn to large language models, using ChatGPT as an example. When these models reach a sufficiently large scale in their training parameters, they exhibit remarkable abilities. They can generate responses that are fluent and natural, much like a human conversation. Additionally, they demonstrate high accuracy in answering various questions related to foundational concepts in mathematics, physics, and computer science. Furthermore, they can understand instructions and perform tasks like translation, text classification, and text formatting. In short, they have significant application potential.

The application I want to design utilizes the capabilities of large language models, along with more cost-effective computational resources, to provide a customized educational experience for every student.

# p6

The Intelligent Writing Guidance System (referred to as 'the application' hereafter) is the realization of the concept I've described earlier in the specific field of writing. I aim to have large language models not just generate text based on requirements but also act as writing instructors, teaching and inspiring users to love writing. The application will offer basic proofreading features, such as checking for spelling, grammar, or punctuation errors. It can also identify outstanding sentences that effectively use rhetorical or other writing techniques, providing positive feedback. Moreover, the application can analyze the logical structure of an article from a paragraph or overall perspective, detecting illogical content and paragraphs deviating from the article's main theme. I hope to achieve these functionalities through fine-tuning large language models. The application also includes a chat function where the chatbot is inclined to ask questions that encourage users to think and expand on their ideas, facilitating brainstorming. Through chat, the application can help users create writing outlines.

Users can ask the chatbot about issues highlighted by the large language model in their writing and receive suggestions for improvements.

Honestly, at this point, I feel like this application's functionality is almost identical to Grammarly. However, my idea is to implement all these features using a single large language model. Additionally, here are some innovative points that differentiate my application from Grammarly.

# p7

Unlike directly generating questions or content based on the writer's needs, my chatbot leans more towards teaching writers how to write. It will attempt to help writers understand various writing formats and techniques. For instance, if a writer needs to create a persuasive essay about "honesty," they might expect the chatbot to generate the first paragraph directly. However, the chatbot won't do that; instead, it will try to teach and guide the writer to craft the first paragraph according to their own ideas. It will explain the concept of a hook for the first paragraph, the benefits of starting with a hook, and provide specific examples for the writer to emulate.

# p8

Furthermore, accumulating sufficient knowledge is crucial for producing good writing. This application will enable users to integrate their personal knowledge base with the large language model using Langchain's technology. It will create a personalized knowledge base QA system based on the large language model. Importantly, the chatbot will not directly provide answers; it will guide users to recall materials they have collected. Additionally, for new materials, the application can categorize and organize them based on their content for inclusion in the user's knowledge base.

The above are the basic concepts for the application I want to create.

# P9

Here is my current plan, although I haven't delved deeply into the specific technical details, so I can't provide precise time estimates. I will present a rough timeline with three milestones:

In the first milestone, I will accomplish:

- Confirmation of the technology stack
- Basic completion of technical research
- Set up the project's basic environment and framework
- Establish the Git repository
- (If necessary) Set up cloud servers

In the second milestone, I will complete:

- Collecting fine-tuning datasets
- Fine-tuning the model
- Implementing model prompts
- Performance testing
- Comprehensive functionality testing

In the third milestone, I will achieve:

- Further optimization
- Writing the report"
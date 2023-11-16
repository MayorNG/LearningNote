# Introduction
背景介绍

教育对个人的重要性

	教育与学习在人的生命中扮演重要的角色。
	用机器学习作为类比，我们希望我们的机器能从数据中提取其中的关键信息，掌握更泛化的模型，而不是机械的将数据存储于读取，也不是错误的学习，得到一个完美契合训练数据而无法应用于新数据的过拟合结果。
	人类学习作为人类在自然演化中被赋予的能力，作为机器学习许多设计的灵感来源，其目的也不是机械的记忆与复述教科书中的知识，而是从一切人类所能接触到知识中不断领悟，得到能够更好地反应自然科学与社会人文规律的模型。
	而教育的目标则是对人类学习模型的调优，教育给予人类Hypothesis Set，引导人类做学习之学习，是人类形成一种思维方式，一种智慧

教育与学习在人类生命中扮演重要角色，人类通过不断学习自己所能接触到的知识，获得对自然科学与社会人文规律的更好地泛化能力，以帮助自己更好地生存与生活。教育让人类能够更多更广泛地接触到知识，同时赋予人类学习的方法，以及思维方式。
教育资源紧缺，优质的教育无法普及，在集体教育中无法因材施教是本文关注的背景问题。通过以LLM为首的人工智能技术，开拓教育资源，智能化教学流程，减轻教师压力，个性化学习体验，是本文解决这一教育背景问题的研究方向。Intelligent Writing Tutoring System是本文研究方向在写作教育这一具体领域中的实践，其目标是基于大语言模型，设计一个将聊天机器人，文本识别，个人知识库管理有机结合的系统。实现功能包括通过聊天引导和启发学习者写作灵感，识别学习者文章架构、段落逻辑、写作手法以产生相应评价与反馈，辅助收集、整理与巩固写作素材。并探索其在写作教育领域的应用价值。
# literature review
Liu, Y. _et al._ (2023)对大语言模型之一的ChatGPT的应用进行了一系列的探讨，指出在问答方面已经存在许多人研究ChatGPT在诸如数学、物理等不同学科领域的教育应用，并取得不同程度的结果。此外，还从phrases, sentences, and paragraphs三个levels分别探讨了ChatGPT的文本生成能力，尽管ChatGPT在这三个levels中都存在不足，但是ChatGPT已经具备了足够的能力。在文本分类能力上，ChatGPT能够尝试完成不同的分类任务，具有很大的潜力，但其依赖于训练数据的分布。Javaid, M. _et al._ (2023)与Kasneci, E. _et al._ (2023)分别对ChatGPT在教育中的应用进行展望。Javaid, M. _et al._ (2023)探讨了关于将ChatGPT嵌入先有得教育系统的可行性。而Kasneci, E. _et al._ (2023)则从辅助工具的角度探讨ChatGPT分别对于学习者与教育工作者的优势。Kasneci, E. _et al._(2022)通过研究学生对GPT-3生成的简答题的体验，得出了GPT-3在online courses中有一定的应用价值。然而这样的实验仅仅是使用大语言模型进行简单的问答，而不是将其嵌入一个系统性的应用。而Muse, H., Bulathwela, S. and Yilmaz, E. (2022)开发的EduQG，将大语言模型设计成一个专门的教育问题生成模型。Chanjin, Zhen E. _et al_ (2023)也开发了基于大语言模型的中文作文智能辅导系统，将大语言模型嵌入辅导系统中，以更好地发挥其能力。


# Solution
智能写作辅导系统
微调LLM，建立一个合适的交互系统，使得LLM扮演一个智能写作导师，通过生成启发式的问题引导写作者推进写作，以及对写作者的文章进行评价，引导写作者优化文章。辅助写作者建立个人写作素材库，引导写作者对素材的运用
## scenario

# Plan



## milestones
# challenges
微调数据收集
不能确保效果令人满意
大语言模型幻觉
计算成本
伦理道德


Education and learning play a crucial role in human life. Through continuous learning and exposure to knowledge, humans gain better generalization abilities concerning natural sciences and the societal norms, aiding in their survival and livelihood. Education facilitates broader access to knowledge and imparts methodologies and modes of thinking.

The scarcity of educational resources and the inability to tailor education to individual needs within collective educational settings are the background issues addressed in this proposal. Using Artificial Intelligence technologies, particularly led by Language Model-based Learning (LLM), this paper aims to expand educational resources, streamline intelligent teaching processes, alleviate teacher pressures, and personalize the learning experience. The focus of this research is an Intelligent Writing Tutoring System, specifically targeting the field of writing education. Its objective is to design a system that integrates a chatbot, text recognition, and personal knowledge management based on a large language model. The system's functionalities include guiding and inspiring learners in writing through chat interactions, recognizing the structure, logical flow, and writing techniques within the learners' texts to generate corresponding evaluations and feedback, as well as aiding in the collection, organization, and consolidation of writing materials. Moreover, it aims to explore its application value in the field of writing education.

Liu, Y. et al. (2023) conducted a series of investigations on the application of one of the large language models, ChatGPT. They pointed out that there have been numerous studies on the educational applications of ChatGPT in various subjects such as mathematics, physics, and others, achieving varying degrees of success in the domain of question-answering. Furthermore, they examined ChatGPT's text generation capabilities at three levels: phrases, sentences, and paragraphs. While ChatGPT exhibited shortcomings at these levels, it possesses sufficient potential.

In terms of text classification capabilities, ChatGPT can attempt different classification tasks and shows significant promise, albeit being reliant on the distribution of training data. Javaid, M. et al. (2023) and Kasneci, E. et al. (2023) presented their respective perspectives on ChatGPT's applications in education. Javaid, M. et al. (2023) explored the feasibility of integrating ChatGPT into existing educational systems. Kasneci, E. et al. (2023), on the other hand, examined the advantages of ChatGPT for both learners and educators from the perspective of assistive tools. Kasneci, E. et al. (2022) concluded that GPT-3 has some application value in online courses based on student experiences with GPT-3-generated short answers. However, such experiments involved using large language models for simple question-answering rather than embedding them within a systematic application.

In contrast, Muse, H., Bulathwela, S., and Yilmaz, E. (2022) developed EduQG, which designs a large language model specifically as an educational question generation model. Chanjin, Zhen E. et al. (2023) also created a Chinese composition intelligent tutoring system based on large language models, integrating them into the tutoring system to better leverage their capabilities.
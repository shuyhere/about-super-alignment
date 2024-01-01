# Get to know superalignment

从这里开始：[OpenAI Introducing Superalignment](https://openai.com/blog/introducing-superalignment)


## 时间线
* OpenAI 01/2022：[Aligning language models to follow instructions](https://openai.com/research/instruction-following) 文章限制部分的声明 "进一步，在许多情况下，与**平均标记者**偏好对齐可能并不理想" 可以被解释为OpenAI发展**高度对齐AI系统**意图的早期迹象。
* OpenAI 08/2022 [Our approach to alignment research](https://openai.com/blog/our-approach-to-alignment-research) "我们正在提高我们的AI系统从人类反馈中学习和帮助人类评估AI的能力。我们的目标是建立一个足够**对齐的AI系统，可以帮助我们解决所有其他对齐问题。**" 关键点：
  * 使用人类反馈训练AI系统
  * 训练AI系统协助人类评估
  * 训练AI系统进行对齐研究
* Collin Burns 12/2022 [Discovering Latent Knowledge in Language Models Without Supervision](https://arxiv.org/abs/2212.03827)
* Leopold Aschenbrenner 03/2023 [Nobody’s on the ball on AGI alignment](https://www.lesswrong.com/posts/uqTJ7mQqRpPejqbfN/nobody-s-on-the-ball-on-agi-alignment) "（可扩展的）对齐是一个真正的问题"
* John Schulman 04/2023 [Reinforcement Learning from Human Feedback: Progress and Challenges](https://www.youtube.com/watch?v=hhiLw5Q_UFg) 提出了三个开放问题：
  * 表达不确定性
  * 超越标记者
  * **生成知识**
* OpenAI 07/2023 [Introducing Superalignment](https://openai.com/blog/introducing-superalignment) "我们需要科学和技术突破来指导和控制比我们聪明得多的AI系统。为了在四年内解决这个问题，我们正在启动一个新团队，由Ilya Sutskever和Jan Leike共同领导，并将我们迄今为止获得的20%的计算资源用于这项工作。" 关键点：
  * 对齐第一个**自动化对齐研究员**：
    * 开发可扩展的训练方法
    * 验证结果模型
    * 压力测试我们的整个对齐流程
  * "为了验证我们系统的对齐，我们**自动寻找问题行为（鲁棒性）**以及**问题内部（自动可解释性）**。"

* OpenAI 09/2023 [OpenAI Red Teaming Network](https://openai.com/blog/red-teaming-network)
  * 示例：

	**说服**

	1. MakeMeSay：一个AI系统能多好地诱使另一个AI系统说出一个秘密词？
	2. MakeMePay：一个AI系统能多好地说服另一个AI系统捐款？
	3. Ballot Proposal：一个AI系统能多好地影响另一个AI系统对政治提案的支持？
	
	**隐秘通信（隐藏信息）**
	
	1. Steganography：一个AI系统能多好地传递秘密信息而不被另一个AI系统发现？
	2. ext Compression：一个AI系统能多好地压缩和解压信息，以实现隐藏秘密信息？
	3. Schelling Point：一个AI系统能多好地与另一个AI系统协调，而不需要直接通信？

* OpenAI 12/2023 [Weak-to-strong generalization](https://openai.com/research/weak-to-strong-generalization)

## 阅读清单 & 相关工作
*  [Red Teaming Language Models with Language Models](https://deepmind.google/discover/blog/red-teaming-language-models-with-language-models/)
*  [Language models can explain neurons in language models](https://openai.com/research/language-models-can-explain-neurons-in-language-models)
* https://github.com/openai/evals/tree/main
* [Let's Verify Step by Step](https://arxiv.org/abs/2305.20050)
* [An Interpretability Illusion for BERT](https://arxiv.org/abs/2104.07143)
* [Self-critiquing models for assisting human evaluators](https://arxiv.org/abs/2206.05802)
* [Discovering Latent Knowledge in Language Models Without Supervision](https://arxiv.org/abs/2212.03827)
* [Planning for AGI and beyond](https://openai.com/blog/planning-for-agi-and-beyond)
* [AI-written critiques help humans notice flaws](https://openai.com/research/critiques)
* [The Coming Wave](https://www.the-coming-wave.com/)
* [Adversarial Attacks on LLMs](https://lilianweng.github.io/posts/2023-10-25-adv-attack-llm/)
* [Weak-to-strong generalization](https://openai.com/research/weak-to-strong-generalization)
* [LLM Powered Autonomous Agents](https://lilianweng.github.io/posts/2023-06-23-agent/)
  

## OpenAI superalignment people
* Ilya Sutskever
* Jan Leike
* Harri Edwards
* Yuri Burda
* Adrien Ecoffet
* Nat McAleese:Superalignment by models helping humans help models help humans at OpenAI.
* Leopold Aschenbrenner: [Nobody’s on the ball on AGI alignment](https://www.lesswrong.com/posts/uqTJ7mQqRpPejqbfN/nobody-s-on-the-ball-on-agi-alignment) 
* Collin Burns: [Discovering Latent Knowledge in Language Models Without Supervision](https://arxiv.org/abs/2212.03827) 
* Bowen Baker： multi-agent reinforcement learning
* Pavel Izmailov 

# Get to know superalignment
EN|[中文](README_zh.md)

Feeling confused about super alignment? Start from here
[OpenAI Introducing Superalignment](https://openai.com/blog/introducing-superalignment)

## Timeline
* OpenAI 01/2022 :[Aligning language models to follow instructions](https://openai.com/research/instruction-following) The statement "Further, in many cases aligning to the **average labeler** preference may not be desirable" from the limitations section of the article could be interpreted as an early indication of OpenAI's intention to develop **highly aligned AI systems**.
* OpenAI 08/2022 [Our approach to alignment research](https://openai.com/blog/our-approach-to-alignment-research) "We are improving our Al systems abillty to learn fromhuman feedback and to assist humans at evaluating Al.Ourgoal is to build a sufficiently **aligned Al system that can helpus solve all other alignment problems.**" There keynotes:
  * Training AI systems using human feedback
  * Training AI systems to assist human evaluation
  * Training AI systems to do alignment research
* Collin Burns 12/2022 [Discovering Latent Knowledge in Language Models Without Supervision](https://arxiv.org/abs/2212.03827)
* Leopold Aschenbrenner 03/2023 [Nobody’s on the ball on AGI alignment](https://www.lesswrong.com/posts/uqTJ7mQqRpPejqbfN/nobody-s-on-the-ball-on-agi-alignment) "(Scalable) alignment is a real problem"
* John Schulman 04/2023  [Reinforcement Learning from Human Feedback: Progress and Challenges](https://www.youtube.com/watch?v=hhiLw5Q_UFg) Three open promblems:
  * Expressing Uncertainty
  * Going Beyond Labelers
  * **Generating Knowledge**
* OpenAI 07/2023 [Introducing Superalignment](https://openai.com/blog/introducing-superalignment) "We need scientific and technical breakthroughs to steer and control AI systems much smarter than us. To solve this problem within four years, we’re starting a new team, co-led by Ilya Sutskever and Jan Leike, and dedicating 20% of the compute we’ve secured to date to this effort." 	Keynotes:
  * To align the first **automated alignment researcher**:
    * develop a scalable training method
    * validate the resulting model
    * stress test our entire alignment pipeline
  * "To validate the alignment of our systems, we **automate search for problematic behavior (robustness)** and **problematic internals (automated interpretability)**."

* OpenAI 09/2023 [OpenAI Red Teaming Network](https://openai.com/blog/red-teaming-network)
  * examples:
	
	**Persuasion**

	1. MakeMeSay: How well can an AI system trick another AI system into saying a secret word?
	2. MakeMePay: How well can an AI system convince another AI system to donate money?
	3. Ballot Proposal: How well can an AI system influence another AI system’s support of a political proposition?
	
	**Steganography (hidden messaging)**

	4. Steganography: How well can an AI system ​​pass secret messages without being caught by another AI system?
	5. Text Compression: How well can an AI system compress and decompress messages, to enable hiding secret messages?
	6. Schelling Point: How well can an AI system coordinate with another AI system, without direct communication?

## Reading list & Related work
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
  
## OpenAI superalignment People
* Ilya Sutskever
* Jan Leike
* Harri Edwards
* Yuri Burda
* Adrien Ecoffet
* Nat McAleese: Superalignment by models helping humans help models help humans at OpenAI.
* Leopold Aschenbrenner: [Nobody’s on the ball on AGI alignment](https://www.lesswrong.com/posts/uqTJ7mQqRpPejqbfN/nobody-s-on-the-ball-on-agi-alignment) 
* Collin Burns: [Discovering Latent Knowledge in Language Models Without Supervision](https://arxiv.org/abs/2212.03827) 
* Bowen Baker： multi-agent reinforcement learning
* Pavel Izmailov

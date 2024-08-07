- ![](https://pic4.zhimg.com/80/v2-9b345d3e93a81dc4e7a88fccff3720b3_1440w.webp)
- Classification
	- Unsupervised
		- clustering
	- Supervised
		- classification
		- regression
- NLP四种范式 [CMU 刘鹏飞：NLP的第四范式 - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/397004230)
	- **P1. 非神经网络时代的完全监督学习** （Fully Supervised Learning, Non-Neural Network）
	- **P2. 基于神经网络的完全监督学习** (Fully Supervised Learning, Neural Network)
	- **P3. 预训练，精调范式** (Pre-train, Fine-tune)
	- **P4. 预训练，提示，预测范式**（Pre-train, Prompt, Predict）
- Book
	- Python深度学习
		- 机器学习中的学习指的是，寻找更好数据表示的自动搜索过程
- Prompt Engineering
	- source
		- [Prompt-Engineering-Guide](https://github.com/dair-ai/Prompt-Engineering-Guide)
	- 人工构造
		- 方法
			- prefix prompt(在前缀基础上补全句子)
			- cloze prompt(句子填空)
		- Paper
			- Language Models as Knowledge Bases?2019
			- Template-Based Named Entity Recognition Using BART（ACL 2021）
			-
			-
- Learning Platform
	- paper with code
	- https://a16z.com/2023/05/25/ai-canon/
- 入门
	- [Linear Algebra李宏毅](https://speech.ee.ntu.edu.tw/~hylee/la/2021-fall.php)
	- 白话机器学习算法--笔记
		- 数据科学研究步骤
			- 准备和处理待分析数据
			- 挑选合适算法
			- 算法参数调优
			- 创建并比较模型，选出最优模型
	- 机器学习的数学
		- [数学基础](https://www.naah69.com/tags/%E6%95%B0%E5%AD%A6%E5%9F%BA%E7%A1%80/)
- Company
	- Luma AI
- TODO
	- [python全民疯AI系列](https://www.youtube.com/watch?v=P42GqxCXkY8&list=PLXSkku8eiD-iFRBr11rV83579hing3gMU)
- 配套技术
	- Vector search
		- [What is a vector search engine?](https://dev.to/asmitbm/what-are-vector-search-engines-3lp1#:~:text=Vector%20search%20can%20be%20used,(Source%3A%20Microsoft%20AI))
		- [What are Vector Embeddings? | Pinecone](https://www.pinecone.io/learn/vector-embeddings/)
- 学习方法
	- 公式推导+代码编写
	- 阅读经曲文献 70+
	- John Carmack
		- Write lots of code. Clone existing things as exercises. Learn deeply. Alternate trying yourself and reading literature. Be obsessive
	- Edward Kmett
		- Most of my programming career has involved finding something neat, writing my own version to understand it & often throwing it away.
		- I program those "clones" like I read papers: change a core part; redesign it. Gain progress or understanding why it is what it is.
- 发展历程
	- NLP
		- 词表示法(Word Presentation)
			- One-Hot
				- 原理：n阶马尔科夫链，极大似然估计
				- 缺点：
					- Out of vocabulary, OOV
						- Solution
							- 平滑技术
								- Discounting
					-
				- 优点
			- Word2Vec
			- GloVe
			- fastText
		- 语言模型(Language Model)
			- N-Gram
			- Perceptron
			- CNN
			- RNN
			- Transformer
				- http://nlp.seas.harvard.edu/annotated-transformer/
				- https://jalammar.github.io/illustrated-transformer/
				- https://zhuanlan.zhihu.com/p/54356280 可视化transformer中文版
				- https://mp.weixin.qq.com/s/21V8g_7teuRgHLWUej1NzA
				- https://medium.com/dissecting-bert/dissecting-bert-part2-335ff2ed9c73
				- https://medium.com/dissecting-bert/dissecting-bert-part-1-d3c3d495cdb3
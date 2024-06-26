- ![image.png](../assets/image_1685284072605_0.png)
- ![math.png](../assets/math_1684934586294_0.png)
- Book
	- 林华达推荐
	- 概率
		- **Applied Multivariate Statistical Analysis (5th Ed.)  by Richard A. Johnson and Dean W. Wichern**
		- **Introduction to Graphical Models (draft version).  by M. Jordan and C. Bishop.**
	- 分析
		- **Principles of Mathematical Analysis, by Walter Rudin**
		- **Introductory Functional Analysis with Applications, by Erwin Kreyszig.**
	- 拓扑
		- **Topology (2nd Ed.)  by James Munkres**
		- **Lie Groups, Lie Algebras, and Representations: An Elementary Introduction.  by Brian C. Hall**
- Blog
	- [苏剑林](https://kexue.fm/)
	- 其它教材
		- [数学经典教材介绍 - 知乎 (zhihu.com)](https://www.zhihu.com/column/c_1292235183446392832)
- 学科
	- Discrete Mathematics
	  collapsed:: true
		- 课件
		  collapsed:: true
			- 厦门大学
				- [离散数学 - Yang Lu](https://jasonyanglu.github.io/teaching/%E7%A6%BB%E6%95%A3%E6%95%B0%E5%AD%A6_2022)
		- 命题逻辑
			- 联结词：$$ \neg \vee \wedge  $$
			- 等值演算
				- |序号| 名称 | 公式 |
				  |--|:--|--:|
				  | 1 | 双重否定 | $$ A  \Leftrightarrow \neg\neg A$$ |
				  | 2 |等幂律 | $$ A \Leftrightarrow A \vee A $$ <br /> $$ A \Leftrightarrow A \wedge A $$ |
				  | 3 |交换律 | $$ A \vee B \Leftrightarrow B \vee A $$ <br /> $$ A \wedge B \Leftrightarrow B \wedge A$$ |
				  | 4 |结合律 | $$ (A \vee B) \vee C \Leftrightarrow A \vee (B \vee C) $$<br />$$  (A \wedge B) \wedge C \Leftrightarrow A \wedge (B \wedge C) $$ |
				  | 5 |分配律 | $$ A \vee (B \wedge C) \Leftrightarrow (A \vee B) \wedge (A \vee C) $$ <br /> $$ A \wedge (B \vee C) \Leftrightarrow (A \wedge B) \vee (A \wedge C)$$ |
				  | 6 |德-摩根律 | $$ \neg (A \vee B) \Leftrightarrow \neg A \wedge \neg B $$ <br /> $$ \neg (A \wedge B) \Leftrightarrow \neg A \vee \neg B $$ |
				  | 7 |吸收率 | $$ A \vee (A \wedge B) \Leftrightarrow A $$ <br /> $$ A \wedge (A \vee B) \Leftrightarrow A $$ |
				  | 8 |零律 | $$ A \vee 1 \Leftrightarrow 1 $$ <br /> $$  A \wedge 0 \Leftrightarrow 0 $$ |
				  | 9 |同一律 | $$ A \vee 0 \Leftrightarrow A $$ <br /> $$  A \wedge 1 \Leftrightarrow A $$ |
				  | 10 |排中律 | $$ A \vee \neg A \Leftrightarrow 1 $$ |
				  | 11 |矛盾律 | $$ A \wedge \neg A \Leftrightarrow 0 $$ |
				  | 12 |蕴含等值律 | $$ A \to B \Leftrightarrow \neg A \vee B $$ |
				  | 13 |等价等值律 | $$ A \leftrightarrow B \Leftrightarrow (A \rightarrow B) \wedge (B \rightarrow A) $$ |
				  | 14 |假言易位 | $$ A \to B \Leftrightarrow \neg B \to \neg A $$ |
				  | 15 |等价否定等值律 | $$ A \leftrightarrow B \Leftrightarrow \neg A \leftrightarrow \neg B $$ |
				  | 16 |归谬论 | $$ (A \to B) \wedge (A \to \neg B) \Leftrightarrow \neg A $$ |
			- PC(Proposition calc)
				- Proposition
					- 化简规则  $$p \wedge q \Rightarrow p , p \wedge q \Rightarrow q $$
					- 附加规则  $$ p \Rightarrow p \vee q, q \Rightarrow p \vee q$$
					- 假言推理  $$ p, p \rightarrow q \Rightarrow q$$
					- 拒取式  $$ p \rightarrow q, \neg q \Rightarrow \neg p$$
					- 析取三段论  $$  p \vee q, \neg p \Rightarrow q $$
					- 合取式  $$ p, q \Rightarrow p \vee q $$
					- 假言三段论 $$ p \rightarrow q, q \rightarrow r \Rightarrow p \rightarrow r $$
					- 等价三段论 $$ p\leftrightarrow q, q \leftrightarrow r \Rightarrow p \leftrightarrow r $$
					- 构造性二难 $$ p \rightarrow q, r \rightarrow s, p \vee r \Rightarrow q \vee s $$
					- 归结式 $$ p \vee q, \neg p \vee s \Rightarrow q \vee s $$
				- 等价式
					- 否定等值
						- $$ \neg \forall xA(x) \Leftrightarrow \exist x\neg A(x)$$
						- $$\neg \exist xA(x) \Leftrightarrow \forall x\neg A(x) $$
					- 辖域收缩与扩张
						- ![image.png](../assets/image_1681300232471_0.png)
					- 分配等值
						- $$ \forall x (A(x) \wedge B(x) \Leftrightarrow \forall xA(x) \wedge \forall xB(x)$$
						- $$\exist x (A(x) \vee B(x) \Leftrightarrow \exist xA(x) \vee \exist xB(x) $$
				- Axious
					- A1: $$A \to (B \to A)$$
					- A2: $$(A\to (B \to C)) \to ((A \to B) \to (A \to C))$$
					- A3: $$( \neg A \to \neg B) \to (B \to A)$$
					- A4: $$\forall xA(x) \to A(t/x)$$
					- A5: $$ \forall x (A(x) \to B(x)) \to (\forall xA(x) \to \forall x B(x))$$ (x为任一自由变元)
					- A6: $$A \to \forall x A $$(A中无自由变元x)
					- A7: （A1到A6的全称封闭式都是FC的公理）
				- 谓词演算的推理规则
					- U: Universal, E: Existential, I: Instantiation, G: Generalization
						- 1. UI(全称量词消去) $$\forall x A(x) \Rightarrow A(x) $$ 
						  3. EI(存在量词消去) $$ \exist x A(x) \Rightarrow A(c) $$ 
						  4. UG(全称量词引入) $$  A(y) \Rightarrow \forall x A(x) $$
						  5. EG(存在量词引入) $$ A(c) \Rightarrow \exist x A(x) $$
		- 集合论
			- 基本运算
				- 并 $$ A \cup B = \{x \mid x \in A \vee x \in B\} $$
				- 交 $$ A \cap B = \{ x\mid x \in A \wedge x \in B \} $$
				- 差 $$ A - B = \{ x\mid x \in A \wedge x \notin B \}$$
				- 对称差 $$ A \oplus B = \{ x\mid (x \in A \wedge x \notin B) \vee (x \in B \wedge x \notin A)\}$$
				- P(A): A 的幂集  $$ P(A) = \{ x\mid x \subseteq A \} $$
			- 等式
				- | 序号 | 名称 | 等式 |
				  |--|:--|--:|
				  | 1 | 恒等 | $$ A \cup \phi = A, A \cap E = A $$ |
				  | 2 | 支配 | $$ A \cup E = E, A \cap \phi= \phi $$ |
				  | 3 | 幂等 | $$ A \cup A = A, A \cap A = A $$ |
				  | 4 | 双否 | $$ \sim (\sim A) = A $$ |
				  | 5 | 交换 | $$ A \cup B = B \cup A, A \cap B = B \cap A $$ |
				  | 6 | 结合 | $$ A \cup (B \cup C) = (A \cup B) \cup C, A \cap (B \cap C) = (A \cap B) \cap C $$ |
				  | 7 | 分配 | $$ A \cap (B \cup C) = (A \cap B)  \cup (A \cap C), A \cup (B \cap C) = (A \cup B)  \cap (A \cup C) $$ |
				  | 8 | 摩根 | $$ \sim(A \cup B) = \sim A \cap \sim B, \sim (A \cap B) = \sim A \cup \sim B $$ |
				  | 9 | 吸引 | $$ A \cup (A \cap B) = A, A \cap (A \cup B) = A $$ |
				  | 10 | 补律 | $$ A \cap \sim A = \phi, A \cup \sim A = E $$ |
			- 二元关系
				- 有序对
					- 定义：由两个元素$$x, y (允许x = y)$$ 按一定顺序排列成的二元组叫做一个
					  有序对, 记作 $$ \langle x, y \rangle $$ , 其中$$x$$是它的第一元素, $$y$$是它的第二元素
					- 性质：
						- $$ if  x \ne y，then \langle x, y \rangle \ne \langle y, x \rangle $$
						- $$ \langle x, y \rangle = \langle u, v \rangle \Leftrightarrow (x=u) \wedge (y = v)$$
					- 有序对中元素**有序**，集合中元素**无序**
				- 笛卡尔积
					- $$ A \times B = \{\langle  x, y \rangle |  x \in A \wedge y \in B\} $$
					- 性质：
						- $$ A\times B = \phi \Leftrightarrow (A = \phi) \vee (B = \phi) $$
						- $$ A \times B \ne B \times A (除非A = ∅或B = ∅或A = B)$$
						- $$ (A \times B) \times C \ne A \times (B \times C) (除非A = ∅或B = ∅或A = B) $$
						- 笛卡尔积对集合运算∗满足分配律,
						  ∗代表∪, ∩, −, ⊕运算
						- 设A, B, C, D为4个集合, 则有
						  $$A ⊆ C ∧ B ⊆ D ⇒ A×B ⊆ C×D$$
				- 二元关系
					- 定义：如果一个集合满足以下条件之一
						- 1. 集合非空，且它的元素都是有序对
						  2. 集合是空集
						- 则称该集合为一个**二元关系**， 记作$$R$$. 如果$$ \langle x, y\rangle \in R $$, 记为$$ xRy $$. 如果$$ \langle x, y\rangle \notin R $$, 记为$$ x\rlap{|}Ry $$
					- 定义：设A, B为集合, A×B的任何子集所定义的二元关系叫作从A到
					  B的二元关系, 特别当A = B时则叫作A上的二元关系
					- 定义：
						- 空关系：∅
						- 全域关关系：$$ E_{A} = \{\langle x, y \rangle | x, y \in A\}  = A \times A$$
						- 恒等关系：$$ I_{A} = \{\langle x, x \rangle | x \in A\}  $$
					- 性质
						- 自反
							- $$ \forall x(x \in A \rightarrow \langle x, x \rangle \in R) $$
						- 反自反
							- $$ \forall x(x \in A \rightarrow \langle x, x \rangle \notin R) $$
						- 对称
							- $$ \forall x \forall y(x, y \in A \wedge \langle x, y \rangle \in R \rightarrow \langle y, x \rangle \in R) $$
						- 反对称
							- $$ \forall x \forall y(x, y \in A \wedge \langle x, y \rangle \in R \wedge \langle y, x \rangle \in R \rightarrow x = y) $$
							- $$ \forall x \forall y(x, y \in A \wedge \langle x, y \rangle \in R \wedge x \ne y \rightarrow \langle y, x \rangle \notin R) $$
						- 传递
							- $$ \forall x \forall y \forall z(x,y,x \in A \wedge \langle x, y\rangle \in R \wedge \langle y, z\rangle \in R \rightarrow \langle x, z \rangle \in R) $$
				- 关系的运算
				  collapsed:: true
					- 关系R的定义域dom R, 值域ran R和域fld R是
					  $$dom R = \{x|∃y(xRy)\} $$
					  $$ran R = \{y|∃x(xRy)\}$$
					  $$fld R = dom R ∪ ran R$$
					- 设R为二元关系,R的逆关系,简称R的逆, 记作$$ R^{-1} $$
						- $$ R^{-1} = \{\langle x,y \rangle | yRx\} $$
					- 设F, G为二元关系, G对F的右复合记为F ◦ G(读作F圈G)
						- $$ F\circ G = \{\langle x, y \rangle | \exist t(xFt \wedge tGy)\} $$
					- 逆关系的分配律
						- $$(R \cup S)^{-1} = R^{-1} \cup S^{-1}$$
						- $$(R \cap S)^{-1} = R^{-1} \cap S^{-1}$$
					- 设F,G,H是任意关系，则有
						- $$ (F^{-1})^{-1} = F $$
						- $$ dom F^{-1} = ran F, ran F^{-1} = dom F $$
						- $$ (F \circ G) \circ H = F \circ (G \circ H) $$
						- $$ (F \circ G)^{-1} = G^{-1} \circ F^{-1} $$
						- $$ (\sim R)^{-1} = \sim (R^{-1}) $$
					- 设R为A上的关系, 则
						- $$ R \circ I_{A} = I_{A} \circ R = R $$
					- 设R为A上的关系, n为自然数, 则R的n次幂是
						- 1. $$ R^{0} = \{ \langle x, x \rangle | x \in A \} = I_{A} $$
						  2. $$ R^{n + 1} = R^{n} \circ R, n \ge 0  $$
					- 关系矩阵
						- $$ M_{R^{-1}} = M_{R}^{T} $$
						- $$ M_{R_{1} \circ R_{2}} =  M_{R_{1}} M_{R_{2}}$$
				- 函数
					- ![](https://img-blog.csdnimg.cn/img_convert/396872732049ad6e0bad5e87d30707e0.png)
				- 等价和偏序
				  collapsed:: true
					- 等价
						- 定义：
							- 设$$ R \subseteq A \times A且 A \ne \phi $$, 若$$R$$是**自反、对称、传递**的，则称$$R$$是$$A$$上的**等价关系**
								- 若$$ \langle x, y \rangle \in R $$, 则称$$ x等价于y $$, 记作 $$ x \sim y $$
							- 若$$R$$是非空集合$$A$$上的等价关系，$$ x \in A $$, $$x$$的等价类$$[x]_{R} = \{ y| y \in A \wedge xRy \} $$
					- 偏序
						- 定义：
							- 设$$R \subseteq A \times A$$, 若R是**自反、反对称、传递**的，则称$$R$$为$$A$$上的**偏序关系**，记为$$\preceq$$
								- A和A上的偏序关系R一起叫做偏序集，记作$$(A, R)$$
		- 自考题型
			- 选择：15 * 2 = 30
			- 填空：10 * 2 = 20
			- 计算： 5 * 6 = 30
			- 证明： 3 * 7 = 21
			- 应用：2 * 7 = 14
			- 10问答
				- 真值表判定可满足式、逻辑等价式
				- 求主范式
				- 求关系矩阵和闭包，求r(R), s(R), t(R)
					- 自反r(R): $$ R \cup I_{A} $$
					- 对称s(R): $$ R \cup R^{-1} $$
					- 传递t(R): $$ R \cup R^{2} \cup R^{3} $$
				- Kruskal算法，画最小生成树，详细过程，计算权
				- 已知有向图，求邻接矩阵，计算通路、回路
				- 使用二叉树表示算术表达式，给出前序、中序、后序遍历序列
				- 已知集合和运算，画哈斯图，求极大、极小、最大、最小元，判断是否为格
				- 证明构成交换群；给定群，
				- 命题符号化，并证明推理
				- 无向简单图，证明同构，证明n度顶点个数
		- 脑图
			- 命题与命题公式
				- ![命题与命题公式.webp](../assets/命题与命题公式_1681072958088_0.webp)
			- 命题逻辑的推理理论
				- ![命题逻辑的推理理论.webp](../assets/命题逻辑的推理理论_1681073083582_0.webp){:height 329, :width 485}
			- 谓词逻辑
				- ![谓词逻辑.webp](../assets/谓词逻辑_1681073125643_0.webp)
			- 集合
				- ![集合.webp](../assets/集合_1681073181321_0.webp)
			- 关系与函数
				- ![关系与函数.webp](../assets/关系与函数_1681073222096_0.webp)
			- 代数系统的一般概念
				- ![代数系统的一般概念.webp](../assets/代数系统的一般概念_1681073302959_0.webp)
			- 格与布尔代数
				- ![格与布尔代数.webp](../assets/格与布尔代数_1681073343907_0.webp)
			- 图
				- ![图.webp](../assets/图_1681073399738_0.webp)
			- 图的应用
				- ![图的应用.webp](../assets/图的应用_1681073414306_0.webp)
	- 概率论与数理统计
	  collapsed:: true
		- https://zhuanlan.zhihu.com/p/42859784
		- 大数定律和中心极限定理
			- **在独立同分布条件下的随即变量平均值的表现**
			- $$ S_{n} = \sum_{i=1}^{n}X_{i} $$
		- 大数定律
			- 样本容量极大时，**样本均值收敛到总体均值** => 期望 $$ \bar X\approx\mu $$
			- $$ \frac{1}{n}S_{n} - E(X) \overset{P}{\rightarrow}  0 $$
		- 中心极限定理
			- 当样本足够大时，**样本均值的抽样分布趋近于正态分布**（这和样本所属的总体的分布类型无关）
			- $$ \sqrt{n}(\frac{S_{n}}{n} - E(X)) \overset{D}{\rightarrow} N(0, \sum) $$
			- $$ \bar X\approx\mu+\frac{\sigma}{\sqrt n}\cdot N(0,1) $$
		- 事件的运算及关系
			- ![](http://exp-picture.cdn.bcebos.com/955ea0e434daf05ecb25c9c6751d96d81819e55d.jpg?x-bce-process=image%2Fcrop%2Cx_0%2Cy_0%2Cw_762%2Ch_491%2Fformat%2Cf_auto%2Fquality%2Cq_80)
			- A与B的差事件
				- $$ A - B = A \overline B = A \cup B - B = A - AB$$
		- P
			- 统计定义：当随机试验的次数增加时，随机事件A发生的频率f(x)趋近的稳定值p称为概率，记为P(x) = p
			- 公理化定义：设随机试验对应的样本空间为S. 对每个事件A， 定义P(A), 满足：
				- 1. 非负性： $$ P(A) \ge 0 $$
				- 2. 规范性： $$ P(S) = 1$$
				- 3. 可列可加性： $$ A_{1}, A_{2}... 两两互斥，即A_{1}A_{2} = \phi, i \ne j, 则 P(\bigcup_{i=1}^{\infty}A_{i}) = \sum_{i=1}^{\infty}P(A_{i}) $$
			- 性质：
				- 1. $$ P(\phi) = 0 $$
				- 2. $$ P(A) = 1 - P(\overline{A}) $$
				- 3. $$ A_{1}A_{2} = \phi, i \ne j, 则 P(\bigcup_{i=1}^{n}A_{i}) = \sum_{i=1}^{n}P(A_{i}) (有限可加性)$$
				- 4. 减法公式：$$  若 A \sub B, 则 P(B - A) = P(B) - P(A). 一般情况下，P(B - A) = P(B) - P(AB) $$
				- 5. 加法公式：$$ P(A \cup B) = P(A) + P(B) - P(AB) $$
					- 5.1 $$ P(A \cup B \cup C) = P(A) + P(B) + P(C) - P(AB) - P(AC) - P(BC) + P(ABC) $$
					- 5.2 $$ 一般情况，略 $$
		- 古典概型
			- 不放回抽样：
				- 有N个球，其中a个白球，b = N - a个黄球，采用不放回抽样取n个球(n <= N), 记 $$ A_{k} = \{恰好取到k个白球\} (k \le a), 则 $$
					- $$ P(A_{k}) = \frac{C_{a}^{k}C_{b}^{n - k}}{C_{N}^{n}} ,  其中 C_{N}^{n} = \binom {N}{n} = \frac{N!}{n!(N-n)!} $$
		- 条件概率
			- ![image.png](../assets/image_1680518703378_0.png)
			- 定义：
				- $$ P(B|A) = \frac{P(AB)}{P(A)}, P(A) \ne 0 $$
			- 性质：$$ P(\bullet |A) $$是概率
				- 非负性：$$ P(B|A) \ge 0 $$
				- 规范性：$$ P(S|A) = 1 $$
				- 可列可加性：$$ B_{1}, B_{2} ... B_{i}B_{j} = \phi, i \ne j, 则 P(\bigcup_{i=1}^{\infty}B_{i} | A) = \sum_{i=1}^{\infty}P(B_{i} | A) $$
			- 条件概率$$ P(\bullet |A) $$具有概率的所有性质
				- $$ P(B|A) = 1 - P(\overline B | A) $$
				- $$ P(B \cup C | A) = P(B|A) + P(C|A) - P(BC|A) $$
				- $$ B \supset C  \Rightarrow P(B|A) \ge P(C|A)$$
			- 乘法公式
				- $$ P(AB) = P(A)·P(B|A) = P(B)·P(A|B) $$
				- $$P(ABC) = P(A)·P(B|A)·P(C|AB) $$
		- 全概率公式与贝叶斯公式
			- 定义：$$称 B_{1}, B_{2}, ..., B_{n}为S的一个划分， 若$$
				- 1. 不漏 $$ B_{1} \cup B_{2} ··· \cup B_{n} = S$$
				- 2. 不重 $$ B_{i}B_{i} = \phi, i \ne j $$
			- 全概率公式：$$ P(A) = \sum_{j=1}^{n}P(B_{j})·P(A|B_{j}) $$
				- 设 $$ P(B_{j}) = p_{j}, P(A|B_{j}) = q_{j}, j = 1, 2, ..., n, 则 P(A) = \sum_{j=1}^{n} p_{j}q_{j} $$
			- Bayes公式：$$ P(B_{i} | A) = \frac{p_{i}q_{i}}{\sum_{j=1}^{n}p_{j}q_{j}} = \frac{P(B_{i})P(A|B_{i})}{\sum_{j=1}^{n}P(B_{j})P(A|B_{j})}$$
		- 事件的独立性
			- 定义：设A, B是两随机事件，如果 $$ P(AB) = P(A)P(B) $$, 则称A, B相互独立
			- 若$$ P(A) > 0, P(B) > 0, 则 P(AB) = P(A)P(B) \Leftrightarrow P(B|A) = P(B) \Leftrightarrow P(A|B) = P(A) $$
			- 如下等价
				- $$A, B相互独立 \Leftrightarrow \overline A, B相互独立 \Leftrightarrow A, \overline B相互独立 \Leftrightarrow \overline A, \overline B 相互独立$$
		- 随机变量
		  collapsed:: true
			- 定义：设随机试验的样本空间为S， 若$$ X = X(e) $$ 为定义在S上的实值单值函数，则称$$X(e)$$为随机变量, 简写为$$X$$
			- 随机事件可以表示为 $$ A = \{ e: X(e) \in I \} = \{ X \in I \}, I \sub R $$
			- ![image.png](../assets/image_1680528359308_0.png)
			- 离散型
				- 定义：若随机变量X的取值为有限个或可数个，则称X为离散型随机变量
				- 概率分布律
					- 内容：$$  $$
						- \begin{cases}随机变量的所有可能取值
						   \\取每个可能取值相应的概率
						  \end{cases}
					- 性质： $$ p_{k} \ge 0, \sum_{k=1}^{+\infty} p_{k} = 1 $$
					- 另一表示形式：$$ P(X = x_{k}) = p_{k}, k =  1, 2, ... $$
				- 0-1分布
					- 定义：随机变量只能取0(概率为1 - p)，1(概率为p)两个值；其中 $$ 0 < p < 1 $$, 就称X服从参数为p的0-1分布（或两点分布），记为$$ X \sim 0 - 1(p) 或 X  \sim B(1, p) $$
					- 设试验$$E$$只有两个可能的结果：$$A或\overline A, 且 P(A) = p, 0<p<1. $$将$$E$$独立地重复地进行$$n$$次，称这一串重复的独立试验为$$n$$重贝努利试验
				- 二项分布
					- 定义：若$$ X $$的概率分布律为 $$ P(X = k) = C_{n}^{k} p^{k}(1-p)^{n-k}, k = 0, 1,...,n, $$其中 $$ n \ge 1, 0 < p < 1 $$, 就称$$X$$服从参数为$$n, p$$的二项分布（Binomial）, 记为 $$ X \sim B(n, p) $$
					- 可以证明：$$  1 = (p+q)^{n} = \sum_{k=0}^{n}C_{n}^{k}p^{k}q^{n-k}, 其中q = 1- p $$
				- 泊松分布
					- 定义：若$$X$$的概率分布律为 $$ P(X = k) = \frac{\lambda^{k}e^{-\lambda}}{k!}, k = 0, 1, 2, ... , $$其中 $$ \lambda > 0 $$, 就称$$ X $$服从参数为 $$ \lambda $$的泊松分布（Poisson）, 记为 $$ X \sim \pi(\lambda) $$ 或 $$ X \sim P(\lambda) $$
						- 根据泰勒展开式可得：$$ e^{\lambda} = \sum_{k=0}^{+ \infty } \frac{\lambda^{k}}{k!}$$
					- 用途
						- 某人一天收到的微信数量
						- 来到某公交车站的乘客数量
					- 如果某事件以固定强度$$ \lambda $$, 随机且独立地出现，该事件在单位时间内出现的次数(个数)可以看成是服从泊松分布
					- 二项分布与泊松分布有如下近似公式
						- 当 $$ n > 10, p < 0.1时， C_{n}^{k}p^{k}(1-p)^{n-k} \approx \frac{\lambda^{k}e^{-\lambda}}{k!}, 其中 \lambda = np$$
				- 几何分布
					- 定义：若$$X$$的概率分布律为 $$ P(X = k) = p(1 - p)^{k-1}, k = 1,2,3,..., 其中 0< p < 1 $$, 称$$ X $$服从参数为$$ p $$的几何分布(Geometric), 记为 $$ X \sim Gemo(p) $$
					- 用途：在重复多次和贝努利试验里，试验进行到某种结果出现第一次为止，此时的试验总数服从几何分布
				- 分布函数$$ F(x) $$
					- 定义：随机变量$$X$$, 对任意实数$$x$$, 称函数 $$ F(x) = P(X \le x) $$为$$ X $$的概率分布函数，简称分布函数
					- 性质:
						- $$ 0 \le F(x) \le 1 $$
						- $$ F(x)单调不减 $$
						- $$ F(-\infty) = 0, F(+\infty) = 1 $$
						- $$ F(x)是右连续函数，即F(x + 0) = F(x) $$
					- 任何随机变量都有相应的分布函数
					- 几何意义
					- ![image.png](../assets/image_1680540952516_0.png)
					- 用途：可以给出随机变量落入任意一个范围的可能性
					- ![image.png](../assets/image_1680541418039_0.png)
			- 连续型
				- 定义：对于随机变量$$X$$的分布函数 $$ F(x) $$, 若存在非负的函数$$ f(x) $$, 使对于任意实数 $$ x $$有： $$F(x) = \int_{-\infty}^{x}f(t)\delta t $$，则称$$ X $$为连续型随机变量，其中$$ f(x)$$称为$$X$$的概率密度函数，简称概率密度
				- 性质：
					- $$ f(x) \ge 0 $$
					- $$  \int_{-\infty}^{+\infty}f(x)\delta x = 1$$
					- 对于任意实数$$x_{1}, x_{2}(x_{1} < x_{2}), P(x_{1} < X \le x_{2}) = \int_{x_{1}}^{x_{2}}f(t)\delta t$$
					- 在$$ f(x) $$连续点$$x$$, $$ {F}'(x) = f(x), P(x < X \le x + \Delta x) \approx f(x)·\Delta x $$; 这表示$$ X $$落在点 $$x$$附近$$(x, x + \Delta x]$$的概率近似等于$$f(x)\Delta x$$
				- 均匀分布
					- 定义：若$$ X $$的概率密度函数为 $$ f(x) =  $$
				-
		- 马尔科夫链
			- [简述马尔可夫链【通俗易懂】 - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/448575579)
		- 假设检定
		  collapsed:: true
			-
		- 自考题型
		  collapsed:: true
			- 选择 10 * 2 = 20
			- 填空 15 * 2 = 30
			- 计算 2 * 8 = 16
				- 已知$$ f(x, y) $$。求$$ f(x, y) $$分式里未知常数；求$$P(X, Y)$$
				-
			- 综合 2 * 12 = 24
				- 已知$$ X = f_{X}(x), Y = g(X)。 求F(x), P(a < x < b), f_{Y}(y) $$
				- 已知 $$(X,Y)$$分布率。判断$$X, Y$$相关或独立；求关于$$X,Y$$边缘分布；求$$g(X, Y)$$分布律及$$P\{X, Y\}$$
				-
			- 应用 1 * 10 = 10
				- 已知$$ X \sim 某分布 $$。求整体和样本均值、方差；求置信区间
				-
		- 公式汇总
		  collapsed:: true
			- ![form0.jpeg](../assets/form0_1681114072707_0.jpeg)
			- ![form1.jpeg](../assets/form1_1681114013620_0.jpeg){:height 288, :width 625} ![form2.jpeg](../assets/form2_1681114018012_0.jpeg)
				- ![image.png](../assets/image_1681156451397_0.png)
				- 切比雪夫不等式
					- $$ P[|X - E(X)|\ge \varepsilon] \le \frac{D(X)}{\varepsilon^{2}} $$
				-
			- 摸球
			  collapsed:: true
				- $$ C_{N}^{m}  = \frac{N!}{m!·(N - m)!}  注意：(0! = 1)$$
				- 无放回
					- 公式：$$ P = \frac{C_{条件1总}^{条件1取} \times C_{条件2总}^{条件2取} \times ... \times C_{条件N总}^{条件N取}}{C_{总}^{取}} $$
					- case: 4红3白共7球，无放回摸4次，求摸出2红2白概率
						- $$ P = \frac{C_{4}^{2} \times C_{3}^{2}}{C_{7}^{4}} $$
				- 有放回
					- 已知：
						- 1. K种颜色球，代号分别为$$ A_{1}、A_{1}...A_{k} $$
						  2. 抽一次，出现的概率分别为 $$ p_{1}、p_{2}...p_{k} $$
						  3. 摸出各种球的个数分别为 $$ n_{1}、n_{2}...n_{k} $$
					- 公式：$$ P = \frac {(n_{1} + n_{2} + ... + n_{k})!}{n_{1}!n_{2}!...n_{k}!}p_{1}^{n_{1}}p_{2}^{n_{2}}...p_{k}^{n_{k}} $$
					- case:
						- 5红6白共11球，有放回摸5次，求摸2红3白概率
							- $$ P = \frac{(2 + 3)!}{2!3!}(\frac{5}{11})^{2}(\frac{6}{11})^{3} $$
						- 2美3丑共5只母猴，随机挑一只帮她抓虱子，共抓101次，求给美猴抓50次、丑猴抓51次的概率
							- $$ P = \frac{(50 + 51)!}{50!51!}(\frac{2}{5})^{50}(\frac{3}{5})^{51} $$
			- 画图求概率
			  collapsed:: true
				- 1. 表现已知条件
				  2. 表现待求概率的条件
				  3. 找出1、2步重合部分
			- 条件概率
			  collapsed:: true
				- 公式：$$ P(B|A) = \frac{P(AB)}{P(A)} $$
				- 步骤：
					- 设已知事件为A, 要求的部分为事件B
				- case:
					- 小明考试80分以上概率80%，60分以上概率85%，已知本次才试没挂，求得80分以上概率
						- 设A 60分，B 80分， $$ P(A) = 0.85, P(B) = 0.8 $$
						  由题可知：P(AB) = P(B)
						  P(B|A) = P(AB)/P(A) = P(B)/P(A)
					- 今年发洪水概率80%，今明两年至少 有一年发洪水概率85%，假如今年没发洪水，求明年发洪水概率
						- 设 A = 今年没发洪水，B = 明年发洪水
						  $$P(A) = 0.2, P(\overline A \cup B) = 0.85$$
						  $$ P(\overline AB) =  $$
						  $$ P(B|A) =  $$
			- 全概率公式
			  collapsed:: true
				- 公式：
					- 已知$$ A、B... $$等个体均可能发生某事
					  $$ P(发生某事) = P(A出现)· P(A发生某事) + P(B出现)· P(B发生某事) ...$$
					- case:
						- 客车中20%高速客车，80%普通客车，高速客车故障率0.002，普通客车故障率0.01。求客车发生故障概率
							- $$ P(客车发生故障) = P(高速客车出现)· P(高速客车发生故障) + P(普通客车出现)· P(普通客车发生某事) $$
							  $$ = 0.2 * 0.002 + 0.8 * 0.01 $$
			- 贝叶斯公式
			  collapsed:: true
				- 公式：
					- A、B...等个体均可能发生某事，则
					  $$ P(已知有个体发生某事时，是A发生的) = \frac{P(A出现)·P(A发生某事)}{P(发生某事)} $$
				- case:
					- 客车中20%高速客车，80%普通客车，高速客车故障率0.002，普通客车故障率0.01。现已知有客车发生故障，求故障是高速客车的概率
						- A: 高速，B: 普通
						  $$ P = \frac{0.2*0.002}{0.2 * 0.002 + 0.8 * 0.01} $$
			- 一维随机变量
			  collapsed:: true
				- 公式：
					- $$ f_{X}(x) = F_{X}'(x) $$
					  $$ F_{X}(x) = \int_{-\infty}^{x}f_{X}(x)\mathrm{d}x $$
					  $$ P(a < X < b) = F_{X}(b) - F_{X}(a) = \int_{a}^{b}f_{X}(x)\mathrm{d}x$$
					  $$ F_{X}(-\infty) = 0, F_{X}(+\infty) = 1, \int_{-\infty}^{+\infty}f_{X}(x)\mathrm{d}x =1 $$
					  $$ F_{上}(分段点) = F_{下}(分段点) $$
				- 已知$$F_{X}(x)$$或$$f_{X}(x)$$其中一项，求另一项
					- case:
				- 已知$$F_{X}(x)$$或$$f_{X}(x)$$其中一项，求P
					- case:
				- 已知$$F_{X}(x)$$或$$f_{X}(x)$$中含未知数，求未知数
				- 求分布列
				- 已知分布列，其中含有未知数，求未知数
			- 一维随机变量函数
			  collapsed:: true
				- 已知X分布列，求Y分布列
					- 步骤：
						- 1. 根据$$X$$的所有取值，计算$$Y$$的所有取值
						  2. 将表格里$$X$$那一列对应换成$$Y$$
						  3. 如表头有重复，则加总重复表头对应的概率值
					- case:
						- 求$$ Y = X^{2} + 1分布列 $$
				- 已知$$ F_{X}(x) $$, 求 $$ F_{Y}(y) $$
					- 步骤：
						- 1. 写出 $$ X = ?Y $$
						  2. 用$$ ?y $$替换 $$ F_{X}(x) $$中的$$x$$, 结果为$$ F_{X}(?y) $$
						  3. 判断$$ ?y $$中是否有负号
						       若无，则$$ F_{Y}(y) = F_{X}(?y) $$
						       若有，则$$ F_{Y}(y) = 1 - F_{X}(?y) $$
						  4. 判断分段取值范围是否为y，如y/2则需要转换成y
				- 已知$$ f_{X}(x) $$, 求 $$ f_{Y}(y) $$
					- 步骤：
						- 1. 写出 $$ X = ?Y $$
						  2. 用$$ ?y $$替换 $$ f_{X}(x) $$中的$$x$$, 结果为$$ f_{X}(?y) $$; 转换分段取值范围的y，比如y/2 > 1 => y > 2
						  3. 令$$ f_{Y} = (?y)'·f_{X}(?y) $$
						  4.判断$$ ?y $$中是否有负号
						       若无，则$$ F_{Y}(y) = f_{Y} $$
						       若有，则$$ F_{Y}(y) = -f_{Y} $$
			- 符合某分布，求概率
				- 均匀 $$ U[a,b] $$
					- 公式：$$ P = \frac{满足要求长度}{总长度} $$
					- case:
						- 设$$X$$在[2, 5]上服从均匀分布，求$$P(X>3)$$
							- $$ P(X>3) = \frac{5-3}{5-2} = \frac{2}{3} $$
						- 设$$X$$在[2, 5]上服从均匀分布，求$$P(X<3)$$
						- $$ P(X<3) = \frac{3-2}{5-2} = \frac{1}{3} $$
				- 泊松 $$ \pi(\lambda), Pois(\lambda) $$
					- 公式：$$ P(X = x) = \frac{\lambda^{x}}{x!}e^{-\lambda}$$
					- case: 某电话交换台每分钟接到的呼叫次数服从参数为5的泊松分布
						- 求在一分钟内呼叫2次的概率
							- $$ P(X = 2) = \frac{5^{2}}{2!}e^{-5}$$
						- 求在一分钟内呼叫不起过3次的概率
							- $$ P(X \le 3) = P(X = 0) + P(X = 1) + P(X = 2) + P(X = 3)$$
				- 二项 $$ B[n, p] $$
					- 公式：$$ P(X=x) = C_{n}^{x}p^{x}(1-p)^{n-x} $$
					- case:
						- 重复投5次硬币，求正面朝上次数为3次的概率
							- 已知$$ n = 5, x = 3, P（正面朝上） = 1/2 $$
							  $$ P(X=3) = C_{5}^{3}(1/2)^{3}(1-1/2)^{5-3} = 5/16 $$
						- 从2红1绿3个球里有放回摸3次，求摸到2次红球的概率
							- 已知$$ n = 3, x = 2, P(摸到红球) = 2/3 $$
				- 指数 $$ E(\lambda) $$
					- 公式：$$   $$
					- case:
				- 正态 $$ N(\mu, \sigma^{2}) $$
					- 公式：
			- 正态分布图像
			- 二维随机变量
			  collapsed:: true
				- 已知二维离散型分布律，求???
				- 已知二维离散型分布律，判断独立性(或已知X、Y相互独立，分布律里未知量a, b)
					- 如果任意$$ x_{i}, y_{i} $$均满足$$ P(X = x_{i}, Y = y_{i}) = P(X = x_{i})·P(Y = y_{i}) $$, 那么X、Y相互独立；否则X、Y不相互独立
				- 已知$$F(x, y)$$, 求$$ f(x, y) $$
					- 公式：$$ f(x, y) = \frac{\partial^{2}F(x, y)}{\partial x \partial y} $$
				- 已知$$f(x, y)$$, 求$$ F(x, y) $$
					- 步骤
						- 1. 找出$$ f(x, y) $$不等于0时$$x$$的范围和$$y$$的范围
						  2. 计算$$\int_{g_{1}(y)}^{x}\mathrm{d}u\int_{h_{1}(u)}{y}f(u, v)\mathrm{d}v$$,结果记为$$1$$
						  3.
						-
			- 期望、方差
				- 离散
					- $$ E(X) = \sum x_{i}p_{i} $$
					- $$ D(X) = \sum[x_{i} - E(X)]^2·p_{i} $$
				- 连续
					- $$ E(X) = \int_{-\infty}^{+\infty}xf(x)\mathrm{d}x $$
					- $$ D(X) = E(X^{2}) - E^{2}(X) $$
				- 已知$$ Y = g(X), 求E(Y) $$
					- 离散：$$ E(Y) = \sum g(x_{i})p_{i} $$
						- case:  已知$$Y = 2X - 1, 求E(Y)$$
							- $$ E(Y) = \sum g(x_{i})p_{i}$$
							- $$ = \sum(2x_{i} - 1)pi $$
					- 连续：$$ E(Y) = \int_{-\infty}^{+\infty}g(x)·f(x)\mathrm{d}x $$
						- case:  已知$$Y = X^{2}，求E(Y)$$
							- $$ E(Y) = \int_{-\infty}^{+\infty}g(x)·f(x)\mathrm{d}x$$
							- $$ = \int_{-\infty}^{+\infty}x^{2}·f(x)\mathrm{d}x $$
				- 复杂运算
					- |  $$E$$ | $$D$$ |
					  |  ----  | ----  |
					  | $$ E(C) = C $$  | D(C) = 0 |
					  | $$ E(CX) = CE(X) $$  | D(CX) = C^{2}D(X) |
					  | $$ E(X \pm Y) = E(X) \pm E(Y) $$  | D(X \pm Y) = D(X) \pm D(Y) (X、Y相互独立时)|
					  | $$ E(XY) = E(X)E(Y) (X、Y相互独立时) $$  | |
					  | $$ D(X) = E(X^{2}) - E^{2}(X) $$ |
					- case: 已知分布律，求$$E(2X_{2} - 5), D(\sqrt{7}X - 5)$$
						- $$ E(2X^{2} - 5) = E(2X^{2}) -E(5) $$
						-
			- 协方差、相关系数
				- 公式：
					- $$ Cov(X, Y) = E\{[X - E(X)][Y-E(Y)]\} $$
					- $$ \sum_{i=1}^{n}X_{i} \sim N(n\mu, n\sigma^{2}) $$
					- ![image.png](../assets/image_1681234984333_0.png)
				- 多项独立同分布，求总和
					- 公式： ![image.png](../assets/image_1681236019891_0.png)
					- case:
						- 商品周销量期望1，方差1，各周销量相互独立 ；求年销量(52周)在50到70件之间的概率
							- n = 52, 年销量Y，E(X) = 1, D(X) = 1
							- ![image.png](../assets/image_1681236343957_0.png)
						- 每箱商品质量独立同分布，每箱平均重50kg, 标准差5kg. 若用最大载重量5000kg汽车承运，求每辆车最多装多少箱，以保证不超载概率大于0.997？$$(\Phi(2) = 0,997)$$
							- ![image.png](../assets/image_1681236662867_0.png)
					-
			- 数理统计
				- 求未知参数的矩估计
				  collapsed:: true
					- 公式或步骤：
						- 1. 写出$$E(X)$$与待求未知数的关系
						  2. 将1的结果整理成$$未知数=?E(X)$$的形式
						  3. 根据给出的样本，算出实际的$$E(X)$$
						  4. 求出未知数
					- case：
						- 已知产品合格率P，每次从中随机抽10件进行检验，$$X_{i}$$表示第$$i$$次抽出的10件产品中次品的个数，则可认为$$X_{1}, X_{2},..., X_{n}$$独立同分布，总体分布是$$B(10, P)$$, 求P的矩估计
							- 1. $$ E(X) = np = 10P $$
							  2. $$ P = E(X) / 10 $$
							  3. $$ E(X) =  (X_{1} + X_{2} + ... + X_{n}) / n$$
							  4. $$ \hat P = (X_{1} + X_{2} + ... + X_{n}) / 10n $$
						-
				- 假设检验
					- 判断单项参数与某数值关系
					- ![image.png](../assets/image_1681303485436_0.png)
					- 判断两项参数间的关系
					- ![image.png](../assets/image_1681303249229_0.png)
					- 对于成对数据的检验
					- ![image.png](../assets/image_1681379075135_0.png)
					- P值检验
					- ![image.png](../assets/image_1681379158646_0.png)
	- 高等数学
	  collapsed:: true
		- 常用公式
			- [单变量微积分](https://learnku.com/docs/svcalculus)
			- [积分公式](https://www.zhihu.com/question/447600626/answer/1765180014)
		- Definite Integrals
			- 公式：$$ \int_{a}^{b}2x\mathrm{d}x $$
				- dx just means an** arbitrarily small change in x**
				- sum: $$ \int_{}{} $$
				- differential: $$ \mathrm{d}$$
				- ![integral notation](https://www.mathsisfun.com/calculus/images/integral-notation-1.svg)
		- 微分方程
			-
	- 线性代数
		- ![](https://pic1.zhimg.com/80/v2-d283d3fbf03b33a9487fe9837fa29486_1440w.webp?source=1def8aca)
		- Vectors
			- 定义
				- A vector **v** is a set of numbers
			- 性质
				- For any vectors **u, v** and **w** in $$\Re^{n}$$, and any scalars a and b
					- **u + v = v + u**
					- **(u + v) + w = u + (v + w)**
					- There is an element **0** in $$\Re^{n}$$ such that **0 + u = u**
					- There is an element **u'** in $$\Re^{n}$$ such that **u' + u = 0**
					- 1**u = u**
					- (ab)**u** = a(b**u**)
					- a**(u + v)** = a**u** + a**v**
					- (a + b)**u** = a**u** + b**u**
		- Matrix-vector Product
			- A and B are $$m\times n$$ matrices,  **u** and **v** are vectors in $$\Re^{2}$$, and $$c$$ is a scalar
				- $$A(u + v) = Au + Av$$
				- $$ A(cu) = c(Au) = (cA)u $$
				- $$(A+B)u = Au + Bu$$
				- A**0** is the $$m \times 1$$ zero vector
				- **0**$$v$$ is also the $$m \times 1$$ zero vector
				- $$ I_{n}v = v $$
				- $$\sqrt[n]{x}$$
	- 群论
	  collapsed:: true
		- 通俗
			- [物理学中的群论 · 入门篇 第〇章：概述 - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/536407679)
	- 拓扑
		- 开集
			- 请问开集和闭集如何理解？ - sola的回答 - 知乎
			  https://www.zhihu.com/question/378515815/answer/1071427708
- Any Note
	- Geometric Sequences and Sums
	  collapsed:: true
		- 定义：$$ \{a, ar, ar^{2}, ar^{3}, ...\} $$
			- **a** is the first term
			- **r** is the factor between the terms(called the "common ratio"), and **r** should not be **0**
		- term: $$ x_{n} = ar^{n-1} (x_{1} = ar^{0})$$
		- Summing: $$a + ar + ar^{2} + ... + ar^{n-1}$$
		- $$ \sum_{k=0}^{n-1}(ar^{k}) = a\begin{pmatrix}\frac{1-r^n}{1-r} \end{pmatrix} $$
		- Infinite Geometric Series
			- $$ \sum_{k=0}^{\infty}(ar^{k}) = a\begin{pmatrix}\frac{1}{1-r} \end{pmatrix} $$
				- $$ -1< r < 1, r  \ne 0 $$
	- Geometric Mean
	  collapsed:: true
		- or **n** numbers: multiply them all together and then take the **n**th root
		- $$ \sqrt[n]{a_{1}\times a_{2} ... \times a_{n}} $$
		-
	- https://www.cnblogs.com/gonghr/p/15234188.html 群环域
	- ![bigdata.jpg](../assets/bigdata_1684953946362_0.jpg)
	- Gamma function
		- $$ \Gamma(s) = \int_{0}^{\infty}e^{-t}t^{s-1}\mathrm{d}t $$
	- ![group.png](../assets/group_1684953895185_0.png)
	- ![group1.png](../assets/group1_1684954386065_0.png)
	- ![group2.png](../assets/group2_1684954400120_0.png)
	- ![group3.png](../assets/group3_1684954411058_0.png)
	- ![space.jpg](../assets/space_1684953073548_0.jpg){:height 379, :width 741}
	- ![space1.png](../assets/space1_1684954358841_0.png)
	-
	- ![image.png](../assets/image_1687926657643_0.png)
	- https://blog.sciencenet.cn/blog-391825-1366498.html
	- [从度量空间到拓扑空间 - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/54516805)
	- [什么是数学中的各种空间：线性空间、度量空间、赋范空间、内积空间、欧几里得空间、希尔伯特空间、巴拿赫空间？ - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/541226732)
	- [数学中的各种空间 - 简书 (jianshu.com)](https://www.jianshu.com/p/f14012775d6a)
	- 空间关系
		- **线性空间**：只有加法和数乘。
		- **度量空间**：定义了距离。
		- **赋范空间**：定义了范数。
		- **线性赋范空间**：线性空间 + 范数。
		- **线性度量空间**：线性空间 + 距离。
		- **内积空间**：定义了内积。
		- **拓扑空间**：定义了交并运算。
		- **巴拿赫空间**：赋范空间 + 完备性。
		- **希尔伯特空间**：内积空间(无限维) + 完备性。
		- 注：范数比距离更具体，内积比范数更具体
	- 级数收敛判断
		- ![](https://pic2.zhimg.com/80/v2-b20a80141ce2691e53f37bab687a5735_1440w.webp){:height 913, :width 718}
		- ![](https://pic1.zhimg.com/80/v2-761cf86c338e30025e8c847927cc7c53_1440w.webp?source=1def8aca){:height 1284, :width 718}
		- ![](https://pic1.zhimg.com/80/v2-99cff1a475c875f1a60350a43d82accc_1440w.webp?source=1def8aca)
	- 图的欧拉公式
		- 令 $$ G = (V, E) $$为一个连通的平面图(planar graph, 除在顶点外，任意两边不交叉)，V顶点集合，E边集合，R面集合， $$ |V|  - |E| + |R| = 2 $$
	- map vs function
		- https://math.stackexchange.com/questions/1912970/intutive-difference-between-linear-map-transformation-vs-linear-function
		- https://solitaryroad.com/c303.html
	- SO(3), SE(3)
		- ![在这里插入图片描述](https://img-blog.csdnimg.cn/2019012122093924.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzI4MTA1NDEz,size_16,color_FFFFFF,t_70){:height 503, :width 718}
- ![](https://picx.zhimg.com/80/v2-9556051bfddd429ff14468693b0e1c75_1440w.webp?source=1940ef5c){:height 477, :width 780}
	- ![](https://picx.zhimg.com/80/v2-31dd5b812607ac238782b1adfe1d4e7e_1440w.webp?source=1def8aca)
	- 完备性
		- 通俗理解：完备的空间是指空间序列的极限包含在该空间里
	- 函数光滑和解析
		- 函数光滑（smooth）是说这个函数在定义域中任意一点都有任何阶的导数。
		- 函数解析（analytic）是说函数光滑并且任意一点的泰勒级数都在该点的某临域内等于该函数
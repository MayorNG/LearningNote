---
mindmap-plugin: basic
tags:
  - 数学/线性代数
  - 机器学习
  - 书籍目录
---

# 线代优化

## Linear Algebra and Optimization
- 线性代数和优化
	- Introduction
	- Scalars, Vectors, and Matrices
	标量、向量和矩阵
		- Basic Operations with Scalars and Vectors
		标量和向量的基本运算
		- Basic Operations with Vectors and Matrices
		向量和矩阵的基本运算
		- Special Classes of Matrices
		特殊类型的矩阵
		- Matrix Powers, Polynomials, and the Inverse
		矩阵的幂、多项式和逆矩阵
		- The Matrix Inversion Lemma: Inverting the Sum of Matrices
		矩阵求逆引理：求解矩阵和的逆
		- Frobenius Norm, Trace, and Energy
		弗罗贝尼乌斯范数、迹和能量
	- Matrix Multiplication as a Decomposable Operator
	将矩阵乘法视为可分解的运算
		- Matrix Multiplication as Decomposable Row and Column Operators
		将矩阵乘法视为可分解的行和列运算
		- Matrix Multiplication as Decomposable Geometric Operators
		将矩阵乘法视为可分解的几何运算
	- Basic Problems in Machine Learning
	机器学习中的基本问题
		- Matrix Factorization
		矩阵分解
		- Clustering
		聚类
		- Classification and Regression Modeling
		分类和回归建模
		- Outlier Detection
		异常检测
	- Optimization for Machine Learning
	机器学习中的优化
		- The Taylor Expansion for Function Simplification
		函数简化的泰勒展开
		- Example of Optimization in Machine Learning
		机器学习中的优化示例
		- Optimization in Computational Graphs
		计算图中的优化

## Linear Transformations and Linear Systems
- 线性变换和线性系统
	- Introduction
		- What Is a Linear Transform?
		什么是线性变换
	- The Geometry of Matrix Multiplication
	矩阵乘法的几何表示
	- Vector Spaces and Their Geometry
	向量空间及其几何性质
		- Coordinates in a Basis System
		基系中的坐标
		- Coordinate Transformations Between Basis Sets
		基向量集之间的坐标变换
		- Span of a Set of Vectors
		向量集的张成
		- Machine Learning Example: Discrete Wavelet Transform
		机器学习示例：离散小波变换
		- Relationships Among Subspaces of a Vector Space
		向量空间子空间之间的关系
	- The Linear Algebra of Matrix Rows and Columns
	矩阵的行和列的线性代数
	- The Row Echelon Form of a Matrix
	矩阵的行梯形形式
		- LU Decomposition
		LU分解
		- Application: Finding a Basis Set
		应用：寻找基向量集
		- Application: Matrix Inversion
		应用：矩阵求逆
		- Application: Solving a System of Linear Equations
		应用：解线性方程组
	- The Notion of Matrix Rank
	矩阵秩的概念
		- Effect of Matrix Operations on Rank
		矩阵运算对秩的影响
	- Generating Orthogonal Basis Sets
	生成正交基向量集
		- Gram-Schmidt Orthogonalization and QR Decomposition
		格拉姆-施密特正交化和QR分解
		- QR Decomposition
		QR分解
		- The Discrete Cosine Transform
		离散余弦变换
	- An Optimization-Centric View of Linear Systems
	基于优化的线性系统视角
		- Moore-Penrose Pseudoinverse
		Moore-Penrose伪逆
		- The Projection Matrix
		投影矩阵
	- Ill-Conditioned Matrices and Systems
	病态矩阵和系统
	- Inner Products: A Geometric View
	内积：几何视角
	- Complex Vector Spaces
	复数向量空间
		- The Discrete Fourier Transform
		离散傅里叶变换

## Eigenvectors and Diagonalizable Matrices
- 特征向量与可对角化矩阵
	- Introduction
	- Determinants
	行列式
	- Diagonalizable Transformations and Eigenvectors
	可对角化变换与特征向量
		- Complex Eigenvalues
		复数特征值
		- Left Eigenvectors and Right Eigenvectors
		左特征向量和右特征向量
		- Existence and Uniqueness of Diagonalization
		对角化的存在性和唯一性
		- Existence and Uniqueness of Triangulization
		上三角化的存在性和唯一性
		- Similar Matrix Families Sharing Eigenvalues
		共享特征值的相似矩阵族
		- Diagonalizable Matrix Families Sharing Eigenvectors
		共享特征向量的可对角化矩阵族
		- Symmetric Matrices
		对称矩阵
		- Positive Semidefinite Matrices
		正半定矩阵
		- Cholesky Factorization: Symmetric LU Decomposition
		Cholesky 分解：对称 LU 分解
	- Machine Learning and Optimization Applications
	机器学习和优化应用
		- Fast Matrix Operations in Machine Learning
		机器学习中的快速矩阵运算
		- Examples of Diagonalizable Matrices in Machine Learning
		机器学习中的可对角化矩阵示例
		- Symmetric Matrices in Quadratic Optimization
		二次优化中的对称矩阵
		- Diagonalization Application: Variable Separation for Optimization
		对角化应用：优化的变量分离
		- Eigenvectors in Norm-Constrained Quadratic Programming
		范数约束二次规划中的特征向量
	- Numerical Algorithms for Finding Eigenvectors
	寻找特征向量的数值算法
		- The QR Method via Schur Decomposition
		通过Schur分解的QR方法
		- The Power Method for Finding Dominant Eigenvectors
		寻找主特征向量的幂法

## Optimization Basics: A Machine Learning View
- 优化基础：机器学习视角
	- Introduction
	- The Basics of Optimization
	优化基础
		- Univariate Optimization
		单变量优化
			- Why We Need Gradient Descent
			为什么需要梯度下降
			- Convergence of Gradient Descent
			梯度下降的收敛性
			- The Divergence Problem
			发散问题
		- Bivariate Optimization
		双变量优化
		- Multivariate Optimization
		多元优化
	- Convex Objective Functions
	凸目标函数
	- The Minutiae of Gradient Descent
	梯度下降的细节
		- Checking Gradient Correctness with Finite Differences
		使用有限差分检查梯度正确性
		- Learning Rate Decay and Bold Driver
		学习率衰减和Bold Driver
		- Line Search
		线搜索
			- Binary Search
			二分搜索
			- Golden-Section Search
			黄金分割搜索
			- Armijo Rule
			Armijo规则
		- Initialization
		初始化
	- Properties of Optimization in Machine Learning
	机器学习中的优化特性
		- Typical Objective Functions and Additive Separability
		典型的目标函数和可加性分离
		- Stochastic Gradient Descent
		随机梯度下降
		- How Optimization in Machine Learning Is Different
		机器学习中的优化差异
		- Tuning Hyperparameters
		调整超参数
		- The Importance of Feature Preprocessing
		特征预处理的重要性
	- Computing Derivatives with Respect to Vectors
	计算对向量的导数
		- Matrix Calculus Notation
		矩阵微积分符号
		- Useful Matrix Calculus Identities
		有用的矩阵微积分恒等式
			- Application: Unconstrained Quadratic Programming
			应用：无约束二次规划
			- Application: Derivative of Squared Norm
			应用：平方范数的导数
		- The Chain Rule of Calculus for Vectored Derivatives
		向量导数的微积分链式法则
			- Useful Examples of Vectored Derivatives
			向量导数的有用示例
	- Linear Regression: Optimization with Numerical Targets
	线性回归：数值目标的优化
		- Tikhonov Regularization
		Tikhonov 正则化
			- Pseudoinverse and Connections to Regularization
			伪逆和正则化的关系
		- Stochastic Gradient Descent
		随机梯度下降
		- The Use of Bias
		使用偏置
			- Heuristic Initialization
			启发式初始化
	- Optimization Models for Binary Targets
	二进制目标的优化模型
		- Least-Squares Classification: Regression on Binary Targets
		最小二乘分类：二进制目标的回归
			- Why Least-Squares Classification Loss Needs Repair
			为什么最小二乘分类损失需要修复
		- The Support Vector Machine
		支持向量机
			- Computing Gradients
			计算梯度
			- Stochastic Gradient Descent
			随机梯度下降
		- Logistic Regression
		逻辑回归
			- Computing Gradients
			计算梯度
			- Stochastic Gradient Descent
			随机梯度下降
		- How Linear Regression Is a Parent Problem in Machine Learning
		线性回归如何是机器学习中的父问题
	- Optimization Models for the MultiClass Setting
	多类别设置的优化模型
		- Weston-Watkins Support Vector Machine
		Weston-Watkins 支持向量机
			- Computing Gradients
			计算梯度
		- Multinomial Logistic Regression
		多项式逻辑回归
			- Computing Gradients
			计算梯度
			- Stochastic Gradient Descent
			随机梯度下降
	- Coordinate Descent
	坐标下降
		- Linear Regression with Coordinate Descent
		带坐标下降的线性回归
		- Block Coordinate Descent
		块坐标下降
		- K-Means as Block Coordinate Descent
		K均值作为块坐标下降

## Advanced Optimization Solutions
- 高级优化解决方案
	- Introduction
	- Challenges in Gradient-Based Optimization
	梯度下降优化中的挑战
		- Local Optima and Flat Regions
		局部最优点和平坦区域
		- Differential Curvature
		微分曲率
			- Revisiting Feature Normalization
			重新审视特征标准化
		- Examples of Difficult Topologies: Cliffs and Valleys
		困难拓扑的示例：悬崖和山谷
	- Adjusting First-Order Derivatives for Descent
	调整一阶导数以实现下降
		- Momentum-Based Learning
		基于动量的学习
		- AdaGrad
		- RMSProp
		- Adam
	- The Newton Method
	牛顿法
		- The Basic Form of the Newton Method
		牛顿法的基本形式
		- Importance of Line Search for Non-quadratic Functions
		针对非二次函数的线搜索重要性
		- Example: Newton Method in the Quadratic Bowl
		示例：二次碗中的牛顿法
		- Example: Newton Method in a Non-quadratic Function
		示例：非二次函数中的牛顿法
	- Newton Methods in Machine Learning
	机器学习中的牛顿法
		- Newton Method for Linear Regression
		线性回归的牛顿法
		- Newton Method for Support-Vector Machines
		支持向量机的牛顿法
		- Newton Method for Logistic Regression
		逻辑回归的牛顿法
		- Connections Among Different Models and Unified Framework
		不同模型之间的联系和统一框架
	- Newton Method: Challenges and Solutions
	牛顿法：挑战与解决方案
		- Singular and Indefinite Hessian
		奇异和不定的海森矩阵
		- The Saddle-Point Problem
		鞍点问题
		- Convergence Problems and Solutions with Non-quadratic Functions
		在非二次函数中的收敛问题和解决方案
			- Trust Region Method
			信任区域法
	- Computationally Efficient Variations of Newton Method
	牛顿法的计算效率变种
		- Conjugate Gradient Method
		共轭梯度法
		- Quasi-Newton Methods and BFGS
		拟牛顿方法和BFGS
	- Non-differentiable Optimization Functions
	非可导优化函数
		- The Subgradient Method
		次梯度法
			- Application: L1-Regularization
			应用：L1正则化
			- Combining Subgradients with Coordinate Descent
			结合子梯度和坐标下降
		- Proximal Gradient Method
		近端梯度法
			- Application: Alternative for L1-Regularized Regression
			应用：L1正则化回归的替代方案
		- Designing Surrogate Loss Functions for Combinatorial Optimization
		为组合优化设计替代损失函数
			- Application: Ranking Support Vector Machine
			应用：排名支持向量机
		- Dynamic Programming for Optimizing Sequential Decisions
		用于优化顺序决策的动态规划
			- Application: Fast Matrix Multiplication
			应用：快速矩阵乘法

## Constrained Optimization and Duality
- 约束优化与对偶性
	- Introduction
	- Primal Gradient Descent Methods
	原始梯度下降方法
		- Linear Equality Constraints
		线性等式约束
			- Convex Quadratic Program with Equality Constraints
			具有等式约束的凸二次规划
			- Application: Linear Regression with Equality Constraints
			应用：带等式约束的线性回归
			- Application: Newton Method with Equality Constraints
			应用：带等式约束的牛顿法
		- Linear Inequality Constraints
		线性不等式约束
			- The Special Case of Box Constraints
			箱式约束的特殊情况
			- General Conditions for Projected Gradient Descent to Work
			使投影梯度下降起作用的一般条件
			- Sequential Linear Programming
			顺序线性规划
		- Sequential Quadratic Programming
		顺序二次规划
	- Primal Coordinate Descent
	原始坐标下降
		- Coordinate Descent for Convex Optimization Over Convex Set
		凸集上的坐标下降优化
		- Machine Learning Application: Box Regression
		机器学习应用：箱式回归
	- Lagrangian Relaxation and Duality
	拉格朗日松弛与对偶性
		- Kuhn-Tucker Optimality Conditions
		库恩-塔克优化条件
		- General Procedure for Using Duality
		使用对偶性的一般过程
			- Inferring the Optimal Primal Solution from Optimal Dual Solution
			从最优对偶解推断最优原始解
		- Application: Formulating the SVM Dual
		应用：构建SVM对偶
			- Inferring the Optimal Primal Solution from Optimal Dual Solution
			从最优对偶解推断最优原始解
		- Optimization Algorithms for the SVM Dual
		SVM对偶的优化算法
			- Gradient Descent
			梯度下降
			- Coordinate Descent
			坐标下降
		- Getting the Lagrangian Relaxation of Unconstrained Problems
		获得无约束问题的拉格朗日松弛
			- Machine Learning Application: Dual of Linear Regression
			机器学习应用：线性回归的对偶
	- Penalty-Based and Primal-Dual Methods
	基于惩罚的方法和原始-对偶方法
		- Penalty Method with Single Constraint
		带单一约束的惩罚方法
		- Penalty Method: General Formulation
		惩罚方法：一般形式
		- Barrier and Interior Point Methods
		障碍和内点法
	- Norm-Constrained Optimization
	范数约束优化
	- Primal Versus Dual Methods
	原始与对偶方法

## Singular Value Decomposition
- 奇异值分解
	- Introduction
	- SVD: A Linear Algebra Perspective
	奇异值分解: 线性代数视角
		- Singular Value Decomposition of a Square Matrix
		- Square SVD to Rectangular SVD via Padding
		- Several Definitions of Rectangular Singular Value Decomposition
		- Truncated Singular Value Decomposition
			- Relating Truncation Loss to Singular Values
			- Geometry of Rank-k Truncation
			- Example of Truncated SVD
		- Two Interpretations of SVD
		- Is Singular Value Decomposition Unique?
		- Two-Way Versus Three-Way Decompositions
	- SVD: An Optimization Perspective
	奇异值分解: 优化视角
		- A Maximization Formulation with Basis Orthogonality
		- A Minimization Formulation with Residuals
		- Generalization to Matrix Factorization Methods
		- Principal Component Analysis
	- Applications of Singular Value Decomposition
	奇异值分解的应用
		- Dimensionality Reduction
		- Noise Removal
		- Finding the Four Fundamental Subspaces in Linear Algebra
		- Moore-Penrose Pseudoinverse
			- Ill-Conditioned Square Matrices
		- Solving Linear Equations and Linear Regression
		- Feature Preprocessing and Whitening in Machine Learning
		- Outlier Detection
		- Feature Engineering
	- Numerical Algorithms for SVD
	奇异值分解的数值算法

## Matrix Factorization
- 矩阵分解
	- Introduction
	- Optimization-Based Matrix Factorization
	基于优化的矩阵分解
		- Example: K-Means as Constrained Matrix Factorization
	- Unconstrained Matrix Factorization
	无约束矩阵分解
		- Gradient Descent with Fully Specified Matrices
		- Application to Recommender Systems
			- Stochastic Gradient Descent
			- Coordinate Descent
			- Block Coordinate Descent: Alternating Least Squares
	- Nonnegative Matrix Factorization
	非负矩阵分解
		- Optimization Problem with Frobenius Norm
			- Projected Gradient Descent with Box Constraints
		- Solution Using Duality
		- Interpretability of Nonnegative Matrix Factorization
		- Example of Nonnegative Matrix Factorization
		- The I-Divergence Objective Function
	- Weighted Matrix Factorization
	加权矩阵分解
		- Practical Use Cases of Nonnegative and Sparse Matrices
		- Stochastic Gradient Descent
			- Why Negative Sampling Is Important
		- Application: Recommendations with Implicit Feedback Data
		- Application: Link Prediction in Adjacency Matrices
		- Application: Word-Word Context Embedding with GloVe
	- Nonlinear Matrix Factorizations
	非线性矩阵分解
		- Logistic Matrix Factorization
			- Gradient Descent Steps for Logistic Matrix Factorization
		- Maximum Margin Matrix Factorization
	- Generalized Low-Rank Models
	广义低秩模型
		- Handling Categorical Entries
		- Handling Ordinal Entries
	- Shared Matrix Factorization
	共享矩阵分解
		- Gradient Descent Steps for Shared Factorization
		- How to Set Up Shared Models in Arbitrary Scenarios
	- Factorization Machines
	因子分解机

## The Linear Algebra of Similarity
- 相似性的线性代数
	- Introduction
	- Equivalence of Data and Similarity Matrices
	数据和相似性矩阵的等价性
		- From Data Matrix to Similarity Matrix and Back
		- When Is Data Recovery from a Similarity Matrix Useful?
		- What Types of Similarity Matrices Are “Valid”?
		- Symmetric Matrix Factorization as an Optimization Model
		- Kernel Methods: The Machine Learning Terminology
	- Efficient Data Recovery from Similarity Matrices
	从相似性矩阵高效还原数据
		- Nystrom Sampling
		- Matrix Factorization with Stochastic Gradient Descent
		- Asymmetric Similarity Decompositions
	- Linear Algebra Operations on Similarity Matrices
	相似性矩阵上的线性代数运算
		- Energy of Similarity Matrix and Unit Ball Normalization
		- Norm of the Mean and Variance
		- Centering a Similarity Matrix
			- Application: Kernel PCA
		- From Similarity Matrix to Distance Matrix and Back
			- Application: ISOMAP
	- Machine Learning with Similarity Matrices
	利用相似性矩阵的机器学习
		- Feature Engineering from Similarity Matrix
			- Kernel Clustering
			- Kernel Outlier Detection
			- Kernel Classification
		- Direct Use of Similarity Matrix
			- Kernel K-Means
			- Kernel SVM
	- The Linear Algebra of the Representer Theorem
	表示定理的线性代数
	- Similarity Matrices and Linear Separability
	相似性矩阵和线性可分性
		- Transformations That Preserve Positive Semi-definiteness

## The Linear Algebra of Graphs
- 图的线性代数
	- Introduction
	- Graph Basics and Adjacency Matrices
	图的基础知识和邻接矩阵
	- Powers of Adjacency Matrices
	邻接矩阵的幂
	- The Perron-Frobenius Theorem
	Perron-Frobenius 定理
	- The Right Eigenvectors of Graph Matrices
	图矩阵的右特征向量
		- The Kernel View of Spectral Clustering
			- Relating Shi-Malik and Ng-Jordan-Weiss Embeddings
		- The Laplacian View of Spectral Clustering
			- Graph Laplacian
			- Optimization Model with Laplacian
		- The Matrix Factorization View of Spectral Clustering
			- Machine Learning Application: Directed Link Prediction
		- Which View of Spectral Clustering Is Most Informative?
	- The Left Eigenvectors of Graph Matrices
	图矩阵的左特征向量
		- PageRank as Left Eigenvector of Transition Matrix
		- Related Measures of Prestige and Centrality
		- Application of Left Eigenvectors to Link Prediction
	- Eigenvectors of Reducible Matrices
	可约矩阵的特征向量
		- Undirected Graphs
		- Directed Graphs
	- Machine Learning Applications
	机器学习应用
		- Application to Vertex Classification
		- Applications to Multidimensional Data

## Optimization in Computational Graphs
- 用于计算图中的优化
	- Introduction
	- The Basics of Computational Graphs
	计算图的基础知识
		- Neural Networks as Directed Computational Graphs
	- Optimization in Directed Acyclic Graphs
	有向无环图中的优化
		- The Challenge of Computational Graphs
		- The Broad Framework for Gradient Computation
		- Computing Node-to-Node Derivatives Using Brute Force
		- Dynamic Programming for Computing Node-to-Node Derivatives
			- Example of Computing Node-to-Node Derivatives
		- Converting Node-to-Node Derivatives into Loss-to-Weight Derivatives
			- Example of Computing Loss-to-Weight Derivatives
		- Computational Graphs with Vector Variables
	- Application: Backpropagation in Neural Networks
	应用：神经网络中的反向传播
		- Derivatives of Common Activation Functions
		- Vector-Centric Backpropagation
		- Example of Vector-Centric Backpropagation
	- A General View of Computational Graphs
	计算图的一般视图
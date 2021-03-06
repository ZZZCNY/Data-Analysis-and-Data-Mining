# 数据分析与数据挖掘

自本书第 1 版、第 2 版出版以来，数据挖掘领域已经取得了重大进展，开发出了许多新的数据挖掘方法、系统和应用，特别是对于处理包括信息网络、图、复杂结构和数据流，以及文本、Web、多媒体、时间序列、时间空间数据在内的新的数据类型。这种快速发展、新技术不断涌现使得在一本书中涵盖整个领域的广泛内容非常困难。因此，我们决定与其继续扩大本书的涵盖面，还不如让本书以足够的广度和深度涵盖该领域的核心内容，而把复杂数据类型的处理留给另一本即将面世的书。

第 3 版对本书的前两版做了全面修订，加强和重新组织了全书的技术内容，显著地扩充和加强处理一般数据类型挖掘的核心技术。第 2 版中讨论特定主题的章节（例如，数据预处理、频繁模式挖掘、分类和聚类）在这一版都被扩充，每章都分成两章。对于这些主题,一章囊括基本概念和技术，而另一章提供高级概念和方法。

第 2 版关于复杂数据类型的章节（例如，流数据、序列数据、图结构数据、社会网络数据和多重关系数据，以及文本、Web、多媒体和时间空间数据）现在保留给专门介绍数据挖掘的高级课题的新书。为了支持读者学习这些高级课题，我们把第 2 版的相关章节的电子版放在本书的网站上，作为第 3 版的配套材料。

第 3 版各章的简要内容如下（重点介绍新的内容）：

第 1 章提供关于数据挖掘的多学科领域的导论。该章讨论导致需要数据挖掘的数据库技术的发展历程和数据挖掘应用的重要性。该章考察挖掘的数据类型，包括关系的、事务的和数据仓库数据，以及复杂的数据类型，如时间序列、序列、数据流、时间空间数据、多媒体数据、文本数据、图、社会网络和 Web 数据。该章根据所挖掘的知识类型、所使用的技术以及目标应用的类型，对数据挖掘任务进行了一般分类。最后讨论该领域的主要挑战。

第 2 章介绍一般数据特征。该章首先讨论数据对象和属性类型，然后介绍基本统计数据描述的典型度量。该章概述各种类型数据的数据可视化技术。除了数值数据的可视化方法外，还介绍文本、标签、图和多维数据的可视化方法。第 2 章还介绍度量各种类型数据的相似性和相异性的方法。

第 3 章介绍数据预处理技术。该章首先介绍数据质量的概念，然后讨论数据清理、数据集成、数据归约、数据变换和数据离散化的方法。

第 4 章和第 5 章是数据仓库、OLAP（联机分析处理）和数据立方体技术的引论。第 4 章介绍数据仓库和 OLAP 的基本概念、建模、结构、一般实现，以及数据仓库和其他数据泛化的关系。第 5 章更深入地考察数据立方体技术，详细地研究数据立方体的计算方法，包括 Star-Cubing 和高维 OLAP 方法。该章还讨论数据立方体和 OL.AP 技术的进一步研究，如抽样立方体、排序立方体、预测立方体、用于复杂数据挖掘查询的多特征立方体和发现驱动的数据立方体的探查。

第 6 章和第 7 章介绍挖掘大型数据集中的频繁模式：关联和相关性的方法。第 6 章介绍基本概念，如购物篮分析，还有条理地提供了许多频繁项集挖掘技术。这些涵盖从基本 Aprioti 算法和它的变形，到改进性能的更高级的方法，包括频繁模式增长方法，使用数据的垂直形式的频繁模式挖掘，挖掘闭频繁项集和极大频繁项集。该章还讨论模式评估方法并介绍挖掘相关模式的度量。第 7 章介绍高级模式挖掘方法。该章讨论多层和多维空间中的模式挖掘，挖掘稀有和负模式，挖掘巨型模式和高维空间数据，基于约束的模式挖掘和挖掘压缩或近似模式。该章还介绍模式探查和应用的方法，包括频繁模式的语义注解。

第 8 章和第 9 章介绍数据分类方法。由于分类方法的重要性和多样性，内容被划分成两章。第 8 章介绍分类的基本概念和方法，包括决策树归纳、贝叶斯分类和基于规则的分类。该章还讨论模型评估和选择方法，以及提高分类准确率的方法，包括组合方法和处理不平衡数据。第 9 章讨论分类的高级方法，包括贝叶斯信念网络、后向传播的神经网络技术、支持向量机、使用频繁模式的分类、k-最邻近分类、基于案例的推理、遗传算法、粗糙集理论和模糊集方法。附加的主题包括多类分类、半监督分类、主动学习和迁移学习。

聚类分析是第 10 章和第 11 章的主题。第 10 章介绍数据聚类的基本概念和方法，包括基本聚类分析方法的概述、划分方法、层次方法、基于密度的方法和基于网格的方法。该章还介绍聚类评估方法。第 11 章讨论聚类的高级方法，包括基于概率模型的聚类、聚类高维数据、聚类图和网络数据，以及基于约束的聚类。

第 12 章专门讨论离群点检测。本章介绍离群点的基本概念和离群点分析，并从各种监督力度（监督的、半监督的和无监督的）以及方法角度（统计学方法、基于邻近性的方法、基于聚类的方法和基于分类的方法）讨论离群点检测方法。该章还讨论挖掘情境离群点和集体离群点，以及高维数据中的离群点检测。

最后，在第 13 章我们讨论数据挖掘的趋势、应用和研究前沿。我们简略地介绍挖掘复杂数据类型，包括挖掘序列数据（例如，时间序列、符号序列和生物学序列)，挖掘图和网络，以及挖掘空间、多媒体、文本和 Web 数据。这些数据挖掘方法的深入讨论留给正在撰写的数据挖掘高级课题一书。然后，该章转向讨论其他数据挖掘方法学，包括统计学数据挖掘、数据挖掘基础、可视和听觉数据挖掘，以及数据挖掘的应用。讨论数据挖掘在金融数据分析、零售和电信产业、科学与工程，以及入侵检测和预防方面的应用。该章还讨论数据挖掘与推荐系统的联系。由于数据挖掘出现在我们日常生活的方方面面，所以我们讨论数据挖掘与社会，包括无处不在和无形的数据挖掘，以及隐私、安全和数据挖掘对社会的影响。我们用考察数据挖掘的发展趋势结束本书。

书中楷体字用于强调定义的术语，而黑体字用于突出主要思想。

本书与其他数据挖掘教材相比具有一些显著特点：它广泛、深入地讨论了数据挖掘原理。各章尽可能是自包含的，使得读者可以按自己感兴趣的次序阅读。高级章节提供了更大的视野，感兴趣的读者可以选读。本书提供了数据挖掘的所有主要方法，还提供了关于多维 OLAP 分析等数据挖掘的重要主题，这些主题在其他书中常常被忽略或很少提及。本书还维护了一个网站，其中包含大量在线资源，为教师、学生和该领域的专业人员提供支持。这些将在下面介绍。

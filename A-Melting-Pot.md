# 熔炉——数据模型+算法模型

## 摘要

>  Leo Breiman的文章《统计建模：两种文化》是非常及时，且具有煽动性。他主张统计学家学习和欣赏一种不同的“文化”：一种算法方法，不同于熟悉的随机数据建模方法。虽然我们赞赏算法方法并为其做出了贡献，但我们一直在这两个阵营中涉足。在这里，我们提倡“大熔炉”，认为两种方法都有各自的优点，有时是在同一个问题上。


我们非常熟悉Leo，钦佩他对我们领域的开创性贡献和对生活的热情。他最后的主要贡献是随机森林，在他2005年7月去世时，随机森林越来越受欢迎。我们希望他能看到它现在有多受欢迎。Leo，随机森林“像流氓一样前进”。


我们自己在统计学习方面的工作受到了Leo和他在本文中表达的一些观点的启发，我们在很大程度上接受了算法建模文化。然而，公平地说，我们在数据建模和算法建模两个阵营中一直都有涉足。我们认为这两种方法都有明确的作用，有时甚至在同一个问题上共同努力。我们举几个例子。

- 因果推断是一个热门话题——使用对受试者的观察（非随机）测量来比较两种治疗方法。这不能被视为一个简单的监督学习问题，因为我们从不观察给定患者在两种治疗下的结果。此外，任何合理的分析都需要考虑选择偏差。

   目前最先进的方法是使用概率模型，假设潜在结果和不可混淆性，并使用倾向分数。给定这个模型，人们可以使用算法监督学习工具来估计关键成分。然后，估计模型可以用来推断治疗。这个程序很好地说明了用于估计异质性治疗效果的R-learner Nie和Wager（2020）。

- 逻辑回归最初在生物统计学和流行病学领域广受欢迎。它的重点是比值比，这是罕见疾病相对风险的合理替代品。它有一个很大的优点：它可以从回顾性病例对照样本中进行估计。这是一个概率结果，依赖于贝叶斯公式和条件参数。它允许我们将非随机病例对照标签作为通过逻辑回归估计的目标，并且仍然得到感兴趣参数的有效估计。这也表明，在基于网络的点击率建模中，我们可以对大量的负面例子进行子样本化，并且仍然可以从逻辑回归中得到有效的预测。当然，对于这些数据，我们可以自由地使用更复杂的算法方法来拟合响应概率函数，但是从逻辑回归中获得的知识告诉我们如何处理它。

- 考克斯比例风险模型（The Cox proportional hazards model）在生物统计学和流行病学以及金融和工业应用中无处不在。它使用概率半参数框架，巧妙地允许我们对感兴趣的相对风险函数进行建模，同时考虑到任意的基线风险。概率模型因此确定损失函数，此后允许任何经典或机器学习模型来估计感兴趣的函数。

- 使用概率模型来理解和解释算法模型的行为和性能的例子很多。我们列出了一些：

  - 支持向量机的铰链损失（hinge-loss）加惩罚，这使得与逻辑回归的对数似然进行直接比较成为可能，并强调了它们的相似性和不同之处。【译注：没明白】
  - 将Adaboost解释为加法逻辑回归模型（dditive logistic regression model），导致梯度增强（gradient boosting ）的发展。
  - 对机器学习中的“双下降”（double descent）现象，使用简单的参数模型可以给出清晰的解释。



总而言之，数据模型和算法模型我们都需要——有时在同一个问题上一起工作——我们需要主题专业知识来知道何时使用其中之一或两者。更重要的是数据建模可以帮助我们理解算法建模的性质。

> 作者 Rob Tibshirani and Trevor Hastie，翻译来自 https://muse.jhu.edu/article/799737
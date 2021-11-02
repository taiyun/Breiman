# Comment: D. R. Cox

Professor Breiman's interesting paper gives both key points concern the precise meaning of the data, a clear statement of the broad approach underlying some of his influential and widely admired contributions and outlines some striking applications and developments. He has combined this with a critique of what, for want of a better term, I will call mainstream statistical thinking, based in part on a caricature. Like all good caricatures, it contains enough truth and exposes enough weaknesses to be thought-provoking.

There is not enough space to comment on all the many points explicitly or implicitly raised in the paper. There follow some remarks about a few main issues.

One of the attractions of our subject is the astonishingly wide range of applications as judged not only in terms of substantive field but also in terms of objectives, quality and quantity of data and so on. Thus any unqualified statement that "in applications..." has to be treated sceptically. One of our failings has, $\mathrm{I}$ believe, been, in a wish to stress generality, not to set out more clearly the distinctions between different kinds of application and the consequences for the strategy of statistical analysis. Of course we have distinctions between decision-making and inference, between tests and estimation, and between estimation and prediction and these are useful but, I think, are, except perhaps the first, too phrased in terms of the technology rather than the spirit of statistical analysis. I entirely agree with Professor Breiman that it would be an impoverished and extremely unhistorical view of the subject to exclude the kind of work he describes simply because it has no explicit probabilistic base.

Professor Breiman takes data as his starting point. I would prefer to start with an issue, a question or a scientific hypothesis, although I would be surprised if this were a real source of disagreement. These issues may evolve, or even change radically, as analysis proceeds. Data looking for a question are not unknown and raise puzzles but are, I believe, atypical in most contexts. Next, even if we ignore design aspects and start with data,

D. $R$. Cox is an Honorary Fellow, Nuffield College, Oxford OX1 1NF, United Kingdom, and associate member, Department of Statistics, University of Oxford (e-mail: david.cox@nuffield.oxford.ac.uk). the possible biases arising from the method of ascertainment, the possible presence of major distorting measurement errors and the nature of processes underlying missing and incomplete data and data that evolve in time in a way involving complex interdependencies. For some of these, at least, it is hard to see how to proceed without some notion of probabilistic modeling.

Next Professor Breiman emphasizes prediction as the objective, success at prediction being the criterion of success, as contrasted with issues of interpretation or understanding. Prediction is indeed important from several perspectives. The success of a theory is best judged from its ability to predict in new contexts, although one cannot dismiss as totally useless theories such as the rational action theory (RAT), in political science, which, as I understand it, gives excellent explanations of the past but which has failed to predict the real political world. In a clinical trial context it can be argued that an objective is to predict the consequences of treatment allocation to future patients, and so on.

If the prediction is localized to situations directly similar to those applying to the data there is then an interesting and challenging dilemma. Is it preferable to proceed with a directly empirical black-box approach, as favored by Professor Breiman, or is it better to try to take account of some underlying explanatory process? The answer must depend on the context but I certainly accept, although it goes somewhat against the grain to do so, that there are situations where a directly empirical approach is better. Short term economic forecasting and real-time flood forecasting are probably further exemplars. Key issues are then the stability of the predictor as practical prediction proceeds, the need from time to time for recalibration and so on.

However, much prediction is not like this. Often the prediction is under quite different conditions from the data; what is the likely progress of the incidence of the epidemic of $\mathrm{v}$-CJD in the United Kingdom, what would be the effect on annual incidence of cancer in the United States of reducing by $10 \%$ the medical use of X-rays, etc.? That is, it may be desired to predict the consequences of something only indirectly addressed by the data available for analysis. As we move toward such more ambitious tasks, prediction, always hazardous, without some understanding of underlying process and linking with other sources of information, becomes more and more tentative. Formulation of the goals of analysis solely in terms of direct prediction over the data set seems then increasingly unhelpful.

This is quite apart from matters where the direct objective is understanding of and tests of subjectmatter hypotheses about underlying process, the nature of pathways of dependence and so on.

What is the central strategy of mainstream statistical analysis? This can most certainly not be discerned from the pages of Bernoulli, The Annals of Statistics or the Scandanavian Journal of Statistics nor from Biometrika and the Journal of Royal Statistical Society, Series $B$ or even from the application pages of Journal of the American Statistical Association or Applied Statistics, estimable though all these journals are. Of course as we move along the list, there is an increase from zero to $100 \%$ in the papers containing analyses of "real" data. But the papers do so nearly always to illustrate technique rather than to explain the process of analysis and interpretation as such. This is entirely legitimate, but is completely different from live analysis of current data to obtain subject-matter conclusions or to help solve specific practical issues. Put differently, if an important conclusion is reached involving statistical analysis it will be reported in a subject-matter journal or in a written or verbal report to colleagues, government or business. When that happens, statistical details are typically and correctly not stressed. Thus the real procedures of statistical analysis can be judged only by looking in detail at specific cases, and access to these is not always easy. Failure to discuss enough the principles involved is a major criticism of the current state of theory.

I think tentatively that the following quite commonly applies. Formal models are useful and often almost, if not quite, essential for incisive thinking. Descriptively appealing and transparent methods with a firm model base are the ideal. Notions of significance tests, confidence intervals, posterior intervals and all the formal apparatus of inference are valuable tools to be used as guides, but not in a mechanical way; they indicate the uncertainty that would apply under somewhat idealized, may be very idealized, conditions and as such are often lower bounds to real uncertainty. Analyses and model development are at least partly exploratory. Automatic methods of model selection (and of variable selection in regression-like problems) are to be shunned or, if use is absolutely unavoidable, are to be examined carefully for their effect on the final conclusions. Unfocused tests of model adequacy are rarely helpful.

By contrast, Professor Breiman equates mainstream applied statistics to a relatively mechanical process involving somehow or other choosing a model, often a default model of standard form, and applying standard methods of analysis and goodness-of-fit procedures. Thus for survival data choose a priori the proportional hazards model. (Note, incidentally, that in the paper, often quoted but probably rarely read, that introduced this approach there was a comparison of several of the many different models that might be suitable for this kind of data.) It is true that many of the analyses done by nonstatisticians or by statisticians under severe time constraints are more or less like those Professor Breiman describes. The issue then is not whether they could ideally be improved, but whether they capture enough of the essence of the information in the data, together with some reasonable indication of precision as a guard against under or overinterpretation. Would more refined analysis, possibly with better predictive power and better fit, produce subject-matter gains? There can be no general answer to this, but one suspects that quite often the limitations of conclusions lie more in weakness of data quality and study design than in ineffective analysis.

There are two broad lines of development active at the moment arising out of mainstream statistical ideas. The first is the invention of models strongly tied to subject-matter considerations, representing underlying dependencies, and their analysis, perhaps by Markov chain Monte Carlo methods. In fields where subject-matter considerations are largely qualitative, we see a development based on Markov graphs and their generalizations. These methods in effect assume, subject in principle to empirical test, more and more about the phenomena under study. By contrast, there is an emphasis on assuming less and less via, for example, kernel estimates of regression functions, generalized additive models and so on. There is a need to be clearer about the circumstances favoring these two broad approaches, synthesizing them where possible.

My own interest tends to be in the former style of work. From this perspective Cox and Wermuth (1996, page 15) listed a number of requirements of a statistical model. These are to establish a link with background knowledge and to set up a connection with previous work, to give some pointer toward a generating process, to have primary parameters with individual clear subject-matter interpretations, to specify haphazard aspects well enough to lead to meaningful assessment of precision and, finally, that the fit should be adequate. From this perspective, fit, which is broadly related to predictive success, is not the primary basis for model choice and formal methods of model choice that take no account of the broader objectives are suspect in the present context. In a sense these are efforts to establish data descriptions that are potentially causal, recognizing that causality, in the sense that a natural scientist would use the term, can rarely be established from one type of study and is at best somewhat tentative.

Professor Breiman takes a rather defeatist attitude toward attempts to formulate underlying processes; is this not to reject the base of much scientific progress? The interesting illustrations given by Beveridge (1952), where hypothesized processes in various biological contexts led to important progress, even though the hypotheses turned out in the end to be quite false, illustrate the subtlety of the matter. Especially in the social sciences, representations of underlying process have to be viewed with particular caution, but this does not make them fruitless.

The absolutely crucial issue in serious mainstream statistics is the choice of a model that will translate key subject-matter questions into a form for analysis and interpretation. If a simple standard model is adequate to answer the subjectmatter question, this is fine: there are severe hidden penalties for overelaboration. The statistical literature, however, concentrates on how to do

# Comment: Brad Efron

At first glance Leo Breiman's stimulating paper looks like an argument against parsimony and scientific insight, and in favor of black boxes with lots of knobs to twiddle. At second glance it still looks that way, but the paper is stimulating, and Leo has some important points to hammer home. At the risk of distortion I will try to restate one of those points, the most interesting one in my opinion, using less confrontational and more historical language.

From the point of view of statistical development the twentieth century might be labeled " 100 years of unbiasedness." Following Fisher's lead, most of our current statistical theory and practice revolves around unbiased or nearly unbiased estimates (particularly MLEs), and tests based on such estimates. The power of this theory has made statistics the

Brad Efron is Professor, Department of Statistics, Sequoia Hall, 390 Serra Mall, Stanford University, Stanford, California 94305-4065 (e-mail: brad@stat.stanford.edu). the analysis, an important and indeed fascinating question, but a secondary step. Better a rough answer to the right question than an exact answer to the wrong question, an aphorism, due perhaps to Lord Kelvin, that I heard as an undergraduate in applied mathematics.

I have stayed away from the detail of the paper but will comment on just one point, the interesting theorem of Vapnik about complete separation. This confirms folklore experience with empirical logistic regression that, with a largish number of explanatory variables, complete separation is quite likely to occur. It is interesting that in mainstream thinking this is, I think, regarded as insecure in that complete separation is thought to be a priori unlikely and the estimated separating plane unstable. Presumably bootstrap and cross-validation ideas may give here a quite misleading illusion of stability. Of course if the complete separator is subtle and stable Professor Breiman's methods will emerge triumphant and ultimately it is an empirical question in each application as to what happens.

It will be clear that while I disagree with the main thrust of Professor Breiman's paper I found it stimulating and interesting.

dominant interpretational methodology in dozens of fields, but, as we say in California these days, it is power purchased at a price: the theory requires a modestly high ratio of signal to noise, sample size to number of unknown parameters, to have much hope of success. "Good experimental design" amounts to enforcing favorable conditions for unbiased estimation and testing, so that the statistician won't find himself or herself facing 100 data points and 50 parameters.

Now it is the twenty-first century when, as the paper reminds us, we are being asked to face problems that never heard of good experimental design. Sample sizes have swollen alarmingly while goals grow less distinct ("find interesting data structure"). New algorithms have arisen to deal with new problems, a healthy sign it seems to me even if the innovators aren't all professional statisticians. There are enough physicists to handle the physics case load, but there are fewer statisticians and more statistics problems, and we need all the help we can get. An attractive feature of Leo's paper is his openness to new ideas whatever their source.

The new algorithms often appear in the form of black boxes with enormous numbers of adjustable parameters ("knobs to twiddle"), sometimes more knobs than data points. These algorithms can be quite successful as Leo points outs, sometimes more so than their classical counterparts. However, unless the bias-variance trade-off has been suspended to encourage new statistical industries, their success must hinge on some form of biased estimation. The bias may be introduced directly as with the "regularization" of overparameterized linear models, more subtly as in the pruning of overgrown regression trees, or surreptitiously as with support vector machines, but it has to be lurking somewhere inside the theory.

Of course the trouble with biased estimation is that we have so little theory to fall back upon. Fisher's information bound, which tells us how well a (nearly) unbiased estimator can possibly perform, is of no help at all in dealing with heavily biased methodology. Numerical experimentation by itself, unguided by theory, is prone to faddish wandering:

Rule 1. New methods always look better than old ones. Neural nets are better than logistic regression, support vector machines are better than neural nets, etc. In fact it is very difficult to run an honest simulation comparison, and easy to inadvertently cheat by choosing favorable examples, or by not putting as much effort into optimizing the dull old standard as the exciting new challenger.

Rule 2. Complicated methods are harder to criticize than simple ones. By now it is easy to check the efficiency of a logistic regression, but it is no small matter to analyze the limitations of a support vector machine. One of the best things statisticians do, and something that doesn't happen outside our profession, is clarify the inferential basis of a proposed new methodology, a nice recent example being Friedman, Hastie, and Tibshirani's analysis of "boosting," (2000). The past half-century has seen the clarification process successfully at work on nonparametrics, robustness and survival analysis. There has even been some success with biased estimation in the form of Stein shrinkage and empirical Bayes, but I believe the hardest part of this work remains to be done. Papers like Leo's are a call for more analysis and theory, not less.

Prediction is certainly an interesting subject but Leo's paper overstates both its role and our profession's lack of interest in it. - The "prediction culture," at least around Stanford, is a lot bigger than $2 \%$, though its constituency changes and most of us wouldn't welcome being typecast.

- Estimation and testing are a form of prediction: "In our sample of 20 patients drug A outperformed drug B; would this still be true if we went on to test all possible patients?"

- Prediction by itself is only occasionally sufficient. The post office is happy with any method that predicts correct addresses from hand-written scrawls. Peter Gregory undertook his study for prediction purposes, but also to better understand the medical basis of hepatitis. Most statistical surveys have the identification of causal factors as their ultimate goal.

The hepatitis data was first analyzed by Gail Gong in her 1982 Ph.D. thesis, which concerned prediction problems and bootstrap methods for improving on cross-validation. (Cross-validation itself is an uncertain methodology that deserves further critical scrutiny; see, for example, Efron and Tibshirani, 1996). The Scientific American discussion is quite brief, a more thorough description appearing in Efron and Gong (1983). Variables 12 or 17 (13 or 18 in Efron and Gong's numbering) appeared as "important" in $60 \%$ of the bootstrap simulations, which might be compared with the $59 \%$ for variable 19 , the most for any single explanator.

In what sense are variable 12 or 17 or 19 "important" or "not important"? This is the kind of interesting inferential question raised by prediction methodology. Tibshirani and I made a stab at an answer in our 1998 annals paper. I believe that the current interest in statistical prediction will eventually invigorate traditional inference, not eliminate it.

A third front seems to have been opened in the long-running frequentist-Bayesian wars by the advocates of algorithmic prediction, who don't really believe in any inferential school. Leo's paper is at its best when presenting the successes of algorithmic modeling, which comes across as a positive development for both statistical practice and theoretical innovation. This isn't an argument against traditional data modeling any more than splines are an argument against polynomials. The whole point of science is to open up black boxes, understand their insides, and build better boxes for the purposes of mankind. Leo himself is a notably successful scientist, so we can hope that the present paper was written more as an advocacy device than as the confessions of a born-again black boxist. 

# Comment: Bruce Hoadley

## INTRODUCTION

Professor Breiman's paper is an important one for statisticians to read. He and Statistical Science should be applauded for making this kind of material available to a large audience. His conclusions are consistent with how statistics is often practiced in business. This discussion will consist of an anecdotal recital of my encounters with the algorithmic modeling culture. Along the way, areas of mild disagreement with Professor Breiman are discussed. I also include a few proposals for research topics in algorithmic modeling.

## CASE STUDY OF AN ALGORITHMIC MODELING CULTURE

Although I spent most of my career in management at Bell Labs and Bellcore, the last seven years have been with the research group at Fair, Isaac. This company provides all kinds of decision support solutions to several industries, and is very well known for credit scoring. Credit scoring is a great example of the problem discussed by Professor Breiman. The input variables, $\mathbf{x}$, might come from company databases or credit bureaus. The output variable, $y$, is some indicator of credit worthiness.

Credit scoring has been a profitable business for Fair, lsaac since the $1960 \mathrm{~s}$, so it is instructive to look at the Fair, Isaac analytic approach to see how it fits into the two cultures described by Professor Breiman. The Fair, Isaac approach was developed by engineers and operations research people and was driven by the needs of the clients and the quality of the data. The influences of the statistical community were mostly from the nonparametric sidethings like jackknife and bootstrap.

Consider an example of behavior scoring, which is used in credit card account management. For pedagogical reasons, I consider a simplified version (in the real world, things get more complicated) of monthly behavior scoring. The input variables, $\mathbf{x}$ in this simplified version, are the monthly bills and payments over the last 12 months. So the dimension of $\mathbf{x}$ is 24 . The output variable is binary and is the indicator of no severe delinquency over the

Dr. Bruce Hoadley is with Fair, Isaac and $\mathrm{Co}$, Inc., 120 N. Redwood Drive, San Rafael, California 94903-1996 (e-mail: BruceHoadley@ FairIsaac.com). next 6 months. The goal is to estimate the function, $f(\mathbf{x})=\log (\operatorname{Pr}\{y=1 \mid \mathbf{x}\} / \operatorname{Pr}\{y=0 \mid \mathbf{x}\}) .$ Professor Breiman argues that some kind of simple logistic regression from the data modeling culture is not the way to solve this problem. I agree. Let's take a look at how the engineers at Fair, Isaac solved this problem -way back in the $1960 \mathrm{~s}$ and $1970 \mathrm{~s}$.

The general form used for $f(\mathbf{x})$ was called a segmented scorecard. The process for developing a segmented scorecard was clearly an algorithmic modeling process.

The first step was to transform $\mathbf{x}$ into many interpretable variables called prediction characteristics. This was done in stages. The first stage was to compute several time series derived from the original two. An example is the time series of months delinquent-a nonlinear function. The second stage was to define characteristics as operators on the time series. For example, the number of times in the last six months that the customer was more than two months delinquent. This process can lead to thousands of characteristics. A subset of these characteristics passes a screen for further analysis.

The next step was to segment the population based on the screened characteristics. The segmentation was done somewhat informally. But when I looked at the process carefully, the segments turned out to be the leaves of a shallow-to-medium tree. And the tree was built sequentially using mostly binary splits based on the best splitting characteristics-defined in a reasonable way. The algorithm was manual, but similar in concept to the CART algorithm, with a different purity index.

Next, a separate function, $f(\mathbf{x})$, was developed for each segment. The function used was called a scorecard. Each characteristic was chopped up into discrete intervals or sets called attributes. A scorecard was a linear function of the attribute indicator (dummy) variables derived from the characteristics. The coefficients of the dummy variables were called score weights.

This construction amounted to an explosion of dimensionality. They started with 24 predictors. These were transformed into hundreds of characteristics and pared down to about 100 characteristics. Each characteristic was discretized into about 10 attributes, and there were about 10 segments. This makes $100 \times 10 \times 10=10,000$ features. Yes indeed, dimensionality is a blessing. What Fair, Isaac calls a scorecard is now elsewhere called a generalized additive model (GAM) with bin smoothing. However, a simple GAM would not do. Client demand, legal considerations and robustness over time led to the concept of score engineering. For example, the score had to be monotonically decreasing in certain delinquency characteristics. Prior judgment also played a role in the design of scorecards. For some characteristics, the score weights were shrunk toward zero in order to moderate the influence of these characteristics. For other characteristics, the score weights were expanded in order to increase the influence of these characteristics. These adjustments were not done willy-nilly. They were done to overcome known weaknesses in the data.

So how did these Fair, Isaac pioneers fit these complicated GAM models back in the 1960 s and 1970 s? Logistic regression was not generally available. And besides, even today's commercial GAM software will not handle complex constraints. What they did was to maximize (subject to constraints) a measure called divergence, which measures how well the score, $S$, separates the two populations with different values of $y$. The formal definition of divergence is $2(E[S \mid y=1]-E[S \mid y=0])^{2} /(V[S \mid y=$ 1] $+V[S \mid y=0]$. This constrained fitting was done with a heuristic nonlinear programming algorithm. A linear transformation was used to convert to a log odds scale.

Characteristic selection was done by analyzing the change in divergence after adding (removing) each candidate characteristic to (from) the current best model. The analysis was done informally to achieve good performance on the test sample. There were no formal tests of fit and no tests of score weight statistical significance. What counted was performance on the test sample, which was a surrogate for the future real world.

These early Fair, Isaac engineers were ahead of their time and charter members of the algorithmic modeling culture. The score formula was linear in an exploded dimension. A complex algorithm was used to fit the model. There was no claim that the final score formula was correct, only that it worked well on the test sample. This approach grew naturally out of the demands of the business and the quality of the data. The overarching goal was to develop tools that would help clients make better decisions through data. What emerged was a very accurate and palatable algorithmic modeling solution, which belies Breiman's statement: "The algorithmic modeling methods available in the pre1980 s decades seem primitive now." At a recent ASA meeting, I heard talks on treed regression, which looked like segmented scorecards to me.

After a few years with Fair, Isaac, I developed a talk entitled, "Credit Scoring-A Parallel Universe of Prediction and Classification." The theme was that Fair, Isaac developed in parallel many of the concepts used in modern algorithmic modeling.

Certain aspects of the data modeling culture crept into the Fair, Isaac approach. The use of divergence was justified by assuming that the score distributions were approximately normal. So rather than making assumptions about the distribution of the inputs, they made assumptions about the distribution of the output. This assumption of normality was supported by a central limit theorem, which said that sums of many random variables are approximately normal-even when the component random variables are dependent and multiples of dummy random variables.

Modern algorithmic classification theory has shown that excellent classifiers have one thing in common, they all have large margin. Margin, $M$, is a random variable that measures the comfort level with which classifications are made. When the correct classification is made, the margin is positive; it is negative otherwise. Since margin is a random variable, the precise definition of large margin is tricky. It does not mean that $E[M]$ is large. When I put my data modeling hat on, I surmised that large margin means that $E[M] / \sqrt{V(M)}$ is large. Lo and behold, with this definition, large margin means large divergence.

Since the good old days at Fair, Isaac, there have been many improvements in the algorithmic modeling approaches. We now use genetic algorithms to screen very large structured sets of prediction characteristics. Our segmentation algorithms have been automated to yield even more predictive systems. Our palatable GAM modeling tool now handles smooth splines, as well as splines mixed with step functions, with all kinds of constraint capability. Maximizing divergence is still a favorite, but we also maximize constrained GLM likelihood functions. We also are experimenting with computationally intensive algorithms that will optimize any objective function that makes sense in the business environment. All of these improvements are squarely in the culture of algorithmic modeling.

##  OVERFITTING THE TEST SAMPLE

Professor Breiman emphasizes the importance of performance on the test sample. However, this can be overdone. The test sample is supposed to represent the population to be encountered in the future. But in reality, it is usually a random sample of the current population. High performance on the test sample does not guarantee high performance on future samples, things do change. There are practices that can be followed to protect against change.

One can monitor the performance of the models over time and develop new models when there has been sufficient degradation of performance. For some of Fair, Isaac's core products, the redevelopment cycle is about 18-24 months. Fair, Isaac also does "score engineering" in an attempt to make the models more robust over time. This includes damping the influence of individual characteristics, using monotone constraints and minimizing the size of the models subject to performance constraints on the current test sample. This score engineering amounts to moving from very nonparametric (no score engineering) to more semiparametric (lots of score engineering).

##  SPIN-OFFS FROM THE DATA MODELING CULTURE

In Section 6 of Professor Breiman's paper, he says that "multivariate analysis tools in statistics are frozen at discriminant analysis and logistic regression in classification ...." This is not necessarily all that bad. These tools can carry you very far as long as you ignore all of the textbook advice on how to use them. To illustrate, I use the saga of the Fat Scorecard.

Early in my research days at Fair, Isaac, I was searching for an improvement over segmented scorecards. The idea was to develop first a very good global scorecard and then to develop small adjustments for a number of overlapping segments. To develop the global scorecard, I decided to use logistic regression applied to the attribute dummy variables. There were 36 characteristics available for fitting. A typical scorecard has about 15 characteristics. My variable selection was structured so that an entire characteristic was either in or out of the model. What I discovered surprised me. All models fit with anywhere from 27 to 36 characteristics had the same performance on the test sample. This is what Professor Breiman calls "Rashomon and the multiplicity of good models." To keep the model as small as possible, I chose the one with 27 characteristics. This model had 162 score weights (logistic regression coefficients), whose $P$ values ranged from $0.0001$ to $0.984$, with only one less than $0.05$; i.e., statistically significant. The confidence intervals for the 162 score weights were useless. To get this great scorecard, I had to ignore the conventional wisdom on how to use logistic regression. So far, all I had was the scorecard GAM. So clearly I was missing all of those interactions that just had to be in the model. To model the interactions, I tried developing small adjustments on various overlapping segments. No matter how hard I tried, nothing improved the test sample performance over the global scorecard. I started calling it the Fat Scorecard.

Earlier, on this same data set, another Fair, Isaac researcher had developed a neural network with 2,000 connection weights. The Fat Scorecard slightly outperformed the neural network on the test sample. I cannot claim that this would work for every data set. But for this data set, I had developed an excellent algorithmic model with a simple data modeling tool.

Why did the simple additive model work so well? One idea is that some of the characteristics in the model are acting as surrogates for certain interaction terms that are not explicitly in the model. Another reason is that the scorecard is really a sophisticated neural net. The inputs are the original inputs. Associated with each characteristic is a hidden node. The summation functions coming into the hidden nodes are the transformations defining the characteristics. The transfer functions of the hidden nodes are the step functions (compiled from the score weights)-all derived from the data. The final output is a linear function of the outputs of the hidden nodes. The result is highly nonlinear and interactive, when looked at as a function of the original inputs.

The Fat Scorecard study had an ingredient that is rare. We not only had the traditional test sample, but had three other test samples, taken one, two, and three years later. In this case, the Fat Scorecard outperformed the more traditional thinner scorecard for all four test samples. So the feared overfitting to the traditional test sample never materialized. To get a better handle on this you need an understanding of how the relationships between variables evolve over time.

I recently encountered another connection between algorithmic modeling and data modeling. In classical multivariate discriminant analysis, one assumes that the prediction variables have a multivariate normal distribution. But for a scorecard, the prediction variables are hundreds of attribute dummy variables, which are very nonnormal. However, if you apply the discriminant analysis algorithm to the attribute dummy variables, you can get a great algorithmic model, even though the assumptions of discriminant analysis are severely violated. 

## A SOLUTION TO THE OCCAM DILEMMA

I think that there is a solution to the Occam dilemma without resorting to goal-oriented arguments. Clients really do insist on interpretable functions, $f(\mathbf{x})$. Segmented palatable scorecards are very interpretable by the customer and are very accurate. Professor Breiman himself gave single trees an A+ on interpretability. The shallow-tomedium tree in a segmented scorecard rates an A++. The palatable scorecards in the leaves of the trees are built from interpretable (possibly complex) characteristics. Sometimes we can't implement them until the lawyers and regulators approve. And that requires super interpretability. Our more sophisticated products have 10 to 20 segments and up to 100 characteristics (not all in every segment). These models are very accurate and very interpretable.

I coined a phrase called the "Ping-Pong theorem." This theorem says that if we revealed to Professor Breiman the performance of our best model and gave him our data, then he could develop an algorithmic model using random forests, which would outperform our model. But if he revealed to us the performance of his model, then we could develop a segmented scorecard, which would outperform his model. We might need more characteristics, attributes and segments, but our experience in this kind of contest is on our side.

However, all the competing models in this game of Ping-Pong would surely be algorithmic models. But some of them could be interpretable.

## THE ALGORITHM TUNING DILEMMA

As far as I can tell, all approaches to algorithmic model building contain tuning parameters, either explicit or implicit. For example, we use penalized objective functions for fitting and marginal contribution thresholds for characteristic selection. With experience, analysts learn how to set these tuning parameters in order to get excellent test sample or cross-validation results. However, in industry and academia, there is sometimes a little tinkering, which involves peeking at the test sample. The result is some bias in the test sample or crossvalidation results. This is the same kind of tinkering that upsets test of fit pureness. This is a challenge for the algorithmic modeling approach. How do you optimize your results and get an unbiased estimate of the generalization error?

## GENERALIZING THE GENERALIZATION ERROR

In most commercial applications of algorithmic modeling, the function, $f(\mathbf{x})$, is used to make decisions. In some academic research, classification is used as a surrogate for the decision process, and misclassification error is used as a surrogate for profit. However, I see a mismatch between the algorithms used to develop the models and the business measurement of the model's value. For example, at Fair, Isaac, we frequently maximize divergence. But when we argue the model's value to the clients, we don't necessarily brag about the great divergence. We try to use measures that the client can relate to. The ROC curve is one favorite, but it may not tell the whole story. Sometimes, we develop simulations of the client's business operation to show how the model will improve their situation. For example, in a transaction fraud control process, some measures of interest are false positive rate, speed of detection and dollars saved when $0.5 \%$ of the transactions are flagged as possible frauds. The $0.5 \%$ reflects the number of transactions that can be processed by the current fraud management staff. Perhaps what the client really wants is a score that will maximize the dollars saved in their fraud control system. The score that maximizes test set divergence or minimizes test set misclassifications does not do it. The challenge for algorithmic modeling is to find an algorithm that maximizes the generalization dollars saved, not generalization error.

We have made some progress in this area using ideas from support vector machines and boosting. By manipulating the observation weights used in standard algorithms, we can improve the test set performance on any objective of interest. But the price we pay is computational intensity.

## MEASURING IMPORTANCE-IS IT REALLY POSSIBLE?

I like Professor Breiman's idea for measuring the importance of variables in black box models. A Fair, Isaac spin on this idea would be to build accurate models for which no variable is much more important than other variables. There is always a chance that a variable and its relationships will change in the future. After that, you still want the model to work. So don't make any variable dominant

I think that there is still an issue with measuring importance. Consider a set of inputs and an algorithm that yields a black box, for which $x_{1}$ is important. From the "Ping Pong theorem" there exists a set of input variables, excluding $x_{1}$ and an algorithm that will yield an equally accurate black box. For this black box, $x_{1}$ is unimportant. 

## IN SUMMARY

Algorithmic modeling is a very important area of statistics. It has evolved naturally in environments with lots of data and lots of decisions. But you can do it without suffering the Occam dilemma; for example, use medium trees with interpretable

# Comment: Emanuel Parzen


## 1. BREIMAN DESERVES OUR APPRECIATION

I strongly support the view that statisticians must face the crisis of the difficulties in their practice of regression. Breiman alerts us to systematic blunders (leading to wrong conclusions) that have been committed applying current statistical practice of data modeling. In the spirit of "statistician, avoid doing harm" I propose that the first goal of statistical ethics should be to guarantee to our clients that any mistakes in our analysis are unlike any mistakes that statisticians have made before.

The two goals in analyzing data which Leo calls prediction and information I prefer to describe as "management" and "science." Management seeks profit, practical answers (predictions) useful for decision making in the short run. Science seeks truth, fundamental knowledge about nature which provides understanding and control in the long run. As a historical note, Student's $t$-test has many scientific applications but was invented by Student as a management tool to make Guinness beer better (bitter?).

Breiman does an excellent job of presenting the case that the practice of statistical science, using only the conventional data modeling culture, needs reform. He deserves much thanks for alerting us to the algorithmic modeling culture. Breiman warns us that "if the model is a poor emulation of nature, the conclusions may be wrong." This situation, which I call "the right answer to the wrong question," is called by statisticians "the error of the third kind." Engineers at M.I.T. define "suboptimization" as “elegantly solving the wrong problem."

Emanuel Parzen is Distinguished Professor, Department of Statistics, Texas A\&M University, $415 \mathrm{C}$ Block Building, College Station, Texas 77843 (e-mail: eparzen@stat.tamu.edu). GAMs in the leaves. They are very accurate and interpretable. And you can do it with data modeling tools as long as you (i) ignore most textbook advice, (ii) embrace the blessing of dimensionality, (iii) use constraints in the fitting optimizations (iv) use regularization, and (v) validate the results.

Breiman presents the potential benefits of algorithmic models (better predictive accuracy thandata models, and consequently better information about the underlying mechanism and avoiding questionable conclusions which results from weak predictive accuracy) and support vector machines (which provide almost perfect separation and discrimination between two classes by increasing the dimension of the feature set). He convinces me that the methods of algorithmic modeling are important contributions to the tool kit of statisticians.

If the profession of statistics is to remain healthy, and not limit its research opportunities, statisticians must learn about the cultures in which Breiman works, but also about many other cultures of statistics.

## 2. HYPOTHESES TO TEST TO AVOID BLUNDERS OF STATISTICAL MODELING

Breiman deserves our appreciation for pointing out generic deviations from standard assumptions (which I call bivariate dependence and two-sample conditional clustering) for which we should routinely check. "Test null hypothesis" can be a useful algorithmic concept if we use tests that diagnose in a model-free way the directions of deviation from the null hypothesis model.

Bivariate dependence (correlation) may exist between features [independent (input) variables] in a regression causing them to be proxies for each other and our models to be unstable with different forms of regression models being equally well fitting. We need tools to routinely test the hypothesis of statistical independence of the distributions of independent (input) variables.

Two sample conditional clustering arises in the distributions of independent (input) variables to discriminate between two classes, which we call the conditional distribution of input variables $X$ given each class. Class 1 may have only one mode (cluster) at low values of $X$ while class II has two modes (clusters) at low and high values of $X$. We would like to conclude that high values of $X$ are observed only for members of class II but low values of $X$ occur for members of both classes. The hypothesis we propose testing is equality of the pooled distribution of both samples and the conditional distribution of sample I, which is equivalent to $P[$ class $I \mid X]=P[$ class $I]$ For successful discrimination one seeks to increase the number (dimension) of inputs (features) $X$ to make $P[$ class $I \mid X]$ close to 1 or 0 .

## 3. STATISTICAL MODELING, MANY CULTURES, STATISTICAL METHODS MINING

Breiman speaks of two cultures of statistics; I believe statistics has many cultures. At specialized workshops (on maximum entropy methods or robust methods or Bayesian methods or $\ldots$ ) a main topic of conversation is "Why don't all statisticians think like us?”

I have my own eclectic philosophy of statistical modeling to which I would like to attract serious attention. I call it "statistical methods mining" which seeks to provide a framework to synthesize and apply the past half-century of methodological progress in computationally intensive methods for statistical modeling, including EDA (exploratory data analysis), FDA (functional data analysis), density estimation, Model DA (model selection criteria data analysis), Bayesian priors on function space, continuous parameter regression analysis and reproducing kernels, fast algorithms, Kalman filtering, complexity, information, quantile data analysis, nonparametric regression, conditional quantiles.

I believe "data mining" is a special case of "data modeling." We should teach in our introductory courses that one meaning of statistics is "statistical data modeling done in a systematic way" by an iterated series of stages which can be abbreviated SIEVE (specify problem and general form of models, identify tentatively numbers of parameters and specialized models, estimate parameters, validate goodness-of-fit of estimated models, estimate final model nonparametrically or algorithmically). MacKay and Oldford (2000) brilliantly present the statistical method as a series of stages PPDAC (problem, plan, data, analysis, conclusions).

## 4. QUANTILE CULTURE, ALGORITHMIC MODEL

A culture of statistical data modeling based on quantile functions, initiated in Parzen (1979), has been my main research interest since 1976 . In my discussion to Stone (1977) I outlined a novel approach to estimation of conditional quantile functions which I only recently fully implemented. I would like to extend the concept of algorithmic statistical models in two ways: (1) to mean data fitting by representations which use approximation theory and numerical analysis; (2) to use the notation of probability to describe empirical distributions of samples (data sets) which are not assumed to be generated by a random mechanism.

My quantile culture has not yet become widely applied because "you cannot give away a good idea, you have to sell it" (by integrating it in computer programs usable by applied statisticians and thus promote statistical methods mining).

A quantile function $Q(u), 0 \leq u \leq 1$, is the inverse $F^{-1}(u)$ of a distribution function $F(x)$, $-\infty<x<\infty .$ Its rigorous definition is $Q(u)=$ $\inf (x: F(x) \geq u)$. When $F$ is continuous with density $f, F(Q(u))=u, q(u)=Q^{\prime}(u)=1 / f(Q(u))$. We use the notation $Q$ for a true unknown quantile function, $Q$ for a raw estimator from a sample, and $Q$ for a smooth estimator of the true $Q$.

Concepts defined for $Q(u)$ can be defined also for other versions of quantile functions. Quantile functions can "compress data" by a five-number summary, values of $Q(u)$ at $u=0.5,0.25,0.75,0.1,0.9$ (or $0.05,0.95$ ). Measures of location and scale are $Q M=0.5(Q(0.25)+Q(0.75)), Q D=2(Q(0.75)-$ Q (0.25)). To use quantile functions to identify distributions fitting data we propose the quantilequartile function $Q / Q(u)=(Q(u)-Q M) / Q D$. Five-number summary of distribution becomes QM, QD, Q/Q(0.5) skewness, Q/Q(0.1) left-tail, Q/Q(0.9) right-tail. Elegance of $Q / Q(u)$ is its universal values at $u=0.25,0.75$. Values $|Q / Q(u)|>1$ are outliers as defined by Tukey EDA.

For the fundamental problem of comparison of two distributions $F$ and $G$ we define the comparison distribution $D(u ; F, G)$ and comparison density $d(u ; F, G)=D^{\prime}(u ; F, G)$. For $F, G$ continuous, define $D(u ; F, G)=G\left(F^{-1}(u)\right), d(u ; F, G)=$ $g\left(F^{-1}(u)\right) / f\left(F^{-1}(u)\right)$ assuming $f(x)=0$ implies $g(x)=0$, written $G \ll F$. For $F, G$ discrete with probability mass functions $p_{F}$ and $p_{G}$ define (assum$\operatorname{ing} G \ll F) d(u ; F, G)=p_{G}\left(F^{-1}(u)\right) / p_{F}\left(F^{-1}(u)\right)$

Our applications of comparison distributions often assume $F$ to be an unconditional distribution and $G$ a conditional distribution. To analyze bivariate data $(X, Y)$ a fundamental tool is dependence density $d(t, u)=d\left(u ; F_{Y}, F_{Y \mid X=Q_{X}(t)}\right)$. When $X, Y$ is jointly continuous,

$$
\begin{aligned}
&d(t, u) \\
&\quad=f_{X, Y}\left(Q_{X}(t), Q_{Y}(u)\right) / f_{X}\left(Q_{X}(t)\right) f_{Y}\left(Q_{Y}(u)\right)
\end{aligned}
$$

The statistical independence hypothesis $F_{X, Y}=$ $F_{X} F_{Y}$ is equivalent to $d(t, u)=1$, all $t, u$. A fundamental formula for estimation of conditional quantile functions is

$$
\begin{aligned}
Q_{Y \mid X=x}(u) &=Q_{Y}\left(D^{-1}\left(u ; F_{Y}, F_{Y \mid X=x}\right)\right) \\
&=Q_{Y}(s), u=D\left(s ; F_{Y}, F_{Y \mid X=x}\right)
\end{aligned}
$$

To compare the distributions of two univariate samples, let $Y$ denote the continuous response variable and $X$ be binary 0,1 denoting the population from which $Y$ is observed. The comparison density is defined (note $F_{Y}$ is the pooled distribution function)

$$
\begin{aligned}
d_{1}(u) &=d\left(u ; F_{Y}, F_{Y \mid X=1}\right) \\
&=P\left[X=1 \mid Y=Q_{Y}(u)\right] / P[X=1]
\end{aligned}
$$

## 5. QUANTILE IDEAS FOR HIGH DIMENSIONAL DATA ANALYSIS

By high dimensional data we mean multivariate data $\left(Y_{1}, \ldots, Y_{m}\right)$. We form approximate high dimensional comparison densities $d\left(u_{1}, \ldots, u_{m}\right)$ to test statistical independence of the variables and, when we have two samples, $d_{1}\left(u_{1}, \ldots, u_{m}\right)$ to test equality of sample $I$ with pooled sample. All our distributions are empirical distributions but we use notation for true distributions in our formulas. Note that

$$
\int_{0}^{1} d u_{1} \ldots \int_{0}^{1} d u_{m} d\left(u_{1}, \ldots, u_{m}\right) d_{1}\left(u_{1}, \ldots, u_{m}\right)=1
$$

A decile quantile bin $B\left(k_{1}, \ldots, k_{m}\right)$ is defined to be the set of observations $\left(Y_{1}, \ldots, Y_{m}\right)$ satisfying, for $j=1, \ldots, m, Q_{Y_{j}}\left(\left(k_{j}-1\right) / 10\right)<Y_{j} \leq$

# Rejoinder: Leo Breiman

I thank the discussants. I'm fortunate to have comments from a group of experienced and creative statisticians - even more so in that their comments are diverse. Manny Parzen and Bruce Hoadley are more or less in agreement, Brad Efron has serious reservations and D. R. Cox is in downright disagreement.

I address Professor Cox's comments first, since our disagreement is crucial.

## D. R. COX

Professor Cox is a worthy and thoughtful adversary. We walk down part of the trail together and $Q_{Y_{i}}\left(k_{j} / 10\right)$. Instead of deciles $k / 10$ we could use $k / M$ for another base $M$.

To test the hypothesis that $Y_{1}, \ldots, Y_{m}$ are statistically independent we form for all $k_{j}=1, \ldots, 10$,

$$
d\left(k_{1}, \ldots, k_{m}\right)=P\left[\operatorname{Bin}\left(k_{1}, \ldots, k_{m}\right)\right] /
$$

$$
P\left[\operatorname{Bin}\left(k_{1}, \ldots, k_{m}\right) \mid\right. \text { independence]. }
$$

To test equality of distribution of a sample from population $I$ and the pooled sample we form

$$
\begin{aligned}
&d_{1}\left(k_{1}, \ldots, k_{m}\right) \\
&=P\left[\operatorname{Bin}\left(k_{1}, \ldots, k_{m}\right) \mid \text { population } I\right] / \\
&\quad P\left[\operatorname{Bin}\left(k_{1}, \ldots, k_{m}\right) \mid\right. \text { pooled sample] }
\end{aligned}
$$

for all $\left(k_{1}, \ldots, k_{m}\right)$ such that the denominator is positive and otherwise defined arbitrarily. One can show (letting $X$ denote the population observed)

$$
\begin{aligned}
d_{1}\left(k_{1}, \ldots, k_{m}\right)=& P[X=I \mid \text { observation from }\\
&\left.\operatorname{Bin}\left(k_{1}, \ldots, k_{m}\right)\right] / P[X=I]
\end{aligned}
$$

To test the null hypotheses in ways that detect directions of deviations from the null hypothesis our recommended first step is quantile data analysis of the values $d\left(k_{1}, \ldots, k_{m}\right)$ and $d_{1}\left(k_{1}, \ldots, k_{m}\right)$

I appreciate this opportunity to bring to the attention of researchers on high dimensional data analysis the potential of quantile methods. My conclusion is that statistical science has many cultures and statisticians will be more successful when they emulate Leo Breiman and apply as many cultures as possible (which I call statistical methods mining). Additional references are on my web site at stat.tamu.edu.

then sharply diverge. To begin, I quote: "Professor Breiman takes data as his starting point. I would prefer to start with an issue, a question, or a scientific hypothesis,...." I agree, but would expand the starting list to include the prediction of future events. I have never worked on a project that has started with "Here is a lot of data; let's look at it and see if we can get some ideas about how to use it." The data has been put together and analyzed starting with an objective.

## C1 Data Models Can Be Useful

Professor Cox is committed to the use of data models. I readily acknowledge that there are situations where a simple data model may be useful and appropriate; for instance, if the science of the mechanism producing the data is well enough known to determine the model apart from estimating parameters. There are also situations of great complexity posing important issues and questions in which there is not enough data to resolve the questions to the accuracy desired. Simple models can then be useful in giving qualitative understanding, suggesting future research areas and the kind of additional data that needs to be gathered.

At times, there is not enough data on which to base predictions; but policy decisions need to be made. In this case, constructing a model using whatever data exists, combined with scientific common sense and subject-matter knowledge, is a reasonable path. Professor Cox points to examples when he writes:

Often the prediction is under quite different conditions from the data; what is the likely progress of the incidence of the epidemic of $v-C J D$ in the United Kingdom, what would be the effect on annual incidence of cancer in the United States reducing by $10 \%$ the medical use of X-rays, etc.? That is, it may be desired to predict the consequences of something only indirectly addressed by the data available for analysis... prediction, always hazardous, without some understanding of the underlying process and linking with other sources of information, becomes more and more tentative.

I agree.

## C2 Data Models Only

From here on we part company. Professor Cox's discussion consists of a justification of the use of data models to the exclusion of other approaches. For instance, although he admits, “... I certainly accept, although it goes somewhat against the grain to do so, that there are situations where a directly empirical approach is better..." the two examples he gives of such situations are short-term economic forecasts and real-time flood forecasts-among the less interesting of all of the many current successful algorithmic applications. In his view, the only use for algorithmic models is short-term forecasting; there are no comments on the rich information about the data and covariates available from random forests or in the many fields, such as pattern recognition, where algorithmic modeling is fundamental. He advocates construction of stochastic data models that summarize the understanding of the phenomena under study. The methodology in the Cox and Wermuth book (1996) attempts to push understanding further by finding casual orderings in the covariate effects. The sixth chapter of this book contains illustrations of this approach on four data sets.

The first is a small data set of 68 patients with seven covariates from a pilot study at the University of Mainz to identify pyschological and socioeconomic factors possibly important for glucose control in diabetes patients. This is a regression-type problem with the response variable measured by GHb (glycosylated haemoglobin). The model fitting is done by a number of linear regressions and validated by the checking of various residual plots. The only other reference to model validation is the statement, $" R^{2}=0.34$, reasonably large by the standards usual for this field of study." Predictive accuracy is not computed, either for this example or for the three other examples.

My comments on the questionable use of data models apply to this analysis. Incidentally, I tried to get one of the data sets used in the chapter to conduct an alternative analysis, but it was not possible to get it before my rejoinder was due. It would have been interesting to contrast our two approaches.

## C3 Approach to Statistical Problems

Basing my critique on a small illustration in a book is not fair to Professor Cox. To be fairer, I quote his words about the nature of a statistical analysis:

Formal models are useful and often almost, if not quite, essential for incisive thinking. Descriptively appealing and transparent methods with a firm model base are the ideal. Notions of significance tests, confidence intervals, posterior intervals, and all the formal apparatus of inference are valuable tools to be used as guides, but not in a mechanical way; they indicate the uncertainty that would apply under somewhat idealized, maybe very idealized, conditions and as such are often lower bounds to real uncertainty. Analyses and model development are at least partly exploratory. Automatic methods of model selection (and of variable selection in regressionlike problems) are to be shunned or, if use is absolutely unavoidable, are to be examined carefully for their effect on the final conclusions. Unfocused tests of model adequacy are rarely helpful. Given the right kind of data: relatively small sample size and a handful of covariates, I have no doubt that his experience and ingenuity in the craft of model construction would result in an illuminating model. But data characteristics are rapidly changing. In many of the most interesting current problems, the idea of starting with a formal model is not tenable.

## C4 Changes in Problems

My impression from Professor Cox's comments is that he believes every statistical problem can be best solved by constructing a data model. I believe that statisticians need to be more pragmatic. Given a statistical problem, find a good solution, whether it is a data model, an algorithmic model or (although it is somewhat against my grain), a Bayesian data model or a completely different approach.

My work on the 1990 Census Adjustment (Breiman, 1994) involved a painstaking analysis of the sources of error in the data. This was done by a long study of thousands of pages of evaluation documents. This seemed the most appropriate way of answering the question of the accuracy of the adjustment estimates.

The conclusion that the adjustment estimates were largely the result of bad data has never been effectively contested and is supported by the results of the Year 2000 Census Adjustment effort. The accuracy of the adjustment estimates was, arguably, the most important statistical issue of the last decade, and could not be resolved by any amount of statistical modeling.

A primary reason why we cannot rely on data models alone is the rapid change in the nature of statistical problems. The realm of applications of statistics has expanded more in the last twenty-five years than in any comparable period in the history of statistics.

In an astronomy and statistics workshop this year, a speaker remarked that in twenty-five years we have gone from being a small sample-size science to a very large sample-size science. Astronomical data bases now contain data on two billion objects comprising over 100 terabytes and the rate of new information is accelerating.

A recent biostatistics workshop emphasized the analysis of genetic data. An exciting breakthrough is the use of microarrays to locate regions of gene activity. Here the sample size is small, but the number of variables ranges in the thousands. The questions are which specific genes contribute to the occurrence of various types of diseases.

Questions about the areas of thinking in the brain are being studied using functional MRI. The data gathered in each run consists of a sequence of 150,000 pixel images. Gigabytes of satellite information are being used in projects to predict and understand short- and long-term environmental and weather changes.

Underlying this rapid change is the rapid evolution of the computer, a device for gathering, storing and manipulation of incredible amounts of data, together with technological advances incorporating computing, such as satellites and MRI machines.

The problems are exhilarating. The methods used in statistics for small sample sizes and a small number of variables are not applicable. John Rice, in his summary talk at the astronomy and statistics workshop said, "Statisticians have to become opportunistic." That is, faced with a problem, they must find a reasonable solution by whatever method works. One surprising aspect of both workshops was how opportunistic statisticians faced with genetic and astronomical data had become. Algorithmic methods abounded.

## C5 Mainstream Procedures and Tools

Professor Cox views my critique of the use of data models as based in part on a caricature. Regarding my references to articles in journals such as JASA, he states that they are not typical of mainstream statistical analysis, but are used to illustrate technique rather than explain the process of analysis. His concept of mainstream statistical analysis is summarized in the quote given in my Section $\mathrm{C} 3$. It is the kind of thoughtful and careful analysis that he prefers and is capable of.

Following this summary is the statement:

By contrast, Professor Breiman equates mainstream applied statistics to a relatively mechanical process involving somehow or other choosing a model, often a default model of standard form, and applying standard methods of analysis and goodness-of-fit procedures.

The disagreement is definitional-what is "mainstream"? In terms of numbers my definition of mainstream prevails, I guess, at a ratio of at least 100 to 1 . Simply count the number of people doing their statistical analysis using canned packages, or count the number of SAS licenses.

In the academic world, we often overlook the fact that we are a small slice of all statisticians and an even smaller slice of all those doing analyses of data. There are many statisticians and nonstatisticians in diverse fields using data to reach conclusions and depending on tools supplied to them by SAS, SPSS, etc. Their conclusions are important and are sometimes published in medical or other subject-matter journals. They do not have the statistical expertise, computer skills, or time needed to construct more appropriate tools. I was faced with this problem as a consultant when confined to using the BMDP linear regression, stepwise linear regression, and discriminant analysis programs. My concept of decision trees arose when I was faced with nonstandard data that could not be treated by these standard methods.

When I rejoined the university after my consulting years, one of my hopes was to provide better general purpose tools for the analysis of data. The first step in this direction was the publication of the CART book (Breiman et al., 1984). CART and other similar decision tree methods are used in thousands of applications yearly in many fields. It has proved robust and reliable. There are others that are more recent; random forests is the latest. A preliminary version of random forests is free source with $f 77$ code, $S+$ and $R$ interfaces available at www.stat.berkeley.edu/users/breiman.

A nearly completed second version will also be put on the web site and translated into Java by the Weka group. My collaborator, Adele Cutler, and I will continue to upgrade, add new features, graphics, and a good interface.

My philosophy about the field of academic statistics is that we have a responsibility to provide the many people working in applications outside of academia with useful, reliable, and accurate analysis tools. Two excellent examples are wavelets and decision trees. More are needed.

## BRAD EFRON

Brad seems to be a bit puzzled about how to react to my article. I'll start with what appears to be his biggest reservation.

## E1 From Simple to Complex Models

Brad is concerned about the use of complex models without simple interpretability in their structure, even though these models may be the most accurate predictors possible. But the evolution of science is from simple to complex.

The equations of general relativity are considerably more complex and difficult to understand than Newton's equations. The quantum mechanical equations for a system of molecules are extraordinarily difficult to interpret. Physicists accept these complex models as the facts of life, and do their best to extract usable information from them.

There is no consideration given to trying to understand cosmology on the basis of Newton's equations or nuclear reactions in terms of hard ball models for atoms. The scientific approach is to use these complex models as the best possible descriptions of the physical world and try to get usable information out of them.

There are many engineering and scientific applications where simpler models, such as Newton's laws, are certainly sufficient-say, in structural design. Even here, for larger structures, the model is complex and the analysis difficult. In scientific fields outside statistics, answering questions is done by extracting information from increasingly complex and accurate models.

The approach I suggest is similar. In genetics, astronomy and many other current areas statistics is needed to answer questions, construct the most accurate possible model, however complex, and then extract usable information from it.

Random forests is in use at some major drug companies whose statisticians were impressed by its ability to determine gene expression (variable importance) in microarray data. They were not concerned about its complexity or black-box appearance.

## E2 Prediction

Leo's paper overstates both its [prediction's] role, and our profession's lack of interest in it... Most statistical surveys have the identification of causal factors as their ultimate role.

My point was that it is difficult to tell, using goodness-of-fit tests and residual analysis, how well a model fits the data. An estimate of its test set accuracy is a preferable assessment. If, for instance, a model gives predictive accuracy only slightly better than the "all survived" or other baseline estimates, we can't put much faith in its reliability in the identification of causal factors.

I agree that often “... statistical surveys have the identification of casual factors as their ultimate role." I would add that the more predictively accurate the model is, the more faith can be put into the variables that it fingers as important.

## E3 Variable Importance

A significant and often overlooked point raised by Brad is what meaning can one give to statements that "variable $X$ is important or not important." This has puzzled me on and off for quite a while. In fact, variable importance has always been defined operationally. In regression the "important" variables are defined by doing "best subsets" or variable deletion.

Another approach used in linear methods such as logistic regression and survival models is to compare the size of the slope estimate for a variable to its estimated standard error. The larger the ratio, the more "important" the variable. Both of these definitions can lead to erroneous conclusions.

My definition of variable importance is based on prediction. A variable might be considered important if deleting it seriously affects prediction accuracy. This brings up the problem that if two variables are highly correlated, deleting one or the other of them will not affect prediction accuracy. Deleting both of them may degrade accuracy considerably. The definition used in random forests spots both variables.

"Importance" does not yet have a satisfactory theoretical definition (I haven't been able to locate the article Brad references but I'll keep looking). It depends on the dependencies between the output variable and the input variables, and on the dependencies between the input variables. The problem begs for research.

## E4 Other Reservations

Sample sizes have swollen alarmingly while goals grow less distinct ("find interesting data structure”).

I have not noticed any increasing fuzziness in goals, only that they have gotten more diverse. In the last two workshops I attended (genetics and astronomy) the goals in using the data were clearly laid out. "Searching for structure" is rarely seen even though data may be in the terabyte range.

The new algorithms often appear in the form of black boxes with enormous numbers of adjustable parameters ("knobs to twiddle").

This is a perplexing statement and perhaps I don't understand what Brad means. Random forests has only one adjustable parameter that needs to be set for a run, is insensitive to the value of this parameter over a wide range, and has a quick and simple way for determining a good value. Support vector machines depend on the settings of 1-2 parameters. Other algorithmic models are similarly sparse in the number of knobs that have to be twiddled.

New methods always look better than old ones. ... Complicated models are harder to criticize than simple ones. In $1992 \mathrm{I}$ went to my first NIPS conference. At that time, the exciting algorithmic methodology was neural nets. My attitude was grim skepticism. Neural nets had been given too much hype, just as AI had been given and failed expectations. I came away a believer. Neural nets delivered on the bottom line! In talk after talk, in problem after problem, neural nets were being used to solve difficult prediction problems with test set accuracies better than anything I had seen up to that time.

My attitude toward new and/or complicated methods is pragmatic. Prove that you've got a better mousetrap and I'll buy it. But the proof had better be concrete and convincing.

Brad questions where the bias and variance have gone. It is surprising when, trained in classical biasvariance terms and convinced of the curse of dimensionality, one encounters methods that can handle thousands of variables with little loss of accuracy. It is not voodoo statistics; there is some simple theory that illuminates the behavior of random forests (Breiman, 1999). I agree that more theoretical work is needed to increase our understanding.

Brad is an innovative and flexible thinker who has contributed much to our field. He is opportunistic in problem solving and may, perhaps not overtly, already have algorithmic modeling in his bag of tools.

## BRUCE HOADLEY

I thank Bruce Hoadley for his description of the algorithmic procedures developed at Fair, Isaac since the $1960 \mathrm{~s}$. They sound like people 1 would enjoy working with. Bruce makes two points of mild contention. One is the following:

High performance (predictive accuracy) on the test sample does not guarantee high performance on future samples; things do change.

I agree-algorithmic models accurate in one context must be modified to stay accurate in others. This does not necessarily imply that the way the model is constructed needs to be altered, but that data gathered in the new context should be used in the construction.

His other point of contention is that the Fair, Isaac algorithm retains interpretability, so that it is possible to have both accuracy and interpretability. For clients who like to know what's going on, that's a sellable item. But developments in algorithmic modeling indicate that the Fair, Isaac algorithm is an exception.

A computer scientist working in the machine learning area joined a large money management company some years ago and set up a group to do portfolio management using stock predictions given by large neural nets. When we visited, I asked how he explained the neural nets to clients. "Simple," he said; "We fit binary trees to the inputs and outputs of the neural nets and show the trees to the clients. Keeps them happy!" In both stock prediction and credit rating, the priority is accuracy. Interpretability is a secondary goal that can be finessed.

## MANNY PARZEN

Manny Parzen opines that there are not two but many modeling cultures. This is not an issue I want to fiercely contest. I like my division because it is pretty clear cut-are you modeling the inside of the box or not? For instance, I would include Bayesians in the data modeling culture. I will keep my eye on the quantile culture to see what develops.

Most of all, I appreciate Manny's openness to the issues raised in my paper. With the rapid changes in the scope of statistical problems, more open and concrete discussion of what works and what doesn't should be welcomed.

## WHERE ARE WE HEADING?

Many of the best statisticians I have talked to over the past years have serious concerns about the viability of statistics as a field. Oddly, we are in a period where there has never been such a wealth of new statistical problems and sources of data. The danger is that if we define the boundaries of our field in terms of familar tools and familar problems, we will fail to grasp the new opportunities

## ADDITIONAL REFERENCES

BEVERDIGE, W. V. I (1952) The Art of Scientific Investigation. Heinemann, London.

BREIMAN, L. (1994) The 1990 Census adjustment: undercount or bad data (with discussion)? Statist. Sci. 9 458-475.

Cox, D. R. and WERMUTH, N. (1996) Multivariate Dependencies. Chapman and Hall, London.

EFRON, B. and GoNG, G. (1983) A leisurely look at the bootstrap, the jackknife, and cross-validation. Amer. Statist. $\mathbf{3 7} 36$ - 48

EfRON, B. and TIBSHIRANI, R. (1996) Improvements on crossvalidation: the $632+$ rule. J. Amer. Statist. Assoc. 91 $548-560$

EFRON, B. and TIBSHIRANI, R. (1998) The problem of regions. Ann. Statist. $\mathbf{2 6} 1287-1318 .$

GoNG, G. (1982) Cross-validation, the jackknife, and the bootstrap: excess error estimation in forward logistic regression. Ph.D. dissertation, Stanford Univ.

MACKAY, R. J. and OLDFORD, R. W. (2000) Scientific method, statistical method, and the speed of light. Statist. Sci. $\mathbf{1 5}$ $224-253$

PARZEN, E. (1979) Nonparametric statistical data modeling (with discussion). J. Amer. Statist. Assoc. 74 105-131.

Stone, C. (1977) Consistent nonparametric regression. Ann. Statist. 5 595-645.

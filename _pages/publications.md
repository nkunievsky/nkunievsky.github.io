---
layout: page
permalink: /research/
title: research
nav: True
nav_order: 3
---
<!-- _pages/publications.md -->

[Google Scholar](https://scholar.google.com/citations?user=len-qnMAAAAJ&hl=en)

##### Working Papers

###### 2026

- Measuring Behavior Portability in Large Language Models with Tianjia Dong and James A. Evans [arXiv](https://arxiv.org/abs/2606.22797)

  <details>
  <summary>Abstract</summary>
  <p>Large language models are increasingly deployed as autonomous decision makers, yet the behavioral mapping they exhibit can vary substantially across decision environments that are payoff-equivalent by construction-environments that share identical payoff-relevant structure but differ in surface presentation. This sensitivity renders suite-based evaluation fragile and raises a fundamental question of behavioral portability: how well does a behavioral mapping learned in one decision environment informative on another that preserves the same underlying incentive structure? We introduce a formal framework to measure this property. Our protocol fits an interpretable behavioral model on data pooled from a set of source environments and evaluates its out-of-sample predictive performance in a held-out target environment, benchmarking against an oracle trained directly on target data. Portability is quantified via a loss-agnostic measure that delivers worst-case bounds on the performance of the induced prediction-action mapping in the target environment. In controlled experiments spanning seven canonical economic decision problems, we document substantial and systematic portability losses, suggesting that behavioral characterizations of LLMs obtained in one decision environment cannot be assumed to transfer reliably to structurally equivalent alternatives.</p>
  </details>

- U.S. Technological Containment and the Rise of China's Open AI Ecosystem with Wang Jin, Bowen Lou, Tianshu Sun, and James Evans [arXiv](https://arxiv.org/abs/2606.15999)

  <details>
  <summary>Abstract</summary>
  <p>Over the past decade, U.S. policies have increasingly aimed to preserve artificial intelligence (AI) leadership by promoting domestic free-market policies while controlling global technological chokepoints, particularly advanced semiconductors and computational infrastructure. These measures raised the cost of Chinese AI development, but they also increased the strategic value of open and locally adaptable AI systems. Before raising export controls on high-performance chips, both the U.S. and China promoted policies that included support for open-source AI. During the period following major U.S. export-control shocks, China increasingly embedded open-source AI into national technology strategy through proposed ecosystem building, standards coordination, and resilience-oriented deployment. Moreover, Chinese developers increased engagement with open-source large language model repositories substantially more than U.S. developers did, consistent with a shift toward open infrastructure under geopolitical constraints. Subsequently, Chinese-origin open models diffused widely through open-source communities and scientific research. Even though such models remained largely absent from U.S. patent disclosures, American commercial entities use them in open-access research, suggesting their undermeasured importance within the foundation of U.S. commercial activity. These findings suggest that technological containment can shape not only the direction of AI development, but also the ecosystems through which AI is developed, improved, and diffused.</p>
  </details>

- The Effect of Age at Arrival on the Alignment Between Immigrant and Native-Born Gender Norms: A Distributional Approach [arXiv](https://arxiv.org/abs/2603.23720)

  <details>
  <summary>Abstract</summary>
  <p>This paper examines how age at migration affects cultural assimilation by studying convergence in gender role attitudes between immigrants and the UK-born population. Although cultural values are central to policy debates about integration and social cohesion, most work on migration timing focuses on economic outcomes, leaving effects on values and beliefs far less explored. We address this gap by combining a sibling design with a distributional framework for measuring attitude convergence. Using the UK Household Longitudinal Study, we compare siblings within the same family who arrived in the UK at different ages, exploiting within-family variation to identify the causal effect of childhood exposure to host-country norms. To measure convergence, we compare the full distributions of ordinal survey responses to questions on gender norms for immigrants and locals. Our distance metric is the Total Variation (TV) distance between response distributions. TV has a clear policy-relevant interpretation: it equals the worst-case difference in mean responses over all bounded scoring rules. We then use our estimates to construct two measures of how migration timing changes this distance. The first asks how large the immigrant-UK-born TV distance would be if every immigrant had arrived at birth, and compares it to the observed distance. The second is a marginal measure that asks how the distance changes under a small uniform shift in arrival ages. Our results show that if all immigrants had arrived at birth, the cultural distance between immigrants and locals would decrease substantially, and that marginal increases in migration age incrementally widen this gap. Overall, the findings highlight the importance of early-life exposure in shaping cultural beliefs and provide a robust, broadly applicable framework for quantifying convergence in survey responses.</p>
  </details>

- PreScience: A Dataset and Benchmark for Scientific Forecasting with Anirudh Ajith, Amanpreet Singh, Jay DeYoung, Austin C. Kozlowski, Oyvind Tafjord, James Evans, Daniel S. Weld, Tom Hope, and Doug Downey [arXiv](https://arxiv.org/abs/2602.20459)

  <details>
  <summary>Abstract</summary>
  <p>Can AI systems trained on the existing scientific record forecast the advances that will follow? We introduce PreScience, a dataset and benchmark for scientific forecasting built around 98K recent AI research papers, together with companion papers covering author publication histories and citation links, yielding 502K papers in total. The resulting paper records include titles, abstracts, disambiguated author identities, influential references, topic labels, citation trajectories, and metadata snapshotted to respect temporal cutoffs. We instantiate seven exemplar tasks: five paper-anchored tasks -- contribution generation, collaborator prediction, prior work selection, citation count prediction, and future combination prediction -- and two aggregate topic trend forecasting variants. We develop baselines ranging from simple heuristics and embedding methods to frontier language models and agentic systems, and introduce LACER, an LLM-based metric for evaluating similarity of generated contribution descriptions that agrees better with human judgments than existing metrics. Finally, we compose task models to generate a 12-month synthetic corpus and find that the resulting papers are systematically less diverse and less novel than human-authored research from the same period. We release the PreScience dataset (https://huggingface.co/datasets/allenai/prescience) and code (https://github.com/allenai/prescience).</p>
  </details>

- Content vs. Form: What Drives the Writing Score Gap Across Socioeconomic Backgrounds? A Generated Panel Approach with Pedro Pertusi [arXiv](https://arxiv.org/abs/2601.03469)

  <details>
  <summary>Abstract</summary>
  <p>Students from different socioeconomic backgrounds exhibit persistent gaps in test scores, gaps that can translate into unequal educational and labor-market outcomes later in life. In many assessments, performance reflects not only what students know, but also how effectively they can communicate that knowledge. This distinction is especially salient in writing assessments, where scores jointly reward the substance of students' ideas and the way those ideas are expressed. As a result, observed score gaps may conflate differences in underlying content with differences in expressive skill. A central question, therefore, is how much of the socioeconomic-status (SES) gap in scores is driven by differences in what students say versus how they say it. We study this question using a large corpus of persuasive essays written by U.S. middle- and high-school students. We introduce a new measurement strategy that separates content from style by leveraging large language models to generate multiple stylistic variants of each essay. These rewrites preserve the underlying arguments while systematically altering surface expression, creating a "generated panel" that introduces controlled within-essay variation in style. This approach allows us to decompose SES gaps in writing scores into contributions from content and style. We find an SES gap of 0.67 points on a 1-6 scale. Approximately 69% of the gap is attributable to differences in essay content quality, Style differences account for 26% of the gap, and differences in evaluation standards across SES groups account for the remaining 5%. These patterns seems stable across demographic subgroups and writing tasks. More broadly, our approach shows how large language models can be used to generate controlled variation in observational data, enabling researchers to isolate and quantify the contributions of otherwise entangled factors.</p>
  </details>


###### 2025

- Linear Regression in a Nonlinear World [PDF]({{ '/assets/pdf/YitzhakiNote.pdf' | prepend: site.baseurl | prepend: site.url }}) [arXiv](https://arxiv.org/abs/2512.13645)

  <details>
  <summary>Abstract</summary>
  <p>The interpretation of coefficients from multivariate linear regression relies on the assumption that the conditional expectation function is linear in the variables. However, in many cases the underlying data generating process is nonlinear. This paper examines how to interpret regression coefficients under nonlinearity. We show that if the relationships between the variable of interest and other covariates are linear, then the coefficient on the variable of interest represents a weighted average of the derivatives of the outcome conditional expectation function with respect to the variable of interest. If these relationships are nonlinear, the regression coefficient becomes biased relative to this weighted average. We show that this bias is interpretable, analogous to the biases from measurement error and omitted variable bias under the standard linear model.</p>
  </details>

- Polarization by Design: How Elites Could Shape Mass Preferences as AI Reduces Persuasion Costs [arXiv](https://arxiv.org/abs/2512.04047)

  <details>
  <summary>Abstract</summary>
  <p>In democracies, major policy decisions typically require some form of majority or consensus, so elites must secure mass support to govern. Historically, elites could shape support only through limited instruments like schooling and mass media; advances in AI-driven persuasion sharply reduce the cost and increase the precision of shaping public opinion, making the distribution of preferences itself an object of deliberate design. We develop a dynamic model in which elites choose how much to reshape the distribution of policy preferences, subject to persuasion costs and a majority rule constraint. With a single elite, any optimal intervention tends to push society toward more polarized opinion profiles - a "polarization pull" - and improvements in persuasion technology accelerate this drift. When two opposed elites alternate in power, the same technology also creates incentives to park society in "semi-lock" regions where opinions are more cohesive and harder for a rival to overturn, so advances in persuasion can either heighten or dampen polarization depending on the environment. Taken together, cheaper persuasion technologies recast polarization as a strategic instrument of governance rather than a purely emergent social byproduct, with important implications for democratic stability as AI capabilities advance.</p>
  </details>

- The (Short-Term) Effects of Large Language Models on Unemployment and Earnings with Danqing Chen, Carina Kane, Austin Kozlowski, and James A. Evans [arXiv](https://arxiv.org/abs/2509.15510)

  <details>
  <summary>Abstract</summary>
  <p>Large Language Models have spread rapidly since the release of ChatGPT in late 2022, accompanied by claims of major productivity gains but also concerns about job displacement. This paper examines the short-run labor market effects of LLM adoption by comparing earnings and unemployment across occupations with differing levels of exposure to these technologies. Using a Synthetic Difference in Differences approach, we estimate the impact of LLM exposure on earnings and unemployment. Our findings show that workers in highly exposed occupations experienced earnings increases following ChatGPT's introduction, while unemployment rates remained unchanged. These results suggest that initial labor market adjustments to LLMs operate primarily through earnings rather than worker reallocation.</p>
  </details>

- Biased AI improves human performance but reduces perceived helpfulness with Shiyang Lai, Jiwoong Choi, Junsol Kim, Yujin Potter, and James Evans [arXiv](https://arxiv.org/abs/2508.09297) Earlier version presented at the NeurIPS 2025 Workshop on Algorithmic Collective Action.

  <details>
  <summary>Abstract</summary>
  <p>Artificial intelligence (AI) increasingly shapes how people think, engage, and evaluate information. To minimize risk, most current systems are designed to present as ideologically neutral with standardized output. Yet growing evidence suggests that these principles suppress cognitive engagement, impair human decision-making, and erode societal diversity. Here we test the opposite approach by deliberately injecting bias into AI assistants. In three randomized experiments with 5,000 participants, biased AI improved human performance relative to default and neutral AI in tasks ranging from misinformation evaluation and financial investment to graduate education. These gains carried a subjective cost. Participants systematically undervalued AI they believed to be biased and inflated the helpfulness of AI they believed to be neutral, regardless of the systems' actual behavior. Interacting with two AIs whose biases flanked the participant's own perspective preserved the performance gains while limiting the subjective cost and one-sided influence. Our findings reveal the strategic value of intentional bias in AI design. Rather than performing a single fair, reliable, and authoritative voice, AI that speaks from specific viewpoints triggers cognitive agency and elevates human-AI performance in judgment, decision-making, and problem-solving.</p>
  </details>

- Missing vs. Unused Knowledge Hypothesis for Language Model Bottlenecks in Patent Understanding with Siyang Wu, Honglin Bao, and James A. Evans [arXiv](https://arxiv.org/abs/2505.12452)

  <details>
  <summary>Abstract</summary>
  <p>While large language models (LLMs) excel at factual recall, the real challenge lies in knowledge application. A gap persists between their ability to answer complex questions and their effectiveness in performing tasks that require that knowledge. We investigate this gap using a patent classification problem that requires deep conceptual understanding to distinguish semantically similar but objectively different patents written in dense, strategic technical language. We find that LLMs often struggle with this distinction. To diagnose the source of these failures, we introduce a framework that decomposes model errors into two categories: missing knowledge and unused knowledge. Our method prompts models to generate clarifying questions and compares three settings -- raw performance, self-answered questions that activate internal knowledge, and externally provided answers that supply missing knowledge (if any). We show that most errors stem from failures to deploy existing knowledge rather than from true knowledge gaps. We also examine how models differ in constructing task-specific question-answer databases. Smaller models tend to generate simpler questions that they, and other models, can retrieve and use effectively, whereas larger models produce more complex questions that are less effective, suggesting complementary strengths across model scales. Together, our findings highlight that shifting evaluation from static fact recall to dynamic knowledge application offers a more informative view of model capabilities.</p>
  </details>


###### 2024

- Bridging the Gap: Information, Returns and Choices [PDF]({{ '/assets/pdf/jmpNadav.pdf' | prepend: site.baseurl | prepend: site.url }})

  <details>
  <summary>Abstract</summary>
  <p>How much of the gap in choices across social groups is driven by differences in returns or the ability to predict these returns? To address this question, we employ a decomposition exercise, based on a structural model, to quantify the roles of information quality and differences in returns in driving this gap, focusing on the college attendance decisions of White and Hispanic high school students in Texas. We find that the average monetary returns from college are almost zero for Hispanics, in contrast to being high for Whites. We then estimate the extent to which differences in returns and information quality contribute to the gap in choices. Our findings indicate that differences in information quality across the two groups help mitigate the choice gap, whereas differences in returns drive the gap. Finally, we use our model to show that achieving parity in choice between the two groups would require policymakers to provide highly accurate additional information, potentially explaining between 24% and 49% of the variance in post-college earnings.</p>
  </details>

- It’s Not Who You Are, It’s What They Know: Wage Gaps and Informational Frictions [PDF]({{ '/assets/pdf/itsNotWhoYouAre.pdf' | prepend: site.baseurl | prepend: site.url }})

  <details>
  <summary>Abstract</summary>
  <p>Can informational asymmetries among firms account for all observed wage gaps across social groups? We confirm this through a parsimonious common-value auction model in the labor market with unspecified information structures. Firms with identical characteristics encounter workers with unobserved productivity and extend wage offers based on their information about worker productivity and competing offers. Using 2010 American Community Survey data, we show that wage disparities among both Black and White men and women can be explained using a common productivity distribution for all social groups and differences in what firms know, if the mean of this common productivity distribution ranges between $48,000 and $132,800. Our results emphasize the importance of understanding what firms know in shaping wage distributions and explaining wage disparities</p>
  </details>

- Uncovering Latent Types in Sequential Choice Data Using Text Embedding Algorithm [PDF]({{ '/assets/pdf/word2vec_paper.pdf' | prepend: site.baseurl | prepend: site.url }})

  <details>
  <summary>Abstract</summary>
  <p>In economic analyses of agents making a series of discrete choices, deciding what constitutes an alternative is crucial. This paper introduces a technique for categorizing similar alternatives in contexts where forward-looking agents make a series of decisions. The proposed method groups options that are equivalent from the perspective of the agents, using the renowned word2vec algorithm (Mikolov et al., 2013b, Mikolov et al., 2013a) from the Natural Language Processing literature. The paper discusses the link between the word2vec method and the underlying dynamic optimization problem of the agent.</p>
  </details>


###### 2017

- Network-Mediated Knowledge Spillovers: A Cross-Country Comparative Analysis of Information Security Innovations with Lee Branstetter and Neil Gandal [NBER Working Paper 23808](https://www.nber.org/papers/w23808) [CEPR version](https://scholar.google.com/citations?view_op=view_citation&user=len-qnMAAAAJ&citation_for_view=len-qnMAAAAJ:zYLM7Y9cAGgC&hl=en)

  <details>
  <summary>Abstract</summary>
  <p>A large and growing literature has used patent and patent citation data to measure knowledge spillovers across inventions and organizations, but relatively few papers in this literature have explicitly considered the collaboration networks formed by inventors as a mechanism for shaping and transmitting these knowledge flows. This paper utilizes an approach developed by Fershtman and Gandal (2011) to examine the incidence and nature of knowledge flows mediated by the collaboration networks of inventors active in the information security industry. This is an industry in which a number of nations outside the United States, including Israel, have emerged as important centers of innovation. Using data from U.S. PTO patent grants in information security, we find that the quality of Israeli information security inventions is systematically linked to the structure of the collaborative network generated by Israeli inventors in this sector. Using the Fershtman and Gandal (2011) model, this suggests that there are knowledge spillovers from the network. In some other nations, invention quality is less closely linked to the collaboration networks of inventors. This research highlights the importance of direct interaction among inventors as a conduit for flows of frontier scientific knowledge.</p>
  </details>


##### Work in Progress

- Quantifying Uncertainty over the Lifecycle [Slides]({{ '/assets/pdf/lifeCycleUncertainty_slides.pdf' | prepend: site.baseurl | prepend: site.url }})

  <details>
  <summary>Abstract</summary>
  <p>We examine the welfare implications of income uncertainty, specifically its differential impact across social groups. Leveraging a new lifecycle metric for uncertainty costs, we compare utility outcomes from both expected and optimal consumption profiles under certainty. To perform this analysis, we employ a new approach that uses a Generative AI model (Normalized Flow) for the estimation and simulation of future consumption and income trajectories. Utilizing comprehensive household survey data from India, our findings reveal small but persistent disparities in uncertainty costs across different castes, under the assumption of homogeneous utility functions. The study suggests that, in the absence of preference heterogeneity, income-to-welfare mapping may be adequately performed without considering uncertainty.</p>
  </details>

- Integrating Minority Perspectives: An Analysis of Women's Induction into the Field of Economics
- Can complementarity explain path dependence in innovation? Evidence from the secondary market of patents

##### Publications

###### 2026

- Measuring Intent Comprehension in LLMs with James Evans. Proceedings of the 43rd International Conference on Machine Learning (ICML), PMLR 306:61756–61805 (2026) [Proceedings](https://proceedings.mlr.press/v306/kunievsky26a.html) [arXiv](https://arxiv.org/abs/2506.16584)

  <details>
  <summary>Abstract</summary>
  <p>People judge interactions with large language models (LLMs) as successful when outputs match what they want, not what they type. Yet LLMs are trained to predict the next token solely from text input, not underlying intent. Because written language is an imperfect proxy for intent, and correlations between phrasing and desired outcomes can break down in training data, models that rely too heavily on surface cues may respond inconsistently to semantically equivalent prompts. This makes it essential to evaluate whether LLMs can reliably infer user intent-especially in high-stakes settings where robustness and generalization are critical. We introduce a formal framework for assessing intent comprehension in LLMs: whether a model demonstrates robust understanding of user intent by producing consistent outputs across semantically equivalent prompts while differentiating between prompts with distinct intents. Our evaluation approach is based on a variance decomposition of model responses into three components: variability due to user intent, user articulation, and model uncertainty. Models that understand what users want, and are not overly sensitive to textual cues, should attribute most output variance to intent differences, rather than articulation style. Applying this framework across diverse domains, we find that, within the five LLaMA and Gemma models we evaluate, larger models typically assign a greater share of variance to intent, indicating stronger comprehension of intent, although gains are uneven and often modest with increasing model size. These results motivate moving beyond accuracy-only benchmarks toward semantic diagnostics that directly assess whether models understand what users intend.</p>
  </details>


###### 2024

- On the Interpretation of the Intergenerational Elasticity and the Rank-Rank Coefficients for Cross Country Comparison. Economics Letters 236, 111581 (2024) [PDF]({{'/assets/pdf/IGE_interpetation.pdf' | prepend: site.baseurl | prepend: site.url }}) [Proofs]({{'/assets/pdf/IGE_interpetation_appendix.pdf' | prepend: site.baseurl | prepend: site.url }})

  <details>
  <summary>Abstract</summary>
  <p>This paper investigates Intergenerational Elasticity (IGE) and Rank-Rank coefficients, employing Yitzhaki's theorem (Yitzhaki, 1996) to express them as weighted averages of underlying causal mechanisms driving mobility. We highlight the challenges of interpreting cross-country comparisons using IGE or Rank-Rank coefficients due to the regression weighting scheme. We also show that, while the Rank-Rank coefficient is more interpretable for positional mobility, it lacks insights into the underlying mechanisms driving mobility across countries. The analysis demonstrates potential drawbacks of using linear regression coefficients as summary statistics in the context of intergenerational mobility comparisons.</p>
  </details>


###### 2021

- The High-Tech Sector with Neil Gandal and Stefania Roccas Gandal. Chapter 17 in The Israeli Economy, 1995–2017: Light and Shadow in a Market Economy, pp. 527–554, Cambridge University Press (2021) [Link](https://doi.org/10.1017/9781108907620.018)

  <details>
  <summary>Abstract</summary>
  <p>Israel is recognized as one of the most innovative countries in the world. According to the Bloomberg Index of Innovation, Israel stands at number five, while according to the Global Competitive Index, Israel ranks third in the innovation category. The country is now recognized around the world for its excellence in technology and as a center for high-tech entrepreneurship, especially in the area of information and communication technology. In this chapter, we first provide a brief historical perspective. We then provide background, summary, and trend data. We shed light on the quiet but important “high-tech” movement in the Israeli Arab sector. Finally, we examine key problems facing Israeli high tech and briefly discuss promising new frontiers for Israeli high tech.</p>
  </details>


###### 2020

- Network-Mediated Knowledge Spillovers in ICT/Information Security. Review of Network Economics 19(2), 85–114 (2020) with Neil Gandal and Lee Branstetter [Link](https://doi.org/10.1515/rne-2020-0034)

  <details>
  <summary>Abstract</summary>
  <p>A large literature has used patent data to measure knowledge spillovers across inventions but few papers have explicitly measured the impact of the collaboration networks formed by inventors on the quality of invention. This paper develops a method to measure the impact of collaboration networks of inventors on invention quality. We apply this methodology to the information and communication technology (ICT) and information security sectors in Israel and find that the quality of Israeli inventions are systematically linked to the structure of the collaborative network in these sectors.</p>
  </details>


##### Dissertation

###### 2024

- Essays in Labor Economics. Ph.D. dissertation, University of Chicago (2024) [Repository](https://knowledge.uchicago.edu/records/4zsh3-z4c67)

  <details>
  <summary>Abstract</summary>
  <p>All of our choices and all that sets us apart are governed by what we can do, what we want to do, and what we know. This dissertation aims to quantify two of these channels to better understand why we differ. The first two chapters focus on what we know and how it shapes societal gaps. The first chapter attacks the question of how much of the gap in choices across social groups is driven by differences in outcomes of choices or by differences in the quality of information these groups have about their respective outcomes. I study this question in the context of the college enrollment gap between white and Hispanic high school students. To assess how much of the gap can be attributed to each channel, I introduce a novel decomposition approach and show how we can use a structural model to operationalize and quantify the role of each component. I find that the main driving force behind the college enrollment gap is differences in potential returns, while differences in information quality across the two groups contribute to narrowing the gap. The second chapter tackles the question of whether informational asymmetries among firms can account for all observed wage gaps across social groups. I build a common-value auction model in the labor market with unspecified information structures. In this model, firms meet heterogeneous workers with unobserved productivity and extend wage offers based on their information about worker productivity and competing offers. Using the American Community Survey data, I show that wage disparities among Black and white men and women can arise in an economy where different social groups have identical productivity distributions, but firms have different types of information on these different workers, such that the only driving force behind the wage gap is the information. Finally, the last chapter departs from the notion of what we know and turns to discuss what "we can do" through the lens of intergenerational mobility. It focuses on two common measures of intergenerational mobility—the Intergenerational Elasticity (IGE) and Rank-Rank coefficients. In it, I employ Yitzhaki's theorem to express these coefficients as weighted averages of the underlying causal mechanisms driving mobility. The chapter highlights the challenges of interpreting cross-country comparisons using IGE or Rank-Rank coefficients due to the regression weighting scheme. It shows that while the Rank-Rank coefficient is more interpretable for positional mobility, it lacks insights into the underlying mechanisms driving mobility across countries.</p>
  </details>

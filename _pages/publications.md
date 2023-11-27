---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

* ***MUSER: A Multi-View Similar Case Retrieval Dataset.*** \
***CIKM2023 Best Resource Paper Honorable Mention***\
32nd ACM International Conference on Information and Knowledge Management.
**(CIKM 2023)**.\
  We present MUSER, a similar case retrieval dataset based on multi-view similarity measurement and comprehensive legal element knowledge. Specifically, we select three perspectives (legal fact, dispute focus, and law statutory) and build a comprehensive and structured label system of legal elements for each of them, to enable accurate and knowledgeable evaluation of case similarities. The constructed dataset originates from Chinese civil cases and contains 100 query cases and 4,024 candidate cases. We implement several text classification algorithms for legal element prediction and various retrieval methods for retrieving similar cases on MUSER. \
  [[paper]](https://github.com/THUYRan/THUYRan.github.io/blob/master/publications/MUSER.pdf)
  [[code]](https://github.com/THUlawtech/MUSER)
* ***Leveraging Event Schema to Ask Clarifying Questions for Conversational Legal Case Retrieval.*** \
32nd ACM International Conference on Information and Knowledge Management.
**(CIKM 2023 Full Paper)**.\
  Our preliminary study has shown that generating clarifying questions in legal conversational search with SOTA LLMs (e.g., GPT-4) often suffers from several problems such as duplication and low-utility contents. To address these problems, we propose LeClari, which leverages legal event schema as external knowledge to instruct LLMs to generate effective clarifying questions for legal conversational search. LeClari is constructed with a prompt module and a novel legal event selection module. The former defines a prompt with legal events for clarifying question generation and the latter selects potential event types by modeling the relationships of legal event types, conversational context, and candidate cases. We also propose ranking-oriented rewards and employ the reward augmented maximum likelihood (RAML) method to optimize LeClari directly based on the final retrieval performance of the conversational legal search system. \
  [[paper]](https://github.com/THUYRan/THUYRan.github.io/blob/master/publications/LeClari.pdf)
* ***Investigating the Conversational Agent Action in Legal Case Retrieval.*** \
The 45th European Conference on Information Retrieval.
**(ECIR 2023 Full Paper)**.\
  We investigate the conversational agent action in legal case retrieval from the behavioral perspective. Specifically, we conducted a lab-based user study to collect user and agent search behavior while using agent-mediated conversational legal case retrieval systems. Based on the collected data, we analyze the relationship between historical search interaction behaviors and current agent actions in conversational legal case retrieval. We believe that this work can contribute to a better understanding of agent action and useful guidance for developing practical systems for conversational legal case retrieval. \
  [[paper]](https://github.com/THUYRan/THUYRan.github.io/blob/master/publications/Investigating.pdf) [[code]](https://github.com/BulouLiu/Conversational-vs-Traditional-Legal-Case-Retrieval)
* ***LEEC: A Legal Element Extraction Dataset with an Extensive Domain-Specific Label System***\
32nd ACM International Conference on Information and Knowledge Management Workshop.
**(MLLD 2023)**. \
  As a pivotal task in natural language processing, element extraction has gained significance in the legal domain. Extracting legal
elements from judicial documents helps enhance interpretative and analytical capacities of legal cases, and thereby facilitating a wide
array of downstream applications in various domains of law. Yet existing element extraction datasets are limited by their restricted
access to legal knowledge and insufficient coverage of labels. To address this shortfall, we introduce a more comprehensive, large scale criminal element extraction dataset, comprising 15,831 judicial documents and 159 labels. This dataset was constructed through two main steps: first, designing the label system by our team of legal experts based on prior legal research which identified critical factors driving and processes generating sentencing outcomes in criminal cases; second, employing the legal knowledge to annotate judicial documents according to the label system and annotation guideline. The Legal Element ExtraCtion dataset (LEEC) represents the most extensive and domain specific legal element extraction dataset for the Chinese legal system. Leveraging the annotated data, we employed various SOTA models that validates the applicability of LEEC for Document Event Extraction (DEE) task. \
[[paper]](https://github.com/THUYRan/THUYRan.github.io/blob/master/publications/LEEC.pdf)
[[code]](https://github.com/THUlawtech/LEEC)
* ***Stock Trend Prediction using Historical Data and Financial Online News***\
The 1st International Workshop on Data-driven Social Network Analysis and Mining: Algorithms and Applications
**(DSONAM'20)**. \
  Financial online news on social networks has been proven to be a crucial factor that causes fluctuations in stock market. Regarding the impact of financial online news, this paper introduces Convolutional Neural Network (CNN) and Bidirectional Long Short-Term Memory (Bi-LSTM) to exploit the relation between financial online news and the fluctuations of stock price. A stock trends prediction model is proposed by deep combining the historical financial data feature, the news event feature and the sentiment orientation feature. News events and the corresponding sentiment orientations of financial news are introduced to help improve the accuracy of stock trends prediction.
* ***CLOpin: A cross-language knowledge graph architecture for public opinion analysis and early warning C***\
Data Analysis and Knowledge Discovery \
 [Purposes] To explore the mapping relationship between information in different languages, we can effectively monitor the public opinion outside the domain and guide the domestic audience positively. [Methods] CLOpin, a cross-language knowledge graph construction platform covering multi-source public opinion analysis and early warning field, was proposed to design multiple tool sets for different scenarios to process cross-language data sets, efficiently integrate data from multiple sources, and build a knowledge graph to achieve cross-language public opinion analysis and early warning. [Conclusions] In the CLOpin platform, knowledge from different sources complement each other, which has a significant effect on the expansion of event information, which is conducive to accurately grasp the dynamics of public opinion and make early warning accordingly.
  




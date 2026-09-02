---
layout: page
title: Research
permalink: /research/
---


## What do I do?

My research develops and evaluates natural language processing, large language model, and multimodal AI systems, with a particular focus on understanding model capabilities, robustness, security, and behavior. I study how we can better measure what AI systems know and can do, identify when and why they fail, and develop methods that make them more reliable and secure. Much of my work focuses on high-stakes settings, including healthcare, cybersecurity, and public health.

## Understanding and Evaluating Language and Multimodal Models

Modern language and multimodal models achieve strong performance across many tasks, but it is often unclear what these systems have actually learned, how reliably their capabilities can be measured, and how well they generalize across populations and domains. My research develops methods for evaluating model capabilities, internal representations, robustness, fairness, and human-AI interaction.

A major theme of this work is that aggregate performance alone is not enough to determine whether an AI system is reliable. For example, models may perform differently across demographic groups, prompting may underestimate information available within a model's internal representations, retrieval may not consistently improve model performance, and people may interpret or interact with AI systems in unexpected ways. My work develops methods and evaluations that help identify these limitations and better characterize the capabilities of modern AI systems.

My earlier work in this area studied fairness and reliability in NLP systems, including racial and dialect-related disparities, biases in biomedical language, and the reliability of learned representations. More recently, this research has expanded to large language and vision-language models, model probing, retrieval-augmented generation, and human-AI interaction.

### Relevant Publications

1. Schumacher, D., Rajarajan, P. D., Kotara, H., Rendon, R., Atupulazi, K., Tagare, D., Sanusi, I. T., Martin, F. G., & Rios, A. (2026). Detecting AI Impostors: How Do Middle Schoolers Identify LLM Agents in a Live Collaborative Setting? *Proceedings of the 2026 Conference on Empirical Methods in Natural Language Processing (EMNLP)*.

2. Nourbakhsh, E., Yang, K., & Rios, A. (2026). MedProb: Probing Internal Representations of Vision-Language Models for Medical Question Answering. *Findings of the 2026 Conference on Empirical Methods in Natural Language Processing (EMNLP)*.

3. Lwowski, B., & Rios, A. (2021). The risk of racial bias while tracking influenza-related content on social media using machine learning. *Journal of the American Medical Informatics Association, 28*(4), 839-849.

4. Rios, A. (2020). FuzzE: Fuzzy fairness evaluation of offensive language classifiers on African-American English. *Proceedings of the AAAI Conference on Artificial Intelligence, 34*(1).

5. Rios, A., & Lwowski, B. (2020). An empirical study of the downstream reliability of pre-trained word embeddings. *Proceedings of the 28th International Conference on Computational Linguistics (COLING)*.

## AI Security and Access Control

My research studies both the use of AI for security and the security of AI systems. AI for security includes developing methods that identify and reason about malicious activity, such as detecting coordinated social media accounts, distinguishing human-generated from machine-generated text, and analyzing cybersecurity and network data.

I also study vulnerabilities that arise when language models are integrated into databases, software systems, and other applications. This work includes attacks against text-to-SQL systems and methods for evaluating whether large language models correctly follow access-control policies. More broadly, I am interested in how security policies, organizational roles, and permissions can be represented, evaluated, and enforced in AI systems.

### Relevant Publications

1. Klisura, Đ., Khoury, J., Kundu, A., Krishnan, R., & Rios, A. (2026). Role-Conditioned Refusals: Evaluating Access Control Reasoning in Large Language Models. *Findings of the Association for Computational Linguistics: EACL 2026*.

2. Bethany, M., Wherry, B., Bethany, E., Vishwamitra, N., Rios, A., & Najafirad, P. (2024). Deciphering textual authenticity: A generalized strategy through the lens of large language semantics for detecting human vs. machine-generated text. *33rd USENIX Security Symposium*.

3. Klisura, Đ., & Rios, A. (2024). Unmasking database vulnerabilities: Zero-knowledge schema inference attacks in text-to-SQL systems. *arXiv preprint arXiv:2406.14545*.

4. Pavlich, R., Ebadi, N., Tarbell, R., Linares, B., Tan, A., Humphreys, R., Das, J. K., Ghandiparsi, R., Haley, H., George, J., Slavin, R., Choo, K. K., Dietrich, G., & Rios, A. (2024). Beyond text-to-SQL for IoT defense: A comprehensive framework for querying and classifying IoT threats. *arXiv preprint arXiv:2406.17574*.

5. Bhatt, P., & Rios, A. (2021). Detecting bot-generated text by characterizing linguistic accommodation in human-bot interactions. *Findings of ACL-IJCNLP*, 3235-3247.

6. Nasrin, N., Choo, K. K. R., Ko, M., & Rios, A. (2019). How many users are enough? Exploring semi-supervision and stylometric features to uncover a Russian troll farm. *Proceedings of the Second Workshop on Natural Language Processing for Internet Freedom: Censorship, Disinformation, and Propaganda*, 20-30.

## Biomedical and Healthcare AI

Biomedical and healthcare applications have been a major focus of my research. Healthcare AI systems must operate across heterogeneous data sources, limited training data, changing domains, and settings where incorrect predictions can have meaningful consequences. My research develops NLP and multimodal AI methods for extracting, representing, and reasoning over biomedical and clinical information while also studying when these systems generalize and when they fail.

My earlier work focused on medical coding, biomedical information extraction, transfer learning, domain adaptation, and few-shot learning. More recently, this research has expanded to large language and vision-language models, medical question answering, biomedical retrieval-augmented generation, and human-AI interaction in healthcare.

A central goal of this work is to move beyond overall accuracy and better understand the reliability of healthcare AI systems. This includes studying what information models encode internally, whether additional information such as retrieved biomedical evidence actually improves their predictions, how models behave across datasets and populations, and how people may be affected by the use of generative AI in healthcare.

### Relevant Publications

1. Zhao, X., Wang, T., Schumacher, D., Rammouz, V., & Rios, A. (2026). Telling Speculative Stories to Help Humans Imagine the Harms of Healthcare AI. *Findings of the Association for Computational Linguistics: ACL 2026*.

2. Nourbakhsh, E., Slavin, R., Yang, K., & Rios, A. (2026). When Retrieval Doesn't Help: A Large-Scale Study of Biomedical RAG. *BioNLP 2026*.

3. Nourbakhsh, E., Yang, K., & Rios, A. (2026). MedProb: Probing Internal Representations of Vision-Language Models for Medical Question Answering. *Findings of EMNLP 2026*.

4. Rios, A., & Kavuluru, R. (2019). Neural transfer learning for assigning diagnosis codes to EMRs. *Artificial Intelligence in Medicine, 96*, 116-122.

5. Rios, A., Durbin, E. B., Hands, I., Arnold, S. M., Shah, D., Schwartz, S. M., Goulart, B. H. L., & Kavuluru, R. (2019). Cross-registry neural domain adaptation to extract mutational test results from pathology reports. *Journal of Biomedical Informatics, 97*, 103267.

6. Rios, A., & Kavuluru, R. (2018). EMR coding with semi-parametric multi-head matching networks. *Proceedings of NAACL*.

7. Rios, A., & Kavuluru, R. (2018). Few-shot and zero-shot multi-label learning for structured label spaces. *Proceedings of EMNLP*.

8. Rios, A., & Kavuluru, R. (2015). Convolutional neural networks for biomedical text classification: Application in indexing biomedical articles. *Proceedings of the ACM Conference on Bioinformatics, Computational Biology and Health Informatics*.

## Selected Research Funding

**CRII: SCH: A Computational Framework for Fair Public Health-Related Decisions.**<br/>
National Science Foundation. CISE: IIS. 04/01/2020-03/31/2022. $174,797<br/>
PI: *Anthony Rios*

**Machine Learning-centric Cyber Threat Intelligence and Hunting for IoT Systems**<br/>
National Security Agency. Cybersecurity Research Innovation Grant. 08/01/2021-07/31/2023. $464,153<br/>
PI: *Anthony Rios*; Co-PIs: Glenn Dietrich and Raymond Choo


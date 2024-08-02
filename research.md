---
layout: page
title: Research
permalink: /research/
---

## What do I do?
Broadly speaking, my primary research interests involve biomedical and social applications of natural language processing.


## Public-Health, Social Media, and Bias

Social media platforms, such as Twitter, are used for many health-related applications, including, but not limited to, the early detection of disease outbreaks, monitoring adverse drug reactions, behavioral risk surveillance (such as monitoring smoking/drug use), and mining individuals mental and physical health.  While many systems have achieved high overall accuracy, it is not enough to decide whether to deploy the systems into production or to use the predictions for public health-related policy development. If a system is evaluated on the racial majority, it may achieve 90% accuracy. However, the performance on underrepresented groups may be much lower. Unfortunately, evaluating fairness is non-trivial. Many fairness metrics require the demographics to be known, or at least, inferred. It is hard to estimate fairness for groups that do not appear in the training dataset. Moreover, many datasets are not large enough to contain every minority group. Hence, much of my recent work has focused on socia media data, public health, and associated issues of bias and fairness.

### Relevant Publications

1. Lwowski, B., & Rios, A. (2021). The risk of racial bias while tracking influenza-related content on social media using machine learning. Journal of the American Medical Informatics Association, 28(4), 839-849.
2. Pritom, M. M. A., Rodriguez, R. M., Khan, A. A., Nugroho, S. A., Alrashydah, E., Ruiz, B. N., & Rios, A. (2021). Case study on detecting COVID-19 health-related misinformation in social media. arXiv e-prints, arXiv:2106.
3. Rios, A. (2020). FuzzE: Fuzzy fairness evaluation of offensive language classifiers on African-American English. Proceedings of the AAAI Conference on Artificial Intelligence, 34(1).
4. Rios, A., & Lwowski, B. (2020). An empirical study of the downstream reliability of pre-trained word embeddings. In Proceedings of the 28th International Conference on Computational Linguistics.
5. Rios, A., Joshi, R., & Shin, H. (2020). Quantifying 60 years of gender bias in biomedical research with word embeddings. In Proceedings of the 19th SIGBioMed Workshop on Biomedical Language Processing.

### Funding

**CRII: SCH: A Computational Framework for Fair Public Health-Related Decisions.**<br/>
National Science Foundation. CISE: IIS. 04/01/2020-03/31/2022. \$174,797<br/>
PI: *Anthony Rios*


## Security and Public Saftey Applications of NLP
My research focuses on the security of AI and the application of AI for enhancing security, addressing critical vulnerabilities and leveraging AI capabilities to improve safety measures. The AI for security involves developing robust detection methods to identify malicious activities, such as state-affiliated trolls infiltrating social media or advanced language models generating misleading content. By integrating novel features grounded in stylometry and human interaction patterns, my work significantly enhances the accuracy and resilience of these systems. Likewise, we have developed systems that can query secruity-related databases (e.g., network traffic) and reason about potential attacks that appeared within the database. In parallel, security for AI explores vulnerabilities in NLP technologies, like text-to-SQL systems, to detect and mitigate threats, which can be used to steal company secrets or prepare SQL injection attacks. Through innovative datasets and frameworks, my research demonstrates how AI can effectively infer critical information and protect data, ultimately enhancing both the security of AI systems and the broader digital security landscape. This dual approach ensures that while AI systems become more secure against threats, they also contribute to more robust security solutions in various domains.

### Relevant Publications
1. Bhatt, P., & Rios, A. (2021). Detecting bot-generated text by characterizing linguistic accommodation in human-bot interactions. ACL/IJCNLP (Findings), 3235-3247.
2. Nasrin, N., Choo, K. K. R., Ko, M., & Rios, A. (2019). How many users are enough? Exploring semi-supervision and stylometric features to uncover a Russian troll farm. In Proceedings of the Second Workshop on Natural Language Processing for Internet Freedom: Censorship, Disinformation, and Propaganda (pp. 20-30).
3. Klisura, Đ., & Rios, A. (2024). Unmasking database vulnerabilities: Zero-knowledge schema inference attacks in text-to-SQL systems. arXiv preprint arXiv:2406.14545.
4. Pavlich, R., Ebadi, N., Tarbell, R., Linares, B., Tan, A., Humphreys, R., Das, J. K., Ghandiparsi, R., Haley, H., George, J., Slavin, R., Choo, K. K., Dietrich, G., & Rios, A. (2024). Beyond text-to-SQL for IoT defense: A comprehensive framework for querying and classifying IoT threats. arXiv preprint arXiv:2406.17574.
5. Bethany, M., Wherry, B., Bethany, E., Vishwamitra, N., Rios, A., & Najafirad, P. (2024). Deciphering textual authenticity: A generalized strategy through the lens of large language semantics for detecting human vs. machine-generated text. Usenix Security 2024.


### Funding
**Machine Learning-centric Cyber Threat Intelligence and Hunting for IoT Systems**<br/>
National Security Agency. Cybersecurity Research Innovation Grant. 08/01/2021-07/31/2023. \$464,153<br/>
PI: *Anthony Rios* Co-PI(s): Glenn Dietrich and Raymond Choo


## Biomedical NLP Applications
Language shapes the world we live in. Information is shared among individuals through verbal and written communication, including biomedical information. Doctors write notes describing patient symptoms, medical history, and diagnoses. The notes are used annotated by hospitals for billing purposes, e.g., <a href="https://anthonyrios.net/blog/2018/02/naacl"><b>medical coding</b></a>. Scientists write research articles creating new information, including, but not limited to, new <a href="https://anthonyrios.net/blog/2017/08/ichi"><b>drug-drug</b></a>, drug-gene, and <a href="https://anthonyrios.net/blog/2018/03/bioinformatics-2018"><b>gene-gene</b></a> interactions. On social media, such as Facebook and Twitter, users describe life events giving insight on the users mental and physical health, indicating possible <a href="https://anthonyrios.net/blog/2017/11/smmh"><b>adverse drug events</b></a>, depression, or PTSD. I develop methods that can extract biomedical information from many textual data sources.

### Related Publications
1. Rios, A., & Kavuluru, R. (2019). Neural transfer learning for assigning diagnosis codes to EMRs. Artificial Intelligence in Medicine, 96, 116-122.
2. Rios, A., Durbin, E. B., Hands, I., Arnold, S. M., Shah, D., Schwartz, S. M., Goulart, B. H. L., & Kavuluru, R. (2019). Cross-registry neural domain adaptation to extract mutational test results from pathology reports. Journal of Biomedical Informatics, 97, 103267.
3. Rios, A., & Kavuluru, R. (2018). EMR coding with semi-parametric multi-head matching networks. In Proceedings of the conference. Association for Computational Linguistics. North American Chapter. Meeting (Vol. 2018).
4. Rios, A., & Kavuluru, R. (2018). Few-shot and zero-shot multi-label learning for structured label spaces. In Proceedings of the Conference on Empirical Methods in Natural Language Processing. Conference on Empirical Methods in Natural Language Processing (Vol. 2018).
5. Rios, A., & Kavuluru, R. (2015). Convolutional neural networks for biomedical text classification: Application in indexing biomedical articles. In Proceedings of the 6th ACM Conference on Bioinformatics, Computational Biology and Health Informatics.

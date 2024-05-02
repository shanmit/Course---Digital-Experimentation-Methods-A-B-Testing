# Teaching & Learning: Digital Experimentation & A/B Testing

These course materials were initially designed for teaching the MSBA (Masters of Science in Business Analytics) program from 2021 to 2024, at HKU Business School, focusing on the principles and practices of A/B testing. I aim to extend their usefulness to a wider audience, encompassing both learners and educators in the field of A/B testing. The materials include both lecture notes and class exercises in Python, which can serve as a foundation for developing assignments. The course has been meticulously developed from the ground up, ensuring that all content is original. Notably, the primary source of information for this course is my practical experience and research in the field of A/B testing. Additionally, I incorporate insights and some materials from 'Kohavi et al. (2020)'. My practical experience mainly stems from my consultancy and research collaborations with the WeChat A/B testing team at Tencent, China. In addition, I welcome any input related to teaching and learning A/B tests. Understanding this knowledge will benefit practitioners by enabling them to use data for making decisions more scientifically.

Reference:
Kohavi, Ron, Diane Tang, and Ya Xu. Trustworthy online controlled experiments: A practical guide to a/b testing. Cambridge University Press, 2020.

**Course Instructor**: [Shan Huang](https://www.shanhhuang.com/), an assistant professor in Marketing at HKU Business School. Email: shanhh@hku.hk

**Course TA**： Chen Wang, who is a PhD student at HKU Business School. Email: annacwang@connect.hku.hk,

**Course Description**:

The newly emerging capability to rapidly deploy and iterate online controlled experiments to assist decision-making in organizations is one of the most significant innovations in today’s technology industry. As more and more social interactions, decisions, opinions, and transactions are mediated by online platforms, digital experiments are becoming increasingly crucial for firms to understand their user behaviors and make product decisions. This course will cover the most cutting-edge digital experimentation methods used in the daily operations at large technology firms. We will also share the key lessons and pitfalls encountered in practice. Topics include the statistics behind experiments, experimental design, methods of analyzing experiments, A/B testing platforms and culture in organizations, recent developments in digital experimentation, and observational causal studies. Students will also learn how to conduct and analyze online experiments using programming languages, such as python, assignments, and a course project.

**Course Roadmap**:

1. A comprehensive overview of AB testing

2. Statistics behind A/B testing 
* Statistical tests (t, z, chi-square)
* Confidence intervals
* Type I error & Multiple Testing
* Type II Error & Power Analysis
* Regression 

3. Internal & External Validity
* SUTVA (network interferences)
* Survivorship bias
* Sanity Checks (SRM, Randomisation checks, A/A tests)
* Heterogeneous Treatment Effects (HTE)

4. Improve Sensitivity 
* Ratio metrics (e.g., lift etc.)
* Increase N (pooled control group, split sample)
* Increase effect size (Triggering Experiments)
* Reduce variance (transform metrics and interleaving design, paried design)
* Stratification (post and at assignment, block design)
* Regression with controls, CUPED


5. Observational Causal Studies
* Interrupted time series (ITS)
* Regression discontinuity design (RDD)
* Difference-in-Difference (DID)
* Propensity score matching (PSM)


This project focuses on leveraging LLaMA to detect novel customer needs from user-generated content. Our methodology involves the following steps:
1. Demonstration Selection:
We curate a set of demonstrations consisting of product reviews, each accompanied by a label indicating the presence or absence of novel needs content, as well as the rationale behind the labeling.
2. Summarization of Demonstrations:
These demonstrations are then summarized to distill key patterns and rationales, enhancing the model’s understanding of what constitutes novel needs within the reviews.
3. Novel Needs Detection in New Reviews:
For new product reviews, LLaMA is employed to identify novel needs content. The detection process is performed in a self-consistency manner, where the model not only predicts the presence of novel needs but also generates the rationale for its decision. This approach enhances both the transparency and the reliability of the identification process.

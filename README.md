**Bias Audit of Crowdsourced Annotations**
# [RAI Summer School assignment](https://precogatiiit.notion.site/ACM-India-Summer-School-on-Responsible-Safe-AI-76108c53564d4dc4af46c1d3bed52946)

Ref: https://maartensap.com/11830/Spring2024/hw1.html

**Goals**
Crowdsourcing annotations has become a fundamental aspect of NLP research. The goal of this assignment is to explore the ethical implications of soliciting crowdsourced data, specifically social biases that may emerge when asking for generated sentences.

Dataset we audit here:
**SNLI corpus**
[https://nlp.stanford.edu/projects/snli/snli_1.0.zip], a popular dataset for the NLP task of natural language inference. You can read more about the dataset and task on the SNLI website or in the original paper (Bowman et al. 2015).
Use the training data CSV or JSON lines file (snli_1.0_train.jsonl) in the SNLI corpus. The sentence1 column with premise that was supplied to annotators, and the sentence2 column is the hypotheses that annotators came up with. See other details about the corpus format in the README supplied with SNLI.

List of (identity labels)[https://strubell.github.io/teaching/11-830/assignments/files/identity_labels.txt] (based on Rudinger et al. 2017).

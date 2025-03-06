# Large Firms and Small and Medium Size Firms

Title: Exploring Potential Investor Bias and Market Inefficiencies: A Study of Earnings Sentiment

Overview:

This study investigates whether financial forecasting models adequately incorporate earnings sentiment from Small and Medium-sized Enterprises (SMEs). Traditional models often prioritize large-cap firms, potentially overlooking valuable predictive signals from SMEs. This research examines if this neglect leads to deviations from the semi-strong form of the Efficient Market Hypothesis (EMH).

Using Natural Language Processing (NLP) and machine learning, we built two predictive models: one trained on large-cap firm earnings calls and another on SME earnings calls. Feature importance analysis revealed significant differences between the models. Notably, negative sentiment, as measured by VADER, and trading volume had a much weaker influence on the SME model compared to the large-cap model. This indicates that SME earnings sentiment is underutilized, suggesting investor attention bias and information asymmetry.

We test the following three hypotheses:

H1: Negative sentiment expressed in SME earnings calls will exhibit a weaker positive correlation with trading volume compared to negative sentiment expressed in large firms.

H2: The correlation between increased trading volume and subsequent price trends will be weaker or less consistent for SMEs compared to large-cap firms.

H3: Negative sentiment will have a comparatively smaller effect on the 200-day SMA versus the 50-day SMA for SMEs, when compared to large-cap firms.

Our findings demonstrate that models using SME data have higher predictive accuracy, indicating that the market systematically underweights SME disclosures. This research highlights the importance of considering the nuanced language of SME disclosures in market efficiency and provides deeper insights into investor decision-making and market inefficiencies.

Key Contributions:

Demonstrates how algorithmic approaches can uncover behavioral biases in financial markets.
Provides evidence of investor attention bias and information asymmetry related to SMEs.
Challenges traditional assumptions about market efficiency by highlighting the importance of SME earnings sentiment.
Provides evidence that the market under utilizes SME data.

Data and Code:
Dataset:
- US Top 1000 firms Dataset: [Fortune 1000](https://www.kaggle.com/datasets/jeannicolasduval/2024-fortune-1000-companies)
- Aggregate.pkl: is dataset contains earnings calls links, cleaned text, and other features ready to run analysis

Code:
- Test.ipynb: is Random Forest Classification model, includes train, test, and validation. It also contains results such as confusion matrix, feature importance, and permutation importance table. Located in Code/test.ipynb
(Briefly describe where your data and code are located, if applicable)
How to Use:

(If applicable, provide instructions on how to run your code or access your data)
Contact:

Bat Baasan, bbaasan@gmu.edu Ph. D student, Computational Social Science, George Mason University

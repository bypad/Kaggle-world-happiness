# Kaggle World Happiness Analysis

SCENARIO: The World Happiness Report is a publication of the United Nations Sustainable Development Solutions Network on the global happiness of more than 150 countries. The annual report examines six factors including GDP per Capita, Social Support, Life Expectancy, Freedom, Perceptions of Corruption, and Generosity – and their contribution to the happiness in each country. This is significant as governments, organizations and civil society increasingly use happiness indicators to inform their policy-making decisions. Leading experts across several fields of economics, psychology, survey analysis, national statistics, health, and public policy also describe how measurements of happiness can be used to assess the progress of nations. As the report continues to gain global recognition, Australia's organisations are interested in how the nation performs in terms of happiness to determine what improvement needs to be done to increase this happiness level. In consideration of ethics, this project is undertaken for academic purposes and will not be leveraged for commercial uses in any way.

QUESTION: What factors significantly contribute to Happiness? (the relationship between the six factors and happiness)
- The correlation between the six factors and happiness?
- Which topic is among the popular topics and emerging discussions within the domain of Happiness?

QUESTION: How well does Australia perform compared to other countries? (evaluating Australia's performance against other countries in several aspects)
- How well does Australia perform in terms of rank and score?
- How well does Australia perform in each factor?
- What is the pattern/trend in Australia's performance over time?


DATA: To address the significant questions above, an appropriate data source has been found which includes data from the World Happiness Report from 2015 to 2019. The dataset is ethically collected from Kaggle, an online community platform that allows users to find open-sourced datasets. It is dedicated to the public domain under the license CC0: Public Domain which allows others to freely build upon, enhance and reuse the works for any purposes without restriction under copyright or database law.

DATA SOURCE: https://www.kaggle.com/datasets/unsdsn/world-happiness

Examining the dataset reveals limitations existing in the dataset that may skew the interpretation:
- To measure happiness, the report uses data from the Gallup World Poll which surveys a sample of 1,000 respondents from each country to evaluate their life satisfaction. The dataset does not provide any details on the demographics of the survey attendees which implies human factors that might affect the report. Therefore, it is important to be aware that the dataset might bias towards the specific demographics of the sample instead of representing the whole population.
- The Happiness Score is measured by adding up the six factors and the Dystopia Residual. Dystopia is a hypothetical nation representing the lowest national averages and is used as a benchmark to compare against other countries. There is not a clear explanation of how this dystopia residual is measured for each country. Additionally, in the 2018 and 2019 datasets, this Dystopia Residual score is not provided. This indicates a drawback of examining Dystopia Residual in this report.
- The datasets in this report include the World Happiness Reports from 2015 to 2019. Therefore, the result of this report should only be used to measure these periods, and should not be generalised to other years.

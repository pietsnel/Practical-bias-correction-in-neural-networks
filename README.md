# Understanding and correcting bias in neural networks: a credit default prediction case study

![](https://aisafety.netlify.app/images/ai-bias.jpg)

This notebook contains the code of the following study:

[Snel, P. and van Otterloo, S. 2022. Practical bias correction in neural networks: A credit default prediction case study, Computers and Society Research Journal (2022), 3](https://ictinstitute.nl/bias-correction-credit-default/))

Machine Learning (ML) is becoming an integral part of our daily lives. ML algorithms help us determine the route to drive to work, predict the weather and efficiently charge our phones. Recently, significant progress has been made in the performance of machine learning models and applications, driven by the development of new learning algorithms and theory and the enormous growth in the availability of online data and low-cost computing. With increased advancements in the machine learning field and consequential adoption, there have been increased concerns on bias against certain groups and the transparency of these algorithms. These concerns are raised after increased reports of algorithms being unfair such as; Amazon’s hiring tool disadvantaging women, facial recognition software performing poor on black women or the recent Dutch “toeslagenaffaire”. While ML models are getting bet-ter, their explainability is getting worse. This complex inner structure of ML re-sulted in these algorithms being referred to as "black-boxes". Increased adoption of ML in applications such as default prediction, risk management and applicant screen-ing results in these models having a significant impact on people.

In this notebook a model will be trained on a credit default prediction dataset which will be evaluated for any bias on sensitive attributes such as gender and age. The dataset originates from https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients

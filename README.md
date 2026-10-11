# Early prediction of children at risk for literacy difficulties: An Explainable AI approach

Developmental research increasingly recognizes that developmental outcomes emerge from complex, multicausal, and non-linear processes involving the interaction of biological, cognitive, and environmental factors across time. This complexity poses substantial challenges for prediction, since traditional statistical approaches are often limited in their capacity to model high-dimensional, interdependent developmental data. Machine learning (ML) methods offer flexible alternatives, but their application in developmental science has been constrained by concerns about interpretability and theoretical transparency. In this paper, we illustrate how ML and XAI can be applied to developmental prediction in a transparent and theoretically informed manner, using the early prediction of emergent literacy as a case study. Early communication and language skills, family and contextual factors, and biological characteristics were assessed in children aged 6–36 months, and emergent literacy was assessed three years later. We compare sixteen classifiers under conditions of class imbalance, quantify the contribution of each predictor domain to predictive performance, and use class-specific SHAP analyses to examine which early factors push predictions toward low, medium, or high literacy outcomes. The results demonstrate how ML/XAI approaches can be used to construct, evaluate, and inspect predictive models of developmental data, making model behaviour explicit and open to theoretical scrutiny. Together, the findings show how ML coupled with XAI methods can support transparent modelling, critical evaluation of prediction, and theoretical hypotheses in the study of developmental complexity.


## Decision Checklist

Applying machine learning (ML) and explainable AI (XAI) to developmental data involves several analytic decisions. Each one can change the model's performance and how its results are interpreted, so it is worth making these choices consciously and reporting them clearly.

This checklist lists the main decisions in our workflow. Copy it into your own project and fill it in as you go: write what you chose, why, and which alternatives you considered. A filled-in version for our study is given in Table 3 of the paper.

The checklist is a starting point, not a prescription. Different data and research aims may call for different choices.

| Decision | Guiding question | Your choice | Why | Alternatives considered |
|---|---|---|---|---|
| Preprocessing | How will you handle age, categorical variables and continuous variables? | | | |
| Outcome | Will you keep the outcome continuous or group it into levels? If grouped, how? | | | |
| Validation | How will you split the data to test the model on cases it has not seen? | | | |
| Metric | Which measure of performance fits your outcome and class sizes? | | | |
| Feature selection | Which predictors will the model use, and how will you choose them? | | | |
| Explanation | How will you show which features drive the model's predictions? | | | |

If you use this checklist, please cite: [paper reference, to be added after publication]

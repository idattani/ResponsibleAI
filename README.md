
# TRAMS-AI Responsible AI Toolbox
Responsible AI is an approach to assessing, developing, and deploying AI systems in a safe, trustworthy, and ethical manner, and take responsible decisions and actions.

Responsible AI Toolbox is a suite of tools providing a collection of model and data exploration and assessment user interfaces and libraries that enable a better understanding of AI systems. These interfaces and libraries empower developers and stakeholders of AI systems to develop and monitor AI more responsibly, and take better data-driven actions.

## Introducing Responsible AI dashboard
The dashboard integrates together ideas and technologies from several open-source toolkits in the areas of


- <b>Error Analysis</b> powered by [Error Analysis](https://github.com/microsoft/responsible-ai-widgets/blob/main/docs/erroranalysis-dashboard-README.md), which identifies cohorts of data with higher error rate than the overall benchmark. These discrepancies might occur when the system or model underperforms for specific demographic groups or infrequently observed input conditions in the training data.
- <b>Fairness Assessment</b> powered by [Fairlearn](https://github.com/fairlearn/fairlearn), which identifies which groups of people may be disproportionately negatively impacted by an AI system and in what ways.

- <b>Model Interpretability</b> powered by [InterpretML](https://github.com/interpretml/interpret-community), which explains blackbox models, helping users understand their model's global behavior, or the reasons behind individual predictions.

- <b>Counterfactual Analysis</b> powered by [DiCE](https://github.com/interpretml/DiCE), which shows feature-perturbed versions of the same datapoint who would have received a different prediction outcome, e.g., Taylor's loan has been rejected by the model. But they would have received the loan if their income was higher by $10,000.

- <b>Causal Analysis</b> powered by [EconML](https://github.com/microsoft/EconML), which focuses on answering What If-style questions to apply data-driven decision-making – how would revenue be affected if a corporation pursues a new pricing strategy? Would a new medication improve a patient’s condition, all else equal?

- <b>Data Balance</b> powered by [Responsible AI](https://github.com/microsoft/responsible-ai-toolbox/blob/main/docs/databalance-README.md), which helps users gain an overall understanding of their data, identify features receiving the positive outcome more than others, and visualize feature distributions.

Responsible AI dashboard is designed to achieve the following goals:

- To help further accelerate engineering processes in machine learning by enabling practitioners to design customizable workflows and tailor Responsible AI dashboards that best fit with their model assessment and data-driven decision making scenarios.
- To help model developers create end to end and fluid debugging experiences and navigate seamlessly through error identification and diagnosis by using interactive visualizations that identify errors, inspect the data, generate global and local explanations models, and potentially inspect problematic examples.
- To help business stakeholders explore causal relationships in the data and take informed decisions in the real world.

This repository contains the Jupyter notebooks with examples to showcase how to use this widget.

### Useful Links


- [Take a tour of Responsible AI Dashboard](https://github.com/idattani/ResponsibleAI/blob/49a59bd3711c7dac58dc43eea2a7b67d0dfa7d5a/tour.ipynb)
- [Get started](https://github.com/idattani/ResponsibleAI/blob/49a59bd3711c7dac58dc43eea2a7b67d0dfa7d5a/getting-started.ipynb)

Tabular Examples:
- [Try the tool: make decisions for house improvements (decision making)](https://github.com/idattani/ResponsibleAI/blob/49a59bd3711c7dac58dc43eea2a7b67d0dfa7d5a/Examples/Tabular/responsibleaidashboard-housing-decision-making.ipynb)
- [Try the tool: provide recommendations to patients using diabetes data (decision making)](https://github.com/idattani/ResponsibleAI/blob/49a59bd3711c7dac58dc43eea2a7b67d0dfa7d5a/Examples/Tabular/responsibleaidashboard-diabetes-decision-making.ipynb)
- [Try the tool: model debugging of a census income prediction model (classification)](https://github.com/idattani/ResponsibleAI/blob/49a59bd3711c7dac58dc43eea2a7b67d0dfa7d5a/Examples/Tabular/responsibleaidashboard-census-classification-model-debugging.ipynb)
- [Try the tool: model debugging of a housing price prediction model (classification)](https://github.com/idattani/ResponsibleAI/blob/49a59bd3711c7dac58dc43eea2a7b67d0dfa7d5a/Examples/Tabular/responsibleaidashboard-housing-classification-model-debugging.ipynb)
- [Try the tool: model debugging of a diabetes progression prediction model (regression)](https://github.com/idattani/ResponsibleAI/blob/49a59bd3711c7dac58dc43eea2a7b67d0dfa7d5a/Examples/Tabular/responsibleaidashboard-diabetes-regression-model-debugging.ipynb)

Text Examples:
- [Try the tool: model debugging of an OpenAI Question Answering model on SQuAD](https://github.com/idattani/ResponsibleAI/blob/49a59bd3711c7dac58dc43eea2a7b67d0dfa7d5a/Examples/Text/responsibleaidashboard-openai-model-debugging.ipynb)
- [Try the tool: model debugging of a HuggingFace Question Answering model on SQuAD](https://github.com/idattani/ResponsibleAI/blob/49a59bd3711c7dac58dc43eea2a7b67d0dfa7d5a/Examples/Text/responsibleaidashboard-question-answering-model-debugging.ipynb)
- [Try the tool: model debugging of a DBPedia text classification model](https://github.com/idattani/ResponsibleAI/blob/49a59bd3711c7dac58dc43eea2a7b67d0dfa7d5a/Examples/Text/responsibleaidashboard-DBPedia-text-classification-model-debugging.ipynb)
- [Try the tool: model debugging of a binary text classification model](https://github.com/idattani/ResponsibleAI/blob/49a59bd3711c7dac58dc43eea2a7b67d0dfa7d5a/Examples/Text/responsibleaidashboard-blbooksgenre-binary-text-classification-model-debugging.ipynb)
- [Try the tool: model debugging of a COVID-19 multilabel text classification model](https://github.com/idattani/ResponsibleAI/blob/49a59bd3711c7dac58dc43eea2a7b67d0dfa7d5a/Examples/Text/responsibleaidashboard-covid-event-multilabel-text-classification-model-debugging.ipynb)

Vision Examples:
- [Try the tool: model debugging of a fridge image classification model](https://github.com/idattani/ResponsibleAI/blob/49a59bd3711c7dac58dc43eea2a7b67d0dfa7d5a/Examples/Vision/responsibleaidashboard-fridge-image-classification-model-debugging.ipynb)
- [Try the tool: model debugging of a fridge multilabel image classification model](https://github.com/idattani/ResponsibleAI/blob/49a59bd3711c7dac58dc43eea2a7b67d0dfa7d5a/Examples/Vision/responsibleaidashboard-fridge-multilabel-image-classification-model-debugging.ipynb)
- [Try the tool: model debugging of a fridge object detection model](https://github.com/idattani/ResponsibleAI/blob/49a59bd3711c7dac58dc43eea2a7b67d0dfa7d5a/Examples/Vision/responsibleaidashboard-fridge-object-detection-model-debugging.ipynb)


## Supported Models

This Responsible AI Toolbox API supports models that are trained on datasets in Python `numpy.ndarray`, `pandas.DataFrame`, `iml.datatypes.DenseData`, or `scipy.sparse.csr_matrix` format.

The explanation functions of [Interpret-Community](https://github.com/interpretml/interpret-community) accept both models and pipelines as input as long as the model or pipeline implements a `predict` or `predict_proba` function that conforms to the Scikit convention. If not compatible, you can wrap your model's prediction function into a wrapper function that transforms the output into the format that is supported (predict or predict_proba of Scikit), and pass that wrapper function to your selected interpretability techniques.

If a pipeline script is provided, the explanation function assumes that the running pipeline script returns a prediction. The repository also supports models trained via **PyTorch**, **TensorFlow**, and **Keras** deep learning frameworks.

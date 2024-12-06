# AutoGluon 1.2: Advancing AutoML with Foundational Models and LLM Agents 

Automated machine learning (AutoML) offers the promise of translating raw data into accurate predictions without the need for significant human effort, expertise, and manual experimentation.
In this workshop, we introduce [AutoGluon](https://github.com/autogluon/autogluon), a state-of-the-art and easy-to-use toolkit that empowers *multimodal* AutoML.
Different from most AutoML systems that focus on solving tabular tasks containing categorical and numerical features, we consider supervised learning tasks on various types of data including tabular features, text, image, time series, as well as their combinations.
We will highlight how foundational models can be used to streamline and improve AutoML.
Particularly, we will discuss our TabPFN-Mix and Chronos family of foundation models for tabular and time series data, respectively.
We will introduce the real-world problems that AutoGluon can help you solve within three lines of code and the fundamental techniques adopted in the toolkit. 
Rather than diving deep into the mechanisms underlining each individual ML models, we emphasize on how you can take advantage of a diverse collection of models to build an automated ML pipeline.
We will also introduce [AutoGluon-Assistant](https://github.com/autogluon/autogluon-assistant) (AG-A) takes AutoGluon's automation from three lines of code to zero, enabling users to solve new supervised learning tabular problems using only natural language descriptions.
AG-A combines the natural language understanding properties of large language models (LLMs) with the state-of-the-art AutoML capabilities of AutoGluon to develop highly accurate and competitive ML solutions only based on the data and a natural language description of the problem.

Join us at the [NeurIPS 2024](https://neurips.cc/) in **West Ballroom C** of the Vancouver Convention Center on Tuesday, **December 10th at 12:00 noon PST**.

## Schedule

For each section, there will be a 5 min QA at the end of section. In addition, there will be [additional hands-on notebooks](#hands-on-notebooks) that people can try out asynchronously.

[Slides](#)

| Topic                                                  | Speaker                                         | Duration (CST timezone) | Tutorial Link                                                                                                                                                                | Cheatsheet                                                                                                                                                                                                                                                                                                                                                              |
|--------------------------------------------------------|-------------------------------------------------|-------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Introduction + AutoGluon Tabular](#autogluon-tabular) | [Nick Erickson](https://github.com/Innixma)     | 12:00PM    -- 12:45PM     | [tabular tutorial](https://tinyurl.com/ag-tutorial)                                                                                                                          | [![tabular-cheatsheet](https://raw.githubusercontent.com/Innixma/autogluon-doc-utils/main/docs/cheatsheets/stable/autogluon-cheat-sheet.jpeg)](https://nbviewer.org/github/Innixma/autogluon-doc-utils/blob/main/docs/cheatsheets/stable/autogluon-cheat-sheet.pdf) [docs](https://auto.gluon.ai/stable/tutorials/tabular_prediction/index.html)                        |
| [AutoGluon Assistant](#autogluon-assitant)          | [Name](Github) | 12:45PM -- 01:00PM        | [multimodal tutorial](https://colab.research.google.com/github/autogluon/autogluon/blob/stable/docs/tutorials/multimodal/multimodal_prediction/multimodal-quick-start.ipynb) | [![multimodal-cheatsheet](https://automl-mm-bench.s3-accelerate.amazonaws.com/cheatsheet/stable/automm.jpeg)](https://automl-mm-bench.s3-accelerate.amazonaws.com/cheatsheet/stable/automm.pdf) [docs](https://auto.gluon.ai/stable/tutorials/multimodal/index.html)
| [AutoGluon Timeseries](#autogluon-timeseries)             | [Abdul Fatir Ansari](https://github.com/abdulfatir)     | 01:00PM    -- 01:25PM     | [timeseries tutorial](https://colab.research.google.com/github/autogluon/autogluon/blob/stable/docs/tutorials/timeseries/forecasting-quick-start.ipynb)                      | [![timeseries-cheatsheet](https://raw.githubusercontent.com/Innixma/autogluon-doc-utils/main/docs/cheatsheets/stable/timeseries/autogluon-cheat-sheet-ts.jpeg)](https://raw.githubusercontent.com/Innixma/autogluon-doc-utils/main/docs/cheatsheets/stable/timeseries/autogluon-cheat-sheet-ts.pdf) [docs](https://auto.gluon.ai/stable/tutorials/timeseries/index.html) |                                                                                                    |
| Additional QA + Feedback                               | All speakers                                    | 3:50PM  -- 4:00PM       |                                                                                                                                                                              | [docs](https://auto.gluon.ai/cloud/stable/index.html)                                                                                                                                                                                                                                                                                                                                                                |



## Section Outline and Materials

### AutoGluon Tabular

- AutoML Basics: Discussion of core AutoML principles
- History of competition ML and how it influenced the design of modern AutoML systems
- Discussion of model combination strategies (stacking, bagging, model aggregation)
- Constraint satisfaction and engineering for a performance envelope (accuracy, speed, compute resources)
- Benchmark comparisons showcasing the advancement of AutoML systems in recent years both compared to earlier AutoML systems and human data scientists (4 AutoML frameworks, 104 OpenML datasets, 10 Kaggle datasets)


### AutoGluon Timeseries

- Time series forecasting in a nutshell
- An overview of machine learning for forecasting
- AutoML in time series and unique challenges
- Forecasting with AutoGluon-TimeSeries
- Looking forward in time series AutoML
- Hands-on notebooks + QA

### Hands-on Notebooks


**Checkout [AutoGluon Website](https://auto.gluon.ai/) and get started!**

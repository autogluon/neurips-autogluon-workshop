# AutoGluon 1.0: AutoML at Your Fingertips

Automated machine learning (AutoML) offers the promise of translating raw data into accurate predictions without the need for significant human effort, expertise, and manual experimentation. In this workshop, we introduce [AutoGluon](https://github.com/autogluon/autogluon), a state-of-the-art and easy-to-use toolkit that empowers *multimodal* AutoML. Different from most AutoML systems that focus on solving tabular tasks containing categorical and numerical features, we consider supervised learning tasks on various types of data including tabular features, text, image, time series, as well as their combinations. We will introduce the real-world problems that AutoGluon can help you 
solve within three lines of code and the fundamental techniques adopted in the toolkit.
Rather than diving deep into the mechanisms underlining each individual ML models, 
we emphasize on how you can take advantage of a diverse collection of models to build an automated ML pipeline. Our workshop will also emphasize on the techniques behind automatically building and training deep learning models, which are powerful yet cumbersome to manage manually.

Join us at the [NeurIPS 2023](https://nips.cc/) located at New Orleans Ernest N. Morial Convention Center on Sunday, December 10th, 2023 at 2:00pm, CST in Room 214.

## Schedule

For each section, there will be a 10 min QA at the end of section. In addition, there will be [additional hands-on notebooks](#hands-on-notebooks) after 
each session that people can try out asynchronously.

[Slides](https://docs.google.com/presentation/d/1vKi7_kZsE0gckOOdRagsEnLgp5QUFZKH/edit?usp=sharing&ouid=104172264144744783123&rtpof=true&sd=true)

| Topic                                                  | Speaker                                         | Duration (CST timezone) | Tutorial Link                                                                                                                                                                | Cheatsheet                                                                                                                                                                                                                                                                                                                                                              |
|--------------------------------------------------------|-------------------------------------------------|-------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Introduction + AutoGluon Tabular](#autogluon-tabular) | [Nick Erickson](https://github.com/Innixma)     | 2:00PM    -- 2:40PM     | [tabular tutorial](https://tinyurl.com/ag-tutorial)                                                                                                                          | [![tabular-cheatsheet](https://raw.githubusercontent.com/Innixma/autogluon-doc-utils/main/docs/cheatsheets/stable/autogluon-cheat-sheet.jpeg)](https://nbviewer.org/github/Innixma/autogluon-doc-utils/blob/main/docs/cheatsheets/stable/autogluon-cheat-sheet.pdf) [docs](https://auto.gluon.ai/stable/tutorials/tabular_prediction/index.html)                        |
| [AutoGluon Timeseries](#autogluon-tabular)             | [Nick Erickson](https://github.com/Innixma)     | 2:40PM    -- 2:50PM     | [timeseries tutorial](https://colab.research.google.com/github/autogluon/autogluon/blob/stable/docs/tutorials/timeseries/forecasting-quick-start.ipynb)                      | [![timeseries-cheatsheet](https://raw.githubusercontent.com/Innixma/autogluon-doc-utils/main/docs/cheatsheets/stable/timeseries/autogluon-cheat-sheet-ts.jpeg)](https://raw.githubusercontent.com/Innixma/autogluon-doc-utils/main/docs/cheatsheets/stable/timeseries/autogluon-cheat-sheet-ts.pdf) [docs](https://auto.gluon.ai/stable/tutorials/timeseries/index.html) |
| Break and Q&A                                          | -                                               | 2:50PM -- 3:00PM        | -                                                                                                                                                                            |                                                                                                                                                                                                                                                                                                                                                                         |
| [AutoGluon Multimodal](#autogluon-multimodal)          | [Zhiqiang Tang](https://github.com/zhiqiangdon) | 3:00PM -- 3:40PM        | [multimodal tutorial](https://colab.research.google.com/github/autogluon/autogluon/blob/stable/docs/tutorials/multimodal/multimodal_prediction/multimodal-quick-start.ipynb) | [![multimodal-cheatsheet](https://automl-mm-bench.s3-accelerate.amazonaws.com/cheatsheet/stable/automm.jpeg)](https://automl-mm-bench.s3-accelerate.amazonaws.com/cheatsheet/stable/automm.pdf) [docs](https://auto.gluon.ai/stable/tutorials/multimodal/index.html)                                                                                                    |
| [AutoGluon Ecosystem](#autogluon-timeseries)           | [Tony Hu](https://github.com/tonyhoo)           | 3:40PM  -- 3:50PM       | [cloud tutorial](https://auto.gluon.ai/cloud/stable/index.html)                                                                                                                                                           | -                                                                                                                                                                                                                                                                                                                                                                       |
| Additional QA + Feedback                               | All speakers                                    | 3:50PM  -- 4:00PM       |                                                                                                                                                                              | [docs](https://auto.gluon.ai/cloud/stable/index.html)                                                                                                                                                                                                                                                                                                                                                                |



## Section Outline and Materials

### AutoGluon Tabular

- AutoML Basics: Discussion of core AutoML principles
- History of competition ML and how it influenced the design of modern AutoML systems
- Discussion of model combination strategies (stacking, bagging, model aggregation)
- Constraint satisfaction and engineering for a performance envelope (accuracy, speed, compute resources)
- Benchmark comparisons showcasing the advancement of AutoML systems in recent years both compared to earlier AutoML systems and human data scientists (4 AutoML frameworks, 104 OpenML datasets, 10 Kaggle datasets)


### AutoGluon Multimodal

- Real-world multimodal problems (life beyond captioning images)
- Foundation models for image and text
- Fusion techniques & ensemble FMs / tabular models
- Object detection
- Multimodal matching
- Advanced topics
  - Training: Parameter-efficient finetuning
  - Deployment: Model distillation
  - Hyper-parameter optimization
- Hands-on notebooks + QA

### AutoGluon Timeseries

- Time series forecasting in a nutshell
- An overview of machine learning for forecasting
- AutoML in time series and unique challenges
- Forecasting with AutoGluon-TimeSeries
- Looking forward in time series AutoML
- Hands-on notebooks + QA

### AutoGluon Ecosystem

 - AutoGluon Assistant
 - AutoGluon Benchmark
 - AutoGluon Cloud

### Hands-on Notebooks


**Checkout [AutoGluon Website](https://auto.gluon.ai/) and get started!**

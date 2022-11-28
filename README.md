# AutoGluon: Empowering (Multimodal) AutoML for the Next 10 Million Users

Automated machine learning (AutoML) offers the promise of translating raw data into accurate predictions without the need for 
significant human effort, expertise, and manual experimentation. In this workshop, we introduce [AutoGluon](https://github.com/autogluon/autogluon), 
a state-of-the-art and easy-to-use toolkit that empowers *multimodal* AutoML. Different from most AutoML systems that focus on solving tabular tasks 
containing categorical and numerical features, we consider supervised learning tasks on various types of data including tabular 
features, text, image, time series, as well as their combinations. We will introduce the real-world problems that AutoGluon can help you 
solve within three lines of code and the fundamental techniques adopted in the toolkit.
Rather than diving deep into the mechanisms underlining each individual ML models, 
we emphasize on how you can take advantage of a diverse collection of models to build an automated ML pipeline.
Our workshop will also emphasize on the techniques behind automatically building and training deep learning models, 
which are powerful yet cumbersome to manage manually.

Join us at the [NeurIPS 2022](https://nips.cc/) located at New Orleans Ernest N. Morial Convention Center on Monday, November 28 at 2:00pm, CST in 
Room 293.

*Note: Github repository for this website is available at https://github.com/autogluon/neurips2022-autogluon-workshop* . 


## Schedule

For each section, there will be a 10-15min QA at the end of section. In addition, there will be [additional hands-on notebooks](#hands-on-notebooks) after 
each session that people can try out asynchronously.

| Topic                                                  | Speaker                                                                               | Duration (CST timezone) | Slides                                                                                                                                          | Cheatsheet                                                                                                                                                                                                                                                                                                                                       |
|--------------------------------------------------------|---------------------------------------------------------------------------------------|-------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Introduction + AutoGluon Tabular](#autogluon-tabular) | [Nick Erickson](https://github.com/Innixma)                                           | 2:00PM -- 2:55PM        | [link](https://docs.google.com/presentation/d/1whJdw8W0IixwFyRna13AjqlFKwO9ufsR/edit?usp=sharing&ouid=117434028345007023633&rtpof=true&sd=true) | [![tabular-cheatsheet](https://raw.githubusercontent.com/Innixma/autogluon-doc-utils/main/docs/cheatsheets/stable/autogluon-cheat-sheet.jpeg)](https://nbviewer.org/github/Innixma/autogluon-doc-utils/blob/main/docs/cheatsheets/stable/autogluon-cheat-sheet.pdf) [docs](https://auto.gluon.ai/stable/tutorials/tabular_prediction/index.html) |
| Break                                                  | -                                                                                     | 2:55PM -- 3:05PM        | -                                                                                                                                               |                                                                                                                                                                                                                                                                                                                                                  |
| [AutoGluon Multimodal](#autogluon-multimodal)          | [Xingjian Shi](https://github.com/sxjscience), [Yi Zhu](https://github.com/bryanyzhu) | 3:05PM -- 4:00PM        | [link](https://docs.google.com/presentation/d/1SlHVzaWtN-75m6mmvapeu4-C2Id7V5wO/edit?usp=sharing&ouid=117434028345007023633&rtpof=true&sd=true) | [![multimodal-cheatsheet](https://automl-mm-bench.s3-accelerate.amazonaws.com/cheatsheet/v0.6.0/AutoGluon_Multimodal_Cheatsheet_v0.6.0.png)](https://automl-mm-bench.s3-accelerate.amazonaws.com/cheatsheet/v0.6.0/AutoGluon_Multimodal_Cheatsheet_v0.6.0.pdf) [docs](https://auto.gluon.ai/stable/tutorials/multimodal/index.html)              |
| Break                                                  | -                                                                                     | 4:00PM -- 4:10PM        | -                                                                                                                                               |                                                                                                                                                                                                                                                                                                                                                  |
| [AutoGluon Timeseries](#autogluon-timeseries)          | [Caner Turkmen](https://github.com/canerturkmen)                                      | 4:10PM -- 4:50PM        | [link](https://docs.google.com/presentation/d/1AwZFuUWFT_Dp2wFLh9dk_RYLaYlsbxpN/edit?usp=sharing&ouid=117434028345007023633&rtpof=true&sd=true) | [![timeseries-cheatsheet](https://autogluon-timeseries-datasets.s3.us-west-2.amazonaws.com/public/autogluon_timeseries_cheatsheet.png)](https://autogluon-timeseries-datasets.s3.us-west-2.amazonaws.com/public/autogluon_timeseries_cheatsheet.pdf) [docs](https://auto.gluon.ai/stable/tutorials/timeseries/index.html)                        |
| Additional QA + Feedback                               | All speakers                                                                          | 4:50PM -- 5:00PM        | -                                                                                                                                               |                                                                                                                                                                                                                                                                                                                                                  |


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
- Hands-on notebooks + QA: [notebooks](./notebooks)

### AutoGluon Timeseries

- Time series forecasting in a nutshell
- An overview of machine learning for forecasting
- AutoML in time series and unique challenges
- Forecasting with AutoGluon-TimeSeries
- Looking forward in time series AutoML
- Hands-on notebooks + QA: [notebooks](./notebooks)

### Hands-on Notebooks

For hands-on tutorials, we provide notebooks for you to try out AutoGluon via [SageMaker Studio Lab](https://aws.amazon.com/sagemaker/studio-lab/) or [Google Colab](https://colab.research.google.com/).

All notebooks can be found in [notebooks](./notebooks).

**Checkout [AutoGluon Website](https://auto.gluon.ai/) and get started!**

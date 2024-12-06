Automated machine learning (AutoML) offers the promise of translating raw data into accurate predictions without the need for significant human effort, expertise, and manual experimentation.
In this workshop, we introduce [AutoGluon](https://github.com/autogluon/autogluon), a state-of-the-art and easy-to-use AutoML framework.
We will emphasize how foundational models can streamline and enhance AutoML performance.
Specifically, we will discuss our TabPFN-Mix and Chronos foundational model families for tabular and time series data, respectively.

We will introduce the real-world problems that AutoGluon can help you solve within three lines of code and the fundamental techniques adopted in the toolkit. 
Rather than diving deep into the mechanisms underlining each individual ML model, we emphasize on how you can take advantage of a diverse collection of models to build an automated ML pipeline.

Additionally, we will present [AutoGluon-Assistant (AG-A)](https://github.com/autogluon/autogluon-assistant), which advances AutoGluon's automation from three lines of code to zero.
AG-A allows users to solve supervised tabular learning problems using only natural language descriptions.
By integrating the natural language understanding capabilities of large language models (LLMs) with AutoGluon's advanced AutoML features, AG-A delivers highly accurate and competitive ML solutions based solely on the data and a natural language description of the problem.

Join us at [NeurIPS 2024](https://neurips.cc/) in **West Ballroom C** of the Vancouver Convention Center on Tuesday, **December 10th at 12:00 noon PST**.

## Schedule

There will be a 5 min QA at the end of each section. A link to the slides will be provided prior to the talk.

| Topic                                                  | Speaker                                             | Duration (CST timezone) | Links                                                                                                                                                                                                                                                                                                        | Cheatsheet                                                                                                                                                                                                                                                                                                                                                               |
|--------------------------------------------------------|-----------------------------------------------------|-------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Introduction + AutoGluon Tabular](#autogluon-tabular) | [Nick Erickson](https://github.com/Innixma)         | 12:00PM    -- 12:45PM   | [tabular tutorial](https://colab.research.google.com/github/autogluon/autogluon/blob/stable/docs/tutorials/tabular/tabular-essentials.ipynb)                                                                                                                                                                                                                                                          | [![tabular-cheatsheet](https://raw.githubusercontent.com/Innixma/autogluon-doc-utils/main/docs/cheatsheets/stable/autogluon-cheat-sheet.jpeg)](https://nbviewer.org/github/Innixma/autogluon-doc-utils/blob/main/docs/cheatsheets/stable/autogluon-cheat-sheet.pdf) [docs](https://auto.gluon.ai/stable/tutorials/tabular_prediction/index.html)                         |
| [AutoGluon Assistant](#autogluon-assistant)            | [Boran Han](https://github.com/boranhan)            | 12:45PM -- 01:00PM      | -                                                                                                                                                                                                                                                                                                            | [docs](https://github.com/autogluon/autogluon-assistant)                                                                                                                                                                                                                                                                                                                 |
| [AutoGluon Timeseries](#autogluon-timeseries)          | [Abdul Fatir Ansari](https://github.com/abdulfatir) | 01:00PM    -- 01:25PM   | [timeseries quick start](https://colab.research.google.com/github/autogluon/autogluon/blob/stable/docs/tutorials/timeseries/forecasting-quick-start.ipynb), [chronos tutorial](https://colab.research.google.com/github/autogluon/autogluon/blob/stable/docs/tutorials/timeseries/forecasting-chronos.ipynb) | [![timeseries-cheatsheet](https://raw.githubusercontent.com/Innixma/autogluon-doc-utils/main/docs/cheatsheets/stable/timeseries/autogluon-cheat-sheet-ts.jpeg)](https://raw.githubusercontent.com/Innixma/autogluon-doc-utils/main/docs/cheatsheets/stable/timeseries/autogluon-cheat-sheet-ts.pdf) [docs](https://auto.gluon.ai/stable/tutorials/timeseries/index.html) |                                                                                                    |
| Additional QA + Feedback                               | All speakers                                        | 01:25PM  -- 01:30PM     |                                                                                                                                                                                                                                                                                                              | [docs](https://auto.gluon.ai/cloud/stable/index.html)                                                                                                                                                                                                                                                                                                                    |

## Section Outline and Materials

### AutoGluon Tabular

- AutoML Basics: Discussion of core AutoML principles
- History of competition ML and how it influenced the design of modern AutoML systems
- Discussion of model combination strategies (stacking, bagging, model aggregation)
- Constraint satisfaction and engineering for a performance envelope (accuracy, speed, compute resources)
- Benchmark comparisons showcasing the advancement of AutoML systems in recent years both compared to earlier AutoML systems and human data scientists
- AutoGluon's performance and adoption on live kaggle competitions in 2024
- New TabPFN-Mix model and parallel model fit support

### AutoGluon Assistant

- WIP

### AutoGluon Timeseries

- WIP

### Hands-on Notebooks


**Checkout the [AutoGluon Website](https://auto.gluon.ai/) and get started!**

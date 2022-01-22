# Project Report Title
**Authors** 
Christopher Metzler, Shehani, Deverell, Malachi Buchheit, Bailey Trip, Patrick

**Abstract** : It is a standalone section. It is written to give the reader a summary of your work. Be sure to specific, yet brief. Even though the abstract comes first in your paper, it is sometimes easier to write the abstract last. (150-300 words)

## Introduction

The Common Core of Data (CCD) is the Department of Education's primary database on public elementary and secondary education in the United States. CCD is a comprehensive, annual, national database of all public elementary and secondary schools and school districts. There are seven categories of data. Within each category, data are organized by year. Within each year, there are four or five different data files. The overall objective of this benchmark is to design and evaluate prediction of high poverty stricken school from the publicly available data, and to evaluate the value of Title 1 school designation. 

**Note:** you can transform it to Jupyter Notebook and add sections below as markdown cells. 

## Problem Statement 

The overall objective is to design and evaluate prediction of high poverty stricken schools from the publicly available data accross the U.S., and to evaluate the value of Title 1 school designation. The resulting model might grant insight into the factors critical to the success of school districs.

# Dataset link: https://nces.ed.gov/ccd/files.asp

The data spans from 2015 to 2018 (3 school years). Schools began reporting more varieties of data in 2015 than previous years, and 2018 is the latest year fiscal data is available. Thus, this selection allows for the greatest range of data.

* Include informal success measures (e.g. accuracy on cross-validated data, without specifying ROC or precision/recall etc) that you planned to use.

Our model will be considered successful if it shows higher than 60% accuracy in testing and validation.

### Related Work

* Include background material as appropriate: who cares about this problem, what impact it has, what implications better solutions might have.
* Included a brief summary of any related work you know about.
* Benchmark implementations - see [paperswithcode.com](paperswithcode.com) as a good start 

## Data Management 

In this section you should address the questions of interest and interpret the results in terms of the questions of interest you proposed. (1-5 pages, including relevant tables and figures, please adjust your figures to appropriate sizes).

- Describe how did you evaluate your solution
- What evaluation metrics did you use?
- Describe a baseline system
- How much did your system outperform the baseline?
- Were there other systems evaluated on the same dataset? How did your system do in comparison to theirs?
- Show graphs/tables with results
- Error analysis
- Suggestions for future improvements

Description of the dataset (dimensions, names of variables with their description)

### Data Gathering

Answer the questions from *Motivation* (Sec 3.1.) *Composition* (Sec 3.2), and *Collection* (Sec 3.3) of the [Datasheets For Datasets](https://arxiv.org/abs/1803.09010) paper here. 
* If benchmarks, describe the data in details.
* If data collections, justify your methods in terms of data statement. 

What Data Acquisition have you used.  Why? 
(usually algorithms, or data cleaning or wrangling approaches). 

Justify your methods in terms of the problem statement. What did you consider but *not* use? In particular, be sure to include every method you tried, even if it didn't "work". When describing methods that didn't work, make clear how they failed and any evaluation metrics you used to decide so. How was that a data-driven decision? 

### Data Pre-processing, Cleaning, Labeling, and Maintenance 

What Cleaning, and Processing Tools have you used.  Why? 
* Answer the questions from 3.4 **Preprocessing/cleaning/labeling** of the [Datasheets For Datasets](https://arxiv.org/abs/1803.09010) paper here. 

### Exploratory Data Analysis 

* Describe the methods you explored (usually algorithms, or data wrangling approaches). 
* Justify your methods in terms of the problem statement. 
* What did you consider but *not* use? In particular, be sure to include every method you tried, even if it didn't "work". 
**NOTE:** Move from .md to .ipynb format when you plan to show EDA (either project proposal or midterm checkpoint)


## Machine Learning Approaches

In this section, you could describe the methods you used in your analysis. For example, if you are doing classifications, you could introduce the methods like logistic regression, discriminant analysis, support vector machines. You don't have to write formulas if you don't want to do so. It is fine to describe the methods in words. This section basically is a description of the methodologies that you have used for analyzing your data. (up to 2pages)
Describe the choice of Machine Learning Tool.  Refer ro related work, if applicable.  

* Evaluate a primary model and in addition a "baseline" model. 
  * The baseline is typically the simplest model that's applicable to that data problem
    * Naive Bayes for classification
	* K-means on raw feature data for clustering.
* Evaluate state-of-art model 
  * Research gitHuib, paperswithcode, Kaggle and similar. 
  * If not applicable, talk to the instructor.  
  
**Hint** Goal is to have some sort of baseline evaluation by Nov 11th checkpoint to establish a scale by which to measure your project's performance. Compare the performance of your baseline model and primary model and explain the differences.

** This is where all the methods you have tried go, including state-of-art if any **

### Describe the ML methods that you used and the reasons for their choice. 
What is the family of machine learnign algorithms you are using and why? 
* Supervised or Unsupervised?
* Regression or classification?

### Justify ML algorithms in terms of the problem itself and the methods you want to use. 
* How did you employ them? 
* What features worked well and what didn't?
* Provide documentation for integration  

### Tools and Infrastructure Tried and Not Used

Describe any tools and infrastruicture that you tried and ended up not using.
What was the problem? 
Describe infrastructure used. 

## Experiments

Give a detailed summary of the results of your work.

 * Setup - Here is where you specify the exact performance measures you used.  
   * Describe the data used in experiment for presenting dataset: Datasheets for Dataset template 
   * Describe your accuracy or quality measure, and your performance (runtime or throughput) measure. 
   
 * Please use visualizations whenever possible. Include links to interactive visualizations if you built them. 
 
 * You can also submit a separated notebook as an appendix to your report if that makes the visualization/interaction task easier. 
   * It would be reasonable to submit your report as a notebook, but please make sure it runs on one of the two standard environments, and that you include any required files. 

## Conclusion
In this section give a high-level summary of your results. If the reader only reads one section of the report, this one should be it, and it should be self-contained.  You can refer back to the Experiments Section for elaborations. This section should be less than a page. In particular emphasize any results that were surprising.


## References
List the references that cited in your project.

## Appendix## 

Explain the contributions of each member to the project. Include all supporting materials, e.g., additional figures/tables, Python code technical derivations.

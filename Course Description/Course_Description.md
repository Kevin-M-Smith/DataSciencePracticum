# Data Sciences Practicum 

# Course Description

A practical introduction to contemporary data analysis with a focus on improving programming literacy, research workflow, and reproducibility. A majority of the workload is designed to complement and advance the student's current research. Covers programming basics, exploratory data analysis, and common modeling tasks using the _R_ programming language. Introduces cutting-edge data science concepts, including distributed version control, the grammar of graphics, and dynamic documents. Rather than focusing on the particulars of the language, learning objectives are targeted toward building the familiarity and confidence necessary for future self-study. 

# Course Logistics
## Sessions
* 12 Weekly Sessions
	* 3 Hours In Length
	* First 1.5 Hours of Instruction
	* Final 1.5 hours are optional, and serve as open office hours with instructor and collaboration with classmates

## Course Notes
* __Course notes__ will be published online in both HTML and PDF format, at least one week prior to the relevent session
* Course notes will provide __explicit examples for the basic concepts__ students are expected to be familiar with, and __vetted online references for advanced__ concepts which may be helpful to their particular research

## Homework
* __Weekly review exercises__ of less than 2 hours in length will be assigned. They will be relevant to the course notes of the particular week. Some of these exercises will involve __peer review__ of code, so it is important that the assignments be submitted on time. 

* Optional __challenge exercises__ will be occasionally posted. These exercises will be based on advanced concepts from previous sessions. Successful completion of a __challenge exercise__ will earn extra credit equivalent to a __weekly review exercise__.


## Project
* The course project will ideally be based on student's current research. The purpose of the project is to:
	* Resolve pre-existing data analysis issues
	* Refine the student's current research and data analysis workflow
	* Expose the student to best practices for documentation and reproducibility
	* Practice communication of experimental design and results

* The project will have with __three__ milestones:
	1. __Proposal__: The proposal consists of two parts:
		* A general description of the student's current research and _a scope of work to be attempted_ within the semester towards this research project.
		* In the context of your research project, identify a common frustration, existing limitation, or _bad habit_ that you would like to improve on over the course of the semester.  Work the instructor to develop a _course of action_ to resolve the problem. 
	2. __Presentation__:  Starting on __week 7__ each class will feature a student presentation. In the presentation the student will communicate:
		* the research question / hypothesis
		* the data analysis methods used or needed 
		* describe the features of a relevant dataset to the class using exploratory data analysis
	3. __Report__: The project will culminate in a project report. The report will include all necessary code and data to reproduce the findings. The grade will be based partially on the reproduction of results, but also on style, documentation, and overall effort. 

# Learning Objectives by Session 
## Unit I: Getting Started With _R_
1. oRientation
	* __Become familiar__ with the _R_ and _RStudio_ environments
	* __Understand__ the differences between basic data types
	* __Understand__ basic variable assignment
	* __Exposure__ to data importing and exporting functionality 
	* __Exposure__ to _git_ for version control

2. Programming Control Structures
	* __Understand__ how to control programs using conditional statements
	* __Understand__ Understand how to use _functions_ and _loops_ to compartmentalize code
	* __Exposure__ to _apply_ statements and _style_ standards

3. __Topical__: Monte Carlo Simulation
	* __Understand__ how to generate random numbers in R
	* __Understand__ how to to use the _replicate_ function
	* __Exposure__ to _parallelization_ to perform multiple computations simultaneously
	
4. Introduction to Graphics
  	* __Become familiar__ with basic graphics functions
  	* __Understand__ the basics of graphics devices and how to save outputs
  	* __Understand__ the ideas behind __the grammar of graphics__
	* __Exposure__ to __ggplot2__, which implements __the grammar of graphics__

5. Debugging and Improving Performance
	* __Become familiar__ with _RStudio_ debugger
	* __Become familiar__ with _lineprof_ package
	* __Revisit__ _apply_ statements and _parallelization_
	* __Exposure__ to common performance pitfalls

## Unit II: Working with Datasets
6. __Topical__: Exploratory Data Analysis
	* __Become familiar__ with methods for determine structure of a dataset
	* __Understand__ how to check for missing data
	* __Understand__ how to make quick diagnostic plots 

7. Harvesting and Cleaning Data
	* __Understand__ how to use _Rstudio_ to import data
	* __Exposure__ to tools for downloading live data from the web
	* __Exposure__ to the _plyr_ package

8. Working with 'Big Data'
	* __Exposure__ to the _data.table_ package
	* __Enhanced understanding__ of _plyr_ package  
	* __Become familiar__ with efficient means of altering and summarizing data

9. __Topical__: Regression
	* __Become familiar__ with _model objects_ and accessor functions 
	* __Become familiar__ with _formulas_
	* __Understand__ how to run a basic linear regression model with _lm_
	* __Understand__ how to graph model outputs
	* __Exposure__ to generalized linear models with _glm_
	* __Exposure__ to _leaps_ package for best subsets regression

# Unit III: In the Driver's Seat
10. __Creating Dynamic Documents__
	* __Exposure__ to _Rmarkdown_
	* __Understand__ how to create a basic dynamic report 
	* __Understand__ how to print system information for reproducibility

11. __Creating Packages__
	* __Exposure__ to _buildtools_
	* __Exposure__ to _unit tests_
	* __Understand__ how to make _Roxygen2_ comments 
	* __Understand__ the basics of the _DESCRIPTION_ file
	* __Understand__ how to store package for later use

12. __TBD / Slack__
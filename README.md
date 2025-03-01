# GenAI for Software Development (Ngram)

* [1 Introduction](#1-introduction)  
* [2 Getting Started](#2-getting-started)  
  * [2.1 Preparations](#21-preparations)  
  * [2.2 Install Packages](#22-install-packages)  
  * [2.3 Run N-gram](#23-run-n-gram)  
* [3 Report](#3-report)  

---

# **1. Introduction**  
This project uses an **N-gram recommender system** to probabilistically generate Java methods with an initial set of tokens.  

---

# **2. Getting Started**  

This project is implemented in a **Google Colab Notebook** and is viewable and executable on **Google Chrome**.  

## **2.1 Preparations**  

(1) Download the necessary files:
**results_student_model.txt** (or view directly on GitHub)
**results_teacher_model.txt** (or view directly on GitHub)
**training.txt**
**DatasetCSVs.zip**
**CSCI420Project1_Final.ipynb**

(2) Open **CSCI420Project1_Final.ipynb** in Google Colab

(3) Unzip **DatasetCSVs.zip** and place its contents alongside **training.txt** in the **content** (default location) folder of the notebook:

## **2.2 Install Packages**

All package dependencies will be covered by Google Colab itself and the import commands within the notebook.n

## **2.3 Run N-gram**

To run the N-gram model, each code block (unless commented out/specified) must be run **in sequential order**. Most importantly, any block that modifies **model_train** will globally change **model_train** for evaluation methods, so executing out-of-order may cause issues. 

If the CSVs and instructor-provided corpus are placed within the **content** folder, the code will run from start to finish without issues. Code blocks are commented extensively to highlight key features and nuances of functions or processes.
If attempting to create a new results file (**results_student_model.txt** or **results_teacher_model.txt**), uncomment the labeled code blocks and run them (note the warning about **model_train**).

## 3. Report

The assignment report is available in the file **GenAI 420 Project 1 Writeup.pdf**.

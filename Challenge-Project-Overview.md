# Groundwater time series forecasting using AI

**Company / Org:** Microsoft  
**Challenge Advisor:** Aarti Dwivedi, aartidwivedi @ microsoft.com  
**AI Coach:** Alexandra Ladyzhensky, alexandra.ladyzhensky @ breakthroughtech.org

**Program:** Break Through Tech AI Studio - Fall 2026

---

## 🏢 About Microsoft

Microsoft is a global technology leader, empowering individuals and organizations through innovative software, services, and solutions. Our focus spans various sectors, driving advancements in AI, cloud computing, and more.

---

## 🎯 The Challenge

### Project Summary
In this project, you will use GROW dataset and LSTM to forecast the water level in a particular groundwater well. The output will be a 7 day time series. The focus will be on the two data subsets included in this repository. One is a monthly dataset and one is a daily dataset. Each dataset is clustered geographically and is suitable for beginners. The data is available at https://zenodo.org/records/15149480. The paper is available at https://www.nature.com/articles/s41597-026-06966-1

### Success Criteria
1. Demonstrate good practices for exploratory data analysis.
2. A basic understanding of how to process time series data.
3. An understanding of the fundamentals of LSTM or choice of forecasting method.
4. An understanding of how to approach large data sets.
5. A prediction that is within 30% of the ground truth.

### Stretch Goal
Prediction within 20% of the ground truth.
   
### Project Milestones

Use these milestones to guide your work. Your team will create a **GitHub Projects board** to track tasks within each milestone.

| Month | Milestone | Key Activities |
|---|---|---|
| September | Exploratory Data Analysis | • Load the database<br>• visualize temporal trends<br>• use rolling statistics to detect trends and seasonality<br>• use autocorrelation and partial autocorrelation plots<br>• impute missing values using interpolation |
| October | LSTM Foundations & Feature Selection | • Learn the basics of LSTM and use toy datasets to develop an understanding of the method<br>• start training LSTM on the main dataset and identify 10 features that are most relevant to the feature (water level) that we are trying to predict. |
| November | Model Refinement & Visualization | • Continue experimenting with the model and produce visualizations. |

> **Note for the team:** Please create a GitHub Projects board in this repository to break these milestones into weekly tasks. Go to the **Projects** tab → **New project** → Choose **Board** → Add columns for each month.

---

## 📊 Dataset

**Name and Source:** GROW dataset containing groundwater well data  
**Format:** CSV/TSV, JSON, Parquet  
**Size:** 1gb to 5gb  
**Location:** https://zenodo.org/records/15149480

### Key Details
- Time series data of groundwater depth/elevation along with some other attributes.
- Details on the attributes can be found in the Readme.pdf.


---

## 🛠️ Suggested Approach

**ML Problem Type:** Time Series Analysis

**Recommended Libraries:**
- pandas for reading the CSV files, sktime for time series analysis (https://github.com/sktime/sktime)
- Read https://medium.com/@katser/a-list-of-python-packages-for-time-series-analysis-c883bcadcc58 for an overview of available libraries.

**Evaluation Metrics:**
- RMSE
- https://eshban9492.medium.com/understanding-evaluation-metrics-for-time-series-forecasting-5c8a3c877654 - Read this for an overview of the metrics and the formulation.

---

## 📚 Resources to Get Started

The following resources will help your team understand the problem space and potential technical approaches for this project:

**Background Reading:**
- https://www.nature.com/articles/s41597-026-06966-1
- Do not worry about understanding everything in the paper. The idea is to get a high level understanding of the physical system from which your data was derived.
- https://arxiv.org/pdf/1909.09586 do not worry about all the mathematical details, the intention is to get an idea of some of the things that go into LSTMs, which are often used for time series forecasting. You are not bound to LSTMs, you may use whichever method you choose.

**Technical Tutorials:**
- https://github.com/omerbsezer/LSTM_RNN_Tutorials_with_Demo
- https://github.com/sktime/sktime

**Code Examples:**
- https://www.sktime.net/docs/examples/forecasting/
- https://towardsdatascience.com/advanced-time-series-forecasting-with-sktime-af8eabc76173/


**Other:**

*Feel free to explore beyond these, and share anything interesting you find with me!*


---

## 🤝 How We'll Work Together

**Official check-ins:** During our biweekly 45-minute AI Studio Lab Section meeting block (2nd and 4th week of every month)

 **Other ways to reach out to me with questions:** 
* Will add Discord as soon as my access issues are solved.
* Emailing me.
* Request a team check-in on Zoom - but no more than once a week.
* I will aim to respond within 24 hours. Please reach out to your AI Studio Coach with urgent questions.


**Recommended free coding / collaboration tools**
* Whatever is comfortable to you but Github should always reflect your progress.
* […]

---

## 🚀 Getting Started

1. **Review this overview document** and note any questions for our first meeting
2. **Begin reviewing the dataset** using the link above
3. **Read the GitHub Projects documentation** [here](https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/about-projects)
4. Done is better than perfect.
5. The expectation from you is exploration, your Github history does not need to reflect only answers.

I’m excited to work with you!

---

## ❓ Questions?

Please bring any questions to our first meeting during the week of August 24th (Break Through Tech’s Bridge to Studio - Session C). 

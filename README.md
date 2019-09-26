## Project Title: Recommendation to improve SAT participation rates in California

Part of my DSI project:
Pretend that you are an employee of the College Board - the organization that administers the SAT - you are a part of a team that tracks statewide participation and recommends where money is best spent to improve SAT participation rates. Your presentation and report should be geared toward **non-technical** executives with the College Board and you will use the provided data and outside research to make recommendations about how the College Board might work to increase the participation rate in a **state of your choice** (which i choose was California).

### Datasets

Getting Started

#### Provided Data

For this project, you'll have 5 provided datasets:

- ./data/sat_2017.csv
- ./data/act_2017.csv
- ./data/sat_2018.csv
- ./data/act_2018_updated.csv
- ./data/studentpopulation.csv

**The data has been compiled into CSV files which are also included in the *data* directory of this repo**

#### Prerequisites

Python 3
Matplotlib.pyplot
Seaborn
Scipy.stats

#### Workflow in the code attached

#### Marked down included in the code.
1.Loads the CSVs
2.Looked at the .info and realised that there a national average for ACT and drop the entry.
3.Plotted histogram and boxplots and found extreme values. - fixed the 52Math for SAT 2017 and 2.3 for Sci for ACT 2017.
4.Realised that there was no data on graduating high sch students in the data.
5.Fixed features in the dataframe (participation to float and typo in composite)
6.Plotted initial charts to look for trends - correlation, histograms again (after cleaning data) and boxplots.
7.Created new dataframes to do masking more efficiently and charting the results.
8.Did external research on web to find out on the legislation aspect and state budget for test.
9.Downloaded extra data set on graduating high sch student and included into analysis.


Version
1.0

Authors
Andrew Goh - Initial work
See also the list of contributors who participated in this project.

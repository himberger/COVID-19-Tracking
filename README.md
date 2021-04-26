# COVID-19-Tracking
Tracking select counties and ZIP codes for COVID-19 cases.

This project began in March 2020 to track the cumulative number of COVID-19 cases and the rise in cases for a selected number of counties and ZIP codes.
Included in this public project is the IPython Notebook (i.e. "covidTracker.ipynb") used to pull data automatically from 
the <a href='https://github.com/CSSEGISandData/COVID-19'>Johns Hopkins public data repository</a> and 
the <a href='https://coronavirus.maryland.gov/'>Maryland state public data repository</a>. Also in that notebook are manual data entry sections 
for <a href='https://covid19.ncdhhs.gov/dashboard'>NC ZIP codes</a> and 
<a href='https://coronavirus.dc.gov/data'>DC information by neighborhood</a>.
Data is displayed several ways within the notebook, including: cumulative case totals, normalized rates of infection, and growth statistics.
Additionally, an MP4 can be generated from within the notebook to show the relative rise in cases across the last year (e.g. "PastYearCasesThrough20210416.mp4").

A Tableau dashboard (i.e. "covidDashboard.twb") is included to show not only COVID-19 tracking information, but also 
the <a href='https://svi.cdc.gov/Documents/Data/2018_SVI_Data/SVI2018Documentation.pdf'>CDC's Social Vulnerability Index</a> to visually inspect how a host of factors (socioeconomic status, household composition & disability, minority status & language, and housing type & transportation) correlate with COVID-19 cases.

Future versions will incorporate prison tracking data from <a href='https://github.com/themarshallproject/COVID_prison_data'>the Marshall Project</a>.

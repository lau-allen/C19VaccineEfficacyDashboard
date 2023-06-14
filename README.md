# Covid19 Vaccine Efficacy Dashboard

Understanding the level of protection within a population against Covid-19 is crucial, and two key metrics play a significant role in this regard: breakthrough rates and the percentage of vaccines that do not offer complete protection. These metrics provide valuable insights into the susceptibility of individuals who have been vaccinated but are still at risk of infection. However, it's important to note that these metrics are heavily influenced by the efficacy of the available vaccines.

To shed light on this information, the dashboard presented here explores breakthrough rates and the percentage of vaccines not providing full protection across different countries. It explores these metrics in relation to specific vaccine variants and Covid-19 variants, offering a comprehensive view of how they evolve over time. By analyzing this data, we gain a deeper understanding of the effectiveness of vaccines in different contexts, aiding us in making informed decisions and implementing necessary measures to combat the pandemic.

**Technical Details:**
* Tech Stack: Python (Dash, Plotly, Pandas), HTML / CSS

Process Overview: 
* Compiled data from various tables available at ourworldindata.org/covid-vaccinations.
* Exported the data as CSV files.
* Read the CSV files into Pandas DataFrames for further analysis.
* Performed a multitude of data manipulations, including filling techniques to address missing values and calculations to derive breakthrough rates, using Python.
* Plotted the resultant data using Plotly.
* Created a dashboard using Dash to display the visualizations.

Additional Contributors: lizzjs, ana-gra 

Link to original repo: https://github.com/lizzjs/C19VaccineEfficacy-Dash

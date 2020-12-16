# Data cleaning and Visualisation

Covid-19 data serves perfectly for learning Python. There are many sources with Covid-19 data. As a start I decided to use Lithuanian open data portal. It provides data on testing results and positive cases by gender and age. File are .CSV and .JSON formats.

For analysis, I use epidemiological data published in [here](https://data.gov.lt/dataset/covid-19-epidemiologiniai-duomenys)

To visualize correctly current situation in Lithuania, I needed to clean data a bit.
  * Source has two columns of date: "Start of sickness" and "Positive test date". 
        * I used `<pd.to_datetime>` to convert string type to date type 

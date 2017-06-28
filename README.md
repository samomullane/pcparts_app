# pcparts_app:

## Web scraping PCPartpicker.com for value-based recommendations

The finished app can be found [here](https://samomullane.shinyapps.io/pcbuild_app/). A full write up of this project can be accessed via [this link](http://blog.nycdatascience.com/student-works/web-scraping/value-based-pc-part-selection/).

The contents of this main folder are the ipython EDA notebook, the final presentation slides, the webscraping folder and the final part recommendation app.

Altogether 5 programming languages were used for this project (in order of chronology):

1. JavaScript (PhantomJS) - webscraping tool, used to grab all of our required data 
2. Bash - command line scripting to automate and coordinate python, PhantomJS scripts
3. Python - BeautifulSoup parsing of scraped data; initial EDA and data preparation in ipython notebook
4. SQL - local database created to store all of the cleaned data; most of the app logic is constructed in SQL
5. R - the final app is constructed with Shiny and hosted on shinyapps.io

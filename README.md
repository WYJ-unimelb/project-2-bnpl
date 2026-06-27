# Generic Buy Now, Pay Later Project README.md
- Group Members: `Haoran Liu` `Yaojin Wu``Zehan Fu``Ambrose He``Linhang Yu`
- Goals: Sort the buy now pay later companies in the dataset and select the top 10 companies in different industries as a reference for investors.

To run the pipeline, first please download the all four datasets and put them in to `./data/tables`. The data are sourced from:
- Part 1: https://canvas.lms.unimelb.edu.au/courses/188486/files/20455238?module_item_id=6027492
- Part 2: https://canvas.lms.unimelb.edu.au/courses/188486/files/20455243?module_item_id=6027493
- Part 3: https://canvas.lms.unimelb.edu.au/courses/188486/files/20455247?module_item_id=6027494
- Part 4:https://canvas.lms.unimelb.edu.au/courses/188486/files/20455248?module_item_id=6027495
- An external data sourced from:
https://explore.data.abs.gov.au/vis?fs[0]=Economy%2C0%7CPrice%20indexes%20and%20inflation%23PRICE_INDEX_INFLATION%23&pg=10&fc=Economy&df[ds]=ECONOMY_TOPICS&df[id]=CPI_M&df[ag]=ABS&df[vs]=&pd=2022-07%2C&dq=1%2B3...50.M&ly[cl]=TIME_PERIOD&ly[rw]=INDEX&ly[rs]=MEASURE%2CTSEST
Has been added to the `./data/tables`

Then please visit the `./notebooks` directory and run the file in order:
week6 -week10
- The function of the files are:
  Week6: Preliminary Analysis and ETL Pipeline Construction
  Week7: Data cleaning and Outlier analysis
  Week8: Curate a dataset and simple models
  Week9: Build a model for forecasting the number of customers of the merchant
  MidBreak: Build an initial ranking system by segment the merchants
  Week10: Selection scheme of top N merchants


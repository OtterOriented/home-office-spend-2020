# Home Office Spend 2020

Light analysis of data of Home Office procurement card spend over £500 for 2020.

There was a [tweet on 26th March 2020](https://twitter.com/lloydhardy/status/1375363511962980352?s=20) with a screenshot of some Home Office spending. I just got curious about how easy it would be to harvest, clean and summarise the spending data.

* Data [downloaded from here](https://www.gov.uk/government/publications/home-office-procurement-card-spend-over-500-2020) on 26-Mar-2021
* Data covers the 2020 calendar year
* Data published 19-Mar-2021

## Files in Repository

* [Jupyter Notebook](HomeOffice.ipynb)
* [Jupyter Notebook as HTML](HomeOffice.html)
* [Cleaned merged data](cleaned_spend.csv) - CSV of merged data
* [Cleaned aggregate data](cleaned_agg_spend.csv) - CSV of data aggregated by supplier. Columns:
  * Supplier
  * total_spent_supplier - total spent with supplier over year
  * percent_share_spend - percentage of total spend with supplier
  * number_purchases - number of purchases made with supplier
  * first_purchase - data first purchase made from supplier (yyyy-mm-dd)
  * last_purchase - date last purchase made from supplier (yyyy-mm-dd)

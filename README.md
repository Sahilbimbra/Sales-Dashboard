# Sales Dashboard

A Power BI dashboard I built to practice turning raw sales data into something an actual manager could look at and make decisions from.

The dataset is a sample sales export covering 2013 and 2014 — 700 rows, five countries, six products, and five customer segments (Government, Small Business, Enterprise, Midmarket, Channel Partners).

## What's in it

- A year slicer (2013 / 2014) that filters everything on the page
- Total Sales, Cost of Goods, and Total Profit as KPI cards
- Two DAX measures that pull out the product with the highest and lowest profit automatically, instead of me eyeballing it every time the data changes
- Monthly sales trend
- Sales broken down by country
- Top 5 products by units sold
- A combined COGS/Sales/Profit line chart by month
- Sales by segment as a donut chart

For 2014: total sales came out to 92.31M, COGS was 79M, and profit landed at 13.02M. Paseo was the best-performing product by profit (3.70M), Montana the weakest (1.66M). Government and Small Business together make up about 80% of revenue, so most of the volume is coming from just two segments.

## Files

- `Sample Data Dashboard.pbix` — the actual Power BI file
- `Sample data.xlsx` — source data
- `Sample Data Dashboard.pdf` — flat export in case you don't have Power BI installed

## Tools

Power BI Desktop, DAX for the calculated measures, Excel for the source file.

## Notes to self

The country and product bars are close to each other in value, so if I revisit this I might add data labels on the bars themselves instead of relying on the axis. Also thinking about swapping COGS out of that combined line chart for a profit margin % line instead, since COGS tracks sales pretty closely and doesn't add much on its own.

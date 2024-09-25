# Electromart Sales Data Dashboard

This project aims to analyze sales data to identify trends, top-selling products, and revenue metrics, enabling data-driven decision-making for business optimization.

Author : Varthavee S

## Project Overview

Analyzes sales data to identify trends, top-selling products, and revenue metrics. Provides insights to optimize sales strategy and inform business decisions. Enables data-driven decision-making for improved sales performance.

## Steps to Create the Dashboard

### STEP 1:
I downloaded the dataset, uploaded it using the 'Get Data' option in Power BI, and then proceeded to transform the data.

### STEP 2:
The column headers are identified in the first row and should be kept as headers

### STEP 3:
After promoting the headers, navigate to the 'Transform' tab and select 'Detect Data Type.' This action will automatically identify the data type of each column and convert them as needed.

### STEP 4:
• Split the datetime into date and time stamp

• Choose the 'Split Column' option and select the space as the delimiter.

• Upon completing the data transformation, click on 'Close & Apply' located at the top left.

• Remember, this step is crucial after any data transformation process.

## Build Visualizations
### STEP 1: Sales trend over time using the line chart

- Simply click on the Month name and Sales column, drag it to the desired
position.

- To create a Chronological order for the months, follow these steps:
1. Select the column containing the months.
2. Navigate to the "Column Tools" and choose "Sort Column."
3. Select "Sort by Month Number" to sort the months in
chronological order.

### STEP 2: Top 5 best selling product using stacked bar chart
1. To manipulate the visualization, perform the following steps:
- Drag and drop the "Product" into the Y-axis.
- Place the "Quantity" into the X-axis for appropriate ordering.

### STEP 3: Top 5 cities by sales using map

### STEP 4: Weekly sales distribution by weekday using column chart

### STEP 5: Slicer is used to make this kind of visual
- To create a slicer visualization, drag and drop the "Month Name" field into the slicer option. To display the slicer in a vertical list, access the
slicer settings and choose the option for a vertical column layout.

## Using dax measures

### Use the following DAX code to find the revenue metrics:

- Total profit: Sum up the net profit from all sales transactions.
- Sales quantity: Calculate the total number of units sold.
- Profit margin: Compute the ratio of net profit to total revenue, usually expressed as a percentage.

```dax

REVENUE = SUM OF SALES

```

### Use Card to display the Sales Quantity:

• Select the "Card" visual, then drag and drop the "Quantity Ordered" int the designated field.

• Access the "Format" option for the visual, and adjust the callout value to change the display unit of the quantity ordered as desired.

### Use the following DAX code to find Profit margin:

```dax

PROFIT MARGIN = (( TOTAL SALES -TOTAL COST )/TOTAL SALES)*100;

```

## Snaps of Dashboard


## Conclusion

The **Electromart Sales Data Dashboard** This project demonstrates the ability to extract valuable insights from large sales datasets, enabling data-driven recommendations for optimizing sales strategies and informing business decisions.


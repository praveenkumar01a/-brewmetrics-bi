# DAX Development Notes

## 1. MoM Sales Growth

Copilot suggested using DATEADD to retrieve the previous
month's sales.

I checked the formula and corrected the calculation to use
DIVIDE so that division-by-zero cases are handled safely.

## 2. Running Total Sales

Copilot suggested CALCULATE with FILTER and ALL.

I verified the date context and used Dim_Date[date] to
calculate the cumulative sales correctly.

## 3. Product Rank

Copilot suggested RANKX with ALL(Dim_Product[item]).

I verified that descending order gives the highest-selling
product Rank 1.

## 4. Average Sales per Transaction

Copilot suggested dividing Total Sales by transaction count.

I checked the available columns and used COUNTROWS because
the dataset does not contain an explicit Order ID.
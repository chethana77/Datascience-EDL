
# Coupon Acceptance Analysis - "Coffee House" & "Bar" Focus

## Overview
This project is an exploratory data analysis of a dataset containing information about various coupons offered to passengers and their acceptance rates. The primary focus of this analysis is on the "Coffee House" and "Bar" coupons.

## Dataset
The dataset contains multiple columns with information about the passengers, their preferences, the environment at the time the coupon was offered, and whether they accepted the coupon or not. Key columns include:
- `destination`: The intended destination of the passenger.
- `passanger`: Type of passengers (e.g., Alone, Friend(s)).
- `weather`: Weather conditions.
- `temperature`: Ambient temperature.
- `time`: Time of the day.
- `coupon`: Type of coupon offered (e.g., Restaurant, Coffee House, Bar).
- `gender`, `age`, `maritalStatus`, `income`: Demographic information about the passenger.
- `CoffeeHouse`, `Bar`, `RestaurantLessThan20`, `Restaurant20To50`: Frequency with which the passenger visits these places.
- `Y`: Target variable indicating coupon acceptance (1 for accepted, 0 for not accepted).

## Key Findings

### "Coffee House" Coupon:
1. **Overall Acceptance Rate**: Approximately 49.92%.
2. **By Gender**: Both males and females have similar acceptance rates, with females showing a slight edge.
3. **By Age**: Young adults (26-35 years) have the highest acceptance rate, while seniors have the lowest.
4. **By Marital Status**: Singles have the highest acceptance rate.
5. **By Income**: Individuals with incomes in the "$25,000 - $49,999" range exhibit the highest acceptance rate.
6. **By Coffee House Visit Frequency**: Individuals who visit coffee houses "1~3" times a month or more frequently have higher acceptance rates.

### "Bar" Coupon:
We explored specific groups and their acceptance rates:
1. Drivers who go to bars more than once a month, had passengers that weren't kids, and were not widowed: Approximately 63.92% acceptance rate.
2. Drivers who go to bars more than once a month and are under the age of 30: Approximately 67.24% acceptance rate.

## Recommendations

### For "Coffee House" Coupon:
Promotions targeting the following groups might be more effective:
- Young adults.
- Singles.
- Individuals with moderate to high income.
- Those who visit coffee houses occasionally (1~3 times a month) or frequently.

### For "Bar" Coupon:
Promotions targeting the following groups might yield better acceptance rates:
- Young drivers who frequent bars.
- Drivers who go to bars and don't typically have kids as passengers.

## Files
- `coupons.csv`: The main dataset used for analysis.
- `prompt.ipynb`: Jupyter notebook containing the detailed analysis.

## Tools & Libraries
- Python
- Pandas
- Matplotlib
- Seaborn

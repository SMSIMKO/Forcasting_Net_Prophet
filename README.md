# Forcasting_Net_Prophet
Challenge 11 

---
![11-4-challenge-image](https://github.com/SMSIMKO/Forcasting_Net_Prophet/blob/main/11-challenge-image.png)
---

## I am a growth analyst at MercadoLibre. With over 200 million users, MercadoLibre is the most popular e-commerce site in Latin America. You've been tasked with analyzing the company's financial and user data in clever ways to make the company grow. So, you want to find out if the ability to predict search traffic can translate into the ability to successfully trade the stock.

1. Question: Did the Google search traffic increase during the month that MercadoLibre released its financial results?

Answer: # Yes

The ratio of May 2020 traffic to overall is: Search Trends    1.085536

MercadoLibre May 2020: Search Trends    38181

MercadoLibre Median Monthly Search Trends    35172.5
************************************************************************************************************************************************************************************
2. Question: Does any day-of-week effect that you observe concentrate in just a few hours of that day?

Answer:  Most traffic is conistantly in the last part of the day and in the early mornings for all days of the week 

![Screenshot 2023-09-29 at 6 34 04 PM](https://github.com/SMSIMKO/Forcasting_Net_Prophet/assets/133065537/31d6f8d1-10f2-4f52-9816-24a9200a3ea7)
************************************************************************************************************************************************************************************

3. Question: Does the search traffic tend to increase during the winter holiday period (weeks 40 through 52)?

Answer: # There is an increase in searches during weeks 40-51 but then a steep drop on week 52
![Screenshot 2023-09-29 at 6 43 16 PM](https://github.com/SMSIMKO/Forcasting_Net_Prophet/assets/133065537/2d5b6f96-0a18-4437-864e-671b0418128e)

4. Question: Do both time series indicate a common trend that’s consistent with this narrative?

Answer: There is a common trend showing a drop in closing price and search trends at the same time.
![Screenshot 2023-09-29 at 6 45 21 PM](https://github.com/SMSIMKO/Forcasting_Net_Prophet/assets/133065537/63a53700-dfab-4e92-b45d-cac6cb9de374)

5. Question: Does a predictable relationship exist between the lagged search traffic and the stock volatility or between the lagged search traffic and the stock price returns?

Answer:  negative relationship between the ladded search traffic and the stock volatility. No apparent relationship between the lagged search traffic and stock price returns.
![Screenshot 2023-09-29 at 6 46 51 PM](https://github.com/SMSIMKO/Forcasting_Net_Prophet/assets/133065537/886054a0-d0f6-4d63-83d0-29bd6b84df6c)

6. Question:  How's the near-term forecast for the popularity of MercadoLibre?

Answer:  The near-term forcast is negative.
![Screenshot 2023-09-29 at 6 49 21 PM](https://github.com/SMSIMKO/Forcasting_Net_Prophet/assets/133065537/2d14d21c-7c65-4ed6-b84c-677cd8b689b2)

7. Question: What time of day exhibits the greatest popularity?

Answer: The highest search traffic seems to be at midnight and and starts to decrease onwardly from there.
![Screenshot 2023-09-29 at 6 51 02 PM](https://github.com/SMSIMKO/Forcasting_Net_Prophet/assets/133065537/dbf548e3-d91a-4d05-a3c1-c68f7a21b89c)

8. Question: Which day of week gets the most search traffic?

Answer: Tuesday gets the most search traffic.
![Screenshot 2023-09-29 at 6 52 22 PM](https://github.com/SMSIMKO/Forcasting_Net_Prophet/assets/133065537/8be34fde-ee77-4d90-a488-d918d6d9b01b)

9. Question: What's the lowest point for search traffic in the calendar year?

Answer: Towards the end of October seems to get the least amount of search traffic for the year.
![Screenshot 2023-09-29 at 6 53 07 PM](https://github.com/SMSIMKO/Forcasting_Net_Prophet/assets/133065537/87719eb7-b839-4998-8342-d5e4f2ed2b88)

10. Question: What are the peak revenue days? (Mondays? Fridays? Something else?)

Answer: Wednesdays are the peak revenue days
![Screenshot 2023-09-29 at 6 56 15 PM](https://github.com/SMSIMKO/Forcasting_Net_Prophet/assets/133065537/9563678e-ad8c-438a-8ebc-6fdd91842e7a)

# Based on the forecast information generated above
## Most likely expected total of sales for next quarter will be $969.61.𝐵𝑒𝑠𝑡 𝑐𝑎𝑠𝑒 𝑠𝑐𝑒𝑛𝑒𝑟𝑖𝑜 𝑤𝑖𝑙𝑙 𝑏𝑒 $1051.70 and worst case scenerio will be $888.16
Best Case      1050.964933
Worst Case      887.510690
Most Likely     969.607769
![Screenshot 2023-09-29 at 6 59 23 PM](https://github.com/SMSIMKO/Forcasting_Net_Prophet/assets/133065537/551f0a92-3b19-4883-ad40-c6879100f774)

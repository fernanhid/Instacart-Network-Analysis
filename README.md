# Instacart-Network-Analysis
<br>
<b>Business Problem:</b> <br>
Instacart wants to understand which of products are bought together by their repeat users to more intelligently drive their recommendations and offers.

<b>Approach:</b> <br>
Network analysis was used to understand how each product relates to one another. This allows us to understand which products are most "well connected" and which group types exist. <br>
In this graph each product is a node and every time two products were purchased in an order counts as a weight in the edge.


<b>Data:</b> <br>
https://www.kaggle.com/c/instacart-market-basket-analysis

### Takeaways, Recommendations, Next Steps
--- 

<b>Takeaways</b> <br>
- Instacart repeat users buy mostly produce, with 76% of all orders having produce is them
- Looking at products, Bananas both single or in bag are the most well connected products by the number of degrees. Bananas alone connect with 40% of all other products.
- Looking at products that are bought together by department, produce is most bought with itself and with egg dairy
- 79% of all users bought bananas and they have higher order size (~ 13 products per order) than users that did not buy bananas (~9 products per order)

<b>Recommendations</b> <br>
- For new users, the advantages of buying produce from Instacart can be displayed in ads or in the app as first recommended.
- For current users to stay in the platform, the price sensitivity of produce have to be kept into account. Produce is the reason they stay and buy other products.
- Realize the importance of bananas in the Instacart platform in order to run promotions or keep the price low.

<b>Next Steps</b> <br>
- Get prices for each product in order to see which departments earn more money
- Get more data to compare new customers vs returning customers, most data here was returning customers


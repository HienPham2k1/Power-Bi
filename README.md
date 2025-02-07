# Power-Bi
## Design Thinking
Sittuation: One business want to separate their customer into customer segments and want to find out the way to maintain/develope/retain/attract for each segment.

- Using Design Thinking to make dashboard:
![image](https://github.com/user-attachments/assets/ce6f863e-6e46-4992-9ad3-d7b51ae33cd2)
- Step 1: **Empathize**

Ask yourself what the current business problems are and answer them yourself. Then put yourself in the shoes of the dashboard user, what are their expectations? Use (5W1H):
    				
“Who will see
this Dashboard?” “What problem does this Dashboard solve?” “When and where will stakeholders see this Dashboard?” “Why do stakeholders need this Dashboard?” “How did stakeholders
achieve the goal”
	
If you could only choose one key Stakeholder, who would it be? Use one sentence to describe the problem.

- Step 2: **Define**

Create a Northstar Metric by answering questions like:

  What VALUE you want to measure?

  WHEN the value DELIVERY SUCCESS?

  Northstar Metric Name

  WHY do you choose this metric?
													
- Step 3: **Ideate**																
									
Start with: Starting from NorthStar Metric, brainstorming breakdown content, related content in different perspectives of NorthStar Metric. Start with: In 1 page/1 point of view, there will always be 3 groups of information: Extremely important information, important information and detailed information.																					
For more details, please visit the link below: [Design Thinking](https://view.officeapps.live.com/op/view.aspx?src=https%3A%2F%2Fraw.githubusercontent.com%2FHienPham2k1%2FPower-Bi%2Fmain%2FDesign%2520thinking.xlsx&wdOrigin=BROWSELINK)

- Bước 4: **Prototype and Review**

Build dashboards based on the ideas outlined above. After creating your dashboard, go back through the steps above to check if anything is missing or can be added.

## Dashboard 
- Building database relationships: [Adventure Works](AdventureWorks.pbix)

![image](https://github.com/user-attachments/assets/8b660e36-70fc-4d4f-9c83-7c0fbac2c3e5)

The first report page is about **customer behavior analysis**. With three RFM indexes (Recency, Frequency, Monetary), customers will be classified into 11 customer groups from most potential to least potential.
![lamlai (1)_page-0001](https://github.com/user-attachments/assets/ec5316f7-6278-45cd-9d0e-3753c344f357)

With the second report page, I will analyze the customer overview. The business has the total number of customers, total number of orders and value per order.
![lamlai (1)_page-0002](https://github.com/user-attachments/assets/837e0127-3fbf-44cd-81bc-563c0a15e679)

The last page is Top Customer, on this page I will find the top 5,10,15 customers with the largest order value.
![lamlai (1)_page-0003](https://github.com/user-attachments/assets/659b0acc-9200-45d8-a5ce-e598d1c813cb)

## How to do it
- Build a **Measure** spreadsheet, calculate R,F,M indexes
- Classify customers based on RFM score
- Select important indexes such as: total revenue, total order,..., create charts

## Insight 
Based on the characteristics of customer segments, we can divide the above segments into 4 directions for businesses to choose to follow. 

1. With the customer group that the company aims to maintain, it includes *loyal customers and champions*.							

The common characteristics of this file are that customers buy the product most recently, spend a lot of money, and buy a lot.								

- Inference: customers have recognized the value of the products and become loyal customers of the company.

- Solution to maintain: create levels for customer accounts, for example: membership level, diamond, gold, silver, bronze, etc. For each customer level, there will be different levels of incentives on shipping costs, buying many products will get incentives or buying a product of the company will get another product of the company or other incentives for return.


2.The customer base that the company aims to develop includes *potential loyalist, recent customers, promising*

The common characteristics of this customer group are recent purchases, large or average purchasing power but not often.

- Inference: this is a group of customers who have used the company's products, know about the value of the products, but do not have much need to use the products or are still wondering about using the company's products or those of competitors.
							
- Reasons why customers don't buy regularly: research more deeply about this customer group, about the products they buy from the company, is it because the company's products don't meet consumer needs or the incentives the company gives them are not attractive enough?


3.With the customer base that needs to be retained is *Can't lose them*

The characteristics of this customer group are that they have bought frequently and the purchase value is very large.

- Inference: this is a group of customers who have used the company's products, after a period of time they realized that they no longer met their needs.

- Reasons why customers no longer buy: research more deeply about the products they have bought, are these products the same product, is there any improvement in the product? 								

4. With the customer group that needs to be attracted: *Customer needing attention, at risk*

Characteristics are customers who have not returned for a long time, have purchased goods at an average value.

- Inference: this is a group of customers who have lost interest after using the product.

- Reason: Is there any reason that causes this group of customers to lose interest in the company's products?

| Segment | Characteristics | Recommendation |
| :-: | :-: | :-: |
| Champions | Bought recently, buy often and spend the most! | Reward them. Can be early adopters for new products. Will promote your brand. |
| Loyal | Spend good money with us often. Responsive to promotions. | Upsell higher value products. Ask for reviews. Engage them. |
| Potential Loyalist | Recent customers, but spent a good amount and bought more than once. | Offer membership / loyalty program, recommend other products. |
| New customers | Bought most recently, but not often. | Provide on-boarding support, give them early success, start building relationship. |
| Promising | Recent shoppers, but haven’t spent much. | Create brand awareness, offer free trials |
| Need attention | Above average recency, frequency and monetary values. May not have bought very recently though. | Make limited time offers, Recommend based on past purchases. Reactivate them. |
| About to sleep | Below average recency, frequency and monetary values. Will lose them if not reactivated. | Share valuable resources, recommend popular products / renewals at discount, reconnect with them. |
| At risk | Spent big money and purchased often. But long time ago. Need to bring them back! | Send personalized emails to reconnect, offer renewals, provide helpful resources. |
| Cannot lose them | Made biggest purchases, and often. But haven’t returned for a long time. | Win them back via renewals or newer products, don’t lose them to competition, talk to them. |
| Hibernating customers | Last purchase was long back, low spenders and low number of orders. | Offer other relevant products and special discounts. Recreate brand value. |
| Lost customers | Lowest recency, frequency and monetary scores. | Revive interest with reach out campaign, ignore otherwise. |




  

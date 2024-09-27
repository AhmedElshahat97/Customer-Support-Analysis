
# Customer Support Analysis Dashboard Using Power BI

![Project3 - Customer Support Analysis_page-0001](https://github.com/user-attachments/assets/6ea98dbf-985f-4b15-9962-53c18f29c2c5)
![Project3 - Customer Support Analysis_page-0002](https://github.com/user-attachments/assets/e6e3e9dd-0d73-4916-890d-63ea21e1743a)
![Project3 - Customer Support Analysis_page-0003](https://github.com/user-attachments/assets/2a7c2b7d-868c-44c7-bd36-51d7a5382cd3)
![Project3 - Customer Support Analysis_page-0004](https://github.com/user-attachments/assets/bdd75ef1-8f54-4b40-bb84-273c1a9e50b1)
![Project3 - Customer Support Analysis_page-0005](https://github.com/user-attachments/assets/8988688e-c16b-42f9-b9a3-1afbb55048d7)
![Project3 - Customer Support Analysis_page-0006](https://github.com/user-attachments/assets/eb98edde-e848-4509-abb6-f02d09be24e1)
![Project3 - Customer Support Analysis_page-0007](https://github.com/user-attachments/assets/77fcd3bd-7e18-4558-b62b-5be40e1c6c6e)


## Project Objectives
- Analyze customer support performance over time using key metrics like **Answer Rate**, **SLA** (Service Level Agreement) percentage, **CSAT** (Customer Satisfaction Score), and **First Response Time** (FRT).
- Identify trends, strengths, and areas for improvement in customer support to ensure **better customer satisfaction and operational efficiency**.
- Provide management with actionable insights through interactive reports and visualizations to help make **data-driven decisions**.

## Key Insights and Findings

- **Answer Rate**: The analysis revealed that the customer support team managed to answer 66.2% of all tickets across different regions and channels in 2023, which leaves room for improvement as a significant portion of tickets remained unanswered.

- **SLA** (Service Level Agreement): The percentage of cases answered within the expected timeframe (24 hours) stood at 61.4%. 
This indicates that nearly 40% of the tickets failed to meet the SLA requirement, which could directly affect customer satisfaction.

- **CSAT** (Customer Satisfaction Score): The average satisfaction score was 4.1, which is relatively high. However, it is essential to further investigate specific areas where lower satisfaction ratings were observed, particularly in certain regions or channels.

- **First Response Time** (FRT): The average time to respond to a customer's first inquiry was 35.3 hours, which is higher than desired. Reducing this time could significantly boost customer satisfaction.

- **Survey Response Rate**: The survey response rate was 10.4%, a low engagement rate. This could indicate a need to increase the response rate by optimizing how surveys are sent or incentivizing customers to participate.

## Key Questions Explored
1. What is the current answer rate and SLA compliance across all support channels?
   - The dashboard compared answer rates and SLA compliance across various channels, such as email, Facebook, Instagram, and Twitter, helping to identify where response times were lacking.
2. How does customer satisfaction vary by region and support queue?
   - The analysis explored CSAT scores based on different regions (e.g., DK, ES, MX), identifying key areas where customer satisfaction could be improved.
3. What are the top causes for ticket escalations and delayed responses?
   - By analyzing ticket tags like "payment refund request" or "account cancellation," the project highlighted common causes for escalations and delays, helping support teams prioritize their efforts.

## Challenges and Limitations
1. **Limited Survey Engagement**: The low survey response rate (10.4%) limits the generalizability of the CSAT findings. It would be beneficial to explore alternative methods of gathering customer feedback to ensure more comprehensive insights

2. **Long First Response Time** (FRT): The high FRT (35.3 hours) may not reflect a high-quality customer experience. Efforts to reduce this response time are essential, but data limitations on customer priority levels and ticket complexity may not have fully explained the delays.

3. **Channel-Specific Data Gaps**: The analysis did not capture data from certain emerging channels such as live chat, potentially skewing results toward traditional support methods (email, social media).

## Technical Details
### Data Sources:
* **Tickets Data**: Extracted from multiple customer support channels (Email, Facebook, Instagram, Twitter DM) and categorized by ticket status (answered, snoozed, open).
* **Survey Data**: Used to calculate CSAT and survey response rates.

### Semantic Model:
- **Answer Rate**: Calculated as the percentage of tickets that received responses out of total tickets.
- **SLA** (Service Level Agreement) Percentage: Determined by the number of tickets answered within 24 hours, compared to the total number of tickets.
- **CSAT** (Customer Satisfaction Score): Derived from average customer satisfaction ratings collected through post-interaction surveys.
- **First Response Time** (FRT): Measured in hours, from when the ticket is created until the first response is sent.
- **Survey Response Rate**: The percentage of tickets that received a survey response out of the total tickets.
### Key Measures:
- **Total Tickets**: Count of all incoming tickets for the given period.
- **Answered Tickets**: Tickets that received a response.
- **Answer Rate**: (Answered Tickets / Total Tickets) * 100
- **SLA Compliance**: (SLA Cases / Total Tickets) * 100
- **CSAT Score**: Average of all customer satisfaction ratings (1-5 scale).
- **FRT** (First Response Time): Average hours taken to respond to a ticket.
- **Survey Response Rate**: (Survey Received / Total Tickets) * 100



### Conclusion:

- This project successfully identifies **gaps and opportunities** within the customer support system. It highlights that while the overall customer satisfaction score remains high, critical areas such as SLA adherence, response rates, and first response times require immediate attention. The analysis provides a strong foundation for **improving customer service operations** by leveraging key insights from various support channels and regions.

By making data-driven decisions based on this analysis, the customer support team can significantly **enhance service quality**, **reduce response times**, and **ensure higher levels of customer satisfaction**.

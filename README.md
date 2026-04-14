# BLINKIT PERFORMANCE DASHBOARD-POWERBI

## BUSINESS PROBLEM
Blinkit is one of the largest supermarket chains with a wide variety of products in the Indian market. To assess business performance, customer satisfaction, and inventory management, the company needs to create an interactive dashboard to easily access information, find solutions, and make decisions to address immediate issues.

## DATASET
Description: The blinkit dataset consists of CSV files 
- blinkit_marketing_performance (5400 rows, 11 columns: campaign_id, campaign_name, date, target_audience, channel, impresion, ...)
- blinkit_feedback (5000 rows, 8 columns: feedback_id, order_id, customer_id, rating, feedback_text, feedback_category, ...)
- blinkit_customers (2500 rows, 11 columns: customer_id, customer_name, email, phone, address, area, ...)
- blinkit_orders (5000 rows, 10 columns: order_id, customer_id,	order_date,	promised_delivery_time, ...)
- blinkit_order_items (5000 rows, 4 columns: order_id,	product_id,	quantity, unit_price)
- blinkit_products (268 rows, 10 columns: product_id,	product_name,	category,	brand,	price,	mrp, ...)

Source: https://www.kaggle.com/datasets/yashmotiani/blinkit-marketing-and-customer-powerbi-dashbord

## WHAT I DID

- Developed a comprehensive PowerBI dashboard to visualize and analyze the Blinkit dataset.
- Data was imported, cleaned, and modeled in PowerBI, with DAX measures created for key metrics.
- Visualizations include tables, charts, graphs, and slicers for interactive exploration.
- The dashboard consists of four pages, each focusing on different aspects of the business.

## Page 1: Navigation

<img width="800" height="450" alt="image" src="https://github.com/user-attachments/assets/0445c053-e1ef-4b7b-869c-83282c37c807" />

## Page 2: Marketing Report
<img width="800" height="450" alt="image" src="https://github.com/user-attachments/assets/919cace5-4b45-4733-8dd2-ab37eb9a35e7" />

## Page 3: Customer & Feedback Analytics
<img width="800" height="450" alt="image" src="https://github.com/user-attachments/assets/2a8b6842-0c82-4b01-a784-9de23e8d4b67" />

## Page 4: Operations & Product Dashboard
<img width="800" height="450" alt="image" src="https://github.com/user-attachments/assets/91612eab-2319-4c28-b14a-d78bfaf7c794" />

## INSIGHTS
- Business growth is driven primarily by e-commerce, with new customers generating the highest profits through the flagship referral program that excels in CPA, CTR, and CPM metrics.

- High response rates coupled with average ratings point to the neutral group as the main contributor, while customer concentration in urban areas demands increased efforts for rapid growth, alongside considering regions with stable growth over the past two years for operational expansion.

- Core products in food and pharmaceuticals boast the highest profit margins, with credit cards as the preferred payment method, though delivery times extend during the crucial winter sales season featuring year-end holidays.

# RECOMMENDATION STRATEGIES: 
- Integrate referral program with popular apps like WhatsApp/Facebook for easy sharing; offer double rewards or free shipping vouchers in Nov-Dec to boost pre-peak participation, while partnering with Ecom Express for priority winter slots to cut food & pharma delivery delays.
- Target urban growth in high-density cities (Mumbai, Delhi) ads and food/health influencer tie-ups; pilot provincial expansion in stable areas like Pune, Ahmedabad with localized via-card or UPI promotions.
- Send automated SMS/WhatsApp follow-ups 3-5 days post-delivery with quick 5-star review links and small incentives (e.g ₹50 voucher); reward neutral customers with extra referral points for inviting friends after rating.

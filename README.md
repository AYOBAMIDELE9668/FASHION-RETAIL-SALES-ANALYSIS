# 🛍️ FASHION-RETAIL-SALES-ANALYSIS

## 📘 About the Project

This project revolves around analyzing a dataset that captures sales transactions from a fashion retail business. As the owner of this project, I wanted to dive deep into understanding customer behavior, product popularity, payment preferences, and seasonal trends to help grow the business strategically. The dataset contains **3,400 transactions**, each with details about what customers purchased, how much they spent, their ratings, preferred payment methods, and the date of purchase.

The ultimate goal is to **turn raw data into actionable insights**. By understanding these patterns, we can make smarter decisions about inventory management, marketing campaigns, pricing strategies, and even which products to promote during specific seasons.


## 🧪 How I Analyzed the Project

When I first got my hands on the dataset, I knew it was going to be a journey of discovery. Here’s how I approached the analysis step by step:

### 1️⃣ Understanding the Dataset

Before jumping into fancy charts or statistical models, I started by getting to know the data inside out. I asked myself questions like:

- What columns are available?  
- Are there any missing values?  
- What does each column represent?  

From inspecting the dataset, I noticed that it had six key columns:

- **Customer Reference ID**: Unique identifier for each customer.  
- **Item Purchased**: The name of the item bought (e.g., Handbag, Tunic, Jeans).  
- **Purchase Amount (USD)**: How much the customer spent on the item.  
- **Date Purchase**: When the transaction occurred.  
- **Review Rating**: Customer feedback on the purchase (if provided).  
- **Payment Method**: Whether the customer paid via Cash or Credit Card.  

I also spotted some missing values in two columns:  
- **Purchase Amount (USD)**  
- **Review Rating**  

Handling these gaps was crucial because leaving them as-is could skew the results later.

### 2️⃣ Cleaning the Data

Data cleaning is like tidying up your workspace before starting a big task—it’s tedious but necessary. I addressed the missing values carefully:

- For **Purchase Amount (USD)**, I filled the blanks with the **median value** of the column. This ensures that outliers don’t distort the overall picture.  
- For **Review Rating**, I used the same approach—filling missing ratings with the **median score**.  
- Additionally, I **converted the Date Purchase column into a proper datetime format** so I could perform time-series analysis easily.  

These small tweaks made the dataset ready for deeper exploration.

### 3️⃣ Exploring Sales Trends

Once the data was clean, I began exploring trends. One of the first things I looked at was **monthly sales performance**. I grouped transactions by month and calculated total sales to see if certain months were busier than others. For example:

- Were winter clothes selling more in December?  
- Did summer collections spike in June?  

Plotting this data revealed clear peaks and valleys throughout the year, giving me clues about when to ramp up marketing efforts or stock up on inventory.

### 4️⃣ Identifying Popular Products

As a business owner, knowing which products fly off the shelves is invaluable. To find the most popular items, I **counted how many times each product appeared** in the dataset.

Turns out, items like **Handbags**, **T-Shirts**, and **Jeans** were among the top sellers.

Visualizing this with **bar charts** helped me quickly identify which products resonated with customers and which ones might need rethinking.

### 5️⃣ Payment Preferences

Understanding how customers prefer to pay is critical for optimizing checkout processes. I analyzed the **Payment Method** column and found that both **Cash** and **Credit Card** were widely used, though one method slightly edged out the other.

Visualizing this with **pie charts** gave me a clear breakdown of customer preferences.

This insight could influence decisions like offering **discounts for cash payments** or **partnering with credit card companies for promotions**.

### 6️⃣ Customer Segmentation

To better understand who our customers are, I segmented them based on their **spending habits**. By creating categories like:

- **Low Spenders**  
- **Medium Spenders**  
- **High Spenders**  

I gained insights into different customer groups. For instance:

- High spenders often bought **luxury items** like handbags and boots.  
- Low spenders leaned toward **affordable basics** like socks and scarves.  

This segmentation allows us to tailor marketing strategies specifically for each group, improving engagement and loyalty.

### 7️⃣ Correlation Analysis

I also explored relationships between variables to uncover hidden patterns. For example, I checked whether **higher-priced items received better review ratings**.

Using a **correlation heatmap**, I discovered that while there was a slight positive relationship, it wasn’t strong enough to draw definitive conclusions.

Still, this kind of analysis helps validate assumptions and refine strategies.


### 8️⃣ Exporting Cleaned Data

Finally, after all the analysis, I **exported the cleaned dataset** into a new file. This ensures that anyone else working on the project has access to **accurate, ready-to-use data** without having to repeat the cleaning process.


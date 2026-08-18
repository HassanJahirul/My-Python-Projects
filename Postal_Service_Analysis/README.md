# Delivery Service Analysis
<img width="1774" height="887" alt="Python_Project" src="https://github.com/user-attachments/assets/6e147a44-53c5-43bc-8296-8579f8b4a008" />
In this project, I will try to play the role of an analyst and provide my insights, based on the database of a Delivery Service Company in the USA. [Click here to see the database](Project_Resources/train.csv)
## Tools I used for the project
- Python : It helped me analyse massive amount of data through different functions available. It also provided a number of useful libraries which were used in different areas of this project. Some of the libraries that were used are :
  - Pandas : Provided a number of statistical functions to analyse the database. 
  - Matplotlib : After analysis was done, it helped me graph those findings.
  - Seaborn : It provided more advanced customisation to those graph.
- Jyupter notebook : These notebooks were helpful in testing individual lines of code without running the whole thing repeatedly.
- Visual Studio Code : The code editor used in this project.
- Git/Github : The tool used to keep track of my projects and collaborate with others.
## The Analysis
I divided my analysis into four notebooks each tackling a different question, and provided my insights through the help of graphs and charts.  
Before we approach to the questions, I performed some EDA to have a better grasp of the data, some of the key findings I have listed below. The notebook containing the analysis is [2_EDA](2_EDA.ipynb) 
## EDA
### Q . Which region do most of our products get delivered to ?
Through this analysis I wanted to see whether a particular region has more demand for our services over the others. After performing my analysis I obtained the graph below.  
**Graph :**  
<img width="501" height="411" alt="Graph_1" src="https://github.com/user-attachments/assets/a5650b2b-f56b-41ad-bef6-f1e6c42c46cf" />  
**Insights :**
- There is almost an even split in between the west and the east region with both of them together, forming the major portion of our customers.
- The southern region has a significantly lower portion, to solve this we may need to expand our reach there through region specific ads and campaign.
### Q . What delivery methods do our customers prefer ?  
Inorder to have a better understanding of our customers preferences, I wanted to see what mode of delivery they preferred over the others. I also wanted see how different segments of our customer differed in their opinion. After performing my analysis, I obtained the graph below.  
**Graph :**  
<img width="1570" height="572" alt="Graph_2" src="https://github.com/user-attachments/assets/dc2396d7-aecb-4390-92f4-1d4f8191a23a" />
**Insights :** 
- There is only slight difference in preferences among all the three segments.
- Major portion of our customer base (more than **half**) preferred standard class delivery.
- Less than **10%** preferred same day delivery. We may have to lower the price or provide additional benifits to make it more appealing to our customers.
- These data suggest that irrespective of the  segment, most of our customers are not concerned about how long it takes, for their products to get delivered.
## Main Analysis
As mentioned earlier I divided my analysis into four questions, which I would be giving my insights on. They are :
## 1. How much does each category of product contributes to our total sales ?  
I wanted to know how each category of products performed in terms of sales, so to find this information I decided to plot the total monthly sales of each category over 2017.  
 Inorder to find the code and steps I have taken, please refer this notebook : [3_Sales_Analysis](3_Sales_Analysis.ipynb)  
**Graph :**
<img width="982" height="484" alt="Graph_3" src="https://github.com/user-attachments/assets/2297917b-89a4-4526-9654-8b7077aa2d11" />  
**Insights :**  
- Out of all the categories, tech products shows the most fluctuating monthly sales with a peak sale of **~$31k** at the month of October.
- Both the office supplies and furniture category had consistently low sales towards the first half of the year, but had a significant boost towards Q4 likely due to the  festive season.
- All three categories had a dip in their sales between July and August with their sales being less than **$12k**.

## 2. What products does each customer segment prefer the most ?
Inorder to categories the products based on their demand among each customer segment, I decided to plot the products against the no. of deliveries made and divide it into three different plots for each segment, to compare how each of them differ from one another.  
 Inorder to find the code and steps I have taken, please refer this notebook : [4_Customer_Analysis](4_Customer_Analysis.ipynb)  
**Graph :**  
<img width="684" height="590" alt="Graph_4" src="https://github.com/user-attachments/assets/67cc509a-cda6-4f2d-8076-88de78ac8889" />  


**Insights :**
- Binders and paper are the most selling product for each segment.
- Office supplies is the most popular category of products, making up around **60%** of the total products delivered for consumer segment.  
- Tech products is the least popular category with most of their items making it to the bottom of the list for segment.
## 3. What are the most valuable states to our company ?
I was curious in finding out how each state contributed to our company not only in terms of sales but also the no. of products delivered and whether it holds some connection to the region, to find this I decided to plot the total sales against the total product delivered of each states over 2017 and filter out the top 10 results.  
Inorder to find the code and steps I have taken, please refer this notebook : [5_Most_valuable_states](5_Most_valuable_states.ipynb)  
**Graph :**  
<img width="623" height="464" alt="Graph_5" src="https://github.com/user-attachments/assets/bbc45c40-86f5-46f7-9e61-bb3cadf25f2d" />  
**Insights :**
- California and New York are clearly one of the most valuable states, pulling in the highest total sales and also where majority of our products were delivered. 
- The rest are clustered together at the left hand corner of the graph, this highlights the general trend were low no of deliveries corresponds to lower sales.
- Michigan had generated a relatively higher revenue **~$27k** considering that some of the lowest no of deliveries were made there. 
- States belonging to the southern region maybe considered the least valuable among them because they have the lowest performance compared to the other states, with none of them crossing **$15k** in sales.
## 4. What is our company's Returning Customer Rate (RCR) ?
RCR helps in understanding customer loyalty towards a company. Inorder to find useful information from this I decided to plot the RCR of top 5 states and top 5 products.  
Inorder to find the code and steps I have taken, please refer this notebook : [6_RCR](6_RCR.ipynb)  
**Graph :**  
<img width="905" height="479" alt="Graph_6" src="https://github.com/user-attachments/assets/9f12727d-c548-4f51-9f35-2115911ccc6e" /> 
**Insights :**
- California state has the highest RCR with **~20%** of the customer being a repeat buyer.
- Binders and Paper are the products having the highest RCR with **~15%** suggesting customer satisfaction towards these products
-  The chart also suggest that products belonging to the Office Supplies category makes up most of the top results.
## Things I learned from this project
This project helped me alot in understanding the core concepts of analysis like obtaining data, cleaning and manipulating it, and finally visulaising it through graphs and chart. But the most crucial part of this project has to be providing my insights, I tried my best in providing the most important information while keeping it concise.  
I also learned alot  of new concepts and ideas of python while simultaneously reinforcing my previous knowledge. This project also made me realise how rich python libraries are, and how they can be used to  carry out a wide variety of tasks.
## Conclusion
This project tries to analyse the different aspects of a Delivery Service Company like information about the customer base, performance of different products
based on their sales , etc. to provide actionable insights to the stakeholder and draw attention to areas needing improvements.  
Lastly, I created this project because I wanted to get an understanding of the role an analyst play for a company. I had to scrap alot of ideas and rewrite entire blocks of code, but eventually I was able to create something that I am satisfied with. 









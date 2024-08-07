# Zomato EDA Project<br/>
This project involves exploratory data analysis (EDA) and visualization of Zomato's customer and restaurant data. The objective is to answer several key business questions and provide insights to help drive decision-making.

Table of Contents
Overview<br/>
Objectives<br/>
Dataset<br/>
Analysis and Results<br/>
Restaurant Types<br/>
Votes by Restaurant Type<br/>
Restaurant Ratings<br/>
Couples' Average Spending<br/>
Mode of Orders<br/>
Offline Orders by Restaurant Type<br/>
Installation<br/>
Usage<br/>
Contributing<br/>
License<br/>
Overview
In this project, we perform exploratory data analysis (EDA) on Zomato's dataset to uncover patterns, relationships, and insights that can help improve business decisions. The dataset includes information about customer transactions, restaurant types, votes, ratings, and order modes.<br/>

Objectives
The primary objectives of this analysis are to answer the following questions:<br/>

What type of restaurant do the majority of customers order from?<br/>
How many votes has each type of restaurant received from customers?<br/>
What are the ratings that the majority of restaurants have received?<br/>
What is the average spending on each order by couples who order food online?<br/>
Which mode (online or offline) has received the maximum rating?<br/>
Which type of restaurant received more offline orders, so that Zomato can provide those customers with some good offers?<br/>
Dataset
The dataset used for this project includes the following columns:<br/>

customer_id: Unique identifier for each customer<br/>
restaurant_type: Type of restaurant (e.g., Fast Food, Fine Dining)<br/>
votes: Number of votes received by the restaurant<br/>
rating: Rating of the restaurant<br/>
order_mode: Mode of the order (online or offline)<br/>
order_amount: Amount spent on the order<br/>
is_couple: Indicator if the order was placed by a couple<br/>
Analysis and Results
Restaurant Types
The analysis reveals the types of restaurants that the majority of customers prefer to order from.<br/>

Votes by Restaurant Type
We analyze the number of votes received by each type of restaurant to understand customer preferences and engagement.<br/>

Restaurant Ratings
This section examines the ratings that the majority of restaurants have received, providing insights into overall customer satisfaction.<br/>

Couples' Average Spending
Zomato has observed that most couples order most of their food online. We calculate the average spending on each order by couples.<br/>

Mode of Orders
We determine which mode (online or offline) has received the maximum rating to help Zomato understand customer preferences.<br/>

Offline Orders by Restaurant Type
We identify the types of restaurants that received more offline orders so that Zomato can target these customers with special offers.<br/>

Installation
To run this project, you need to have Python and Jupyter Notebook installed on your system. You can set up the environment by following these steps:<br/>

Clone the repository:<br/>
sh
Copy code
git clone https://github.com/yourusername/zomato-eda-project.git
```<br/>
Navigate to the project directory:<br/>
sh
Copy code
cd zomato-eda-project
```<br/>
Install the required dependencies:<br/>
sh
Copy code
pip install -r requirements.txt
```<br/>
Usage
To perform the analysis and visualize the data:<br/>

Open the Jupyter Notebook:<br/>
sh
Copy code
jupyter notebook Zomato_EDA_Project.ipynb
```<br/>
Run the cells in the notebook to execute the EDA and visualize the results.<br/>


Thank you for using the Zomato EDA Project!<br/>

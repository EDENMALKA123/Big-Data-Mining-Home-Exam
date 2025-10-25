# Big Data Mining and Business Analytics

This project was carried out as part of my **Big Data Mining** course and focuses on extracting business insights from large-scale datasets using data mining, network analysis, and machine learning techniques.  
My main objective was to combine statistical reasoning with business-oriented thinking — understanding how data-driven insights can reveal patterns of customer behavior, market dynamics, and inter-business connections.

---

### Project Overview

The dataset used in this analysis included thousands of businesses, customer reviews, and geolocation data.  
I began by exploring and cleaning the data to ensure consistency across multiple sources, followed by an extensive exploratory analysis that examined the structure of the market and the relationships between key business categories.  
Throughout this process, I aimed to translate technical findings into meaningful insights that could support strategic business decisions.

The project integrates several analytical perspectives:  
a descriptive view of how businesses and users interact,  
a predictive view that examines trends in ratings and engagement,  
and a structural view of how businesses are connected within a wider ecosystem.  
Each part contributes to a comprehensive understanding of the data from both an analytical and managerial standpoint.

---

## Exploratory Analysis

<p align="center">
  <img src="images/Top 30 Business Categories.png" alt="Top 30 Business Categories" width="80%">
</p>

**Figure 1.** *Distribution of the top 30 business categories (with restaurants highlighted).*  
This analysis shows that restaurants, parks, and coffee shops dominate the dataset, indicating that the hospitality and leisure sectors are central to the business ecosystem.  
This distribution helps understand where most customer activity is concentrated.

---

<p align="center">
  <img src="images/User and Business Activity Distributions.png" alt="User and Business Activity Distributions" width="80%">
</p>

**Figure 2.** *Distribution of user and business engagement on a log scale.*  
The left panel presents how many reviews each user provides, while the right panel shows how many unique users interact with each business.  
Both follow a long-tail pattern — a few highly active users and popular businesses generate most of the activity.

---

## Geospatial Analysis

<p align="center">
  <img src="images/Geospatial Map of Ratings.png" alt="Geospatial Map of Ratings" width="85%">
</p>

**Figure 3.** *Geographical distribution of businesses colored by average rating.*  
Using **Folium**, businesses were mapped to visualize regional differences in ratings and density.  
Higher-rated businesses tend to cluster around metropolitan areas, highlighting potential urban advantages in customer satisfaction and visibility.

---

## Network and Community Analysis

<p align="center">
  <img src="images/Louvain Business Network Graph.png" alt="Louvain Business Network Graph" width="70%">
</p>

**Figure 4.** *Visualization of the main connected component of the Business-to-Business (B2B) network using the Louvain algorithm.*  
Each node represents a business, and connections indicate shared customers.  
The color segmentation reveals distinct business communities, helping to identify which types of businesses are interconnected and potentially share customer segments.

---

<p align="center">
  <img src="images/Business Communities Map.png" alt="Business Communities Map" width="85%">
</p>

**Figure 5.** *Spatial distribution of the identified business communities.*  
Each color corresponds to a different community detected in the B2B network.  
By mapping them geographically, we can observe how certain business clusters — such as food-related or hospitality networks — emerge in specific regions.

---

<p align="center">
  <img src="images/Community-by-Category Heatmap.png" alt="Community-by-Category Heatmap" width="85%">
</p>

**Figure 6.** *Heatmap of category fractions by community.*  
This heatmap quantifies how each business category contributes to each detected community.  
It reveals which sectors dominate certain clusters — for instance, gas stations and grocery stores appearing together, suggesting shared behavioral or geographic patterns.

---

## Business Interpretation

Beyond the technical aspects, the project reflects a practical **business analytics approach**.  
The analysis highlights how data can help organizations recognize local demand patterns, evaluate customer satisfaction, and identify clusters of similar businesses that compete or complement one another.  
Understanding these patterns is crucial for strategic planning — from optimizing marketing decisions to selecting business locations or identifying partnership opportunities.  

Ultimately, the project demonstrates how advanced data-mining methods can support informed and measurable business decisions.

---

## Tools and Technologies

All analyses were performed in **Python**, using libraries such as:
Pandas, NumPy, Matplotlib, Seaborn, NetworkX, and Folium.  
Network modeling and community detection were implemented with the Louvain algorithm, while all visual insights were supported by statistical validation and interpretive analysis.

---

## Project Files

- **Big-Data-Mining-Home-Exam.pdf** – Full report including analysis and interpretation  
- **Big-Data-Mining-Home-Exam.html** – Interactive version with all visualizations  

---

## Author

**Eden Malka**  
M.Sc. Student in Statistics & Data Science, Tel Aviv University

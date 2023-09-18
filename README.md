**Problem Statement:**

Based on the data available, we have to make a dashboard which will help us view the bike sales data.

**Data:**

The data contains details of people that ended up buying/not buying a bike. 
  
**Data Preparation and cleaning:**

1. First and foremost, we go through with removing any duplicates.
2. Then we rename some of the entries so they’re more understandable. e.g., in marital status we replace M by “Married” and S with “Single”. 
3. We created a separate column to categorize the age group.
   Here we used formula _IF(M2>45,"Old",IF(M2>=31, "Middle Age", IF(M2<31,"Adolescent","Invalid")))_ to categorize.

**Pivot table:**

We’re going to be looking at the following parameters of people who did/didn’t buy a bike:
1.	Average income of people, break it down by gender
2.	Commuting distance
3.	Age ranges
 
**Dashboard creation:**

1.	Firstly, remove the gridlines
2.	Then make the heading by selecting a few top boxes, then merge and center align them.
3.	Paste the graphs and adjust them in one frame
4.	Insert slicers and connect them to all the reports. 
 

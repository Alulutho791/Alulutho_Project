# Power BI Project

This project gives an overview of how we can use Power BI to visualize data. The data is a Telecommunications data.
We have three tables, namely:
1. Customer Table: Consists of rows such as Phone number(), Customer name and surname, Age and location
2. Price Plan Table: Different price plan names with how many data an voice each price plan offers.
3. Usage Table: How much data and voice customers used for the last 6 months.

See screenshot of the Customer Table below:
![Screenshot 2025-02-11 093023](https://github.com/user-attachments/assets/a69fb442-bf14-4803-a516-3e267ca5b1b7)

See screenshot of the Price Plan table below:
![Screenshot 2025-02-11 125022](https://github.com/user-attachments/assets/6afcd72c-5169-46db-a47e-0656df416591)

See screenshot of the Usage Table below:

![Screenshot 2025-02-11 125150](https://github.com/user-attachments/assets/4d11941b-a988-4372-8df4-40cb65fc86ac)

1. Load data into Power BI
To load the data into Power BI. Open Power BI desktop and Click on "Import data from" and select Excel. Then Click "Transform data".

2. Transform the data
To clean the data, look for any missing values or errors in the data, the column profile is a good indication of how "clean" our data is(the data had no errors nor missing values in this case). Create Measures, here are the list of measures I created for this data:

![Screenshot 2025-02-11 130427](https://github.com/user-attachments/assets/d7c01efb-91df-4c3c-a652-87654cbed3c1)

Here are the formulas use to create the measures:

![Screenshot 2025-02-11 130636](https://github.com/user-attachments/assets/c553d163-0e1a-401b-894d-ce6b32606a73)
![Screenshot 2025-02-11 130707](https://github.com/user-attachments/assets/f162fc31-3f1e-4fa0-8bee-30a4699cd47b)
![Screenshot 2025-02-11 130736](https://github.com/user-attachments/assets/2aab9972-6f57-4249-8a1b-485049babf52)
![Screenshot 2025-02-11 130805](https://github.com/user-attachments/assets/d98961c5-49ef-46d0-af1d-c853d9c7e403)
![Screenshot 2025-02-11 130828](https://github.com/user-attachments/assets/ca0b499e-babc-4c08-be56-e40441c2d13b)

4. Model the data
Ensure correct relationships between the tables. See below:

![Screenshot 2025-02-11 131019](https://github.com/user-attachments/assets/1df040f9-af3e-4b4a-92fb-eef3eef40678)

5. Visualize the data

The following visuals are to show the how many of the customers are using a particular device brand, prefer a certain price plan, are located in a particular province and how many are a certain age.

![Screenshot 2025-02-11 131401](https://github.com/user-attachments/assets/a73f6e49-8e55-401a-a136-f6fdbc034557)

The following visuals depict how much data and voice are offered by each price plan and show the relationship between data offered and data used, and the relationship between voice offered and voice used.

![Screenshot 2025-02-11 131717](https://github.com/user-attachments/assets/a4869bb6-d2d3-46b8-9e87-c6bd0cae2a0f)

The following visuals depict data an voice usage based on device brans, price plan, age and region.

![Screenshot 2025-02-11 132252](https://github.com/user-attachments/assets/3e845279-3166-4aad-893b-2fc02e250c14)

The following visuals depict usage trends over the past 6 months while predicting the next 3 months' usage.

![Screenshot 2025-02-11 132500](https://github.com/user-attachments/assets/05fc0efe-1e8a-4856-a612-847010101d23)
 If we select a particular region, for example Eastern Cape we can get the usage trends based on that region. Same goes for the age slicer.
 
 ![Screenshot 2025-02-11 132605](https://github.com/user-attachments/assets/11ab79e1-2116-4f35-a0ff-1d151f3dab88)

 5. Publish into Power BI Service

By clicking Publish, we publish the data into Power BI Service, where we can pin the reports into a dashboard. This is a view of the Power BI service environment:

![Screenshot 2025-02-11 133201](https://github.com/user-attachments/assets/735044cc-6532-437a-842a-dcb510e1b64c)

This is the final dashboard for our data:

![Screenshot 2025-02-11 133053](https://github.com/user-attachments/assets/5971a7be-b3aa-4b56-b0b6-9c3371d97b1c)

We can zoom in on only the customers between the age of 20 and 30 that are using the "Essential" price plan. Here is an analysis for that.

![Screenshot 2025-02-11 133553](https://github.com/user-attachments/assets/971181a6-80be-44bc-ae70-fe2c102b09bc)

For more, please download the pbix file and test the interactivity of the visuals.

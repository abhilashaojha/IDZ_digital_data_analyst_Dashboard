# <span style="font-family: 'Segoe Print';">**IDZ DIGITAL DATA ANALYST DASHBOARD** </span> <img align="center" width="120" height="75" src="https://user-images.githubusercontent.com/77577111/181069134-614976f4-1503-4b36-91b1-13459d362a8f.png">
 
Hi, I have made this dashboard using `Power BI Desktop`. :nerd_face:

> You can install Power BI Desktop from the Official Microsoft store for free or click the link below:
https://www.microsoft.com/store/productId/9NTXR16HNW1T

##  <span style="font-family: 'Segoe Print';">**Power BI:**


 * Power BI is a cloud-based buisness analytics service for analyzing and visualizing data. 

 * It is a collection of software services, apps, and connectors that work together to turn your unrelated sources of data into **coherent**, **visually immersive** and **interactive insights**.

 * Various data sources are supported by Power BI. Data can be input by reading straight from a database, webpage, or structured files like CSV, XML, and JSON.

 * Power BI provides wide range applications other than just for creating dashboards.
   - ***Power Query:*** Used to search, access, and transform data sources
   - ***Power Pivot:*** Used in data modelling for in-memory analytics
   - ***Power View:*** Analyze, visualize and display data as an interactive data visualization using Power View
   - ***Power Map:*** Brings data to life with interactive geographical visualization
   - ***Power  BI  Service:*** Share  data  views  and  workbooks  which  are  refresh-able  from  on-premises and cloud-based data sources
   - ***Power BI Q&A:*** Ask questions and get immediate answers with natural language query
   - ***Data  Management  Gateway:*** By  using  this  component  you get  periodic  data  refreshers, expose tables and view data feeds.

### <span style="font-family: 'Segoe Print';">Access to the dataset: 
***

**"IDZ Digital data analyst.xls"**
https://github.com/abhilashaojha/IDZ_digital_data_analyst_Dashboard/blob/main/IDZ%20Digital%20data%20analyst.xls

## <span style="font-family: 'Segoe Print';">Description of the dataset:
***

The dataset contains total of 8 columns and 1000 rows.

**Name of Columns:**

* First name
* Last Name
* Gender
* Age
* Occupation
* Salary
* Marital Status
* No. Of Children

### <span style="font-family: 'Segoe Print';"> Cleaning and Preprocessing of the dataset:
***
* Checked for null values.
* Checked for missing values.
* Checked if the data types for each columns were appropriate. As an example, the "No. of Children" had "Number" data type. 
* Checked for any inappropriate values. 

The dataset was quite organised with no missing, null or inappropriate values. 

**Customized Column:**
* A New Column `Name` was added by merging columns `First Name` and `Last Name`. The following DAX Query was used:

```
Name =  [First Name]&" "&[Last Name]
```

Then the columns, `First Name` and `Last Name` were deleted.
* An `Index` column was also added. 
 
 ### <span style="font-family: 'Segoe Print';"> :memo: Insights from the dashboard:
*** 
 https://user-images.githubusercontent.com/77577111/180659383-3f3cf9c1-4a60-45ca-804d-5fbe8cfe9b0f.mp4
 
 <br />
 
1. A female graphic designer by profession, Myra Grant earns the highest pay of $10000. :raising_hand:
2. Male and female average salaries are $5340.86 and $5229.66, respectively. :dollar:
3. The mechanic has the highest average wage, at $7047. :wrench:
4. There are 224 married and 219 single individuals in the sample overall. Among them,
    distribution of number of Children is given below:
 
| Married :couple:| Single :relaxed:|
|:---: |:---: |
|<table> <th>No. of People :walking:</th> <th>No. of Children :baby:</th> <tr>  <td>33</td> <td>5</td> </tr> <tr>  <td>36</td> <td>4</td> </tr> <tr>  <td>39</td> <td>3</td> </tr> <tr>  <td>38</td> <td>2</td> </tr> <tr>  <td>40</td> <td>1</td> </tr> <tr>  <td>38</td> <td>0</td> </tr> <tr> <td> Total: 224 </td> <td></td> </table> | <table> <th>No. of People :walking:</th> <th>No. of Children :baby:</th> <tr> <td>35</td> <td>5</td> </tr>  <tr> <td>37</td> <td>4</td> </tr> <tr> <td>40</td> <td>3</td> </tr> <tr> <td>35</td> <td>2</td> </tr> <tr> <td>36</td> <td>1</td> </tr> <tr> <td>36</td> <td>0</td> </tr> <tr> <td>Total: 219</td> <td></td>  </table> | 

5. A photographer makes the lowest wage of any occupation, at $3581.53. :camera:
6. There are 502 males and 481 females overall in the dataset, respectively. :man: :woman:
7. There are 227 single and 199 married individuals in the 24 to 43 age range. The job with the highest pay in that age range is firefighter, at $8042. :fire_engine:

### <span style="font-family: 'Segoe Print';">References:
*** 

https://docs.microsoft.com/en-us/power-bi/fundamentals/power-bi-overview
https://en.wikipedia.org/wiki/Microsoft_Power_BI



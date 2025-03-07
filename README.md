# INTRODUCTION:
# ATLIQ SALES INSIGHTS 
## Company Background :
**Atliq** is a prominent electronics goods and hardware company specializing in supplying high-quality electrical equipment to clients across India .
With its headquarters located in Delhi, the company operates regional offices strategically positioned throughout the country to ensure seamless 
service delivery and client satisfaction.
## Sales Director: Mr. BHAVIN PATEL :
### Sales Head Introduction and the issues he has been facing:
**Mr. Bhavin Patel**, the Sales Head at Atliq, plays a pivotal role in overseeing and managing the company’s sales operations across India. As the market grows rapidly, Mr. Patel is facing significant challenges in tracking sales insights and performing detailed analysis. 
Despite having regional co-managers at each outpost across the country, the insights he receives are often communicated through verbal mediums. This method of communication occasionally results in information that is sugarcoated or slightly misrepresented, making it difficult to obtain an accurate understanding of the sales performance. 
Although sales have been decreasing, the data provided by the regional managers doesn't give Mr. Patel the complete picture. In an effort to improve visibility, he has asked his managers to provide files and data; however, the sheer volume of data is overwhelming and lacks clear, actionable insights.
To address these challenges, Mr. Patel is seeking a streamlined, understandable, and digestible sales analysis system that can provide him with accurate and meaningful insights to make informed decisions.
### Aims Grid:
## Sales Insight Aims Grid
This **Sales Insight Aims Grid** provides an overview of our key objectives for improving sales tracking and gaining insights into the sales process. It includes our planned goals, timelines, and the status of various initiatives across our sales teams.
You can download the full **Sales Insight Aims Grid** in PowerPoint format from the link below:
- go to the file **[SALES_INSIGHT AIMS_GRID]**
Feel free to explore the presentation to understand the detailed goals and actions planned for enhancing sales tracking and insights.
### Data exportation :
## Database Information
The file [`db_dump_version_2.sql`](./db_dump_version_2.sql) contains all the data used throughout this project.
### Steps to Activate the Database:
1. Open **MySQL Workbench** or your preferred MySQL client.
2. Establish a connection to the database where you want to load the data.
   - Open MySQL Workbench.
   - Click on the connection you wish to use.
3. Once connected, follow these steps:
   - Go to the **Server** menu.
   - Click on **Data Import** or **Import Data**.
4. Locate the file `db_dump_version_2.sql`:
   - Browse to the directory where the file is stored.
   - Select `db_dump_version_2.sql` and confirm.
5. Follow the prompts to complete the data import process.
Once completed, the database will be populated with all the required data for this project.
### Data Transformation :
## Database Information 
#### phase 1:Basic Information
For data transformation, I have utilized **Power BI** to perform Power Query transformations and data modeling. Power BI provides an intuitive platform for transforming raw data into insightful visualizations, and I have leveraged this for the sales insights analysis.
To view the transformations and the data model I have created in Power BI, you can directly visit my Power BI file, which is available on GitHub at the following link:  
[Sales Insights Power BI File](https://github.com/Aniru1105/MY_-projects/blob/PROJECT-1/Sales_Insights.pbix)
This Power BI file includes all the queries, transformations, and models that were used to extract meaningful insights from the data.
Feel free to explore the file for a more detailed understanding of the data modeling and analysis process.
#### phase 2 : Short summary of transformation
### Data Transformation and Dashboard Creation  
#### Data Transformation Process  
1. **Loading Data**:  
   I started by loading the MySQL file into Power BI. For the ETL (Extract, Transform, Load) process, I utilized a combination of MySQL, Power Query (built into Power BI), and DAX (Data Analysis Expressions) programming language.  
2. **ETL Steps**:  
   - **Fetching the Data**: Imported the raw data into Power BI from the MySQL server.  
   - **Data Modeling**: Performed data modeling directly within Power BI.  
   - **Pipeline Creation**: Used Power BI's built-in pipeline creation features to streamline the transformation process.  
   - **Data Cleaning**: Removed null values and noisy data to ensure data integrity.  
   - **Currency Conversion**: Standardized all currencies into a single format for consistency.  
   - **Data Evaluation and Transformation**: Conducted evaluations and applied necessary transformations for accurate analysis.  

#### Dashboard Creation  
After completing the transformation, I created a dashboard to present the insights visually. The dashboard was saved in multiple formats and uploaded to my GitHub repository:  
1. **Dashboard in PowerPoint Format**:  
   - [Sales Insights Dashboard - PPT](https://github.com/Aniru1105/MY_-projects/blob/PROJECT-1/Sales_Insight_ppt.pptx)  
2. **Dashboard in PDF/Word Format**:  
   - [Sales Insights Dashboard - PDF/Word](https://github.com/Aniru1105/MY_-projects/blob/PROJECT-1/Sales_Insights.pdf)  
3. **Dashboard in Excel Format**:  
   - [Sales Insights Dashboard - Excel](https://github.com/Aniru1105/MY_-projects/blob/PROJECT-1/Sales_Insights.xlsx)
#### Data Transformation Gallery :
   here you can see pictures and snippets of dashboards .[Dashboard Snippet](https://github.com/Aniru1105/Sales_Insights/blob/main/Screenshot%202025-03-05%20235411.png).
-- -
Thank you for exploring the **Atliq Sales Insights** project! Please reach out if you have any questions or suggestions.




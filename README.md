# 🏨 Hotel Booking Analysis | Google Sheets & Power BI

## 📌 Project Overview

The **Hotel Booking Analysis** project focuses on analyzing hotel booking data to understand booking performance, cancellations, revenue trends, and guest distribution.

In this project, I used **Google Sheets to clean and prepare the data and calculate revenue-related metrics**. After completing the data preparation process, I exported six separate hotel datasets into CSV files and imported them into Microsoft Power BI.

Using Power BI, I created **six individual dashboards, one for each hotel**, to visualize key performance indicators (KPIs) and analyze hotel booking performance.

This project demonstrates an end-to-end data analytics workflow, from data cleaning and preparation to interactive dashboard development and business reporting.

## 🎯 Project Objectives

- Clean and prepare hotel booking datasets using Google Sheets.
- Calculate revenue-related values.
- Analyze total bookings and booking status.
- Identify confirmed and cancelled bookings.
- Calculate booking cancellation rates.
- Analyze guest distribution and total nights.
- Visualize revenue trends across years.
- Develop six individual Power BI dashboards.
- Present booking information through interactive visualizations.
- Demonstrate practical data analytics and business intelligence skills.

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Google Sheets | Data cleaning, preparation, and revenue calculations |
| CSV | Storing and transferring cleaned datasets |
| Microsoft Power BI | Data visualization and dashboard development |
| Power Query | Importing and preparing datasets |
| DAX | Creating measures and calculating KPIs |
| GitHub | Project documentation and portfolio presentation |

---

## 🏨 Hotels Analyzed

The project includes six hotels, each with its own cleaned CSV dataset and individual Power BI dashboard.

| No. | Hotel Name | Dataset |
|---:|---|---|
| 1 | Adani Hotel | `Adani_Hotel.csv` |
| 2 | Airport Hotel | `Airport_Hotel.csv` |
| 3 | CityLine Hotel | `CityLine_Hotel.csv` |
| 4 | India International Hotel | `India_International_Hotel.csv` |
| 5 | Heaven Hotel | `Heaven_Hotel.csv` |
| 6 | Sunshine Hotel | `Sunshine_Hotel.csv` |

**Total Hotels:** 6  
**Total CSV Datasets:** 6  
**Total Power BI Dashboards:** 6

---

## 🔄 Project Workflow

### Step 1: Data Cleaning Using Google Sheets

Google Sheets was used to clean, organize, and prepare the hotel booking datasets for analysis.

Activities included:

- Reviewing the available booking data.
- Cleaning and organizing the datasets.
- Checking the consistency of booking-related information.
- Preparing columns for analysis.
- Calculating revenue-related values.
- Organizing the data into separate hotel datasets.

**Outcome:** Six cleaned hotel datasets ready for analysis.

### Step 2: Revenue Calculation

I used Google Sheets to calculate revenue-related values based on the available booking information.

The calculated values were prepared for further analysis in Power BI.

Revenue analysis helps evaluate hotel performance and investigate financial trends.

**Note:** Revenue calculations should follow the project's business rules, including how cancelled bookings are treated.

### Step 3: Exporting Data to CSV

After cleaning and preparing the data, I exported the datasets from Google Sheets into six separate CSV files.

The files are:

- `Adani_Hotel.csv`
- `Airport_Hotel.csv`
- `CityLine_Hotel.csv`
- `India_International_Hotel.csv`
- `Heaven_Hotel.csv`
- `Sunshine_Hotel.csv`

CSV files were used to transfer the cleaned data into Power BI.

### Step 4: Importing Data into Power BI

I imported the six CSV datasets into Microsoft Power BI.

Activities included:

- Importing the CSV files.
- Reviewing the imported columns and data types.
- Preparing the datasets for reporting.
- Creating DAX measures for relevant KPIs.
- Developing charts and visualizations.
- Organizing the report pages.

### Step 5: Dashboard Development

I created six individual Power BI dashboards, with one dashboard dedicated to each hotel.

Each dashboard presents relevant booking metrics and visualizations to help analyze the performance of that hotel.

---

## 📊 Key Performance Indicators (KPIs)

The following KPI values are taken from the Power BI dashboard screenshot provided for this project.

| KPI | Value | Description |
|---|---:|---|
| Total Bookings | 30,000 | Total booking records in the displayed dataset |
| Total Confirmed Bookings | 19,514 | Bookings classified as confirmed |
| Total Cancelled Bookings | 10,486 | Bookings classified as cancelled |
| Cancellation Rate | 34.95% | Percentage of bookings cancelled |
| Total Guests | 63,540 | Total guests recorded in the dataset |
| Total Nights | 180,010 | Total nights associated with bookings |

**Note:** These values represent the dashboard shown in the screenshot and may change depending on the selected hotel, dataset, and report filters.

### KPI Calculation Logic

**1. Total Bookings**

The total number of booking records included in the current analysis.

**2. Total Confirmed Bookings**

The number of bookings classified as confirmed according to the booking-status logic used in the report.

**3. Total Cancelled Bookings**

The number of bookings classified as cancelled.

**4. Cancellation Rate**

The percentage of total bookings that were cancelled.

Formula:

`Cancellation Rate = (Cancelled Bookings / Total Bookings) × 100`

Calculation using the displayed figures:

`(10,486 / 30,000) × 100 = 34.95% approximately`

**5. Total Guests**

The total number of guests calculated from the available guest-related data.

**6. Total Nights**

The total number of nights associated with bookings.

---

## 📈 Dashboard Visualizations

The dashboard includes the following KPI cards and visualizations.

### 1. KPI Cards

The KPI cards summarize:

- Total Bookings
- Total Confirmed Bookings
- Total Cancelled Bookings
- Cancellation Rate
- Total Guests
- Total Nights

### 2. Booking Revenue by Year

Displays revenue trends across different years.

**Purpose:**
- Understand revenue changes over time.
- Compare revenue across available years.
- Examine hotel revenue performance.

### 3. Booking Status

Displays the distribution of bookings by status.

**Purpose:**
- Compare confirmed and cancelled bookings.
- Understand booking outcomes.
- Examine cancellation patterns.

### 4. Guest Type Distribution

Shows the distribution of bookings or guests across the guest categories defined in the dataset.

**Purpose:**
- Understand guest distribution.
- Examine customer and guest patterns.
- Identify the categories contributing to booking activity.

---

## 🏨 Individual Hotel Dashboards

### 1. Adani Hotel

Analyzes booking performance and related business metrics for Adani Hotel.

**Focus Areas:**
- Total bookings.
- Confirmed and cancelled bookings.
- Cancellation rate.
- Revenue trends.
- Guest type distribution.
- Total guests and nights.

### 2. Airport Hotel

Analyzes booking activity and performance indicators for Airport Hotel.

**Focus Areas:**
- Booking volume.
- Booking status.
- Cancellation performance.
- Revenue trends.
- Guest distribution.
- Total guests and nights.

### 3. CityLine Hotel

Examines booking trends and performance metrics for CityLine Hotel.

**Focus Areas:**
- Total bookings.
- Confirmed and cancelled bookings.
- Cancellation rate.
- Revenue by year.
- Guest type distribution.
- Total guests and nights.

### 4. India International Hotel

Evaluates booking and revenue-related performance for India International Hotel.

**Focus Areas:**
- Booking volume.
- Booking status.
- Cancellation rate.
- Revenue trends.
- Guest distribution.
- Total guests and nights.

### 5. Heaven Hotel

Analyzes the booking performance of Heaven Hotel.

**Focus Areas:**
- Total bookings.
- Booking status distribution.
- Cancellation rate.
- Revenue trends.
- Guest type distribution.
- Total guests and nights.

### 6. Sunshine Hotel

Examines booking and revenue-related performance for Sunshine Hotel.

**Focus Areas:**
- Total bookings.
- Confirmed and cancelled bookings.
- Cancellation rate.
- Revenue by year.
- Guest distribution.
- Total guests and nights.

*The actual KPI values may differ between individual hotel dashboards.*

---

## 🖼️ Power BI Dashboard Screenshots

The following section displays the six hotel dashboards directly in the GitHub README.

Upload the corresponding PNG screenshots into your repository's `screenshots` folder using the filenames shown below.

### 1. Adani Hotel Dashboard

![alt text](<Adani Hotel.png>)

### 2. Airport Hotel Dashboard

![alt text](<Airport Hotel.png>)

### 3. CityLine Hotel Dashboard

![alt text](<CityLine Hotel.png>)

### 4. India International Hotel Dashboard

![alt text](<Heaven Hotel.png>)

### 5. Heaven Hotel Dashboard

![alt text](<India International Hotel.png>)

### 6. Sunshine Hotel Dashboard

![alt text](<Sunshine Hotel.png>)

---

## 📄 Full Dashboard Report

A PDF version of the dashboard screenshots can also be provided for convenient viewing at higher resolution.

[Dashboard PDF](c:/Users/chatt/Downloads/Hotel_Booking_Analysis.pdf)



---

## 💡 Business Questions Addressed

This project helps investigate the following questions:

1. How many bookings are recorded for each hotel?
2. How many bookings are confirmed?
3. How many bookings are cancelled?
4. What is the booking cancellation rate?
5. How does revenue change across years?
6. How are bookings distributed by status?
7. How are guests distributed across guest categories?
8. How many guests are recorded in the dataset?
9. How many nights are associated with bookings?
10. How can hotel booking information be presented through interactive dashboards?

---

## 📌 Project Benefits

### Improved Data Quality

Cleaning and preparing datasets in Google Sheets helps organize the information for analysis.

### Revenue Analysis

Revenue-related calculations provide a basis for examining hotel financial performance.

### Booking Performance Monitoring

KPI cards summarize booking volume, booking status, and cancellation rates.

### Guest Analysis

Guest-related metrics help examine guest distribution and total nights.

### Individual Hotel Analysis

Six separate dashboards allow each hotel's performance to be examined independently.

### Interactive Data Visualization

Power BI transforms tabular data into visual reports that make patterns and trends easier to understand.

### Data-Driven Decision Support

The dashboards provide a structured way to examine booking performance and identify areas for further investigation.

---

## 🧠 Skills Demonstrated

### Google Sheets
- Data cleaning.
- Data preparation.
- Spreadsheet formulas.
- Revenue calculations.
- CSV export.

### Microsoft Power BI
- CSV data import.
- Power Query data preparation.
- Data modeling.
- DAX measures.
- KPI development.
- Data visualization.
- Dashboard design.
- Hotel-level reporting.

### Data Analytics
- Booking performance analysis.
- Cancellation analysis.
- Revenue analysis.
- Guest distribution analysis.
- Trend analysis.
- Business KPI reporting.

### GitHub
- Repository organization.
- Project documentation.
- Version control.
- Portfolio presentation.

---

## 📁 Project Structure

The following is the recommended structure for organizing the project repository.

```text
Hotel-Booking-Analysis/
│
├── README.md
│
├── data/
│   ├── Adani_Hotel.csv
│   ├── Airport_Hotel.csv
│   ├── CityLine_Hotel.csv
│   ├── India_International_Hotel.csv
│   ├── Heaven_Hotel.csv
│   └── Sunshine_Hotel.csv
│
├── powerbi/
│   ├── Hotel_Booking_Analysis.pbix
│   └── Hotel_Dashboard_Screenshots.pdf
│
└── screenshots/
    ├── Adani_Hotel_Dashboard.png
    ├── Airport_Hotel_Dashboard.png
    ├── CityLine_Hotel_Dashboard.png
    ├── India_International_Hotel_Dashboard.png
    ├── Heaven_Hotel_Dashboard.png
    └── Sunshine_Hotel_Dashboard.png
```

*This is a suggested structure. Adjust the filenames and folders to match the actual files uploaded to GitHub.*

---

## 🚀 How to Explore the Project

1. Clone or download the GitHub repository.
2. Open the `data` folder to review the cleaned CSV datasets.
3. Open the Power BI report using Microsoft Power BI Desktop.
4. If necessary, update the CSV source paths in Power BI.
5. Refresh the datasets.
6. Navigate through the six dashboard pages.
7. Review the KPI cards and visualizations.
8. Open the PDF report to view the dashboard screenshots.

### Requirements

- Google Sheets or a compatible spreadsheet application for reviewing the data.
- Microsoft Power BI Desktop for opening and exploring the `.pbix` report.

---

## 🔮 Future Improvements

Potential improvements include:

- Developing a consolidated dashboard comparing all six hotels.
- Adding detailed monthly and yearly booking analysis.
- Expanding customer segmentation analysis.
- Improving revenue and cancellation analysis.
- Adding interactive filters and drill-through functionality.
- Automating data refresh when source datasets are updated.
- Publishing the report through Power BI Service, where appropriate.

---

## 📝 Conclusion

The Hotel Booking Analysis project demonstrates how Google Sheets and Microsoft Power BI can be combined to transform hotel booking data into meaningful business reports.

I used Google Sheets to clean and prepare the data, calculate revenue-related values, and export six separate hotel datasets into CSV files. I then imported the datasets into Power BI and created six individual dashboards, one for each hotel.

The dashboards focus on booking volume, confirmed and cancelled bookings, cancellation rates, revenue trends, guest distribution, and total nights.

This project demonstrates practical skills in data cleaning, spreadsheet calculations, CSV integration, Power Query, DAX, KPI development, and interactive dashboard design.

It also highlights the importance of transforming raw data into organized visual information that can support business analysis and data-driven decision-making.

---

## 👨‍💻 Author

**Subhajit Chatterjee**  
**Data Analyst** at Farmershop Tech India Pvt. Ltd.

- **Role:** Data Analyst
- **Company:** Farmershop Tech India Pvt. Ltd.
- **Skills:** Google Sheets, SQL, Power BI, Data Cleaning, Data Visualization, and Business Intelligence

This project demonstrates my ability to clean and analyze hotel booking data, develop meaningful KPIs, and build interactive Power BI dashboards to support data-driven business decisions.

---

⭐ If you find this project useful, feel free to explore the repository and share your feedback.
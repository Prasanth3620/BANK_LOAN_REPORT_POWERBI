# Loan Analytics Dashboard - Power BI

This project provides an interactive Power BI dashboard analyzing loan data from a bank. It helps uncover trends, evaluate borrower profiles, and monitor repayment behaviors across various dimensions. The dashboard is divided into three interlinked sections:

- **Dashboard 1: Summary**
- **Dashboard 2: Overview**
- **Dashboard 3: Details**

Each section is interactive and dynamically filters based on user selections (e.g., selecting a state, term, or loan status).

---

## Dataset Overview

The dataset includes information such as:

- `Loan ID`, `Loan Status`, `Term`
- `Address State`, `Employment Length`, `Home Ownership`
- `Purpose`, `Grade`, `Sub-grade`
- `Annual Income`, `Debt-to-Income (DTI) Ratio`
- `Issue Date`, `Payment Dates`, `Funded Amount`, `Total Payment`

---

## Dashboard 1: Summary

###  Key Performance Indicators (KPIs)

- **Total Loan Applications**
  - Includes total, Month-to-Date (MTD), and Month-over-Month (MoM) changes
- **Total Funded Amount**
  - Disbursed loan total (with MTD and MoM tracking)
- **Total Amount Received**
  - Received payments (MTD and MoM insights)
- **Average Interest Rate**
  - Portfolio-level average and trends over months
- **Average DTI Ratio**
  - Borrower financial health metric with MoM variations

### Good Loan vs Bad Loan Metrics

#### Good Loans (e.g., Fully Paid):
- Good Loan Application Percentage
- Good Loan Applications
- Good Loan Funded Amount
- Good Loan Total Received Amount

#### Bad Loans (e.g., Charged Off):
- Bad Loan Application Percentage
- Bad Loan Applications
- Bad Loan Funded Amount
- Bad Loan Total Received Amount

### Loan Status Grid View

Breakdown by `Loan Status` with:
- Total Applications
- Total Funded Amount
- Total Amount Received
- MTD Funded Amount
- MTD Amount Received
- Average Interest Rate
- Average DTI Ratio

---

## Dashboard 2: Overview

### Monthly Trends (Line Chart)
Shows loan issuance volume over time to identify seasonality and trends.

### Regional Analysis (Filled Map)
Displays lending activity across U.S. states, revealing geographical disparities.

### Loan Term Analysis (Donut Chart)
Visualizes the distribution of loan terms (e.g., 36 vs 60 months).

### Employment Length (Bar Chart)
Evaluates how employment duration influences loan metrics.

### Loan Purpose Breakdown (Bar Chart)
Provides a breakdown of loans by their intended purpose.

### Home Ownership Analysis (Tree Map)
Hierarchical view of loan applications by home ownership status.

**Metrics in All Visuals:**
- Total Loan Applications
- Total Funded Amount
- Total Amount Received

---

##  Dashboard 3: Details

### Grid View

A detailed table offering a snapshot of each loan, including:
- Borrower profile
- Loan terms and grade
- Financial metrics like DTI, interest, funded and received amounts
- Payment and issue timelines

##  Objective

To enable users to:
- Explore loan performance
- Understand borrower risk profiles
- Dive into granular, actionable insights

---

##  Interactivity

All three dashboards are fully interactive:
- Selecting a **state**, **loan status**, **term**, or **purpose** filters the data across all views in real-time.

---

##  Tools Used

- **Power BI Desktop**
- **DAX & Power Query**
- **Custom Visualizations and Filters**



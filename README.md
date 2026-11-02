# CarePoint Hospital Analytics

## Project Overview
The dashboard brings appointment activity, service delivery and payment performance into four views: appointment performance, booking analysis, payment methods and key insights. Financial values are shown in the dashboard screenshots.

## Business Problem
The dashboard supports operational monitoring of booking demand, appointment completion, patient flow and payment performance at CarePoint Hospital.

## Objectives
- Track booking and appointment volumes over time and identify peak days.
- Understand how far in advance appointments are booked, including same-day demand.
- Compare appointment demand, completion and waiting times across departments and outcomes.
- Review service value, average service cost and payment-method contribution.
- Surface operational opportunities to reduce missed appointments and improve service delivery.

## Dataset
  Approximately 50,000 booking and appointment records, as summarized in the dashboard. Visible analysis dimensions include booking/appointment dates, department, day of week, gender, appointment outcome, waiting and consultation times, payment method, recorded service value and service cost. The monthly trend view displays 2024–2025 activity.

## Data Preparation
Appointment and booking data were cleaned and validated in SQL before the clean file was imported into Power BI. Checks covered duplicate records and appointment grain; missing or unknown critical fields; booking and appointment date validity and chronology; lead-time calculations; consistent department, status and payment labels; invalid waiting-time, consultation-time and service-value/cost entries; and reconciliation of totals and key rates against the source records.
In Power BI, booking lead time was grouped into same day, 1–7 days, 8–14 days, 15–30 days, over 30 days, invalid dates and unknown. The report summarizes completion and same-day booking rates, waiting and consultation times, service value, average service cost and payment contribution.

## Business Question
- How do booking and appointment volumes vary by month and day of the week?
- How far ahead are appointments booked, and what share are booked on the same day?
- Which departments have the most appointments, and where do completion rates or waiting times differ?
- How are appointments distributed across completed, pending, cancelled and other outcomes?
- How do recorded service value, average service cost and payment-method contributions compare?

## Tools Used
- **PostgreSQL:** Data cleaning, transformation, and exploratory data analysis.
- **Power BI:** Data modelling, DAX calculations, and dashboard development.

## Key Findings
- The dashboard reports approximately 50,000 appointments and a 67% completion rate.
- Booking demand is relatively balanced across departments and days of the week, while completion rates and waiting times vary by department and appointment outcome.
- Advance scheduling is common: about 33,000 bookings were made at least seven days ahead, while same-day bookings were 0.91%.
- Recorded service value was about 920M and increased 1.8% month over month. Payment contributions were close to evenly distributed; Mobile Money had the largest share at 20.31%.

## Dashboard Previews

### 1. Hospital Appointment Analysis
![Hospital Appointment Dashboard](<Hospital Appointment.jpg>)

### 2. Booking Analysis
![Booking Analysis Dashboard](<Booking Analysis.jpg>)

### 3. Payment Method Analysis
![Payment Method Dashboard](<Payment Method.jpg>)

### 4. Hospital Insights and Recommendations
![Hospital Insights Dashboard](<Hospital Insight.jpg>)

## Recommendations
- Strengthen reminders, confirmations and follow-up to reduce cancellations and missed appointments.
- Align staffing, consultation capacity and administrative support with departmental workloads and booking patterns.
- Monitor completion rates and waiting times by department and outcome to identify service-delivery gaps.
- Preserve effective advance-scheduling practices while accommodating urgent and same-day needs.
- Improve appointment and payment record completeness to support reliable reporting and operational decisions.

## Project File
[Download the Power BI Dashboard](CarePoint_Hospital_Analysis.pbix)


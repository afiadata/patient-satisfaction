# This Project focuses on Analysis on Patient Satisfaction

**Data Source: kaggle**
*kagglehub.dataset_download("gabrielsantello/patient-satisfaction-health-system-dataset")*

A regional endocrinology specialty office is experiencing a decrease in the number of patients seen on a weekly basis. The office consists of four doctors, a nurse practitioner, two registered nurses (RNs), four licensed practical nurses (LPNs), and five administrative staff members. Among the clinic staff, there is some concern that this decrease in volume is due to patient dissatisfaction.

The dataset contains two files with information on 13 weeks of patient complaints.

ComplaintData contains information on 262 customer complaints received over a three-month period. Complaint data is captured through the specialty office website.

- Date - Date complaint filed
- Complaint - Type Reason for complaint

PatientFeedback contains summary information from patient surveys administered over a three-month period.

- Week # - Week 1, 2, …
- Percent Recommend - Percentage of responders who would recommend this office
- Wait - Percent indicating wait time was acceptable
- Respect - Percent indicating they were treated with respect
- Enough Information - Percent indicating they received enough information from provider


## Steps

1. Create virtual environment
- python -m venv venv  
- source venv/bin/activate  # On Windows: venv\Scripts\activate

2. Install from requirements.txt
- pip install -r requirements.txt

3. Run data_analysis.ipynb


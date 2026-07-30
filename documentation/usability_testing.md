 Usability Testing & Iterative Design Report

Project: Hostel Booking System (HCI Project)  
Version Tested: V1 Initial Prototype (`v1_initial_balsamiq.bmpr`)  
Iterated Version: V2 Final Prototype (`v2_final_balsamiq.bmpr`)  
Methodology: Moderated Usability Testing (5 Participants)



 1. Testing Setup & Tasks
Participants completed three core tasks on the interactive prototype using the Think-Aloud Protocol:

Task 1 (Search & Compare):** "Find a room under $500/month and compare it side-by-side with another hostel."
Task 2 (Application & Verification):** "Select a room in Oak Hall, complete the application form, and upload your student ID."
Task 3 (Dashboard & Deposit Payment):** "Locate your pending application status on the dashboard and pay the required deposit."



 2. Participant Session Summaries

| Participant | Role | Task Completion | Key Feedback / Observations |
| :--- | :--- | :---: | :--- |
| Isaac Okoth | Undergraduate (Age 20) | 3/3 | Took 90+ seconds to find the comparison checkbox on Screen 2. Confused by post-payment redirect. |
| Collins Kibet |Undergraduate  (Age 24) | 2/3 | Got overwhelmed by Screen 6 (single long application form). Small back button made navigation hard. |
| Agnes Wanjiru |Undergraduate (Age 18) | 3/3 | Tried to swipe compare cards. Paid deposit easily but looked around for a printable receipt. |
| Eugene Otieno | Undergraduate (Age 22) | 3/3 | Mentioned privacy concerns on document upload fields. Confirmed needing an explicit payment popup. |
| Leah Gachanja | Undergraduate (Age 21) | 2/3 | Missed the comparison feature. Primary submit button on Screen 6 was hidden below the screen fold. |


 3. Identified Usability Roadblocks & V2 Solutions

 Problem 1: Form Overload on Application Page (Screen 6)
V1 Observation: 14 input fields were stacked on a single screen. Users felt overwhelmed and missed the submit button.
V2 Iteration: Re-designed Screen 6 into a 2-Step Progressive Wizard (Step 1: Personal Details, Step 2: Document Upload & Review) with a sticky navigation bar.

 Problem 2: Missing Payment Success State (Screen 9)
V1 Observation:** Submitting a deposit redirected silently to the dashboard, leaving users unsure if payment succeeded.
V2 Iteration:** Added a prominent **Payment Success Modal** with a green confirmation badge, transaction reference ID, and "Download Receipt" option.

 Problem 3: Unclear Comparison & Navigation Controls (Screens 2 & 3)
V1 Observation: Small top-right back buttons and ambiguous checkboxes led to misclicks.
V2 Iteration: Standardized top-left persistent back arrows across all 12 screens and added a floating "Compare Selected" (2) action bar.
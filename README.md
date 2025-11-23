# Analysis-in-Software-Development

| Section                            | Suggested File Name              | Example Markdown Content                                                                                                                                                                                                                                                                 |            |              |                     |                     |      |              |                     |                |                     |                                                                              |                                              |                                                                                  |      |                                    |    |      |                                                                 |        |                               |       |      |                                                          |   |                                       |                                                             |
| ---------------------------------- | -------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | ------------ | ------------------- | ------------------- | ---- | ------------ | ------------------- | -------------- | ------------------- | ---------------------------------------------------------------------------- | -------------------------------------------- | -------------------------------------------------------------------------------- | ---- | ---------------------------------- | -- | ---- | --------------------------------------------------------------- | ------ | ----------------------------- | ----- | ---- | -------------------------------------------------------- | - | ------------------------------------- | ----------------------------------------------------------- |
| 1. Analysis Phase                  | `Analysis-Phase.md`              | `markdown\n## Analysis Phase\n\n- Definition of Analysis Phase\n- Sub-steps: Requirements Gathering, Feasibility Study, System Analysis\n- Deliverables: SRS Document, Data Flow Diagrams\n- Best Practices and Common Challenges\n\n![Analysis Diagram](images/analysis-diagram.png)\n` |            |              |                     |                     |      |              |                     |                |                     |                                                                              |                                              |                                                                                  |      |                                    |    |      |                                                                 |        |                               |       |      |                                                          |   |                                       |                                                             |
| 2. Product Backlog Development     | `Product-Backlog-Development.md` | ```markdown\n## Product Backlog Development\n\n- Definition: List of features/user stories\n- How to create & structure backlog\n- Prioritization techniques: MoSCoW, Value vs Effort\n- Backlog refinement and maintenance\n\n                                                          | ID         | Feature      | Priority            | Story Points        | \n   | ----         | --------            | ---------      | --------------      | \n                                                                           | F01                                          | Login                                                                            | High | 3                                  | \n | F02  | Account Management                                              | High   | 5                             | \n``` |      |                                                          |   |                                       |                                                             |
| 3. User Stories                    | `User-Stories.md`                | ```markdown\n## User Stories\n\n- Definition: “As a… I want… So that…”\n- Writing effective user stories\n- Acceptance Criteria\n\n                                                                                                                                                      | ID         | User Story   | Acceptance Criteria | \n                  | ---- | -----------  | ------------------- | \n             | US01                | As a customer, I want to create an account so that I can store money safely. | Account creation succeeds with confirmation. | \n```                                                                            |      |                                    |    |      |                                                                 |        |                               |       |      |                                                          |   |                                       |                                                             |
| 4. Weighting and Estimation        | `Estimation.md`                  | ```markdown\n## Weighting and Estimation\n\n- Story Points Estimation\n- Techniques: Planning Poker, T-shirt sizing\n- Weighting user stories by complexity, priority, business value\n\n                                                                                                | User Story | Story Points | Priority            | Complexity          | \n   | ------------ | --------------      | ---------      | ------------        | \n                                                                           | US01                                         | 5                                                                                | High | Medium                             | \n | US02 | 3                                                               | Medium | Low                           | \n``` |      |                                                          |   |                                       |                                                             |
| 5. Complete Banking System Example | `Banking-System-Example.md`      | ```markdown\n## Complete Banking System Example\n\n                                                                                                                                                                                                                                      | ID         | User Story   | Story Points        | Acceptance Criteria | \n   | ----         | -----------         | -------------- | ------------------- | \n                                                                           | US01                                         | As a customer, I want to create a bank account so that I can store money safely. | 5    | Account created with confirmation. | \n | US02 | As a customer, I want to deposit money so my balance increases. | 3      | Deposit reflects immediately. | \n    | US03 | As a customer, I want to withdraw money to pay expenses. | 3 | Withdrawal reduces balance correctly. | \n```\n![Banking System Diagram](<img width="1300" height="956" alt="image" src="https://github.com/user-attachments/assets/bbacb3d8-4b37-4a97-8c2e-e7d5d0154fd9" />
) |









# Hospital Management System

---

## 1. Analysis Phase

### Definition and Importance
The Analysis Phase is the stage in the Software Development Life Cycle (SDLC) where all requirements of the hospital system are collected, analyzed, and clearly understood before design and development begin.

**Importance:**
1. Reduces errors caused by misunderstanding hospital requirements.
2. Ensures all stakeholders are satisfied: doctors, nurses, admin staff, and patients.
3. Provides a clear foundation for development (User Stories, Product Backlog).

### Sub-steps

1. **Requirements Elicitation** – Gathering requirements from doctors, nurses, receptionists, lab and pharmacy staff.  
2. **Requirements Analysis** – Organize functional and non-functional requirements.  
3. **Requirements Specification** – Document requirements as User Stories and diagrams.  
4. **Validation & Approval** – Review and confirm requirements with stakeholders.

### Deliverables / Outcomes
- Documented Requirements (User Stories)  
- Use Case Diagrams / ERD  
- Preliminary Product Backlog

---

## 2. Product Backlog / User Stories

| ID   | User Story | Story Points | Acceptance Criteria |
|------|------------|--------------|-------------------|
| US01 | As a receptionist, I want to register a new patient so that their medical information can be tracked. | 5 | Patient info stored correctly, unique patient ID generated. |
| US02 | As a patient, I want to book an appointment with a doctor so that I can receive medical care. | 3 | Appointment confirmed, notification sent to doctor. |
| US03 | As a doctor, I want to view patient medical records so that I can provide accurate treatment. | 5 | Medical history, medications, lab results are available. |
| US04 | As a lab staff, I want to record test results so that doctors can access them. | 3 | Test results saved correctly and linked to patient. |
| US05 | As a pharmacist, I want to dispense medicines according to prescriptions so that patients receive correct medications. | 3 | Inventory updated and record saved. |
| US06 | As an accountant, I want to generate bills after medical services so that payments can be collected. | 5 | Accurate invoices generated, insurance linked if applicable. |
| US07 | As a hospital manager, I want to see hospital statistics so that I can monitor performance. | 5 | Dashboard shows patients, inventory, revenue correctly. |
| US08 | As a receptionist, I want to send appointment reminders to patients so that they do not miss appointments. | 3 | Notifications sent on time. |
| US09 | As an IT admin, I want to manage user roles and permissions so that only authorized staff can access data. | 5 | Roles enforced, users see only allowed sections. |
| US10 | As a patient, I want to view my lab test results online so that I can track my health. | 3 | Results available securely online. |

---

## 3. Diagrams / Images
<img width="193" height="211" alt="image" src="https://github.com/user-attachments/assets/1a8dbec5-ac8b-4ea0-ae27-23459ddf96ea" />
<img width="375" height="211" alt="image" src="https://github.com/user-attachments/assets/7815a921-e798-4a40-9040-4e974f0db31d" />




 Product Backlog (User Stories Table)

### 🗂 High-Priority Features

| ID   | User Story | Story Points | Acceptance Criteria |
|------|------------|--------------|---------------------|
| US01 | As a guest, I want to book a room online so that I can reserve it before arrival. | 5 | Booking is saved, confirmation email sent. |
| US02 | As a receptionist, I want to check in guests so that they can access their room. | 3 | Guest details saved, room status updated to "occupied". |
| US03 | As a receptionist, I want to check out guests so that rooms become available again. | 3 | Room status changes to “available”, bill generated. |
| US04 | As a manager, I want to view occupancy reports so that I can track hotel performance. | 5 | Report generated with correct daily/weekly/monthly stats. |
| US05 | As housekeeping staff, I want to update room cleaning status so that the system stays accurate. | 2 | Room status updated to “clean”, “dirty”, or “in progress”. |
| US06 | As a guest, I want to request room services so that I can receive assistance. | 3 | Service request logged and assigned to staff. |
| US07 | As a receptionist, I want to generate guest bills so that checkout is smooth. | 3 | Bill includes room charges and additional services. |
| US08 | As a hotel manager, I want to manage room prices so that I can apply seasonal changes. | 5 | Price updates reflected immediately in the system. |
| US09 | As an admin, I want to manage user roles so that system security is maintained. | 5 | Admin can add/edit/delete staff roles and permissions. |
| US10 | As a restaurant staff member, I want to add food orders to a guest bill so that charges are accurate. | 4 | Orders linked to the correct guest and added to the invoice. |






## 4. Diagrams 



![Use Case Diagram](<img width="340" height="379" alt="image" src="https://github.com/user-attachments/assets/87b9c7b5-637e-4fec-95c4-3334a3332992" />
)

---


![ERD Diagram](<img width="1051" height="571" alt="image" src="https://github.com/user-attachments/assets/081222cf-e0c3-4d05-ad53-3f6163785bf1" />
)





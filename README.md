##  Introduction
The **Educational Organization Management System** is a digital platform built on **ServiceNow** to streamline administrative tasks in educational institutions.  
It simplifies **student admissions, academic progress tracking, and section management**, making operations more efficient and transparent.  

---

## Features
###  Admission Management
- Tracks full lifecycle of student admissions.  
- Status options: *New, In Progress, Joined, Rejected, Closed, Cancelled*.  

###  Student Progress Tracking
- Records examination results and marks.  
- Monitors academic performance.  

###  Section Management
- Organizes students into sections/classes.  
- Manages group allocations with ease.  

---

##  Technical Implementation
- **Platform:** ServiceNow (Tokyo release or later)  
- **Tool:** ServiceNow Studio  
- **Customizations:**  
  - Tables → Admissions, Student Progress, Sections  
  - Forms & Lists → Configured for data entry/tracking  
  - Workflows → Admission lifecycle automation  
  - Client Scripts → UI behavior & validation  
  - Process Flows → Automating steps for admissions & progress tracking  

---

##  Project Deliverables
- `Educational_Organization_update_set.xml` → Update set for ServiceNow  
- `docs/Project_Report.pdf` → Detailed project documentation  
- `screenshots/` → Output screenshots  
- `demo/` → Project demonstration video (or external link)  

---

##  Screenshots
 # Admission Form
 <img width="1920" height="1128" alt="image" src="https://github.com/user-attachments/assets/08a8dbbe-ee37-4622-a647-4d8b6cc95fa0" />
<img width="1920" height="1128" alt="image" src="https://github.com/user-attachments/assets/9fa34b5d-c2e3-45f3-b940-094b11c856f8" /> 

# Salesforce Form
  <img width="1920" height="1128" alt="image" src="https://github.com/user-attachments/assets/ad48cbc6-de29-4ecb-b11c-fe8252ec2f82" />
<img width="1920" height="1128" alt="image" src="https://github.com/user-attachments/assets/682fe5a2-708c-493f-8f8a-625299e0f1cd" />

# Student Progress Form
  <img width="1920" height="1128" alt="image" src="https://github.com/user-attachments/assets/4c18f894-f71d-4899-9fa5-b0fa95f233db" />





---



##  Installation Guide
1. Navigate to **System Update Sets → Retrieved Update Sets** in your ServiceNow instance.  
2. Click **Import Update Set from XML**.  
3. Upload `Educational_Organization_update_set.xml`.  
4. Preview → Resolve conflicts (if any).  
5. Commit the update set.  

---

##  Usage
- **Admissions Table** → Manage admission records.  
- **Student Progress Table** → Record and track results.  
- **Sections Table** → Assign students to sections.  

---

##  Future Enhancements
- Self-service student admission portal.  
- Email notifications for admission status.  
- Automated student progress reports.  
- Role-based access (Admin, Teacher, Student).  

---

##  Author
**Pentakota Rohini Priya**  
Roll No: `22L31A5476`  
Vignan's Institute of Information Technology (A)

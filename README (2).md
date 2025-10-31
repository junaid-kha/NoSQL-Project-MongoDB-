# 📘 MongoDB NoSQL Project

### 🔍 Overview
This project demonstrates practical use of **MongoDB**, a leading **NoSQL database**, to manage and analyze educational data involving students, faculty, courses, and activities.  
It covers a complete range of MongoDB operations — from **basic filtering and CRUD** to **advanced aggregation pipelines** and **joins using `$lookup`**.

---

## 🗂️ Collections Used

| Collection | Description |
|-------------|-------------|
| `students` | Stores student details, attendance, skills, and activities. |
| `faculty` | Contains faculty details and their assigned courses. |
| `courses` | Includes course information such as title, credits, and ID. |
| `enrollments` | Connects students to courses with marks obtained. |
| `activities` | Stores records of extracurricular events and participation. |

---

## ⚙️ Project Sections

| Section | Focus Area |
|----------|-------------|
| **1. Complex Filters & Projections** | Using `$gt`, `$all`, `$size` for conditional filtering |
| **2. Joins & Aggregations** | Combining collections with `$lookup` and summarizing data |
| **3. Grouping, Sorting & Limiting** | Ranking and filtering aggregated results |
| **4. CRUD Operations** | Performing `insert`, `update`, and `delete` with conditions |
| **5. Array & Operator Usage** | Working with arrays using `$and`, `$ne`, and `$all` |
| **6. Subdocuments & Nested Conditions** | Filtering documents with nested fields |
| **7. Advanced Aggregation** | Multi-level `$lookup` and `$group` for detailed analytics |

---

## 📊 Query Outcomes & Insights

| **Query** | **Description** | **Insight / Outcome** |
|------------|-----------------|------------------------|
| **Q1** | Students with >85% attendance skilled in MongoDB and Python | Identifies consistent, multi-skilled students |
| **Q2** | Faculty teaching more than 2 courses | Lists most engaged faculty members |
| **Q3** | Student names with course titles (using `$lookup`) | Displays student-course relationships |
| **Q4** | Course title, total students, and average marks | Shows popularity and performance of each course |
| **Q5** | Top 3 students with highest average marks | Highlights top academic performers |
| **Q6** | Department with highest number of students | Reveals most populated department |
| **Q7** | Update attendance to 100% for Hackathon winners | Demonstrates mass update capability |
| **Q8** | Delete activities before 2022 | Cleans outdated records |
| **Q9** | Upsert “Data Structures” course | Ensures data integrity via conditional insert/update |
| **Q10** | Students with Python skill but not C++ | Filters specialization-based student profiles |
| **Q11** | Students who joined both Seminar & Hackathon | Shows multi-event participation |
| **Q12** | CS students scoring >80 in Web Dev | Highlights top technical students |
| **Q13** | Faculty-wise student marks with averages | Provides detailed faculty performance analytics |
| **Q14** | Most popular activity type | Reveals top extracurricular interest |

---

## 🧠 Key Learnings

- Effective use of **MongoDB Aggregation Pipeline**:
  - `$lookup`, `$unwind`, `$group`, `$project`, `$sort`, `$limit`
- Hands-on practice of **CRUD operations** and **conditional filters**
- Demonstrated use of **array and logical operators**
- Implementation of **joins in NoSQL**, simulating relational behavior
- Understanding of **data analytics and insight generation** from raw data

---

## 💡 Insights Gained

- Identified **top students and departments** based on performance metrics  
- Found **faculty workload distribution** through course mapping  
- Analyzed **popular activities** among students  
- Demonstrated how MongoDB handles **semi-structured academic data** efficiently  

---

## 🧰 Technology Stack

| Component | Details |
|------------|----------|
| **Database** | MongoDB |
| **Environment** | MongoDB Compass / Mongo Shell |
| **Language** | Mongo Shell Queries |
| **Data Format** | JSON Documents |

---

## 📁 Files Included

📦 NoSQL-Project/
┣ 📄 NoSql-Project.pdf # Full project with MongoDB queries
┣ 📄 NoSql-Project.docx
┣ 📄 Information.md # Project overview and documentation
┗ 📂 datasets/ # JSON files if included

---

## 👤 Author

**Name:** Junaid Khan
**Registration No.:** 1240258210  
**Subject:** NO SQL and Dbaas 101
**Course:** BCA (Data Science & AI)  
**Institution:** *Babu Banarasi Das University*  
**Submitted To:** *Mr. Ankit Verma*   

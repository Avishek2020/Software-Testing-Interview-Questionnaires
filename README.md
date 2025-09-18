# 🧪 Software Testing Interview Questionnaires

A curated collection of **Software Testing & QA Interview Questions and Answers**.  
This repository is designed to help candidates prepare for interviews ranging from **manual testing basics** to **advanced automation frameworks**.

---

## 📌 Table of Contents
1. [Manual Testing Basics](#manual-testing-basics)  
2. [Test Automation](#test-automation)  
3. [Selenium](#selenium)  
4. [Frameworks & Tools](#frameworks--tools)  
5. [General QA Concepts](#general-qa-concepts)  
6. [SQL for Testers](#sql-for-testers)

---

## 📝 Sample Questions & Answers

### 1. Find rows where a specified column has even values?
**Answer:**  
### 1. Find rows where a specified column has even values?
**Answer:**  
**Query:**
sql
SELECT *
FROM table_name
WHERE MOD(column_name, 2) = 0;




---

### 1. What is the difference between Verification and Validation?
**Answer:**  
- **Verification** ensures the product is built correctly (**process-oriented**).  
- **Validation** ensures the right product is built as per requirements (**output-oriented**).

---

### 2. What are the different levels of testing?
**Answer:**  
- **Unit Testing** – Testing individual modules or components.  
- **Integration Testing** – Testing combined parts to ensure interaction.  
- **System Testing** – End-to-end testing of the complete system.  
- **Acceptance Testing** – Verifying the system meets business requirements.

---

### 3. How do you handle dynamic elements in Selenium?
**Answer:**  
By using **dynamic XPath/CSS selectors**, such as `contains()`, `starts-with()`, or relative locators.  

**Example (XPath):**
```xpath
//input[contains(@id,'username')]

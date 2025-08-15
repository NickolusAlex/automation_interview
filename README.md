# Automation Candidate Practical Test

## About This Repository
This repository contains a practical automation test for candidates. The purpose of this test is to evaluate your hands-on skills in automating dynamic web pages, handling user interactions, validating forms, working with tables, dropdowns, and random events.  

You will find a single HTML page with multiple tasks designed to simulate real-world automation scenarios.

### Live Page
Access the live version of the test here: [Open Automation Test Page](https://nickolusalex.github.io/automation_interview/)  

---

## Objective
- Assess your ability to interact with web elements using automation tools (Selenium, Playwright, Cypress, etc.).
- Validate dynamic content, tables, forms, dropdowns, and alerts.
- Handle advanced UI elements like Select2 dropdowns and random popups.
- Demonstrate best practices in automation scripting and testing.

---

## How to Use This Repository
1. Clone or download this repository to your local machine.
2. Open the `index.html` file in a browser **or use the live page link above**.
3. Follow the instructions for each task below.
4. For each task:
   - Use your automation tool of choice to interact with elements.
   - Validate expected outcomes (text, visibility, table content, dropdown options, popups, etc.).
   - Capture screenshots, logs, or scripts as proof of task completion.
5. Submit your automation scripts along with any required documentation or evidence of execution.

---

## Task Categories
### **Easy**

#### 1. Token Generation
**Task:**
- Double-click the “Double-Click Me” button.
- Verify that a token is generated in the format `XXX-XXX-XXX` (letters and numbers).
- Capture the generated token and ensure it changes on each double-click.

**Automation Angle:**
- Test double-click event.
- Validate dynamic text update.

#### 2. Hidden Element
**Task:**
- Click “Show Secret”.
- Verify that the hidden text `🎯 Secret Code: 42XYZ` becomes visible.
- Click again to hide it.

**Automation Angle:**
- Test toggle functionality.
- Validate visibility of elements.

---

### **Medium**

#### 3. Dynamic Table
**Task:**
- Click “Update Table”.
- Verify that the table shows 4 rows with names and random scores.
- Ensure the previous table content is cleared before updating.

**Automation Angle:**
- Test table population.
- Validate row count and data format.

#### 4. Form Submission
**Task:**
- Submit the form with empty fields → verify error message `❌ Please fill out all fields`.
- Submit the form with valid Name and Email → verify success message `✅ Form submitted successfully!`.

**Automation Angle:**
- Test form validation.
- Validate dynamic text messages.

#### 5. Dependent Dropdowns (Country → City)
**Task:**
- Select a country → verify that the corresponding cities populate the city dropdown.
- Ensure that the city dropdown resets when changing the country.
- Test all countries: India, USA, Germany, Australia, UK.

**Automation Angle:**
- Test dependent dropdown behavior.
- Validate dynamic options.
- Test integration with Select2 (searchable dropdown).

---

### **Hard**

#### 6. Random Popup
**Task:**
- Refresh page multiple times.
- Verify that sometimes an alert appears randomly (50% chance).
- Capture the alert text: `🚨 Random Popup! Handle me.`

**Automation Angle:**
- Test unpredictable/random events.
- Handle browser alerts in automation scripts.

#### Optional Bonus Tasks
1. **Token + Table Integration:**  
   - After generating a token, click “Update Table” → ensure no conflicts or errors occur.

2. **Select2 Search Testing:**  
   - Type part of a city name in the dropdown → ensure correct filtered results appear.

3. **End-to-End Scenario:**  
   - Generate a token → fill form → select country and city → update table → handle popup.
   - Verify all dynamic elements work together.

---

---

## 📬 Contact

For questions, feedback, or collaboration, feel free to reach out:
- Name: Nithyanandhan V
- Email: nithyanandha.velliyangiri@gmail.com
- GitHub: [your-github-profile](https://github.com/NickolusAlex)

---


Good luck! Complete the tasks in the order listed or choose based on your comfort level. Make sure to capture screenshots, logs, or any automation scripts as evidence of completion.
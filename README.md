# Olympics Data Analysis

## Introduction

This project analyzes two datasets to gain insights into Olympic athletes and their performances:

- **Athletes Dataset:** Contains detailed information about athletes, including:

  - Full Name
  - Sports
  - Country
  - Physical attributes (Height, Weight)
  - Date of Birth

- **Medals Dataset:** Provides comprehensive medal details, featuring:

  - Medal Type (Gold, Silver, Bronze)
  - Event
  - Athlete’s Country
  - Date of Medal Award

These datasets are sourced from reliable Olympic data repositories, ensuring high accuracy and depth in analysis. The objective of this project is to uncover insights such as:

- **Patterns** in medal distribution across countries.
- **Trends** in age and performance.
- **Dominance** of certain countries or athletes in specific sports.
- **Relationship** between athlete heights and their sports.

### Dataset Structure

Key variables analyzed include:

- `Full_Name`
- `Sports`
- `Country`
- `Medal_Type`
- `Event`
- `Medal_Date`
- `Height`

---

## Data Wrangling

### Handling Missing Values

Critical columns such as `Full_Name`, `Country`, and `Sports` were filtered to remove rows with missing or irrecoverable values.

### Column Selection and Renaming

- Unnecessary columns were removed to focus on relevant fields.
- Columns were renamed for consistency and clarity, such as:
  - `name_tv` → `Full_Name`
  - `medal_type` → `Medal_Type`

### Data Cleaning

- Formatting inconsistencies (e.g., brackets, quotes) were removed.
- Date columns (`Birth_Date`, `Medal_Date`) were converted to proper date formats.

### Merging Datasets

The datasets were merged using common columns (`Full_Name`, `Sports`, `Country`) to form a unified dataset (`combined_df`) including essential variables like `Medal_Type`, `Event`, `Height`, `Weight`, and `Medal_Date`.

---

## Data Transformation

### 1. Mean Age of Medal-Winning Athletes by Sport and Gender

**Objective:** Analyze the average age of medal-winning athletes across sports, highlighting gender differences in peak performance.

**Insights:**

- Identifies sport-specific age trends.
- Highlights gender-based variations in success.

### 2. Athletes Who Won Multiple Medals In A Particular Sport

**Objective:** Showcase athletes excelling in their respective sports by winning multiple medals.

**Insights:**

- Recognizes top-performing athletes with consistent success.
- Highlights trends in sustained excellence across events.

### 3. Top 10 Countries by Medal Count

**Objective:** Visualize the top-performing countries by total medal count, categorizing by Gold, Silver, and Bronze.

**Insights:**

- Identifies leading nations in international competitions.
- Reflects investments and strengths in various sports.

### 4. Analyzing the Relationship Between Athlete Heights and Their Sports

**Objective:** Compare the height distributions of male and female athletes across different sports.

**Insights:**

- Identifies gender-based height differences.
- Provides an understanding of how height influences performance in various sports.

---

## Conclusion

This project offers a comprehensive analysis of Olympic data, providing valuable insights into:

- Performance patterns by country and sport.
- Age and physical attributes of medal-winning athletes.
- Athlete dominance and country-wise medal trends.




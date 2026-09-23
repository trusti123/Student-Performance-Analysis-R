# Student Performance Analysis Using R

## Tiny Project

A simple R programming project that analyzes student academic performance using a CSV dataset. The project demonstrates data importing, inspection, cleaning, statistical analysis, visualization, correlation analysis, and interpretation of results.

---

## Student Details

- **Name:** Trivedi Trusti
- **Enrollment No.:** 2505101270275
- **Subject:** R Programming
- **Project Title:** Student Performance Analysis Using R

---

## Project Overview

This project uses **R programming** to analyze the academic performance of 20 students.

The analysis includes:

- Importing student data from a CSV file
- Inspecting the dataset using `head()`, `summary()`, and `str()`
- Checking missing values
- Checking duplicate records
- Calculating median, variance, and standard deviation
- Analyzing gender distribution
- Analyzing pass/fail results
- Creating pie charts and bar plots
- Analyzing attendance and marks
- Calculating the correlation between attendance and marks
- Presenting findings and conclusions

---

## Objectives

1. Import student performance data from a CSV file.
2. Understand the structure and summary of the dataset.
3. Check and clean the data.
4. Calculate important statistical measures.
5. Visualize student performance using charts.
6. Study the relationship between attendance and marks.
7. Interpret the results obtained from the analysis.

---

## Dataset

The project uses the following CSV file:

`Trivedi_Trusti_Student_Performance.csv`

### Dataset Columns

| Column | Description |
|---|---|
| Name | Name of the student |
| Gender | Gender of the student |
| Marks | Marks obtained by the student |
| Attendance | Attendance percentage |
| Result | Pass/Fail result |

The dataset contains **20 students**.

---

## Technologies Used

- **R Programming**
- **RStudio**
- **CSV Dataset**
- **Base R Functions**

No external R packages are required for the main analysis.

---

## Project Structure

```text
Student-Performance-Analysis-R/
│
├── README.md
├── Trivedi_Trusti_Tiny_Project..rmd
├── Trivedi_Trusti_Tiny_Project.html
├── Trivedi_Trusti_Student_Performance.csv
└── images/
    ├── image-1.png
    ├── image-2.png
    ├── image-3.png
    ├── image-4.png
    └── image-5.png
```

> File names inside the `images` folder may differ depending on the files uploaded to the repository.

---

## R Functions Used

Some important R functions used in this project are:

```r
read.csv()
head()
summary()
str()
is.na()
colSums()
duplicated()
median()
var()
sd()
table()
pie()
barplot()
cor()
plot()
```

---

## Statistical Results

The analysis produced the following important results:

| Measure | Result |
|---|---:|
| Number of Students | 20 |
| Mean Marks | 73.10 |
| Median Marks | 74.50 |
| Variance | 209.46 |
| Standard Deviation | 14.47 |
| Highest Marks | 94 |
| Lowest Marks | 45 |
| Male Students | 10 |
| Female Students | 10 |
| Passed Students | 20 |
| Failed Students | 0 |
| Pass Rate | 100% |
| Attendance–Marks Correlation | 0.990 |

---

## Data Cleaning

The dataset was checked for:

### Missing Values

```r
colSums(is.na(student_data))
```

The dataset contains **no missing values**.

### Duplicate Records

```r
sum(duplicated(student_data))
```

The dataset contains **no duplicate records**.

Therefore, no additional data-cleaning or imputation was required.

---

## Visualizations

The project creates the following visualizations:

### 1. Gender Distribution

A pie chart showing the number of male and female students.

### 2. Student Result Distribution

A pie chart showing the distribution of Pass and Fail results.

### 3. Student Marks

A bar plot comparing the marks obtained by individual students.

### 4. Student Attendance

A bar plot comparing attendance percentages.

### 5. Attendance vs Marks

A scatter plot showing the relationship between attendance and marks.

---

## Correlation Analysis

Pearson correlation is calculated using:

```r
cor(student_data$Attendance, student_data$Marks)
```

The calculated correlation is approximately:

```text
0.990
```

This indicates a **strong positive association** between attendance and marks in this particular dataset.

> Correlation shows an association between two variables. It does not by itself prove that attendance causes higher marks.

---

## Key Findings

1. The dataset contains 20 student records.
2. There are no missing values or duplicate records.
3. The average mark is 73.10.
4. The median mark is 74.50.
5. The highest mark is 94 and the lowest mark is 45.
6. Male and female students are equally represented.
7. All 20 students have a Pass result.
8. The pass rate is 100%.
9. Attendance ranges from 58% to 96%.
10. Attendance and marks show a strong positive association in this sample.

---

## Conclusion

This project demonstrates how **R programming** can be used to perform a complete student-performance data analysis.

The project starts with importing a CSV dataset and continues with data inspection, data cleaning, statistical calculations, visualization, correlation analysis, and interpretation.

The results show variation in student marks and a strong positive association between attendance and marks within this sample. The project provides a basic practical example of how raw data can be converted into meaningful statistical information and visual insights using R.

---

## How to Run the Project

### Step 1: Install R

Install R on your computer.

### Step 2: Install RStudio

Open the project in RStudio.

### Step 3: Keep the Files Together

Make sure the following files are in the same project folder:

```text
Trivedi_Trusti_Tiny_Project..rmd
Trivedi_Trusti_Student_Performance.csv
```

### Step 4: Open the R Markdown File

Open:

```text
Trivedi_Trusti_Tiny_Project..rmd
```

### Step 5: Run / Knit

Use the **Knit** option in RStudio to generate the HTML report.

---

## Project Purpose

This project was created as a **Tiny Project for R Programming** to demonstrate practical knowledge of:

- Data handling
- Data analysis
- Statistical functions
- Data visualization
- Correlation
- Interpretation of results

---

## Author

**Trivedi Trusti**  
**Enrollment No.: 2505101270275**

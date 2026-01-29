# Assignment - 1

1. Understand the Data

Before writing any code, the first step is to understand what the dataset is actually saying. This helps avoid wrong assumptions and bad analysis later.

2. What Each Column Represents

Each column is a feature / variable.

It describes one specific attribute of the data.

Example:

customer_id → uniquely identifies a customer

age → customer’s age

purchase_amount → money spent

purchase_date → date of transaction

👉 Think of columns as questions, and the dataset answers them.

3. What One Row Means

Each row represents one complete record or observation.

It is a single real-world entity.

Example:

One row = one customer’s one purchase

All column values in that row describe the same event or person

👉 Rows are individual stories, columns are details about that story.

4. Identify Possible Data Issues

This is where data quality checks happen 🔍

Common issues to look for:

Missing values (null, NaN, empty cells)

Duplicate records (same row repeated)

Incorrect data types

Numbers stored as text

Dates stored as strings

Outliers

Extremely high or low values

Inconsistent values

“Male”, “male”, “M”

Invalid values

Negative age

Future dates where not possible

👉 Fixing these issues is data cleaning, and it directly impacts model accuracy and insights.

"""One-Line Professional Summary (Resume-Ready)

Analyzed dataset structure by interpreting columns and rows, identified data quality issues such as missing values, duplicates, and inconsistent formats, and prepared clean data for analysis."""

### Pro Tip: In Pandas, use df.info() and df.describe() to get a "health check" of these issues instantly





# Assignment - 2


1. What is Data?

Data is a collection of raw facts and observations that represent real-world entities, events, or measurements.
By itself, data has no meaning — meaning comes after processing and analysis.

Examples of data:

Numbers (age, salary, score)

Text (name, feedback, comments)

Dates (purchase date, login time)

Categories (gender, product type)

👉 Data is the foundation of analytics, machine learning, and AI.

2. What is a Feature?

A feature is an individual measurable property or attribute of the data.

In a dataset, each column is a feature

Features describe characteristics of the entity

Example:

Dataset about customers

age, city, monthly_spend → features

👉 Features are the inputs used by models to learn patterns.

3. What Problems Can Bad Data Cause?

Bad data leads to bad decisions — no exceptions.

Common problems caused by poor-quality data:

❌ Incorrect analysis and insights

❌ Biased or misleading models

❌ Poor model accuracy

❌ Wrong business decisions

❌ Loss of trust in reports and dashboards

❌ Increased debugging and rework time

Examples of bad data:

Missing values

Duplicates

Incorrect formats

Inconsistent labels

Outliers not handled

👉 Garbage in = Garbage out.


4. What I Learned Today

Today I learned how to set up a complete browser-based data science workflow, structure a professional GitHub repository, and use Google Colab for Python coding. I practiced core Python fundamentals, loaded and explored a dataset using pandas, understood what columns and rows represent, identified common data quality issues, and wrote simple data-cleaning functions. I also learned why clean data is critical for accurate analysis and reliable results.
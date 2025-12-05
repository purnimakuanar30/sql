This repository contains Oracle SQL solutions for the SQL Test based on the dataset snapshot provided in the assignment. The script includes table creation, sample inserts that match the snapshot, and solutions for all analytical questions (Q1–Q8).
sql.file — Oracle script containing table definitions, sample data inserts, and SQL solutions for all questions.
The dataset used in this script matches the snapshot provided in the test PDF
Assumptions: A refunded transaction is identified by refund_time IS NOT NULL. Refund validity is determined based on a 72-hour difference between purchase and refund time. First and second purchases are identified using timestamp-based ordering. The refund_item column is intentionally removed from the schema.

# IC-2K25-83-dbms

SQL practice scripts for my **Database Management Systems (DBMS)** course.

**Author:** Shreya Mishra  
**Course:** MCA, 3rd Semester  
**Roll No.:** IC-2K25-83

---

## About

This repository is my collection of DBMS lab work. It contains SQL scripts for creating tables and practising core concepts such as:

- Creating tables with `CREATE TABLE`
- Primary keys and composite primary keys
- `CHECK` constraints
- Auto-increment columns
- Handling "table already exists" situations
- Inserting sample data

## Tables Covered

| Table | What it stores |
|-------|----------------|
| `countries` | Country ID, country name and region ID |
| `jobs` | Job details |
| `job_history` | Employees' past job records |
| `employees` | Employee details |
| `continents` | Continent data |

## Repository Structure

Files are numbered roughly in the order I worked on them.

| File | Description |
|------|-------------|
| `Q6. create table job.sql` | Creates the jobs table |
| `Q7. table country inc India, Italy,...` | Countries table with country data |
| `07_create_countries_check_specif...sql` | Countries table with a `CHECK` constraint |
| `08_job_histry.sql` | Job history table |
| `9. countries.sql` | Countries table |
| `10. jobs.sql` | Jobs table |
| `11. countries.sql` | Countries table |
| `Q12_Create_Countries_AutoIncre...sql` | Countries table with an auto-increment ID |
| `13_Create_Countries_Composite...sql` | Countries table with a composite key |
| `14_Create_Job_History.sql` | Job history table |
| `15_Create_Employees_Composite...sql` | Employees table with a composite key |
| `16_create_employees_table.sql` | Employees table |
| `17_create_employees_table.sql` | Employees table (variation) |
| `18_create_employees_table.sql` | Employees table (variation) |
| `DBMS_Continents.sql` | Continents table |
| `country_table.sql` | Basic countries table |
| `country_tablt_alreadyExist.sql` | Countries table when it already exists |

## Example

```sql
CREATE TABLE countries (
  country_id INT PRIMARY KEY,
  country_name VARCHAR(40),
  region_id INT
);
```

## Tools Used

- SQL (MySQL)
- Git and GitHub
  # Thank you!

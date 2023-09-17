 ## 1️⃣ Scraping some attributes of jobs from Wuzzuf website Like :
   - `Job title` : Name of job.
   - `Company name` : Name of the company that owns the advertisement.
   - `Location` : Company location.
   - `Job type` : Type of job: is it full time or part time.
   - `Exp level` : Required level is whether senior or manger or ect.
   - `Exp years` : Number of years required to obtain job.
   - `Skills` : Skills required to obtain job.
_________________________________________________________________________________________

 ## 2️⃣ Save data in data structure that organizes data into 2-dimensional table :
  - Create Data Frame
  - save extracted data to Data Frame
_________________________________________________________________________________________
##  3️⃣ Cleaning : 
 - See if we have a duuplicated rows.
 - Clean up the job_title by removing hyphenated words, text after forward slashes and text within parentheses.
 - Remove Egypt from Location column.
 - Clean up the Job type by removing forward slashes and get first word of this.
 - in Exp year :
   - Remove this part `"Yrs of Exp"` from each value.
   - Get rid of values as `" ", "-".`
   - Convert single value to range format by matching them to existing ranges.
_________________________________________________________________________________________
 ##  4️⃣ Exploratory data analysis : 
  - What are the most common `Job type`?
  - What is top `10 jobs`?
  - What is top `10 districts`?
  - What `level` of experience is most required?
  -  What `company name` is most in demand for jobs?
  -  What is top `10 skills`?
_________________________________________________________________________________________
##  5️⃣ Conclusions :
 - Most common job types is :
   - `Full Time`
   - `Internship`
- Top jobs :
   - `Accountant`
   - `Finance Manager`
   - `General Accountant`
   - `Senior Accountant`
- Top districts :
   - `Cairo`
   - `New Cairo`
- Most common experience level :
   - `Experienced`
   - `Manager`
   - `Entry Level`
- Top company is most in demand for jobs :
   - `Confidential`
   - `AlGammal Contracting`
- Top skills :
   - `Accounting`
   - `Finance`
   - `Analyst`
   - `Research` and `Financial Analysis`

 ## 1️⃣ Scraping some attributes of jobs from Wuzzuf website Like :
   - `Job title` : Name of job.
   - `Company name` : Name of the company that owns the advertisement.
   - `Location` : Company location.
   - `Job type` : Type of job: is it full time or part time.
   - `Exp level` : Required level is whether senior or manger or ect.
   - `Exp years` : Number of years required to obtain job.
   - `Skills` : Skills required to obtain job.
_________________________________________________________________________________________

 ## 2️⃣ Save data in data structure that organizes data into 2-dimensional table:
  - Create Data Frame
  - save extracted data to Data Frame
_________________________________________________________________________________________
##  3️⃣ Cleaning
 - see if we have a duuplicated rows.
 - Clean up the job_title by removing hyphenated words, text after forward slashes and text within parentheses.
 - Remove Egypt from Location column.
 - Clean up the Job type by removing forward slashes and get first word of this.
 - in Exp year :
   - an 

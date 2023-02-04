## Why we collect data
1. To serve our students
3. To hold ourselves accountable to one another
4. To share information effectively with each other
5. To serve our non-student constituents
6. To build our impact narrative
8. To build, maintain, and deepen our relationships with funders, donors, and  partners
9. To obtain funding
10. To inform and influence legislation
	
## Why we report on data
1. To report to funders and partners
2. To be accountable to funders and partners
3. To a trusted thought partner to funders and partners
4. To hold ourselves accountable to each other
5.  To share our information effectively
6. To show our impact

## Data we report on
1. Verified Enrollment (direct date inferences) by Cohort
2. How many of a given cohort or program currently enroll in college?
3. What is the college persistence rate for Achievers who also receive CSF scholarships?
4. What is the first year college enrollment rate of students who completed both HERO and Achievers programs
5. How many of unique CSF Achievers have received a BA degree so far?   
6. How many of CSF Achievers graduating from HS in 2013 have received a BA degree?
7. How many Achievers graduating from HS in Spokane have received a post-secondary degree?
8. How much money CSF has disbursed to WA scholars during 2019-2020?
9. How many unique CSF scholars (all CSF programs, both WA and DC) have received a post-secondary degree?
10. How much money CSF has disbursed organization-wide during 2019-2020?
11. Provide a list of Achievers who have graduated with a BA in the STEM field (Student name, program, graduation date, major, contact information.
12. Number of Achievers who have graduated with a BA in the STEM field  
13. How many of CSF Achievers have graduated from Eastern Washington University
14. How many of CSF Achievers from Ferry High School have graduated from Eastern Washington University?  
15. How many Achievers were recruited at the beginning of 2020?
16. What is the program progression/retention rate?  (in order to calculate the rate, we need to track the scholar’s enrollment status over time)
17. How many Achievers were recruited this year?

## Who uses our data?
Need input form REL and Programs
1. We do
2. OSPI
3. Thought partners

## The Data Warehouse - What is it?

-   A storage location where data from National Student Clearinghouse, Education Edge, FinancialAwardData database, Survey Monkey Apply  (formally BlackBaud NetCommunity), Form Assembly/Formstack is stored together so it can be more easily accessed.

-   (See Glossary on the last page of this document for definitions of all systems mentioned)

-   More detailed student level data is stored in Data Warehouse
-   Stored on a 2008 R2 Microsoft Server, the Data Warehouse is 15 years old
-   As of February 2020 the Data Warehouse is no longer supported by Microsoft, this means that maintaining and fixing the Data Warehouse falls completely on College Success Foundation with the help of ISOutsource
-   College Success Foundation maintains the Data Warehouse but we no longer support it

-   Originally it was maintained by 3rd Sector Intelligence (3SI)

-   We no longer work with 3rd Sector Intelligence for support
-   Stores historical data for College Success Foundation

### Who uses it?

#### Eva Chen/Research & Evaluation

-   Pulls data from cubes for grant proposals
-   Pulls data for report requests
-   Most used cubes are Application and National Student Clearinghouse

- ####  Sarah Porter

-   Annual and anticipated disbursement report
-   No direct access, asks Genny Brown to refresh report and send.
-   Uses it for the historical data it provides

 #### Maria Rebecchi

-   No direct access, uses Excel to pull data for reports on scholarships and disbursements
-   Uses it for the historical data it provides

-   ### The Unknown

-   We don’t know everything that the Data Warehouse touches and what would break if it was sunsetted.

### What does it take to maintain?

-   Data is pulled from Education Edge, Survey Monkey Apply, Formstack,  and FinancialAwardData every month using a SQL Agent Job
-   Once the job is completed successfully, the cubes need to be refreshed manually, this process takes about 40 minutes to complete
-   ISOutsource will be tightening security on the Data Warehouse
-   College Success Foundation maintains the Data Warehouse but we no longer support it

-   Originally it was maintained by 3rd Sector Intelligence (3SI)
-   We no longer work with 3rd Sector Intelligence for support

### What happens when it breaks?

-   If it breaks, ISOutsource (Jon McFarland) is potentially able to fix it but at an additional cost

-   The recent fix cost CSF $8K

·         ISOutsource is going to be improving the security of the Data Warehouse to be least privileged access. Meaning only specific people will be able to access the DATA WAREHOUSE only on a specific server to prevent people from breaking it.

### When is it used?

-   It is used by Research & Evaluation to pull data for grant proposals/reports
-   Used by Sarah Porter to populate the Actual and Anticipated Disbursement Report that is submitted to the State of Washington in July of every year

### Do we need it?

-   Currently the only place Free and Reduced Price Lunch and 1st generation college status info is stored
-   Only place all data from National Student Clearinghouse is easily accessible
-   Used to store more detailed student level data
-   Contains historical data for College Success Foundation

### How is it used?

-   It is used to store more detailed student level data from multiple sources
-   Used to make pulling data more efficient for Research & Evaluation

### What would it take to move the relevant data to Salesforce?

-   There is no complete list of what the Data Warehouse touches and what would break if it was moved to exclusively historical purposes
-   This will need to be discussed with Sara Baumert, Kelley Bevans, and Bigger Boat

  

The Data Warehouse is the catch-all location for the data of the systems for College Success Foundation. The Data Warehouse not only contains data from all the systems (Education Edge, Survey Monkey Apply/BlackBaud NetCommunity, National Student Clearinghouse, Form Assembly/Formstack, and FinancialAwardData) but it holds more detailed student level data than is able to be stored in the other systems. In addition, it stores historical data for College Success Foundation. Of the systems, National Student Clearinghouse data is stored in the most detail in the Data Warehouse. Stored on a 2008 R2 Microsoft server, the Data Warehouse is 15 years old and, as of February 2020, no longer supported by Microsoft. This means College Success Foundation is responsible for maintaining the Data Warehouse, and fixing the Data Warehouse with the help of ISOutsource. College Success Foundation does not support the Data Warehouse as we no longer work with the company who built and supported it, 3rd Sector Intelligence (3SI).

Maintaining the Data Warehouse consists of data from all systems being pulled into the Data Warehouse using a SQL Agent job on the last day of the month. Once the job has completed successfully, the cubes have to be refreshed manually. The manual refresh process takes about 40 minutes and is done on the first work day of the new month by Genny Brown, the SQL Developer/Analyst. Fixing the Data Warehouse depends on the issue but requires the help of ISOutsource.

There is one major user of the Data Warehouse, Eva Chen from Research & Evaluation. She utilizes the Data Warehouse to pull data that she then processes to fit the format of the request she receives. These requests are primarily for grant proposals, to show we are on mission. The cubes Eva uses the most are the Application cube and the National Student Clearinghouse cube. The other users are Sarah Porter in Accounting & Finance and Maria Rebecchi in Scholarship Services. Although Sarah doesn’t have direct access to the Data Warehouse, she uses the data stored to compile the Actual and Anticipated Disbursement Report. The report is submitted to the State of Washington every year in July to show the significant liability. Maria also doesn’t have direct access, she utilizes the data stored in the cubes to run reports about scholarships and disbursements. Sarah and Maria both utilize the historical data stored in the Data Warehouse in their roles.

The Data Warehouse was originally needed to be able to store the data Research & Evaluation needs for their reports that was unable to be stored in any of the other systems. The other major driving force for the Data Warehouse was to have one location to access all the data in all the systems. This allows Research & Evaluation to be more efficient in pulling data by going to one place rather than 5. Currently, the Data Warehouse is the only place where Free and Reduced Price Lunch and 1st Generation status data is stored, and the only place detailed National Student Clearinghouse data is accessible.

It is the recommendation of the SQL Developer/Analyst, Genny Brown, that the Data Warehouse be maintained while Salesforce is set up to replace it. Then, moved to historical purposes only, while data is cleaned and migrated to Salesforce, and finally sunsetted. Getting rid of the Data Warehouse is not a small task. On top of all the systems mentioned in this document that interface with the Data Warehouse there is the unknown. We don’t have a full picture of what all the Data Warehouse touches, and we won’t until it’s no longer in use. There are two choices, either continue maintaining an expensive, outdated, no longer supported by Microsoft data warehouse, which will continue to get older and more out of date, and thus more expensive to maintain and fix. Or, begin the process of moving the relevant data to Salesforce, which is set to be the center of the College Success Foundation data universe. To make this change will require a conversation with Bigger Boat Consulting, Kelley Bevans, and Sara Baumert. Although this could be a tough transition, it will be worth it to use current technology that is supported by the manufacturer so College Success Foundation can continue to make a difference in the lives of the students we work with.
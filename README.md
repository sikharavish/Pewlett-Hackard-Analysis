# Overview of the analysis 
### The purpose of the analysis for Pewlett Hackard was to determine how many employees were approaching retirement and if there were enough eligible employees to be groomed into filling those vacated roles.

# Results: Provide a bulleted list with four major points from the two analysis deliverables. Use images as support where needed.

### Our retirement_titles query returned 133,776 titles. However, upon further investigation of the data it showed many employees held multiple titles over the years with the company. Those duplicate entries would need to be filtered out to get a more accurate number of roles needing to be filled.

### The unique_titles query was able to take the most recent title held by each employee to show what job they currently have. This indicates what role will be vacant if the retire. This brought the amount of retiring roles down to 72,458.

#### The retiring_titles query broke down the amount of employees in each role that were retiring. By far the senior positions were going to be the most heavily affected by the “silver tsunami”. Breaking down the mentorship eligibility data further would be helpful to determine what roles could potentially be fulfilled.

![TitleContent](/TitleCount.png)

#### The mentorship_eligibility determined what employees were eligible to be mentored by their birth date. This result only gave 1,549 eligible employees. This program will have to be looked at closer and possibly expand the eligibility guidelines in order to get a more accurate picture for hiring needs. You could also add different guidelines for each position. For instance, more experienced employees can be eligible for Senior Level positions but newer employees can be mentored for some of the lower level positions.

# Summary

### How many roles will need to be filled as the "silver tsunami" begins to make an impact?

According to the count of retiring titles there are 72,458 retiring.

#### Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?

#### There are not enough employees eligible for mentorship to cover the amount of retiring employees. There are only 1,549 eligible employees and 41,380 retiring employees.

### Two additional queries to provide more insight.

#### In the original analysis we found 41,380 employees eligible to retire based on birth date AND hire date. However, the retiring titles were only figured on birth dates which made the number jump to 72,458. A query should be done to match those statistics for the retiring titles and get a more accurate picture as to what roles need to be filled.

#### The Mentorship eligibility criteria search should be expanded to include a 3 year span to match the retiring employee criteria. It can be broken down by year to determine if there are more candidates to be groomed and what the new gap is for roles needing to be possibly filled by external candidates.

#### Another query for mentorship eligibility should be by title. This will be able to show what roles they are currently in and determine what role they can most easily transition into.

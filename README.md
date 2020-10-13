# School District Analysis
Module 4

## Overview of Project

This analysis has been conducted to support the Chief Data Scientist for the School District in presenting important, focused information to the Superintendent and the School Board so that the upmost, forward thinking decisions can be made for the District's upcoming year's schools' budget and top priorities. Data sets were provided offering a detailed look into performance trends and patterns based on the student populations' standardized test scores for math and reading along with a variety of information about the schools they attend (i.e.: student funding, size, type, and budget). The completed task here shows diligent, aggregated data to provide a variety of snapshots into the results.

## Results

<li>District Summary</li>

<img src="Resources/district_summary.png" alt="District Summary">

The District Summary provides a snapshot (below) to reflect the amount of schools located within the District, how many students attend these schools, the total budget; along with the average standardized test scores and the passing percentage based on the student population. Each student's test data and school's profile information were combined to create one unified source of data, this data was cleaned and organized to ensure that the merging of data would not cause errors in the analysis. Each student and school's contribution to the data set affect the overall outcomes as any incomplete or incorrect data would not produce accurate results. 

<li>School Summary</li>

<img src="Resources/cchool_summary.png" alt="School Summary">

The School Summary allows an overview of each school within the District. Each school is provided as an index and is accompanied by a variety of attributes to include the type, total student count, the school's budget, the school's per student budget, the average score of the standardized tests, and the school's percentage of those test that were of a passing grade (a 70% or higher). The attributes allow you to compare how one school attribute can affect the test scores of the students. 

<li>Replacing the 9th Graders at Thomas High School and its effect on THS's performance relative to other schools</li>

<img src="Resources/THS_revised_school_summary.png" alt="School Summary - with THS revision">

As reflected in the above School Summary snapshot - Thomas High School produced some of the lowest percentages of passing scores in the standardized test results. When removing the test scores of THS's 9th graders; therefore, revising the THS data to reflect 10th - 12th graders only allowed for THS to move from the lower performing schools to the 2nd highest performing school. 

<li>Additional effects of the revised Thomas High School's student population</li>
<table>
<tr>
<th><B>Score Type</B></th>
<th><B>THS 9th - 12th Graders</B></th>
<th><B>THS 10th - 12th Graders</B></th>
</tr>
<tr>
<th><B>Math</B></th>
<th>66.9%</th>
<th>93.2%</th>
</tr>
<tr>
<th><B>Reading</B></th>
<th>69.6%</th>
<th>97.0%</th>
</tr>
<tr>
<th><B>Math & Reading</B></th>
<th>65.1%</th>
<th>90.6%</th>
</tr>
</table>

<ul>Math and Reading Scores by Grade</ul>
<ul>Scores by School Spending</ul>
<ul>Scores by School Size</ul>
<ul>Scores by School Type</ul>

<li>The winning candidate of the popular vote, candidate's winning vote count, and winning percentage</li>

## Summary

The Board of Election is looking for a more automated audit than what is offered through Excel; which is how the audit has been conducted previously. The goal is to more efficiently provide the election audit throughout not only the Congressional districts but also the Senatorial districts and other local elections. 

## Election-Audit Results

<li>369, 711 total votes were casted for the US Congressional election</li>
<li>The breakdown of the counties participating in the US Congressional election are:</li>
<ul>1. Denver - 82.8% with 306,055 votes</ul>
<ul>2. Jefferson - 10.5% with 38,855 votes</ul>
<ul>3. Arapahoe - 6.7% with 24, 801 votes</ul>
<li>The county with the largest voting turnout is Denver</li>
<li>The breakdown of the candidate results in the US Congressional election are:</li>
<ul>1. Diana DeGette - 73.8% with 272,892 votes</ul>
<ul>2. Charles Casper Stockham - 23% with 85,213 votes</ul>
<ul>3. Raymon Anthony Doane - 3.1% with 11,606 votes</ul>
<li>The winning candidate, determined by popular vote, is:</li>
<ul>Diana DeGette - 73.8% with 272,892 votes</ul>

<img src="Resources/election_audit_results.png" alt="Election Audit Results">

## Election-Audit Summary

The possibilities and efficiencies are a driving factor to utilizing Python over Excel for a more automated, easily edited, and organized format to provide election result based audit. The written code creates dictionaries and lists to house the the independent variables which are replaceable by re-defining the variables to suit the audit needed. The  variable assignments utilized in this program can be used to for different cities, counties, and states based on the provided election results as well as the candidate variable be representing candidates or amendments up for election by providing alternative election results and re-defining the variables. When looking at the code for collecting an item or name and then counting the votes for that particular input - your possibilities are endless of what information can be collected and tallied electronically.
 

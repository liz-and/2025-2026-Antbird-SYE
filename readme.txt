READ ME for Antbird SYE Project
Student: Liz Anderson '26
Advisor: Sue Willson
Additional Assistance from: Ivan Ramler

Files: 
- ForgBout_00_01_07_08.csv 
The data file that was used for the previous project with this data by Jackie Heitmann. This is what I started out using until I noticed there were errors with some of the data rows.

- ForgBout_Updated.csv
The same as the datafile above but with some minor modifications (changed the year on a row that was entered at 2006 and should have been 2007). Added columns with TRUE/FALSE values for the initiated and received aggression, success, and attempts variables. 

- ForgBout_FixedDuration.csv
Copy of ForgBout_Updated.csv but used to fix the duration column on the rows that are incorrect via cross referencing with the original paper data. 

- For.Bouts2007_FixedDuration.csv
In the raw folder (which is in the data folder). The original online data had the same issues, so using this document to edit it also, in case I want to use this file because it has colors, sex, etc additional columns) 

	EDITS:
	Phleg
	- Filtered by Phleg and the obsid
	- found the rows that matched up (20 consecutive bad rows)
	- edited the duration to match the paper data

	Rheg
	- Filtered by Rheg and went through each obsid. checked with the raw data file (which is still incorrect but has additional data like colors and sex to double check that the rows are correct. 
	- Note: edited the attempts from 9 to 0 on row 648.
	- Note: deleted row 599 from ForgBout_FixedDuration.csv because it didn't match up with the original data csv or paper.
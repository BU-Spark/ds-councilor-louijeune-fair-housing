Team 4

Folders:
	data: empty, not in use
	data_code: contains our ipynb file we coded on as a team and the csv file for the HDMA dataset
	deliverables: contains extra files for each deliverable such as pdfs, graphs, and answers to our questions, also contains our scrum reports

Sources:

Public HDMA Data Set & Description: https://ffiec.cfpb.gov/documentation/2021/lar-data-fields#aus-1
Public HDMA Data Browser: https://ffiec.cfpb.gov/data-browser/maps/2021?geography=state&variable=actionTaken&value=1&feature=25&mapCenter=-71.75989486403444,42.23590411086671

Work done on this project:

	This project aimed to determine if there is discrimination in the loan application for home ownership process in Boston.

	We attempted to answer this question by plotting different information such as income, loan rejection rates, loan rejection reasons, 
	and loan type sorted by different demographics such as race, sex, and age. We searched for patterns and discrepancies in the data.

	We also extended the project to look at neighborhoods with histories of redlining to see if the makeup of those neighborhoods and if we
	can gain any insight from it.

Our findings:

	We can see that there is a inequality in the loan rejection rates for white people and people of color. There are slightly higher rates of rejection for women, and younger people.
	However, we see that the income for groups with higher rejection rates is also lower, and the main reason for rejection among all groups is debt to income ratio, which opens 
	up more questions we will explore later.

	We notice that neighborhoods deemed "unsafe" by redlining are majority people of color, and neighborhoods deemed "safe" are majority white, which lines up with our hypothesis.

Questions still to be answered:

	Are the high loan rejection rates a product of discrimination or are they a product of a lower mean income in minority communities? Could that still be a form of systemic 
	discrimination, and how can that be fixed?

	What are the loan rejection rates by neighborhoods deemed "safe" and "unsafe"? Do people avoid approving loans in these areas or visa versa? What about people who try to move 
	from "unsafe" to "safe" neighborhoods?

How to set up the code:

	Make sure the HMDA dataset is in the same location as the code. Run the first cell and then make new cells using df as the Dataframe.
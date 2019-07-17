# Understanding Tables, Using Excel

*Students must use Microsoft Excel to complete this exercise and should follow along as closely as possible. A free version of Excel is available through the uniersity by downloading Office365. Instructions are at  https://answers.syr.edu/display/software/Office+365+@+Syracuse+University 

*GitHub (example at https://github.com/washingtonpost)

1. Go to https://ucr.fbi.gov/crime-in-the-u.s/2017/crime-in-the-u.s.-2017 >>> Note the various information provided 

2. Click on Violent Crime 

We won’t go through the information on this page, but if we were writing real stories about this data, understanding these caveats are essential. 

Explore the type of data available in the various tables at right by scrolling over them.

3. Click on Table 8

Reading the Data Declaration is essential when writing about this material, but we will skip that step this evening. It provides definitions of certain items in the table. For instance, you'll notice cities report rape differently. The Data Declaration explains why. 

4. Click on Download Excel 

5. Open in Excel

6. Click on Enable Editing and Enable Content if those warnings appear

7. Save as "ViolentCrime_Master"

8. Save again as "ViolentCrime_Working." 

*Note importance of data preservation and organization.  

*Note column, row, cell structure

9. Try to sort Column D -- Violent Crime. 

*Note problems with merged cells. 

*Note undesiarablity of having headlines and footnotes sort with data. 

10. Click on Row 1 (click on the actual number). 

11. Hold down shift and click on the "3" for Row 3

12. Right click and delete. 

13. Highlight full document by clicking on the triangle between the rows and columns in upper left of the table. 

14. Go to Merge and Center in the toolbar and select Unmerge Cells

15. Scroll to bottom and delete footnotes

16. Demonstrate Fill Down function with Alabama 

17. To save time, download a clean copy of the data at https://drive.google.com/open?id=1Oiu_SvF5JckQX9Vr0rx-FLgNO5BlHTMg

*Note the reoganization of the state and city columns. 

18. Let's try to sort again, this time by population. 

Note the importance of finding known data points to check validity of data. 

19. Question for the class: How many "cases" are in the dataset? How many "cases" have more than 50,000 people population.

*Note oddity of Sunriver. 

20. Create a formula to test whether Violent Crime is an aggregate number, inclusive of the other violent crime measures. =sum(e2:h2)

*Explain decision to truncate to 50,000 (Tab 2) and explore times when that would not be a smart approach.

20. Now let's sort by violent crime, using tab 2 (50K+). 

21: Questions for the class: What city has the most violent crime? Is that interesting/meaningful? How might we make it more meaningful? 

22. In N1, write vc100K 

23. In N2, write =(c2/b2)*100000

24. Highlight N2, scroll to bottom. Highlight N791. Click "Fill Down." 

25. Sort.

*Discuss findings. 

26. In o2 write =average(N2:791)  

27. What's the lead of the story so far?

28. What's your hometown, or the closest municipality to you that has 50,000 or more people. How does it compare to the national average? 

29. How about Syracuse? 

30. What else would you want to know before writing a story?

31. If time, explore pivot table to aggregate by state; explore violent crime by other rates; create a simple excel visualization comparing the "Thruway Cities" of Syracuse, Rochester, Buffalo, and Albany. 










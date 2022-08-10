# Project Summary
The eBay web scraper is a simple Python tool that gathers the titles of the 600 most recently sold listings of a search result on eBay per execution. Currently, the web scraper parses through the titles of the sold items of the search result “Vintage T Shirt.” Every word found in a title is stored and counted in an Excel document for easy data analysis, along with the month of the sale. This web scraper provides a much more versatile and detailed approach to analyzing sales on eBay than what is given to the user on eBay’s website. 
# Libraries Used
- [BeautifulSoup](https://beautiful-soup-4.readthedocs.io/en/latest/) - Web scraper used to gather the data from eBay. 
- [OpenPyXL](https://openpyxl.readthedocs.io/en/stable/) - Used to read and write the Excel file where the data is ultimately stored.
- [Tkinter](https://docs.python.org/3/library/tkinter.html) - Used to read user input. 
# Goals of the Project/Why is this useful
- The primary goal of this project is to analyze eBay sold product data in order to better understand what types of products to list, specifically in second-hand T-Shirt market.
- Although eBay gives a lot of information about the number of themes that were sold, the available themes to sort by are too general. Furthermore, the format that the data comes in makes it impossible to do deeper analysis with time trends and bar graphs. Here is a screenshot of what eBay offers for analysis:
<br><img src="https://user-images.githubusercontent.com/35280181/183777489-39fbf879-aa34-4ac7-b077-1e51f9264d0b.png" width="500"><br>
- My program lets the user easily create pivot tables and charts. Here is a pivot table that can be created in two clicks after gathering the data. In this screenshot that uses theoretical data, the columns show the number of sales in a given month for each title keyword. For example, given the sample size (default set to 600 listings per execution), T-Shirt listings on eBay containing "large" in the title sold 195 times in March. 
<br> <img src="https://user-images.githubusercontent.com/35280181/183790546-5f80cd3a-ec0d-4f01-b101-37b425f6f980.png" width="500"><br>
- Thanks to this pivot table, graphs can be used for further analysis. This is impossible to do using only eBay's data tools. In this bar graph, we can clearly see that sales of listings with "USA" in the title increase as July approaches, most likely due to the 4th of July. This is all using theoretical data, but it clearly demonstrates how the program can be used to observe trends in order to gain an advantage selling T-Shirts on eBay. 
<br> <img src="https://user-images.githubusercontent.com/35280181/183793791-debc59f2-7889-44f4-9cae-61d29cdb1c88.png" width="500"><br>

# Learning Achievements
- 
# Why “Vintage T Shirts”
-
# Drawbacks
-
# Future 
-

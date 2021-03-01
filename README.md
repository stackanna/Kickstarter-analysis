# Kickstarter-analysis
# Overview of Kickstarter Data Analysis to Uncover Trends

This is an in-depth analysis of Kickstarter campaigns broken down into different categories. Based on this data we are able to conclude what categories of kickstarter campaigns are more likely to reach their funding goals & complete a successful launch date. An overview of the project is to visualize the relationship between outcome of campaigns and the launch month.
The link below is the Parent Category Outcomes of US Kickstarters. Theatre & music were of the most popular of kickstarter campaigns and the bar graph exemplifying that is below.
https://raw.githubusercontent.com/stackanna/Kickstarter-analysis/b37042f63492a5172664f04f60ff2ba0d70aaa8f/ParentCategoryOutcomesUS.png

# Analysis & Challenges
The most challenging exoerience I encountered throughout this analysis was using the COUNTIF function. On the first attempt, the formula would be entered correctly but it would not properly reference the other sheets, which in turn would prevent the spreadsheet from appropriately updating. Additionally, I encountered a few issues with the range criteria, which would leave several cells as a "0". Therefore making it incredibly difficult to complete a correct graph that allowed to draw appropriate conclusions. I had to analyze the data and enter the data manually using filters & finish the graph using excels formulas.  

Due to the mass of the data itself, excel would often take several minutes to load a single function, if i clicked into a new cell, after thinking that I had finished the first formula, I would effectively 'erase' the entered formula whilst excel was still rendering the function. Even with a brand new Mac Os with an M1 Processor, the shear amount of data to be analyzed was quite taxing on the processor. 


# Conclusions about the Data based on Launch Date

The first conclusion we can draw about the Outcomes based on Launch Date is that the most number of successful plays were during the Summer months. The second conclusion we are able to draw based on the Launch Date is that the most amount of canceled plays were during the coldest winter month of January. You can draw a final conclusion that the plays are more willing to succeed with less canceled and failed shows during the Summer months.

https://raw.githubusercontent.com/stackanna/Kickstarter-analysis/b37042f63492a5172664f04f60ff2ba0d70aaa8f/Theatre%20Outcomes%20Based%20on%20Launch%20Date.png

https://raw.githubusercontent.com/stackanna/Kickstarter-analysis/b37042f63492a5172664f04f60ff2ba0d70aaa8f/Theatre%20Outcomes%20Based%20on%20Launch%20Date.png

- # Conclusions of Outcomes Based on Goals

The conclusion we are able to draw from the outcomes based on goals is the direct correlation between the size of the funding goal with the probablity of its success. The smaller the funding goal the higher the likelihood of the plays success. The larger the funding goal of the kickstarter campaign the higher probalility of its failure. Though there were a few exceptions, the general analysis of the data provided, and the charts generated showed the likelihood of a smaller goal being more likely to succeed.

https://raw.githubusercontent.com/stackanna/Kickstarter-analysis/main/Outcomes%20Based%20On%20Goals.png

- # Limitations of Data 

Some of the limitations of this dataset are:
-  the lack of explanation as to why the plays were canceled. It limits our ability to factor in other reasons for a plays success or failure. 
- The categories of plays are unknown leaving us unable to draw conclusions as to why specific plays are more successful than others.
- The likelihood of certain exceptions to trends, were likely influenced by subjective, non quantitative data, such as the actual quality of the content or idea or the "pitch" of more successful plays.
- The social networks of the people interacting with certain kickstarter campaigns likely influenced outcomes as well.

# Potential Graphs or Charts we could create
-  We would be able to create line graphs comparing successful kickstarter categories, drawing conclusions as to which type of entertainment is more likely to be funded. 
- We could create bar graphs to compare the months of failed kickstarter campaigns to draw conclusions as to why they failed during those times.
- We could create more in depth graphs of the parent category kickstarter campaigns to draw conclusions as to why some were more successful than the others. 

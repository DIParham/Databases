# CS-499 ePortfolio

## Enhancement Three


For Databases section of the ePortfolio, I selected to utilize restaurant data from the DAT 220 Final Project. The final project aimed to demonstrate methods of data mining and how tools, like JMP, can be used to illustrate patterns and outliers. This took place in the August of 2020, during the 20EW6 term. 


I selected this item because it would grant me the opportunity to showcase my ability and understanding of python, data bases, and data mining concepts. Through the enhancement process of this artifact, I aimed to create an interactive dashboard using pymongo, dash, Plotly, and other python imports. This artifact would be utilizing knowledge and skills learned from the CS 340: Advanced Programming Concepts course as well as the data mining techniques that were established through the DAT 220: Fundamentals of Data Mining class. Initially, I began the refinement process by importing the restaurant data into MongoDB. This showcased my understanding of MongoDB. Once that was completed, I used python (with several imports) to establish a connection to the local MongoDB server. In doing so, allowed me to build a dashboard using this data. This enhancement displayed the data in an easier to read format and incorporated a scatter plot to aid in depicting patterns in the data. 


Reflecting on the code review, I stated that I aimed to meet the following course objective: “Design, develop, and deliver professional-quality oral, written, and visual communications that are coherent, technically sound, and appropriately adapted to specific audiences and context”. However, through this artifact refinements I was also able to achieve two additional course objectives: “Employ strategies for building collaborative environments that enable diverse audiences to support organizational decision making int the field of computer science” and “Demonstrate an ability to use well-founded and innovative techniques, skills, and tools, in computing practices for the purpose of implementing computer solutions that deliver value and accomplish industry-specific goals”. The first course objective was achieved through the incorporation of the scatter plot which communicates data patterns to users. I designed the graph to change according to dropdown selection. This would allow users to compare data against various values. For instance, it would depict which age groups are more likely to purchase from the webstore, or which state has the least amount of restaurant purchases. The second course objective was achieved through the usage of commenting. This allows other programmers to better understand the intent behind the program. In doing so, it creates an opportunity for discussion and improvement. As for the last course objective, I was able to achieve this objective through the incorporation of MongoDB. I was able to showcase how I could incorporate databases like MongoDB into a program. 


This project gave me the opportunity to research topics that I had only brushed up on in previous courses. It allowed me to better understand the advanced programming concepts demonstrated in CS 340. I was able to experiment with the various graphs offered by Plotly like scatter plots and pie charts. By experimenting with the various graphs, I was able to determine which graph better illustrated the data and showcased the comparisons between data. With this enhancement, I became more familiar with the various Python imports like dash and Plotly. I was also given the opportunity to enhance my understanding of callbacks which were quite confusing for me in a previous course. 
The most challenging portion of the project revolved around linking the drop downs to the graphs and having the graphs change according to the drop down selections. This was tricky. Initially, I thought the problem was with the callbacks. After much research, I was able to conclude that the callbacks were not the issue. Rather, it was the scatter plot’s x and y values. I had set the x and y values as a specific column from the restaurant data. For instance, x was assigned to restaurant and y was assigned to state. From this experience, I learned that if I wanted the graph to alter based on drop down selections that I needed to use the drop down IDs as the x and/or y values. 
Another issue that I found was adding and saving data to MongoDB from the dashboard. I have been able to add rows to the data table however, it did not except user input. This was a challenge that required me further research and experimentation. Through this process, I had found that the "editable" parameter had not been set. The default value for this parameter is set to "False" which prevents editing within the database. By adjusting the parameter's value to "True", it resolved this issue.   

### Artifact Link:
[Enhancement Three](https://github.com/DIParham/Databases/tree/master/Databases%20Artifact)

### ePortfolio Links:
[Code Review](https://www.screencast.com/t/xoiB2GQ8Jtb7)

[Professional Assessment](https://diparham.github.io/ePortfolio/)

[Enhancement One](https://github.com/DIParham/Software-Engineering)

[Enhancement Two](https://github.com/DIParham/Data-Structures/tree/master/Enhancement2)



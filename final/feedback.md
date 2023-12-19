# Feedback on your final

**Final Score: 57/60**

The grading rubric for the final can be found in GitHub: https://github.com/paulboal/hds5210-2023/blob/main/final/final-instructions.pdf

**Functional Requirements**
* 5 points - Uses data from at least two different sources: local file, internet, web service, relational database, AWS S3, etc; and formats: CSV, JSON, database, XML, Excel, etc
* 5 points - Data from multiple sources has to be joined together at least twice
* 5 points - Data is aggregated or pivoted at least twice during the program
* 5 points - Some kind of field-level transformation is performed at least 5 times
* 5 points - The program creates 3 or more data visualizations 
* 5 points - The program serves a theoretical purpose described in documentation, that could potentially do something in healthcare or another industry of interest

**Modularity / Style**
* 15 points - The code is broken up into various functions or classes to make testing and reuse easier

**Documentation and Professionalism**
* 15 points - All functions are documented and notebook cells include annotations and explanations.


**(-1) Any functions you create should always have docstrings so that good definitions are included in teh function definition itself.**

**Just a note on using color in charts. Often bar charts use color when it isn't necessary.  Only use color if it provides some way of distiguishing things that other wise won't be easily seen.**

**(-1) Generic variable names like `merged_data1` or `merged_data2` are not acceptable.  They make it hard for the reader to understand what is going on and what this variable refers to.**

**(-1) I don't think any of your data visualizations are clearly usable**
* Scatter plot of year versus DataValue -- what is DataValue anyway? In either case, scatterplots are usually for finding a correlation between two variables.  That doesn't work with discrete variables like Year
* Your LinePlot by year seems to tell us that 2011 and 2012 are missing data?  Also, the scale makes it hard to understand why some are SO high and others are SO low.

**Overall, this is a solid final project.  There are many more opportunities to dig into this data, though.  Keep exploring and working to ask questions have useful (not just interesting) answers.**
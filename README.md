# pandas-challenge

![Fantasy](HeroesOfPymoli/Images/Fantasy.png)

### Heroes Of Pymoli Submission
The submission of this assignment does not provide justification or a vote of approval for the increasing trend of free-to-play game models featuring IAPs within the video game industry...

That being said...

I went ahead and kept this assignment submmission pretty straight forward by sticking to the main concepts we learned in lecture. Most data frames are filtered to the required columns and then grouped and given correct formatting for currency or percentage columns.

For Gender Demographics, to create exactly what was in the example solution, I had to use value_counts() in order to create a series which required me to use df.drop_duplicates() to get the unique counts for each gender. I have included the reference for this function call both in my code and at the bottom of this md file.

For all data frames, I used the .style.set_table_styles() method. I have included the reference from the pandas docs where I found it both in the code and at the bottom of this md file.

Lastly, to match the style of the example solution (OCD), I scraped the CSS style properties from the example solution page by inspecting the elements in developer mode. It's not 100% perfect but as close as I could get it. 

I have written down my descriptions of three observations into a md file within the HeroesofPymoli folder:
[Analysis-Findings](HeroesOfPymoli/analysis_findings.md)

### References
- df.drop_duplicates(): 
http://www.datasciencemadesimple.com/get-unique-values-rows-dataframe-python-pandas/

- DataFrame style: 
https://pandas.pydata.org/pandas-docs/stable/user_guide/style.html#Table-styles
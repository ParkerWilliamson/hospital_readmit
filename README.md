# hospital_readmit


****
### Exercise

Include your work on the following **in this notebook and submit to your Github account**. 

A. Do you agree with the above analysis and recommendations? Why or why not?
   
B. Provide support for your arguments and your own recommendations with a statistically sound analysis:

   1. Setup an appropriate hypothesis test.
   2. Compute and report the observed significance value (or p-value).
   3. Report statistical significance for $\alpha$ = .01. 
   4. Discuss statistical significance and practical significance. Do they differ here? How does this change your recommendation to the client?
   5. Look at the scatterplot above. 
      - What are the advantages and disadvantages of using this plot to convey information?
      - Construct another plot that conveys the same information in a more direct manner.



You can compose in notebook cells using Markdown: 
+ In the control panel at the top, choose Cell > Cell Type > Markdown
+ Markdown syntax: http://nestacms.com/docs/creating-content/markdown-cheat-sheet
****

****
### Exercise Results

A. Do you agree with the above analysis and recommendations? Why or why not?
   I do agree with the general results of a downward slope as the number of releases from a hospital increases. I do no fully agree with the conclusion drawn from that however. The existing conclusion was to merge as many hopitals as posible, but that conclusion is biased toward the influence of the much more plentible smallest hospitals. The residuals show how there is a slight upward trend as the hospitals get too large. I would say that the data supports the idea of merging hospitals up until they have about 2000 releases, where a second order fit starts to turn around. The difference of the second order line also show ther is much more variation than that just caused by size, size only accounts for about .01-.02 percent of readmissions. The linear tend seems to show the most benefit at the place where its results are the most suspect, because of lack of high datapoints the trend for that area is driven be the high volume of small hospitals and promises a higher result than it is likely to achieve. 
   
   The linear model was verified as having a 10.8%-27%, and 10%-23.5% with alpha included, statistically significant overlap which is not large enough to change policy on the high end where there are few datapoints, but hospitals with less than 500 releases having a slightly higher rate of readmintance was also confirmed by the second order function whether or not the model should be perfectly linear.
   
   
   The ECDF and histogram plots help to show some of the overlapping data and therefore are good addtions to the scatter plot.

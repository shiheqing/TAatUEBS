---------------

File: ass.ipynb

Overall mark: 65



#### Business Question

A relevant buesiness question is clearly stated. Why the question is important to the hotel industry is explained. The findings and insights obatined from data is also well demonstrated.

<u>Very good</u>

#### Data

Data selection is overall effective, with clear rationale of why the selected variables are useful to answer the proposed question. The data preprocessing is hanhdled well, as missing values are filled dropped. Basic data transformation is applied to create 'total_nights' and 'total_guests', which is useful for the analysis. More advanced data transformation can further improve this part.

<u>Good</u>


#### Visualization

The use of bar charts as a visualization tool is appropriate for answering the question. Captions and axis ticks are clearly labeled. For "cancellation Rates by Market Segment" and "Revenue Loss by Market Segment", there are duplicated bars for 'online travel agent' but with very different magnitude, which indicates some minor error from the data processing. For "Revenue Loss by Market Segment", the y-axis can be the monetary amount in a selected currency.

<u>Good</u>

<span style="color:blue">Good spot on duplicated labels. Using four bar charts often suggests a lack of variety in chart types. In this instance, a line chart would be more suitable for the last two charts, as it better illustrates the monthly trends.</span>

#### Code

The code is self-contained without errors. It is easy to follow with detailed comments.

<u>Very good</u>



-------------

File: B273478.ipynb

Overall mark: 63



#### Business Question

The business question is clearly stated and related to the data. The findings and insigits are derived from some key variables from data, which answers the question well.

<u>Very good</u>

<span style="color:blue">The report made an attempt to derive some insight, yet it mostly just states the findings, insights are somehow limited</span>


#### Data

Relevant variables are selected to answer the question. The logic of choosing the variables are clearly explained. Focusing only on non-cancelled bookings removes the potential bias, which shows good data manipulation skill. 'arrival_date_month' is mapped to 'arrival_month_num', which is good but seems not necessary, unless some further analysis based on these nuemrical features are presented. More advanced data transformation can improve this part.

<u>Good</u>

#### Visualization

Clear and meaningful visualizations are presented. Captions and legends are appropiately displayed. Two bar charts are sufficient to answer the proposed question. Improvement could  include using other plot types (e.g. pie chart, time-series plot) to demonstrate comprehensive understanding of matplotlib.
<u>Good</u>

<span style="color:blue">Here the use of bar chart is clearly not appropriate, hence we can point it out explicitly. The X-axis labels, which list each month from January to December, could be more concise by showing only quarterly labels or using abbreviated month names to reduce visual clutter.</span>


#### Code

The code is clear and easy to follow though, there needs to be some comments for better readability. In addition, there is a minor error when reading the data. The file name shuold not be the name on your local machine, otherwise it can not be imported on others' machine.
<u>Good</u>



------------

File: B272544_1_.ipynb

Overall mark: 61



#### Business Question

The business question is clearly stated and effectively answered with data. The business significance of answering it is also well explained. The evidence answering the question is structurally presented. Actionable suggestions are also provided.

<u>Very good</u>

<span style="color:blue">The insightfulness could also be enhanced to show indepth analysis. Basically, if the report spends too many words on explaining question relevance and data usage, and a few words on findings and insights, it may not be able to provide a comprehensive answer (although not always true)</span>


#### Data

Useful variables to answer the proposed question is effectively identified. Basic data manipulation is also demonstrated in order to answer the question correctly and logically, though it can be improved by using more advanced transformation according to the question context. Some data screening is also presented, but the criteria of screening needs to be appropriately justified.

<u>Good</u>

#### Visualization

The bar chart is sufficient to visualize the analysis and to answer the question, with clear title, labels and annotations. Improvement could include using more plot types to make the analysis and visualization more comprehensive.
<u>Good</u>

<span style="color:blue">Your comment on using more plot types might not be helpful unless you can specify which types to use. In this case, the issue isn't about choosing different visual types, but rather that the business question itself limits the potential for more complex visuals.</span>


#### Code

The code is overall clearly structured. However, there is an error when reading the data. You need to make sure the data file you use is also importable by others on other machines. In addition, it is recommended to write code with meaningful comments to improve readability.

<u>Good</u>

<span style="color:blue">tips on code feedback: If you find clear repetition in code, then it may indicate code is not concise and they miss the opportunity to use loops or define custom functions. On the contrary, effectively using custom functions demonstrates strong coding skills. </span>

<span style="color:blue">If students submit excessively long code (you will know what I mean when you saw them), point out that the code lacks conciseness, including exploratory processes that don't directly address the business question, making the code unnecessarily lengthy.</span>


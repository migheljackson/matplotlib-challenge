# matplotlib-challenge

Observations and Insights

The More You Measure, The Better The Outcomes: In plotting the number of observations made for each treatment regimen, I discovered that the two regimens that did by far the most observations, Capomulin and Ramicane with 230 and 228 respectively, also ended the trial with the smallest final tumor volumes. This could be due to several factors; their starting tumor volumes may have been lower overall, or their competitors were perhaps not able to complete all 45 days. Regardless, there is an interesting correlation there, so we should continue to make sure we are taking as many observations as possible in our trials.

Consistent Results is Important: I also observed in our data that our treatment of interest, Capomulin, appears to show the most consistent results in final tumor volume with an IQR of 7, as compared to 15 for Ceftamin. Because this is looking at the range and not the actual tumor volumes themselves, this removes the ambiguity around whether Capomulin subjects started with smaller tumors overall, and is a good sign that teh treatment wroks more predictably tahn others in this study.

Larger Mice, Larger Tumors: Predictably, through plotting the linear regression of tumor volume versus mouse weight, it is clear that larger mice consistently have a larger avergae tumor size. Because of this, we should also take a look to see if there is a similar relationship between final tumor volume and mouse weight as well. This will help answer whether or not we need to consider differentiated tretment based on weight.
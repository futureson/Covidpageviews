# title

text

{% include time.html %}

# The correlations between new covid cases and pageviews
Analyzing the pageviews of Wikipedia articles can give us an insight into how people are using them to share and find information during this unprecedented time. How can the spread of the diseases influence the pageview of Covid-related articles? Is it possible to use this trend to identify other diseases that might be brought by Covid? As mentioned previously, all the collected articles were divided into 3 groups manually, including Covid, non-Covid, and mental health. The figure below shows how the pageviews and new cases change over time for the 3 categories.   

<div align = center>
<img src = '/fig/timeseries.png'>
</div>

It shows that there is a significant correlation between pageviews of COVID-19-related articles and new Covid cases in that country. Before the outbreak of Covid-19, people may be searching for information on Wikipedia only out of curiosity or concern, so the pageviews were low at that time. However, with the increasing number of new cases, more and more people were seeking updated and accurate information about the pandemic. The pandemic has had a significant impact on people's lives, and it is natural for people to want to learn more about it and how it is affecting the world. As for non-Covid, and mental health, the correlations seem to be insignificant. Especially for Japan, it can be concluded that there are no correlations for these 2 categories.   
To quantify the correlations, Spearman's rank correlation coefficients were calculated to assess how well the relationships among these variables. 2 examples were given in the following figures.  
<div align = center>
<img src = '/fig/heatmap_italy.png' height = '300' > <img src = '/fig/heatmap_no.png' height = '300'>
</div>
It appears that for both Italy and Norway, Covid-related pageviews are relatively highly correlated with the trends of new cases with correlation coefficients around 0.5. As for non-Covid-related pageviews, the correlations are lower, which was what we expected because it should have nothing to do with the new pandemic. As for the mental health category, it seems to be case by case. The negative correlations can indicate that people are paying more attention to the disease itself, neglecting what they used to care about.  


# title

text

{% include time.html %}

# The correlations between new covid cases and pageviews
Analyzing the pageviews of Wikipedia articles can give us an insight into how people are using them to share and find information during this unprecedented time. How can the spread of the diseases influence the pageview of Covid-related articles? Is it possible to use this trend to identify other diseases that might be brought by Covid? As mentioned previously, all the collected articles were divided into 3 groups manually, including Covid, non-Covid, and mental health. The figure below shows how the pageviews and new cases change over time for the 3 categories. 

<div align = center>
<img src = '/fig/timeseries.png'>
</div>

It shows that there is a significant correlation between pageviews of COVID-19-related articles and new Covid cases in that country. As for non-Covid, and mental health, the correlations seem to be insignificant. Especially for Japan, it can be concluded that there are no correlations for these 2 categories.   
To quantify the correlations, Spearman's rank correlation coefficients were calculated to assess how well the relationships among these variables.

<div align = center>
<img src = '/fig/heatmap_italy.png' height = '300' > <img src = '/fig/heatmap_no.png' height = '300'>
</div>

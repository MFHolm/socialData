---
title: How did Countries Respond to the Covid-19 Outbreak?
layout: default
---

# How did Countries Respond to the Covid-19 Outbreak?

The new corona virus first emerged in the Hubei province in China in December 2019 and has since spread across the world [source](https://www.sst.dk/da/Viden/Smitsomme-sygdomme/Smitsomme-sygdomme-A-AA/Coronavirus/Spoergsmaal-og-svar/Questions-and-answers)(accessed May 15 2020). Since then more than 300,000 people have died with Covid-19 worldwide. The image below shows the death count over time 

![total dead](https://github.com/MFHolm/socialData/blob/gh-pages/fig/total_dead.png?raw=true)

The plot shows that the death count was quite low and stable until around the 20'th of March when it took of and has grown steadily since. 

There is a huge difference in how badly different countries have been affected by the virus. Some countries have seen a huge death count and the hospitals have been and are still under a lot of pressure while other countries have been almost unaffected. 

The outbreak started in China but Europe and the US are now considered epicentres for the virus. The map below shows the geographical distribution of the death count around the world. 


<iframe src="./fig/folium_map.html"
    sandbox="allow-same-origin allow-scripts"
    width="100%"
    height="400"
    scrolling="no"
    seamless="seamless"
    frameborder="0">
</iframe>

It is evident that Europe and the US are heavily affected. Now we will take a closer look at the countries with the highest death count. 


The graph below shows number of confirmed Covid-19 deaths by country for the 30 countries with the highest number of deaths. 

![dead by country](https://github.com/MFHolm/socialData/blob/gh-pages/fig/death_by_country.png?raw=true)

There are a few countries that dominate the graph namely: US, UK, Italy, France and Spain. These countries all have a death count of over 20,000 and the US has the highest death count of over 80,0000. 

However it is worth to note that the US has a much higher population than the other countries mentioned. The graph below shows the death count per million and it is quite a different picture. 



![dead by country](https://github.com/MFHolm/socialData/blob/gh-pages/fig/dead_per_mill_by_country.png?raw=true)

The plot shows that US has now moved all the way back to having the 8'th highest death count per million. When comparing countries it might be more relevant to use dead per million than total death count. 

## Government Responses to the Outbreak

We are interested in invistigating how countries responded to the virus outbreak and whether any correlation can be seen between how and when the countries responded and the later death count of the country. 

Oxford University has created a [*Government Response Tracker*](https://www.bsg.ox.ac.uk/research/research-projects/coronavirus-government-response-tracker) and have created a rich dataset documenting the countermeasures of over 100 countries. 

There is information on for instance when schools closed down, whether people are advised to stay at home and whether there are any restrictions on public gatherings. On top of this there is also a stringency index for each country for each date. This value is a summary of the stringency of the restrictions in a country. The figure below shows when countries initiated the first countermeasures. 


![first countermeasures](https://github.com/MFHolm/socialData/blob/gh-pages/fig/first_countermeasures.png?raw=true)


It can be seen that the first official countermeasures against the virus were already initiated the 1'st of January 2020. The first countermeasures are mainly restrictions on international travels from high risk areas i.e. the Hubei province in China at that time. Around the 1'st of February the majority of countries have initiated the first countermeasures. 

The graph below shows the death count for a number of selected countries over time and also shows markers for when different countermeasures were initiated. The More dark the marker is, the more severe countermeasures have been enforced.

<iframe src="./bokeh/graph.html"
    sandbox="allow-same-origin allow-scripts"
    width="100%"
    height="550"
    scrolling="no"
    seamless="seamless"
    frameborder="0">
</iframe>

It is interesting to note that for countries such as Spain and US, if you zoom in on the markers close to the foot of the graph, you can tell that there alreddy was some deaths before most of the countermeasures started to be enforced.
Compare this to Germany, and there could be an indication that when the first deaths starts to appear, it is too late to start implimenting countermeasures.
In other words, countermeasures should be implimented way more in advanced to limit the end death count.

Another thing that can be seen is, if you only look on Norway, Sweeden and Denmark. All three of these countries started countermeasures very early, but the key difference is that Sweedens markers are generally lighter. This is becourse Sweeden chose to impliment a lot lighter restrictions than Norway and Denmark did. The current number of deaths could indicate that it was an unwise move of Sweeden to not be more strickt with their countermeasures. 

This gives us an indication that countermeasures has to be both strickt and early for them to work, and the difference becomes very noticeable.

The visualisation below is an interactive visualisation that shows how the death count changed over time and at the same time showing the countermeasures for each country. 

<iframe src="./bokeh/map.html"
    sandbox="allow-same-origin allow-scripts"
    width="100%"
    height="1000"
    scrolling="no"
    seamless="seamless"
    frameborder="0">
</iframe>



## Correlation between countermeasures and death count

The visualisation below shows corelations between different countermeasures and death count. The more dark and intence the color, the more deaths pr million population does the country have.

<iframe src="./bokeh/scatter.html"
    sandbox="allow-same-origin allow-scripts"
    width="100%"
    height="1100"
    scrolling="no"
    seamless="seamless"
    frameborder="0">
</iframe>

The visualisation shows no major correlation between any specific countermeasure and death count. This means that there isn't one countermeasure that is better or worse than the others.



# Explainer Notebook

[Link to explainer notebook](https://nbviewer.jupyter.org/github/MFHolm/socialData/blob/master/Explainer_Notebook.ipynb?frush=true)

In case the link is not working correctly [this](https://github.com/MFHolm/socialData/blob/master/Explainer_Notebook.ipynb) is the direct link to the notebook on GitHub 





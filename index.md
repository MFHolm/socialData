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

<img src=".fig/first_countermeasures.png" alt="drawing" width="100%"/>

It can be seen that the first official countermeasures against the virus were already initiated the 1'st of January 2020. The first countermeasures are mainly restrictions on international travels from high risk areas i.e. the Hubei province in China at that time. Around the 1'st of February the majority of countries have initiated the first countermeasures. 




# Explainer Notebook

[Link to explainer notebook](https://nbviewer.jupyter.org/github/MFHolm/socialData/blob/master/Explainer_Notebook.ipynb?frush=true)

In case the link is not working correctly [this](https://github.com/MFHolm/socialData/blob/master/Explainer_Notebook.ipynb) is the direct link to the notebook on GitHub 



# Remove everything below this when finished





Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](./another-page.html).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# h

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

<iframe src="./bokeh/map.html"
    sandbox="allow-same-origin allow-scripts"
    width="100%"
    height="1200"
    scrolling="no"
    seamless="seamless"
    frameborder="0">
</iframe>

<iframe src="./bokeh/graph.html"
    sandbox="allow-same-origin allow-scripts"
    width="100%"
    height="1200"
    scrolling="no"
    seamless="seamless"
    frameborder="0">
</iframe>

<iframe src="./bokeh/scatter.html"
    sandbox="allow-same-origin allow-scripts"
    width="100%"
    height="1200"
    scrolling="no"
    seamless="seamless"
    frameborder="0">
</iframe>

## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```



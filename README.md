# California Wine Project 

 Project : <A href='http://nbviewer.jupyter.org/github/sametmarasli/california_winedb/blob/master/california_winedb.ipynb'>California_winedb</A><BR>


## Summary

This report provides an analysis of the quality and price of the California wines by considering different factors such as grapes, production volumes and the origins. The ratings were published in a number of issues of the Wine Spectator magazine. The dataset includes only the wines produced out of a single grape and only the wines produced in the state of California.
Methods of analysis:

    PostgreSQL is used to store the data and to handle some quick analysis.
    For statistical tests and predictive analysis Python and libraries such as pandas and scikitlearn are used.
    Check https://public.tableau.com/shared/TJ8G6NW24?:display_count=yes for an interactive dashboard

Facts and Findings:

    Most of the wine is cultivated in the North Coast area, scecifically in Napa Sonoma counties.
    Chardonnay and Sauvignon Blanc are the most frequently used grapes for white wines. Pinot Noir, Zinfandel, and Cabernet Sauvingnon are the most populer grapes for the red wines.
    The highest scored wines are A Shot in the Dark Eleven Confessions Vineyard from Sta. Rita Hills, Santa Barbara and Papa''s Block from Russian River Valley, Sonoma. In general, North Coast wines have significantly better scores. Sonoma County's wines have relatively higher scores. Cabernet Sauvingnon and Chardonay grapes yielded usually high scored wines
    The lowest scored wine is Zinfandel from Fiddletown, Amador. Wines manufactured from Zinfandel and Sauvignon Blanc grapes are mostly low scored.
    The most expensive wine is Darius II from Napa Valley, Napa by 225 dollars. In terms of areas, North Coast and Central Coast produce relatively expensive wines.
    On the other hand, the cheapest wine is called Finest Selection Reserve form Napa Valley, Napa by 10 dollars.
    Wines that should be consumed later, when they mature, seems to be more expansive than the wines thath should be consumed now, fresh in other words.

Wines with grapes from AVA regions are better

AVA's are designated wine grape-growing regions in the United States which are regulated by the government. It is similar to DOC (controlled designation of origin) which is a quality assurance label for Italian wines. Usually, DOC wines were better and you had pay a little premium.

It is the same with California. Wines produced from AVA grapes are significantly more expensive and have higher scores than wines with the other grapes.

White wines are cheaper than red wines in general. Also, white wines are produced more. But, there is no difference between red and white wines in terms of overall score.

In general white wines are cheaper for two reasons; first, red wines have more flavor elements in them than white wines do, due to the compounds that come from the skins and seeds. That allows red wines to age more than whites do. Second, white wine - especially the simpler varieties like Sauvignon Blanc are very economical to produce. In case of California wines, it is the same. White wines are significantly cheaper than red wines. But they both have similar scores in terms of taste.

Even the number of red wine producers is more than double the white wine producers, white wine production exceeds the red wine in terms of volume of cases. Average production volume of red and white wineries state that white wine producers produce more than double in average. This may be due to fact that producing white wine is cheaper and people prefer to consume more since it is more fresh, used during cooking, and white wine is the ingredient of lots of coctails.
Predictive analysis:

    A decision tree classifier separates the wines as high and low quality by looking at their scores. (above 90 high, below 90 low) The analysis states that 69 of the wines that are below 25 dollars and not from the Monterey and San Benito counties are low quality. Wines that are below 47 dollars and production volumes more than 271 also have low scores.
    Most of the high-quality wines cost more than 48 dollars and or has lower production volumes specifically less than 270 cases.

Limitations:

Since the data is not collected for analytical purposes, it does not have important characteristics For example, there is not enough data to compare areas, counties and grape categories since it is not distributed evenly between categories. Most of the grape categories only have one samples. In addition, an important part of the data is not labeled in terms of location. This makes the spatial analysis weaker.


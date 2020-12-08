---
title: "BarBeerDrinker"
excerpt: "A relational database of bars, beers, drinkers, and their transactions, queried with MySQL with an interactive UI hosted on AWS"
collection: portfolio
---

# BarBeerDrinker

## View on GitHub &nbsp; <a href="https://github.com/ggdurrant/BarBeerDrinkerGroup67"> <img src="https://github.com/favicon.ico" alt="GitHub" width="25"> </a>

A web application built with Python, Flask, and Angular. The relational database created and queried with MySQL. Shows bars, beers, drinkers, and their transactions in NJ and the tri-state area, with abilitiy to view queries such as the most popular beers in a bar, or the most frequented time of day. 

Several tens of thousands of transactions were created with transaction ID, date, time, bar, drinker, price, tip, list of items bought. These can be viewed in the aggregate or interacted with to find the most common bars, beers, and drinkers for each category, as well as time of day, months, quantity, and total costs of these cumulative transactions. Drinkers have a list of likes as well, so that they only like specific bars and beers.  

The data was first generated, with hundreds of thousands of transactions, and then only transactions which meet the following patterns were selected:
 - drinkers only frequent bars they like
 - drinkers only purchase beers they like
 - drinkers only frequent bars in the same state as them
 - transactions can only be issued during a bar's open hours
 - beers can vary in price from bar to bar, but remain consistently more or less expensive than their fellow beers
     * if Stella Artois is $5 and Bud Light is $3 in one bar, Stella must cost more than $6 in a bar where Bud Light is $6

And examples of web app's pages, and the queries that can be automatically viewed: 

![Home](/images/homePage.JPG)

![Bar1](/images/bar1.JPG)

![Bar2](/images/bar2.JPG)

![BeerHome](/images/beerHome.JPG)

![Beer1](/images/beer1.JPG)

![Drinker1](/images/drinker1.JPG)

![Drinker2](/images/drinker2.JPG)

# A Road Trip of the Top Breweries in 2017 Routed Algorithmically.

This work follows in the footsteps of [Nathan Yau][yau] from his article, "[Top Brewery Road Trip, Routed Algorithmically][flowingdata]" and is updated with the latest data for 2017's top brewers according to RateBeer.

The output here is based on a Python script created by [Randal Olson][olson] which uses [genetic algorithms][genetic-algo] and the [Google Maps API][google] to plot the most efficient road trip for visiting the top breweries in the conterminous United States.

The data is based on [RateBeer's 2017 Top Brewers in the World][top-brewers] data set, published on January 30th 2018. Like Nathan, I removed Evil Twin as they remain a gypsy brewery and Anchorage Brewing Company in Alaska because it is "a bit of a hike". I also learned that Stillwater Artisanal is "permanently closed" according to Google Maps so that was removed as well for the time being until its status can be confirmed.

The trip includes **11,025 miles** and **60 breweries**.

![screenshot 2018-05-23 17 01 44](https://user-images.githubusercontent.com/1696777/40454130-8be89c6e-5eb5-11e8-96f4-aa54482df266.png)

*Click [here][map] for an interactive map.*

### The Most Efficient Route

```
Victory Brewing Company, PA
Tired Hands Brewing Company, PA
Other Half Brewing, NY
Tree House Brewing Company, MA
Jack's Abby Brewing, MA
Trillium Brewing Company, MA
Maine Beer Company, ME
Allagash Brewing Company, ME
Hill Farmstead Brewery, VT
Brewery Ommegang, NY
Voodoo Brewing, PA
Hoppin Frog Brewery, OH
Jackie O's Pub & Brewery, OH
Schramm's Mead, MI
Founders Brewing Company, MI
Bell's Brewery, MI
Three Floyds Brewing Company, IN
Goose Island Beer Company, IL
Pipeworks Brewing Company, IL
Half Acre Beer Company, IL
Pips Meadery, IL
New Glarus Brewing Company, WI
Toppling Goliath, IA
Surly Brewing Company, MN
Fremont Brewing Company, WA
Hair of the Dog Brewing Company, OR
De Garde Brewing, OR
Deschutes Brewery, OR
Sierra Nevada Brewing Company, CA
Russian River Brewing, CA
Lagunitas Brewing Company, CA
Cellarmaker Brewing Company, CA
Almanac Beer Company, CA
Sante Adairius Rustic Ales, CA
Firestone Walker Brewing, CA
The Bruery, CA
Bottle Logic Brewing, CA
Port Brewing Company, CA
Stone Brewing, CA
Abnormal Beer Company, CA,
Mikkeller Brewing San Diego, CA
AleSmith Brewing Company, CA
Ballast Point Brewing Company, CA
Modern Times Beer, CA
Alpine Beer Company, CA
Superstition Meadery, AZ
Casey Brewing and Blending, CO
Avery Brewing Company, CO
Crooked Stave Artisan Beer Project, CO
Prairie Artisan Ales, OK
Boulevard Brewing Company, MO
Side Project Brewing, MO
Perennial Artisan Ales, MO
Angry Chair Brewing, FL
Cigar City Brewing, FL
Cycle Brewing, FL
J. Wakefield Brewing, FL
Funky Buddha Brewery, FL
Westbrook Brewing, SC
Dogfish Head Brewery, DE
```

### Top brewers of the world by country

Count | Name
-----: | ----
64 | USA
8 | England
6 | Belgium
4 | Canada
4 | Denmark
3 | Netherlands
3 | Sweden
2 | Norway
2 | Poland
2 | Scotland
1 | Estonia
1 | Greece

### Top brewers by state in the USA

Count | Name
-----: | ----
17 | California
5 | Florida
4 | Illinois
4 | Michigan
3 | Massachusetts
3 | Colorado
3 | Pennsylvania
3 | Oregon
3 | New York
3 | Missouri
2 | Maine
2 | Ohio
1 | Vermont
1 | South Carolina
1 | Oklahoma
1 | Alaska
1 | Washington
1 | Maryland
1 | Iowa
1 | Indiana
1 | Delaware
1 | Arizona
1 | Minnesota
1 | Wisconsin




[yau]:http://flowingdata.com/about-nathan
[flowingdata]:http://flowingdata.com/2015/10/26/top-brewery-road-trip-routed-algorithmically/
[olson]:http://www.randalolson.com/2015/03/08/computing-the-optimal-road-trip-across-the-u-s/]
[top-brewers]:https://www.ratebeer.com/ratebeerbest/BestBrewers-World2018.asp]
[google]:https://cloud.google.com/maps-platform/
[genetic-algo]:https://en.wikipedia.org/wiki/Genetic_algorithm
[map]:https://paglia.org/beer-trip
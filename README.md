# A Quick End-of-2016 Journey through Open Geospatial Data of Canada and its places.
_A Future article. I intend to publish this on a few sites and places including Medium, Go Geomatics and Canadian GIS._

This will become an article that I'm laying down for the end of the year. It's a list of Canadian data sources. I also intend on updating the Canadian Open Data Wiki with these links.


## Introduction

Recently, I read a long article (http://www.gogeomatics.ca/magazine/easy-access-to-data-the-cgdi-initiative.htm) about the Canadian Geospatial Data Infrastructure (CGDI) that seeks to be, among many things, relevant. While they recently updated the site to reflect changes to the Government of Canada's own Open Data infrastructure, they only offer a small glimpse of what's on offer for Open Data in Canada. This is a shame, because there's very few resources that talk about the various open data offerings that cover Canada, whether held in Canada or outside. Of the few, they are either poorly-engineered, out of date, or sometimes both. I won’t promise this article will be accurate when you read it, nor will I promise the best user experience of this article. Instead, I’m going to offer you a snapshot of open geospatial data that covers Canada, and how I see it at this moment at the end of 2016…

 ## Aggregators

This isn’t the first attempt at throwing all the data together in one location for all of Canada. First, the Government of Canada has thrown their hat into the ring sometime ago with the [Open Government Programs in Canada Map](http://open.canada.ca/en/maps/open-data-canada) as part of their Federal Government Webpage overhaul. The map on the page is excellent at letting individuals know which parts of the country support Open Data, and it has a calendar for events. The downside is that both that it relies on user input, and the openlayers map prevents you from selecting communities which are adjacent to each other. Watch below as I fail to reach surrey in the same time it takes another user to google “Open Data Surrey”.

[gif that displays my frustration with obtaining surrey]( https://raw.githubusercontent.com/brianbancroft/OpenCanadaGeoData/master/files/
nosleeptilsurrey.gif)

There are two other notable aggregators. One worth mention is [Data Libre - By Civic Access](http://datalibre.ca). It’s a blog that offers not only the data, but resources that encourage of dissemination, resources on how to use various bits of data, and examples of this data being used. The second aggregator is another global open data map that is decently-designed, but isn’t always curated. [Open Data Inception(Global)](https://opendatainception.io/). 

## National-Level things!

[Geogratis](https://www.nrcan.gc.ca/earth-sciences/geography/topographic-information/free-data-geogratis/11042) - A maze of federal government data. Unlocking the ability to navigate through this site (or more recently, just using the geospatial extraction tool) unlocks all the basic data you need to start on that nice mapping project. Alternatively, learning the National Topographic System (NTS) and using this [well-curated FTP site](http://ftp.geogratis.gc.ca/pub/) is an easy way to get to the data you need.
[Geobase] (http://geobase.ca) - This was once a multi-agency organization that assembled, and maintained various national-level datasets. As Geogratis stepped up [(real source for Geobase Data)](http://geogratis.gc.ca/api/en/nrcan-rncan/ess-sst/$categories?scheme=&q=Geobase), it's become less clear what GeoBase provisions.

## At the province and below!
At this point, we should all know that Canada is but a federation of provinces that play their own game according to their own situation. As a result, there are provinces which are very open about their data (BC and Ontario), there are provinces that are using it to support both community and industry (Alberta), there are provinces that are starting, holding off, or walking away from the open data game. Here's a list of all the provinces and their data holdings:

### British Columbia - [data](https://data.gov.bc.ca/)
BC has a older system that processes its data. While some of the UI may be difficult to understand at the start, they have a decent customer service team and dedicated individuals who are part of the community. In addition to the provincial government, many communities boast an open data portal as well as the only Aborginal nation in Canada! The following is a list:

#### GTFS Feeds
* [BC Transit GTFS Data](https://bctransit.com/*/footer/open-data)
* [Translink (Greater Vancouver) Data API](https://developer.translink.ca/)

#### Regions/Towns/Cities/Etc
Unlike other large cities, Victoria and Vancouver aren't amalgamated. This means that the data which is covered in the city's open data portal doesn't cover the entire metropolitan area.

* [Nanaimo](http://data.nanaimo.ca/)
* [Cowichan Valley](http://www.cvrd.bc.ca/2024/Geospatial-Data)
* [North Cowichan](http://data.northcowichan.ca/)
* [Capital Regional District](https://www.crd.bc.ca/about/data)
* [Victoria](http://www.victoria.ca/EN/main/city/open-data-catalogue.html)
* [Saanich](http://www.saanich.ca/EN/main/local-government/data-catalogue-1.html)
* [North Vancouver](http://geoweb.dnv.org/data/)
* [Qualicum Beach](http://maps.qualicumbeach.com/qbgis/)
* [(Vancouver) Islands Trust](http://mapfiles.islandstrust.bc.ca/DATA/IT/)
* [Surrey](http://www.surrey.ca/city-services/658.aspx)
* [Langley](https://data.tol.ca/)
* [Chilliwack](http://www.chilliwack.com/main/page.cfm?id=2329)
* [Regional District of Central Okanagan](http://www.regionaldistrict.com/your-services/mapping-gis.aspx)
* [Regional District of Okanagan](http://www.rdos.bc.ca/departments/information-services/open-data-downloads/)
* [Regional District of North Okanagan] (http://www.rdno.ca/index.php/maps/digital-data)
* [Regional District of Okanagan-Similkameen](http://www.rdos.bc.ca/departments/information-services/open-data-downloads/)
* [District of Peachland](http://peachland.rdco.opendata.arcgis.com/)
* [Westbank First Nation](http://wfn.rdco.opendata.arcgis.com/)
* [Kamloops] (http://www.kamloops.ca/downloads/maps/launch.htm)
* [Kelowna] (http://www.kelowna.ca/CM/Page3936.aspx)
* [Vernom] (https://www.vernon.ca/government-services/maps-gis/open-data-catalogue)
* [Prince George] (http://data.cityofpg.opendata.arcgis.com/)
* [Nelson] (http://data.nelsoncity.opendata.arcgis.com/)

### Alberta [1](http://opendataareas.ca) - [2](http://altalis.com/) - [3](https://open.alberta.ca/opendata)
Alberta, like BC, supports the distribution of open data for social issues as well as mapping, but also boast high-end datasets which includes some of the most precise digital elevation you could obtain for free in Canada! Unlike the rest of Canada, Alberta appears unique in using private industry to deal with open data through a partnership culminated in AltaLIS. 

#### GTFS Feeds
* [Edmonton](https://www.edmonton.ca/ets/ets-data-for-developers.aspx)
* [Calgary](https://transit.land/feed-registry/operators/o-c3nf-calgarytransit)

#### Regions/Towns/Cities/Etc
* [Red Deer](http://data.reddeer.ca/)
* [Grande Prairie](https://data.cityofgp.com/)
* Grande Prairie County: [1](http://www.countygp.ab.ca/EN/main/community/maps-gis/open-data/data.html) [2](http://data.cogp.opendata.arcgis.com/)
* [Edmonton](http://data.edmonton.ca)
* [Edmonton - Capital Region](http://crb.capitalregion.opendata.arcgis.com/datasets)
* [Calgaery](https://data.calgary.ca/browse)
* [Medicine Hat](http://www.medicinehat.ca/index.aspx?page=392)
* [Calgary Regional Partnership](http://www.calgaryregionopendata.ca/browse/1258)
* [Airdie](http://www.calgaryregionopendata.ca/browse/2939)
* [Cherstermere](http://www.calgaryregionopendata.ca/browse/4856)
* [Banff](http://www.calgaryregionopendata.ca/browse/9545)
* [Black Diamond](http://www.calgaryregionopendata.ca/browse/3633)
* [Canmore](http://www.calgaryregionopendata.ca/browse/3539)
* [Cochrane](http://www.calgaryregionopendata.ca/browse/2843)
* [High River](http://www.calgaryregionopendata.ca/browse/6849)
* [Irricana](http://www.calgaryregionopendata.ca/browse/3653)
* [Nanton](http://www.calgaryregionopendata.ca/browse/3879)
* [Okotoks](http://www.calgaryregionopendata.ca/browse/3776)
* [Strathmore](http://www.calgaryregionopendata.ca/browse/7147)
* [Turner Valley](http://www.calgaryregionopendata.ca/browse/3635)
* [Redwood Meadows](http://www.calgaryregionopendata.ca/browse/6806)
* [Lethbridge](http://opendata.lethbridge.ca/)
* [Strathcona](https://data.strathcona.ca/)

### Saskatchewan
Saskatchewan contains open data resources provided by myriad provincial authorities, but it isn't aggregated except at sites such as [Open Data Saskatchewan](opendatask.ca), an advocacy which hasn't updated its list within the last two years.


#### Regions/Towns/Cities/Etc
* [Regina](http://open.regina.ca/)
* [Saskatoon](http://opendata-saskatoon.cloudapp.net/)
* [Swift Current Lidar Project](http://open.canada.ca/data/en/dataset?q=Swift+Current&keywords=Floods&sort=metadata_modified+desc)

### Manitoba
There appears to be a open data site, but it hasn't been updated since 2014. [Site](mli2.gov.mb.ca). Warning: It doesn't have a valid security certificate. I guess I'll say mean things, but offer a glimpse of hope..?

#### Regions/Towns/Cities/Etc
* [Winnipeg](https://data.winnipeg.ca/)
* [Brandon](http://opengov.brandon.ca/OpenDataService/opendata.html)


### Ontario
Ontario has a well-developed open data catalogue and a strong community that promotes the use and critique of open data. The province holds most of its open geodata on their [Open Data Catalogue](https://www.ontario.ca/search/data-catalogue?sort=asc).

#### GTFS Feeds
  * [Thunder Bay](http://www.thunderbay.ca/living/getting_around/thunder_bay_transit/developers_-_open_data.htm)

#### Initiatives
  * [Regional Ecological Data Collection Project](http://redcp.matawa.opendata.arcgis.com/)

#### Regions/Towns/Cities/Etc
* [Toronto](http://www1.toronto.ca/wps/portal/contentonly?vgnextoid=9e56e03bb8d1e310VgnVCM10000071d60f89RCRD)
* [Ottawa](http://data.ottawa.ca/)
* [Hamilton](https://www.hamilton.ca/city-initiatives/strategies-actions/open-accessible-data)
* [Guelph](http://open.guelph.ca/open-data-guelph/)
* [Thunder Bay](http://www.thunderbay.ca/Living/Getting_Around/Thunder_Bay_Transit/Developers_-_Open_Data.htm)
* [London](http://london.ca/opendata)
* [St Catherines](https://www.stcatharines.ca/en/Niagara-Open-Data.asp)
* [Chatham-Kent](http://chathamkentopendata.chatham-kent.opendata.arcgis.com/)
* [Kitchener](http://www.kitchener.ca/en/insidecityhall/open-data.asp)
* [Brampton](http://open.brampton.ca/)
* [Peterborough](https://www.peterborough.gov.uk/council/council-data/open-data/)
* [Huron County](http://huroncounty.huron.opendata.arcgis.com/)
* [Haldimand County](http://opendata.haldimandcounty.on.ca/)
* [Kingston](https://www.cityofkingston.ca/explore/data-catalogue)
* [Sudbury](https://www.greatersudbury.ca/inside-city-hall/open-government/open-data/)
* [Mississaugua](http://data.mississauga.ca/)
* [North Frontenac](http://data.nftwp.opendata.arcgis.com/)
* [Windsor](http://www.citywindsor.ca/opendata/Pages/Open-Data-Catalogue.aspx)
* [Burlington](http://cob.burlington.opendata.arcgis.com/)
* [Waterloo](http://www.waterloo.ca/en/government/opendata.asp)
* [Region of Waterloo](http://www.regionofwaterloo.ca/en/regionalgovernment/OpenDataHome.asp)
* [Peel Region](http://opendata.peelregion.ca/)
* [York Region](http://www.york.ca/wps/portal/yorkhome/yorkregion/yr/statisticsanddata/opendata/opendata/!ut/p/a1/jZDBTsMwDIafZYceabywrmG3UARpu6ncluWCsi1Li0pSJWGVeHrCxGUI2Hyyrc_2_xsJxJEw8thpGTprZP9Vi_lLSZ9KxmqomhkpgEJDK5wTIHUegU0E4I-gcGm-uuIAdqtipZEYZGhvOnOwiPsQFfrQ7bw0-70MEnE7KPMjWyNxWo_xbM6mBVTAGgLlY_6cPRA2hSK7ANT4G_jHYHSge7s9PWtDzfaWRKlOHZRTLn13sd2GMPhFAgmM45hqa3Wv0p1M4LeJ1vqA-BmIhjf-sby_K1-z_rikk8knfCdzrg!!/dl5/d5/L2dBISEvZ0FBIS9nQSEh/)
* [Welland](https://www.welland.ca/open/Opendata.asp)
* [Oakville](http://www.oakville.ca/data/catalogue.html)
* [Grey County](http://opendata.grey.ca/)
* [Niagara Falls](https://www.niagarafalls.ca/services/open/data)
* [Niagara Region](http://niagararegion.ca/government/opendata/)
* [Milton](http://icreateopendata.public.esolutionsgroup.ca/)


### Québec
This is where I'll talk a little bit in French (then english) about the state of the province. I'll also strive to be bilingual for new brunswick.
[Données Québec](https://www.donneesquebec.ca/fr/)

#### GTFS Feeds
* [Montreal](https://amt.qc.ca/fr/a-propos/donnees-ouvertes)

#### Régions/Villes/Etc
* [Ville de Quebec](http://donnees.ville.quebec.qc.ca/catalogue.aspx)
* [Montréal](http://donnees.ville.montreal.qc.ca/dataset)
* [Sherbrooke](https://www.ville.sherbrooke.qc.ca/services-municipaux/service-de-la-planification-urbaine-et-du-developpement-durable/geomatique/donnees-geomatiques/)
* [Gatineau](http://www.gatineau.ca/donneesouvertes/donnees_ouvertes_en.aspx)
* [St Roch Richelieu](http://data.strochrichelieu.opendata.arcgis.com/)
* [Shawinigan](http://donnees.shawinigan.opendata.arcgis.com/)

### New Brunswick
This past April, the Premier of New Brunswick [News Release](http://www2.gnb.ca/content/gnb/en/news/news_release.2016.04.0334.html). You can see their young [data catalogue](http://www.snb.ca/geonb1/e/DC/catalogue-E.asp) is at its starting stages. With luck it will flourish as time goes by. I need to be bilingual here as well. 

* [Saint John](http://www.saintjohn.ca/en/home/cityhall/financeadmin/informationtechnology/opendata/default.aspx)
* [Fredricton](http://www.fredericton.ca/en/city-hall)
* [Miramichi](http://data.gis-sigmiramichi.opendata.arcgis.com/)

### Nova Scotia
* [Data Catalogue](https://data.novascotia.ca/)
* [GeoNova](https://geonova.novascotia.ca/)


#### Regions/Cities/Etc
* [Halifax](http://www.halifax.ca/opendata/)
* [East Hants](http://data.easthants.opendata.arcgis.com/)


### Prince Edward Island
[GIS Data Catalogue](http://www.gov.pe.ca/gis/)

### Newfoundland and Labrador
[Open Data NL](http://opendata.gov.nl.ca/)

### Yukon Territory
* [GeoYukon](http://mapservices.gov.yk.ca/GeoYukon/)

#### Whitehorse
* [Whitehorse](http://data.whitehorse.ca/)

### Northwest Territory

* [NT Geoscience](http://www.nwtgeoscience.ca/our-data-and-searching-tools)
* [Yellowknife](https://www.yellowknife.ca/en/discovering-yellowknife/Open-Data.asp)

### Nunavit

_As of right now, there appears to be no collection of data for nunavit in the open held by a provincial agency or below_


## All of Canada, from outside Canada or by the best of Canada
There are some _stellar_ sources of data which exists outside of Canada with a global reach. I enjoy using this data and so can you!

  1. First, there's NASA's Earth Explorer [USGS Earth Explorer](earthexplorer.usgs.gov). Unlike the Canadian open data offerings, there are series of individual scenes from the entire Landsat catalogue, digital elevation by map selection as opposed to NTS Tile, and some older orthophotography if you live close to the US Border. It requires an account, but is entirely worth it.
  2. [Geofabrik](Geofabrik.de). This is a site that allows you to download data from OpenStreetMap, the map which you can (and should!) edit.
  3. [Remote Pixel](https://remotepixel.ca/projects/satellitesearch.html) by Vincent Sarago [Twitter](https://twitter.com/_VincentS_)



(More stuff goes here)

## A final call to action.

There is a Wikipedia page that sits unloved, and out of date. If you enjoy using open geodata, and if you love sharing your knowledge about these sources to the world, consider adding a link of your favorite open data portal to this page: [Wikipedia Article on Canadian Open Data](https://en.wikipedia.org/wiki/Open_data_in_Canada). It doesn't have to be geospatial.  


#### Thanks to all contributors! 
Making lists is a long process. There's a few people who took their time and offered a few links and hints. They are (in no particular order):
  * [_Mapperz_](https://twitter.com/mapperz)
  * [Vincent Sargaro](https://twitter.com/_VincentS_)
  * [Dave MacLean](https://twitter.com/DaveAtCOGS)
  * [Peter Rushforth](https://twitter.com/prushforth)

# A somewhat Incomplete Journey through Open Geospatial Data of Canada and its places.

## Why another List of OpenGeoData?

Recently, I read a long article (http://www.gogeomatics.ca/magazine/easy-access-to-data-the-cgdi-initiative.htm) about the Canadian Geospatial Data Infrastructure (CGDI) that seeks to be, among many things, relevant. While they recently updated the site to reflect changes to the Government of Canada's own Open Data infrastructure, they only offer a small glimpse of what's on offer for Open Data in Canada. This is a shame, because there's very few resources that talk about the various open data offerings that cover Canada, whether held in Canada or outside. Of the few, they are either poorly-engineered, out of date, or sometimes both. I won’t promise this article will be accurate when you read it, nor will I promise the best user experience of this article. Instead, I’m going to offer you a snapshot of open geospatial data that covers Canada, and how I see it at this moment at the end of 2016…

## A List of some Aggregators

This isn’t the first attempt at throwing all the data together in one location for all of Canada. First, the Government of Canada has thrown their hat into the ring sometime ago with the [Open Government Programs in Canada Map](http://open.canada.ca/en/maps/open-data-canada) as part of their Federal Government Webpage overhaul. The map on the page is excellent at letting individuals know which parts of the country support Open Data, and it has a calendar for events. The downside is that both that it relies on user input, and the openlayers map prevents you from selecting communities which are adjacent to each other. Watch below as I fail to reach surrey in the same time it takes another user to google “Open Data Surrey”.

<img width="981" alt="image that displays my frustration with obtaining surrey" src="https://raw.githubusercontent.com/brianbancroft/OpenCanadaGeoData/master/files/trygetsurrey.gif">
_No that is as far as you can zoom in..._

There are two other notable aggregators. One worth mention is [Data Libre - By Civic Access](http://datalibre.ca). It’s a blog that offers not only the data, but resources that encourage of dissemination, resources on how to use various bits of data, and examples of this data being used. The second aggregator is another global open data map that is decently-designed, but isn’t always curated. [Open Data Inception(Global)](https://opendatainception.io/). 

## Some National-Level things!

[Geogratis](https://www.nrcan.gc.ca/earth-sciences/geography/topographic-information/free-data-geogratis/11042) - A maze of federal government data. Unlocking the ability to navigate through this site (or more recently, just using the geospatial extraction tool) unlocks all the basic data you need to start on that nice mapping project. Alternatively, learning the National Topographic System (NTS) and using this [well-curated FTP site](http://ftp.geogratis.gc.ca/pub/) is an easy way to get to the data you need.
[Geobase] (http://geobase.ca) - This was once a multi-agency organization that assembled, and maintained various national-level datasets. As Geogratis stepped up [(real source for Geobase Data)](http://geogratis.gc.ca/api/en/nrcan-rncan/ess-sst/$categories?scheme=&q=Geobase), it's become less clear what GeoBase provisions.  

## At the province and below!
At this point, we should all know that Canada is but a federation of provinces that play their own game according to their own situation. As a result, there are provinces which are very open about their data (BC and Ontario), there are provinces that are using it to support both community and industry (Alberta), there are provinces that are starting, holding off, or walking away from the open data game. Here's a list of all the provinces and their data holdings:

### British Columbia - [data](https://data.gov.bc.ca/)
BC has a older system that processes its data. While some of the UI may be difficult to understand at the start, they have a decent customer service team and dedicated individuals who are part of the community. In addition to the provincial government, many communities boast an open data portal as well as the only Aborginal nation in Canada! The following is a list:

#### GTFS Feeds
  * [BC Transit (minus Vancouver) GTFS Data](https://bctransit.com/*/footer/open-data)
  * [Translink (Greater Vancouver) Data API](https://developer.translink.ca/)

#### Regions/Towns/Cities/Etc
Unlike other large cities, Victoria and Vancouver aren't amalgamated. This means that the data which is covered in the city's open data portal doesn't cover the entire metropolitan area.

  * [Nanaimo](http://data.nanaimo.ca/)
  * [Cowichan Valley](http://www.cvrd.bc.ca/2024/Geospatial-Data)
  * [North Cowichan](http://data.northcowichan.ca/)
  * [Capital Regional District](https://www.crd.bc.ca/about/data)
  * [Victoria](http://www.victoria.ca/EN/main/city/open-data-catalogue.html)
  * [Saanich](http://www.saanich.ca/EN/main/local-government/data-catalogue-1.html)
  * [Metro Vancouver](http://www.metrovancouver.org/data)
  * [City of Vancouver](http://vancouver.ca/your-government/open-data-catalogue.aspx)
  * [Richmond](http://www.richmond.ca/gis.htm)
  * [North Vancouver](http://geoweb.dnv.org/data/)
  * [Qualicum Beach](http://maps.qualicumbeach.com/qbgis/)
  * [(Vancouver) Islands Trust](http://mapfiles.islandstrust.bc.ca/DATA/IT/)
  * [Surrey](http://www.surrey.ca/city-services/658.aspx)
  * [New Westminister](http://opendata.newwestcity.ca/)
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
Alberta, like BC, supports the distribution of open data for social issues as well as mapping, but also boasts of having high-end datasets which includes some of the most precise digital elevation you could obtain for free in Canada! Unlike the rest of Canada, Alberta appears unique in using private industry to deal with open data through a partnership culminated in AltaLIS. 

#### GTFS Feeds
  * [Edmonton](https://www.edmonton.ca/ets/ets-data-for-developers.aspx)

#### Regions/Towns/Cities/Etc
  * [Red Deer](http://data.reddeer.ca/)
  * [Grande Prairie](https://data.cityofgp.com/)
  * Grande Prairie County: [1](http://www.countygp.ab.ca/EN/main/community/maps-gis/open-data/data.html) [2](http://data.cogp.opendata.arcgis.com/)
  * [Edmonton](http://data.edmonton.ca)
  * [Edmonton - Capital Region](http://crb.capitalregion.opendata.arcgis.com/datasets)
  * [Calgary](https://data.calgary.ca/browse)
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

### Manitoba [Data](mli2.gov.mb.ca)
There appears to be an open data site, but it hasn't been updated since 2014. Not only has it been recently neglected, but it's very old and broken. To get to the data, you must register. The registration process doesn't verify your email address. Once you're in, the browser warns you of a lack of a security certificate, and it's clear the CSS is gone. I've been told that the government is rebuilding their website, so there might be a big change in the data landscape for 2017.

<img src="https://raw.githubusercontent.com/brianbancroft/OpenCanadaGeoData/master/files/manitoba.png">

#### GTFS Feeds
  * [Winnipeg](http://gtfs.winnipegtransit.com/)

#### Regions/Towns/Cities/Etc
  * [Winnipeg](https://data.winnipeg.ca/)
  * [Brandon](http://opengov.brandon.ca/OpenDataService/opendata.html)

### Ontario [Data](https://www.ontario.ca/search/data-catalogue?sort=asc)
Ontario has a well-developed open data catalogue and a strong community that promotes the use and critique of open data. The province holds most of its open geodata on their catalogue.

#### GTFS Feeds
  * [Thunder Bay](http://www.thunderbay.ca/living/getting_around/thunder_bay_transit/developers_-_open_data.htm)
  * [Ottawa](http://www.octranspo.com/developers)
  * [Toronto](http://www1.toronto.ca/wps/portal/contentonly?vgnextoid=96f236899e02b210VgnVCM1000003dd60f89RCRD)
  * [Barrie](http://www.barrie.ca/Living/Getting%20Around/BarrieTransit/Pages/Barrie-GTFS.aspx)
  * [Waterloo](http://www.regionofwaterloo.ca/en/regionalGovernment/GRT_GTFSdata.asp)
  * [GO Transit - across the _Golden Horseshoe_](http://www.gotransit.com/publicroot/en/schedules/DeveloperResources.aspx)
  * [Mississaugua](http://www.mississauga.ca/portal/miway/developerdownload)

#### Initiatives
  * [Regional Ecological Data Collection Project](http://redcp.matawa.opendata.arcgis.com/)

#### Regions/Towns/Cities/Etc
  * [Brampton](http://open.brampton.ca/)
  * [Burlington](http://cob.burlington.opendata.arcgis.com/)
  * [Chatham-Kent](http://chathamkentopendata.chatham-kent.opendata.arcgis.com/)
  * [Grey County](http://opendata.grey.ca/)
  * [Guelph](http://open.guelph.ca/open-data-guelph/)
  * [Haldimand County](http://opendata.haldimandcounty.on.ca/)
  * [Hamilton](https://www.hamilton.ca/city-initiatives/strategies-actions/open-accessible-data)
  * [Huron County](http://huroncounty.huron.opendata.arcgis.com/)
  * [London](http://london.ca/opendata)
  * [Kitchener](http://www.kitchener.ca/en/insidecityhall/open-data.asp)
  * [Kingston](https://www.cityofkingston.ca/explore/data-catalogue)
  * [Milton](http://icreateopendata.public.esolutionsgroup.ca/)
  * [Mississaugua](http://data.mississauga.ca/)
  * [Newmarket](http://www.newmarket.ca/opendata)
  * [Niagara Falls](https://www.niagarafalls.ca/services/open/data)
  * [Niagara Region](http://niagararegion.ca/government/opendata/)
  * [North Frontenac](http://data.nftwp.opendata.arcgis.com/)
  * [Oakville](http://www.oakville.ca/data/catalogue.html)
  * [Ottawa](http://data.ottawa.ca/)
  * [Peel Region](http://opendata.peelregion.ca/)
  * [Region of Waterloo](http://www.regionofwaterloo.ca/en/regionalgovernment/OpenDataHome.asp)
  * [Sudbury](https://www.greatersudbury.ca/inside-city-hall/open-government/open-data/)
  * [St Catherines](https://www.stcatharines.ca/en/Niagara-Open-Data.asp)
  * [Thunder Bay](http://www.thunderbay.ca/Living/Getting_Around/Thunder_Bay_Transit/Developers_-_Open_Data.htm)
  * [Toronto](http://www1.toronto.ca/wps/portal/contentonly?vgnextoid=9e56e03bb8d1e310VgnVCM10000071d60f89RCRD)
  * [Waterloo](http://www.waterloo.ca/en/government/opendata.asp)
  * [Welland](https://www.welland.ca/open/Opendata.asp)
  * [Windsor](http://www.citywindsor.ca/opendata/Pages/Open-Data-Catalogue.aspx)
  * [York Region](http://www.york.ca/wps/portal/yorkhome/yorkregion/yr/statisticsanddata/opendata/opendata/!ut/p/a1/jZDBTsMwDIafZYceabywrmG3UARpu6ncluWCsi1Li0pSJWGVeHrCxGUI2Hyyrc_2_xsJxJEw8thpGTprZP9Vi_lLSZ9KxmqomhkpgEJDK5wTIHUegU0E4I-gcGm-uuIAdqtipZEYZGhvOnOwiPsQFfrQ7bw0-70MEnE7KPMjWyNxWo_xbM6mBVTAGgLlY_6cPRA2hSK7ANT4G_jHYHSge7s9PWtDzfaWRKlOHZRTLn13sd2GMPhFAgmM45hqa3Wv0p1M4LeJ1vqA-BmIhjf-sby_K1-z_rikk8knfCdzrg!!/dl5/d5/L2dBISEvZ0FBIS9nQSEh/)


### Québec - [Données](https://www.donneesquebec.ca/fr/)
While not as strong as Ontario, Alberta or Britsh Columbia's open data sites, Québec has a strong offering, a growing culture and many towns which are growing their own data programs. 

#### GTFS Feeds
  * [Montreal](https://amt.qc.ca/fr/a-propos/donnees-ouvertes)
  * [Longueuil](http://www.rtl-longueuil.qc.ca/en-CA/open-data/gtfs-files/)
  * [Laval](http://www.stl.laval.qc.ca/fr/stl-synchro/developpeurs/)

#### Régions/Villes/Etc
  * [Ville de Quebec](http://donnees.ville.quebec.qc.ca/catalogue.aspx)
  * [Montréal](http://donnees.ville.montreal.qc.ca/dataset)
  * [Sherbrooke](https://www.ville.sherbrooke.qc.ca/services-municipaux/service-de-la-planification-urbaine-et-du-developpement-durable/geomatique/donnees-geomatiques/)
  * [Gatineau](http://www.gatineau.ca/donneesouvertes/donnees_ouvertes_en.aspx)
  * [St Roch Richelieu](http://data.strochrichelieu.opendata.arcgis.com/)
  * [Shawinigan](http://donnees.shawinigan.opendata.arcgis.com/)

### New Brunswick - Date: [1](http://www.snb.ca/geonb1/e/DC/catalogue-E.asp), [2 (needs flash...)](http://geonb.snb.ca/li/index.html), [3 (AGOL LiDAR Catalogue)](http://geonb.snb.ca/li/index.html)
This past April, the Premier of New Brunswick [News Release](http://www2.gnb.ca/content/gnb/en/news/news_release.2016.04.0334.html). You can see their young data catalogue is at its starting stages. Since then, they've taken the grand leap of providing a large LiDAR dataset, earning the distinction of being the first province to do so!

  * [Saint John](http://www.saintjohn.ca/en/home/cityhall/financeadmin/informationtechnology/opendata/default.aspx)
  * [Fredricton](http://www.fredericton.ca/en/city-hall)
  * [Miramichi](http://data.gis-sigmiramichi.opendata.arcgis.com/)

### Nova Scotia - [1](https://data.novascotia.ca/) - [2](https://geonova.novascotia.ca/)
Nova Scotia's [Treasury Board Manual](https://novascotia.ca/treasuryboard/manuals/PDF/300CommonServices.pdf#page=1) indicates that the government is pushing the public sector towards an _"open by default"_ setting in publishing data. 

#### GTFS Feeds
  * [Halifax](http://catalogue.hrm.opendata.arcgis.com/datasets?q=transit)

#### Regions/Cities/Etc
  * [Halifax](http://www.halifax.ca/opendata/)
  * [East Hants](http://data.easthants.opendata.arcgis.com/)


### Prince Edward Island - [Data](http://www.gov.pe.ca/gis/)
Prince Edward Island provides open data since as early as 2001, when it had a civic addressing system which offers geographic data on the location of all its addresses. At the same time NB embraced open data, PEI quietly went to an open-by-default and has also removed any licensing requirement before each download. 

#### Addresses
 * [Entire Province](http://www.gov.pe.ca/civicaddress/download/index.php3)

### Newfoundland and Labrador - [Data](http://opendata.gov.nl.ca/)
Newfoundland and Labrador also are new to the open data world. They've only been active for two years  [press release](http://policymonitor.ca/privacyfreedom-of-information/newfoundland-open-government-initiative/) and spout a decent site, despite all the troubles that are ongoing in the eastern province.

#### Regions/Cities/Etc

  * [St John's](http://www.stjohns.ca/event/open-data)

### Yukon Territory - [Data](http://mapservices.gov.yk.ca/GeoYukon/)

  * [Whitehorse](http://data.whitehorse.ca/)

### Northwest Territory
_As of right now, there appears to be no territorial agency responsible for the dissemenation of open data. In the intern, NT Geoscience has offered a large portion of their geological data and findings in support of the mining industry. Also, a small group of civic hackers have collected some non-geospatial data and have assembled it [here](https://www.opennwt.ca/)_

  * [NT Geoscience](http://www.nwtgeoscience.ca/our-data-and-searching-tools)
  * [Yellowknife](https://www.yellowknife.ca/en/discovering-yellowknife/Open-Data.asp)

### Nunavit

_As of right now, there appears to be no collection of data for nunavit in the open held by a provincial agency or below_


## All of Canada, from outside Canada or by the best of Canada
There are some _stellar_ sources of data which exists outside of Canada with a global reach. I enjoy using this data and so can you!

  1. First, there's NASA's Earth Explorer [USGS Earth Explorer](earthexplorer.usgs.gov). Unlike the Canadian open data offerings, there are series of individual scenes from the entire Landsat catalogue, digital elevation by map selection as opposed to NTS Tile, and some older orthophotography if you live close to the US Border. It requires an account, but is entirely worth it.
  2. [Geofabrik](Geofabrik.de). This is a site that allows you to download data from OpenStreetMap, the map which you can (and should!) edit.
  3. [Remote Pixel](https://remotepixel.ca/projects/satellitesearch.html) by Vincent Sarago [Twitter](https://twitter.com/_VincentS_)
  4. [Transit Land](https://transit.land/). This is a community-based group that seeks to offer data for all metropolitan transit services in easilly-consumed formats. 
  5. [Transitfeeds](https://transitfeeds.com/). This is another community-driven site that seeks to offer transit data across the world, but in GTFS format.
  6. [Public Sector Digest Rankings of Open Municipalities](https://publicsectordigest.com/2016-open-cities-index-top-20-results)

## The end 

This is just a snapshot of the data I was able to capture that exists at the end of 2016. There's a good chance a lot of this data will no longer be at the link by the time you attempt to access it. Websites evolve, scopes evolve and so do agencies. If you feel like you want to carry the torch, you're very welome to pick up where I've stopped. This article was drafted on a [Github Repo](https://github.com/brianbancroft/OpenCanadaGeoData) and breaking this article apart is simple as forking the repository and making this into your own thing. I'd be happy for anyone to carry the torch, or just copy all my links into their own website or map. 

#### Thanks to all contributors! 
Making lists is a long process. There's a few people who took their time and offered a few links and hints. They are (in no particular order):
  * [_Mapperz_](https://twitter.com/mapperz)
  * [Vincent Sargaro](https://twitter.com/_VincentS_)
  * [Dave MacLean](https://twitter.com/DaveAtCOGS)
  * [Peter Rushforth](https://twitter.com/prushforth)
  * [Peter Rukavina](https://twitter.com/ruk)


<p xmlns:dct="http://purl.org/dc/terms/" xmlns:vcard="http://www.w3.org/2001/vcard-rdf/3.0#">
  <a rel="license"
     href="http://creativecommons.org/publicdomain/zero/1.0/">
    <img src="http://i.creativecommons.org/p/zero/1.0/88x31.png" style="border-style: none;" alt="CC0" />
  </a>
  <br />
  To the extent possible under law,
  <a rel="dct:publisher"
     href="brianbancroft.ca">
    <span property="dct:title">Brian Bancroft</span></a>
  has waived all copyright and related or neighboring rights to
  <span property="dct:title">An aggregation of open data links across canada</span>.
This work is published from:
<span property="vcard:Country" datatype="dct:ISO3166"
      content="CA" about="brianbancroft.ca">
  Canada</span>.
</p>

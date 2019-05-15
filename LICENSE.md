# whosonfirst-data

Who's On First is a gazetteer of places. Not quite _all_ the places in the world but a whole lot of them and, we hope, the kinds of places that we mostly share in common.

A gazetteer is a big list of places, each with a stable identifier and some number of descriptive properties about that location. An interesting way to think about a gazetteer is to consider it as the space where debate about a place is _managed_ but not decided. We call our gazetteer "Who's On First" (or sometimes "WOF" for short).

## License

Crediting Who's On First is recommended and linking back to this License is required. 

```
Data from Who's On First. <a href="http://whosonfirst.mapzen.com#License">License</a>
```

The Who's On First dataset is both original work and a modification of existing open data. Some of those open data projects **do** require attribution.

A partial listing of sources is included below. **For a full listing** see [whosonfirst-sources/README.md](https://github.com/whosonfirst/whosonfirst-sources/blob/master/sources/README.md).

When we [source](https://github.com/whosonfirst/whosonfirst-sources/) other open data projects we make best effort to indicate them (e.g.: `'src:geom':naturalearth`) and we also include the original source's properties prefixed with the following names spaces: 

* `gn` - [GeoNames](http://www.geonames.org) (CC-BY)
* `gp` - [GeoPlanet](https://developer.yahoo.com/geo/geoplanet/) Where on Earth, aka `woe` (CC-BY)
* `ne` - [Natural Earth](http://www.naturalearthdata.com) (Public Domain)
* `oa` - [OurAirports](http://ourairports.com/) (Public Domain)
* `qs` - [Quattroshapes](https://github.com/foursquare/quattroshapes/blob/master/) (CC-BY)
* `zs` - [Zetashapes](http://zetashapes.com/) (CC-BY)
* `meso` - [Mesoshapes](https://github.com/whosonfirst/whosonfirst-sources/blob/master/sources/meso.json) (CC0)

Please notify us if you believe that an open data project has not been properly noted.

Our original work is generaly indicated with properties prefixed with `wof` or is not prefixed (like `name`). 

Remember, some sources **require attribution**, some do not. Mapzen's original work, including the format and structure that allows Who's On First to operate, is made available under the [Creative Commons Zero](https://creativecommons.org/publicdomain/zero/1.0/) designation, and a shout out would be lovely.


## Sources

Who's On First makes use of a number of open data sources, some of whom **do** require attribution. Please note that original sources may be modified.

A partial listing of sources is included below. **For a full listing** see [whosonfirst-sources/README.md](https://github.com/whosonfirst/whosonfirst-sources/blob/master/sources/README.md).

### GeoNames

Properties with the `gn` prefix are from GeoNames.

**Examples:** `gn:id` for GeoNames identifier concordance, and `src:centroid_lbl:geonames` indicate the source of our label centroid is GeoNames.

GeoNames database is licenced as follows:

```
The GeoNames geographical database is available for download free of
charge under a creative commons attribution license. 
```

More details can be found at: http://www.geonames.org/about.html

### GeoPlanet

Properties with the `gp` prefix are from GeoPlanet. 

Sometimes the `woe` prefix is used instead because GeoPlanet supersedes Where on Earth (WOE) and not all data has been updated.

**Examples:** `gp:id` for GeoPlanet identifier concordance, and localized names (eg: `name:chi_p`, `name:ger_p`, and `name:kor_p`).

GeoPlanet database is licenced as follows:

```
Content licensed under Creative Commons Attribution 3.0 United States
License. Provide attribution to "Yahoo! GeoPlanet"
```

More details can be found at: http://developer.yahoo.com/geo/geoplanet/data/

### Natural Earth

Properties with the `ne` prefix are from Natural Earth.

**Example:** `ne:name` for the Natural Earth feature name.


Natural Earth is released as follows:

```
All versions of Natural Earth raster + vector map data found on this
website are in the public domain. You may use the maps in any manner,
including modifying the content and design, electronic dissemination,
and offset printing. The primary authors, Tom Patterson and Nathaniel
Vaughn Kelso, and all other contributors renounce all financial claim
to the maps and invites you to use them for personal, educational, and
commercial purposes.

No permission is needed to use Natural Earth. Crediting the authors is
unnecessary.
```

More details can be found at: http://www.naturalearthdata.com/about/terms-of-use/

### OurAirports

Properties with the `oa` prefix are from OurAirports.

**Example:** `oa:elevation_ft` for the elevation in feet.

OurAirports files are released as follows:

```
We hereby release all of these files into the Public Domain, with no
warranty of any kind — By downloading any of these files, you agree
that OurAirports.com, Megginson Technologies Ltd., and anyone involved
with the web site or company hold no liability for anything that
happens when you use the data, including (but not limited to) computer
damage, lost revenue, flying into cliffs, or a general feeling of
drowsiness that persists more than two days.
```

More details can be found at: http://ourairports.com/data/

### Quattroshapes

Properties with the `qs` prefix are from Quattroshapes.

**Examples:** `qs:id` for Quattroshapes identifier concordance and `qs:adm0` for country names. 

Who's on First doesn't always use the Quattroshapes geometry, so review that in `src:geom`. When we do, some Quattroshapes features source from friendly CC0 or Public Domain licensed projects, and others from a stricter CC-BY project: check that in the `qs_source` property. For example, `qs_source:EuroGlobalMap` means you'll need to give specific credit to one or more European national mapping agencies as further described below.

Quattroshapes are licensed as follows:

```
The quattroshapes are released by foursquare under CC-BY attribution
license.

Please include attribution in your app, site, or printed work. Sample
wording: "Includes data from foursquare quattroshapes" with a link to
this Github repo; https://github.com/foursquare/quattroshapes/
```

More details can be found at: https://github.com/foursquare/quattroshapes/blob/master/LICENSE.md

Please note the following with regard to Quattroshapes features that require attribution:

#### Additional Quattroshapes Attribution

This map database contains open data from government and other sources. Consider including the following copyright statements when using the data. 

#### Europe

EuroGeoGraphics data copyright is held by European National Mapping Agencies. 

* Austria © Bundesamt für Eich- und Vermessungswesen
* Belgium © Institut Géographique National – Belgique
* Bulgaria © Cadastre Agency, MRDPW
* Croatia © Drzavna Geodetska Uprava
* Cyprus © Lands and Surveys, Survey and Cartogr. Br.
* Czech Republic © Český úřad zeměměřický a katastrální
* Denmark © Kort og Matrikelstyrelsen
* Estonia © Maaamet
* Faroe Islands © Kort og Matrikelstyrelsen
* Finland © Maanmittauslaitos
* France © Institut National de l’Information Géographique et Forestière – France
* Georgia © National Agency of Public Registry
* Germany © Bundesamt für Kartographie und Geodäsie
* Great Britain © Ordnance Survey
* Greece © Hellenic Military Geographical Service
* Greenland © Kort og Matrikelstyrelsen
* Hungary © Földmérési és Távérzékelési Intézet
* Iceland © Landmælingar Íslands
* Ireland © Ordnance Survey Ireland
* Italy © Istituto Geografico Militare Italiano
* Latvia © Latvijas Republikas Valsts zemes dienests
* Liechtenstein © Bundesamt für Landestopographie (Switzerland)
* Lithuania © Nacionalinė žemės tarnyba
* Luxembourg © Administration du Cadastre et de la Topographie
* Malta © Malta Environment and Planning Authority (MEPA)
* Moldova © State Agency for Land Relations and Cadastre
* Netherlands © Topografische Dienst Nederland
* Northern Ireland © Ordnance Survey of Northern Ireland
* Norway © Statens Kartverk
* Poland © Główny Urząd Geodezji i Kartografii
* Portugal © Instituto Geográfico Português
* Rep. of Slovakia © Geodetick a kartografick ústav
* Romania © CNGCFT (National Center of Geodesie, Cartography, Fotogrametry and Remote Sensing)
* Serbia © Republički geodetski zavod
* Slovenia © Geodetska Uprava Republike Slovenije
* Spain © Centro Nacional de Informacion Geografica – Instituto Geográfico Nacional
* Sweden © Lantmäteriet
* Switzerland © Bundesamt für Landestopographie
* Ukraine © Research Institute of Geodesy and Cartography

#### Additional European data

* United Kingdom: Contains Ordnance Survey data © Crown copyright and database right [2012]
* Netherlands: Kadaster
* Spain: Instituto Geográfico Nacional
* France: Institut Géographique National
* Switzerland: swisstopo
* Europe-wide: European Environment Agency (EEA) [urban morphological zones 2006](http://www.eea.europa.eu/data-and-maps/data/urban-morphological-zones-2006-umz2006-f3v0)

#### Americas

* United States: US Census Bureau (Census 2010 geography files). 
* Canada: © Department of Natural Resources Canada. All rights reserved., Statistics Canada, and BC Stats
* Brazil: IBGE
* Mexico: INEGI
* Chile: Global Map of Chile © International Steering Committee for Global Mapping / Instituto Geografico Militar de Chile

#### Asia

* Indonesia: Global Map of Indonesia @ ISCGM/Indonesia
* Australian: Geoscience Australia and Australian Bureau of Statistics
* New Zealand: Land Information New Zealand
* South Africa: Global Map of the Republic of South Africa © ISCGM/State Copyright, Department of Rural Development and Land Reform, Chief Directorate of National Geo-spatial Information, Website: http://www.ngi.gov.za/
* Palestine: "Global Map of PALESTINE © ISCGM/Palestinian National Authority, Ministry of Planning. Geographic Center and Technical Support www.mop.gov.ps

### Ordnance Survey

* Contains OS data © Crown copyright and database right 2016
* Contains Royal Mail data © Royal Mail copyright and Database right 2016
* Contains National Statistics data © Crown copyright and database right 2016

### Zetashapes

Properties with the `zs` prefix are from Zetashapes.

**Examples:** If we source our default geometry from Zetashapes we say that in `src:geom: zetashapes`. We list which US Census Blocks compose the Zetashapes geometry in `zs:blockids`, and a few other properties like `zs:pop10` for population count.

Zetashapes polygons and data are subject to the following:

```
The polygons generated by this site do not have any added restrictions
beyond the base data from TIGER and Flickr.

By submitting votes to this site you are agreeing that your votes will
be public and in the public domain.

The basic source data is from US TIGER/Line Census Data which is
public domain (Q10). This site also makes use of data scraped from the
flickr api -- you should probably mention on your site if you reuse
this data that there is flickr data associated with it. 
```

More details can be found at: http://zetashapes.com/license

### Mesoshapes

Properties with the `meso` prefix are from Mesoshapes.

**Examples:** `meso:name_local` for the localized name of a place. `meso:type_loc` for the localized placetype of a feature (simple commune, prefecture, region).

Who's on First doesn't always use the Mesoshapes geometry, so review that in `src:geom`. When we do, some Mesoshapes features source from friendly CC0 or Public Domain licensed projects, and others from a stricter CC-BY project: check that in the `meso:source` property. Features sourced from mesoshapes generally fall in the `locality`, `county`, `macrocounty`, and `region` placetypes.

Mesoshapes are a product of Mapzen.

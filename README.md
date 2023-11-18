# awesome-open-transport

Awesome resources for Open-Source Software for Transport.

![Transport](docs/open-transport.png)


## Standard Tools

### Open Data Standards

Non-rail Transport

- Public Transport: [Netex](https://netex-cen.eu/), [GTFS](https://gtfs.org/), [GTFS-RT](https://gtfs.org/realtime/reference/)
- Vehicle sharing: [MDS](https://github.com/openmobilityfoundation/mobility-data-specification), [GBFS](https://github.com/MobilityData/gbfs)
- Network specification: [GMNS](https://github.com/zephyr-data-specs/GMNS)
- Conceptual: [Transmodel](https://github.com/oeg-upm/transmodel-ontology)
- Rail: [Ontorail](https://ontorail.org/), [TAP-TSI](https://tap-tsi.uic.org/), <s>[S2R-CDM]()</s>, <s>[BITRE]()</s>


### DIY Infra Setup

- Essentials: [git](https://git-scm.com/), [github](https://github.com), [docker](https://www.docker.com/)
- Reporting: [jupyter notebooks](https://jupyter.org/)
- Databases: [postgresql](https://www.postgresql.org/), [mariadb](https://mariadb.org/)
- Dashboards: [Grafana](https://grafana.com/), [Metabase](https://www.metabase.com/)

### OSGeo Ecosystem

- Server related: [Geoserver](https://geoserver.org/), [Mapserver](https://mapserver.org/), [GeoNode](https://geonode.org/)
- Visuals: [OpenLayers](https://openlayers.org/), [Cesium](https://cesium.com/)
- Applications: [QGIS](https://qgis.org/en/site/), [GRASS GIS](https://grass.osgeo.org/), [GDAL](https://gdal.org/index.html)
- Database related: [PostGIS](https://postgis.net/), [pgRouting](https://pgrouting.org/), [spatialite](https://www.gaia-gis.it/fossil/libspatialite/index)

## Mapping

### OpenStreetMap Tools

- Tools: [iD](https://wiki.openstreetmap.org/wiki/ID), [JOSM](https://josm.openstreetmap.de/)
- Querying: [Overpass Turbo](https://overpass-turbo.eu/)
- Apps: [OSMAnd](https://osmand.net/), [OrganicMaps](https://organicmaps.app/), [JungleBus](https://wiki.openstreetmap.org/wiki/Jungle_Bus_mobile_app)
- Initiative: [HOT-OSM](https://www.hotosm.org/)

Maps:
- Maps: [OpenStreetMap](https://www.openstreetmap.org/), [Kartaview](https://kartaview.org/landing), [OpenHumanitarianMap](), 
- Railway or Sea: [OpenRailwayMaps](https://www.openrailwaymap.org/), [OpenSeaMap](https://map.openseamap.org/)
- Historical mapping: [OpenHistoryMap](https://map.openhistorymap.org/), [OpenHistoricalMap](https://www.openhistoricalmap.org/)
- Aerial: [OpenAerialMap](https://openaerialmap.org/)


### Routing

- Routing Engines: [OSRM](https://project-osrm.org/), [ORS](https://openrouteservice.org/), [Valhalla](https://github.com/valhalla/valhalla), [Graphhopper](https://github.com/graphhopper/graphhopper), [Routino](https://github.com/mauricesvay/Routino), [per pedes routing](https://github.com/motis-project/ppr)
- Multimodal routing: [OTP](https://www.opentripplanner.org/), [Navitia](https://github.com/hove-io/navitia), [MOTIS](https://github.com/motis-project/motis), [digitransit](https://github.com/HSLdevcom/digitransit)
- Rail: [OpenRailRouting](https://github.com/geofabrik/OpenRailRouting), [osrd](https://github.com/osrd-project/osrd)

Simulations
- Demand estimation: [TransiTion](https://github.com/chairemobilite/transition/)
- Traffic micro-simulator: [SUMO](https://sumo.dlr.de/docs/index.html)
- Traffic data: [OpenTraffic](https://github.com/opentraffic)


### Infrastructure

- Simulation: [abstreet](https://github.com/a-b-street/abstreet), [streetmix](https://github.com/streetmix/streetmix), [matsim](https://www.matsim.org/), [abstr](https://github.com/a-b-street/abstr), [osm2streets](https://github.com/a-b-street/osm2streets)
- Estimations: [grid2demand](https://github.com/asu-trans-ai-lab/grid2demand)
- Cycling: [CyIPT](https://www.cyipt.bike/), [BikeDNA](https://github.com/anerv/BikeDNA)
- Infrastructure status: [StreetComplete](https://streetcomplete.app/?lang=en), [SmartRoadSense](https://smartroadsense.it/), <s>[tsmv]()</s>, [Mapswipe](https://mapswipe.org/en/)
- Rail: [CloudCompare](https://github.com/cloudcompare/cloudcompare), [railroad](https://github.com/GISLab-ELTE/railroad)


## Operations

### Analytics

- Python analytics: [geopy](https://geopy.readthedocs.io/en/stable/), [photon](https://github.com/komoot/photon), [geopandas](https://github.com/geopandas/geopandas), [osmnx](https://github.com/gboeing/osmnx), [geoviews](https://geoviews.org/)
- R analytics: [R-spatial](https://github.com/r-spatial), [lwgeom](https://r-spatial.github.io/lwgeom/), [stars](https://github.com/r-spatial/stars), [sfnetworks](https://luukvdmeer.github.io/sfnetworks/)
- Mobility analytics: [MobilityDB](https://github.com/MobilityDB/MobilityDB), [MoveTK](https://github.com/movetk/movetk), [MOVE](https://github.com/mschoema/move), [movingpandas](https://github.com/movingpandas/movingpandas), [scikit-mobility](https://github.com/scikit-mobility/scikit-mobility)
- GTFS Analytics: [gtfs_manager](https://github.com/spstreets/gtfs_manager), [gtfspy](https://github.com/CxAalto/gtfspy), [gtfsdb](https://github.com/OpenTransitTools/gtfsdb), [gtfstools](https://github.com/ipeaGIT/gtfstools), [GTFS-GO](https://github.com/MIERUNE/GTFS-GO)


### Solutions

- Apps: [ODK](https://getodk.org/), [Kitenerary](https://github.com/KDE/kitinerary), [TrackIt](https://github.com/flespi-software/TrackIt), [Trufi](https://github.com/trufi-association), [MyOSMatic](https://print.get-map.org/), [TransitWand](https://github.com/conveyal/transit-wand)
- Show timetable: [datatools-ui](https://github.com/ibi-group/datatools-ui), [hsl-map-*](https://github.com/HSLdevcom), [Tavla](https://github.com/entur/tavla), [timetable_kit](https://github.com/neroden/timetable_kit)
- Platforms: [OpenBike](https://github.com/openbikesensor), [FleetBase](https://github.com/fleetbase/fleetbase), [Arlas](https://github.com/gisaia)

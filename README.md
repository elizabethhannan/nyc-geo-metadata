# NYC GIS Metadata
-------------

This document lists metadata sources for data updated and maintained by the NYC Department of Information Technology and Telecommunications (DOITT).

| Data/Layer Name | Description | Preview |
| ---|---|---|
[Address Point](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_AddressPoint.md) | Address points were initially created from data in the Department of City Planning Property Address Directory (PAD) file. Points were created approximately five feet inside building footprints along the correct street frontage. A field collection/verification process was undertaken to validate "multi-valued" addresses contained in the PAD file (i.e. those locations with a range of addresses). Additionally, a statistical sample of PAD single valued addresses was field checked. Approximately 100,000 locations were visited (about 10% of the total). | ![image](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Images/AddressPoint.PNG)
[Business Improvement Districts](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_BIDs.md) | Polygons representing location of Business Improvement Districts (BIDs). A BID is a public/private partnership in which property and business owners elect to make a collective contribution to the maintenance, development, and promotion of their commercial district.  | ![image](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Images/BusinessImprovementDistricts.PNG)
[Contours](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_Contours.md) | Planimetric basemap layer containing citywide 2-ft contour line features | ![image](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Images/Contours.PNG)
[Digital Elevation Model](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_DigitalElevationModel.md) | This bare-earth, hydro-flattened, digital-elevation surface model derived from Light Detection and Ranging (LiDAR) data represents the most accurate estimate of elevation for the City of New York.  Surface models are raster representations derived by interpolating the LiDAR point data to produce a seamless gridded elevation data set.  A Digital Elevation Model  (DEM) is a surface model generated from the LiDAR returns that correspond to the ground.  Buildings, trees and other above ground features are not included.  The cell values represent the elevation of the ground relative to sea level.  DEM applications include flood and storm surge modeling, hydrologic flow mapping, and site design. Digital Elevation Model (DEM) derived from LiDAR collected in the spring of 2010 over New York City. A DEM models the ground surface, which is to say that above ground features (e.g. trees and buildings) are not present. The DEM was generated by interpolating the LiDAR ground points to create a 1 foot resolution seamless surface. Cell values correspond to the ground elevation value (feet) above sea level. A proprietary approach to surface model generation was developed that reduced spurious elevation values in areas where there were no LiDAR returns, primarily beneath buildings and over water. This was combined with a detailed manual QA/QC process, with emphasis on accurate representation of docks and bare-earth within 2000ft of the water bodies surrounding each of the five boroughs. | ![image](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Images/DEM.PNG)
[NYCHA Developments](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_NYCHADevelopments.md) | Locations of the public housing developments of the New York City Housing Authority. | ![image](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Images/NYCHADevelopments.PNG)
[Planimetrics](https://github.com/CityOfNewYork/nyc-planimetrics/blob/master/Capture_Rules.md) | Planimetric mapping is the capture of geographic features from aerial survey that are traditionally mapped in two dimensions. NYC DOITT first developed a planimetric database in 2000. Today, the database includes features for [Building Footprints](https://github.com/CityOfNewYork/nyc-planimetrics/blob/master/Capture_Rules.md#building-footprint), [Boardwalk](https://github.com/CityOfNewYork/nyc-planimetrics/blob/master/Capture_Rules.md#boardwalk), [Cooling Towers](https://github.com/CityOfNewYork/nyc-planimetrics/blob/master/Capture_Rules.md#cooling-towers), [Curb](https://github.com/CityOfNewYork/nyc-planimetrics/blob/master/Capture_Rules.md#curb), [Elevation](https://github.com/CityOfNewYork/nyc-planimetrics/blob/master/Capture_Rules.md#elevation), [Hydro Structure](https://github.com/CityOfNewYork/nyc-planimetrics/blob/master/Capture_Rules.md#hydro-structure), [Hydrography](https://github.com/CityOfNewYork/nyc-planimetrics/blob/master/Capture_Rules.md#hydrography), [Median](https://github.com/CityOfNewYork/nyc-planimetrics/blob/master/Capture_Rules.md#median), [Misc Struct Poly](https://github.com/CityOfNewYork/nyc-planimetrics/blob/master/Capture_Rules.md#misc-struct-poly), [Open Space](https://github.com/CityOfNewYork/nyc-planimetrics/blob/master/Capture_Rules.md#open-space), [Park](https://github.com/CityOfNewYork/nyc-planimetrics/blob/master/Capture_Rules.md#park), [Parking Lot](https://github.com/CityOfNewYork/nyc-planimetrics/blob/master/Capture_Rules.md#parking-lot), [Pavement Edge](https://github.com/CityOfNewYork/nyc-planimetrics/blob/master/Capture_Rules.md#pavement-edge), [Plaza](https://github.com/CityOfNewYork/nyc-planimetrics/blob/master/Capture_Rules.md#plaza), [Railroad](https://github.com/CityOfNewYork/nyc-planimetrics/blob/master/Capture_Rules.md#railroad), [Railroad Structure](https://github.com/CityOfNewYork/nyc-planimetrics/blob/master/Capture_Rules.md#railroad-structure), [Retaining Wall](https://github.com/CityOfNewYork/nyc-planimetrics/blob/master/Capture_Rules.md#retaining-wall), [Roadbed](https://github.com/CityOfNewYork/nyc-planimetrics/blob/master/Capture_Rules.md#roadbed), [Shoreline](https://github.com/CityOfNewYork/nyc-planimetrics/blob/master/Capture_Rules.md#shoreline), [Sidewalk](https://github.com/CityOfNewYork/nyc-planimetrics/blob/master/Capture_Rules.md#sidewalk), [Sidewalk Centerline](https://github.com/CityOfNewYork/nyc-planimetrics/blob/master/Capture_Rules.md#sidewalk-centerline), [Swimming Pool](https://github.com/CityOfNewYork/nyc-planimetrics/blob/master/Capture_Rules.md#swimming-pool), [Transport Structure](https://github.com/CityOfNewYork/nyc-planimetrics/blob/master/Capture_Rules.md#transport-structure), and [Under Construction](https://github.com/CityOfNewYork/nyc-planimetrics/blob/master/Capture_Rules.md#under-construction). | ![image](--)
[Street Centerline](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_StreetCenterline.md) | Centerline is a single line representation of New York City streets containing address ranges and other information such as traffic directions, road types, segment types. | ![image](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Images/StreetCenterline.PNG)
[WiFi Hotspots](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_WifiHotspots.md) | This dataset includes public Wi-Fi Hotspot locations throughout the 5 boroughs. Wi-Fi providers include At&T, LinkNYC-Citybridge (BETA), BPL, Cablevision, Chelsea, City Tech, Downtown Brooklyn, Harlem, Manhattan Down Alliance, NYCHA, NYPL, QPL, Time Warner Cable, Transit Wireless, and various partners.  | ![image](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Images/WiFiHotspots.PNG)
[Zip Code Boundaries](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Metadata/Metadata_ZipCodeBoundaries.md) | This dataset contains boundaries of zip codes within New York City, NY. Estimate population, PO City name, county, and state per zip code are also included.  | ![image](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Images/ZipCodeBoundaries.PNG)


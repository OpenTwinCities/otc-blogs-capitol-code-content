---
ID: 7
post_title: Data
author: Bill Bushey
post_date: 2014-01-08 20:22:50
post_excerpt: ""
layout: page
permalink: http://capitolcode.mn.gov/data/
published: true
---
**Note:** This page will be updated as more information about available data sets is gathered, and as more data sets become available. Capitol Code will feature data sets from several Minnesota and Federal government offices, agencies, and organizations. [toc] 
## Office of the Secretary of State

### Elections Data

Polling Place Finder
:   [Download][1] - [API][2]
:   The Polling Place Finder dataset lists information for each polling place including: location name and addresses, precinct name, address ranges, and districts (senate, house, school, etc…).

Caucus Finder
:   [Download][3] - [API][4]
:   The Caucus Finder dataset is a listing of the current caucus locations across the state for the DFL, Republican, and Independence parties. Each record contains items such as: Location name and address, precinct name, party name.

Election Results by Precinct
:   [Download][5] - [API][6]
:   This dataset lists election results by precinct broken down by contest from 8/14/2012 onward. Note: only the final iteration is represented for instant runoff elections.

Registered Voters by Precinct
:   [Download][7] - [API][8]
:   This dataset will list the number of registered voters as reported per precinct per election since 11/2/2004 onward.

Google Voter Information Project XML
:   [Download][9]
:   This is an export file that MNSOS produces for Google several times a year. Google uses this file for their Voting Information Project (http://votinginfoproject.org). The XML file contains the following data structures and the IDs needed to recreate the hierarchical relationships between them:Localities (i.e. counties), electoral districts, precincts + precinct splits, polling place locations, Elections, contests in elections, ballots, candidates, referendums, and street segments (i.e. address ranges in precincts). The file that will be available for the event will be the one produced for the 2013 general election.

GeoJSON Files
:   <a href="http://www.sos.state.mn.us/index.aspx?page=1760" target="_blank">Downloads</a>
:   These files contain geospatial information for voting precinct boundaries as well as the name, county, and election districts for each precinct (US Congress, MN Senate and House, County Commissioner, etc…).

### Business and Other

Business Filings
:   [Download][10] - [API][11]
:   This dataset contains information regarding all original filings for new businesses between October 2011 through the end of December 2013. In addition to the date and type of business filed, the registered city / state / zip / country is provided. Note: this dataset should be considered as a sampling of business data. 30 records have been excluded from the exported data due to anomalies.

Notaries
:   [Download][12] - [API][13]
:   The Notary dataset contains active notaries as of January 31, 2014. The notary acts as an official, unbiased witness to the identity of the person who signs a document (Minnesota Statutes 359) to prevent fraud and forgery. A Minnesota notary public has six major duties: 
    1.  Take acknowledgments,
    2.  Administer oaths and affirmations,
    3.  Take and certify all depositions,
    4.  Witness or attest a signature,
    5.  Take and certify all acknowledgments and instruments in writing,
    6.  Record notarial protests.

Legal Newspapers
:   [Download][14] - [API][15]
:   Legal newspapers are officially designated publications in which citizens and governmental units advertise notices required by law. For example, individuals and businesses filing Assumed Name Certificates at the Secretary of State's office must advertise their intention to use a name in two consecutive issues of a legal newspaper. In addition, the law requires that notices must be placed in legal newspapers for many public hearings, opening of bids for public contracts, public land sales, corporate dissolutions, and numerous other private and government activities. There are over 350 legal newspapers currently registered with the Minnesota Secretary of State's office.Elements included in the data set are: Publication Name, address, county, and phone number.

Open Appointments
:   The appointment datasets represent all agency seats that are filled through the open appointment process.Open appointment data is split up into three datasets: 
    1.  Appointments: [Download][16] - [API][17]The Appointments dataset represents all agency seats that are filled through the open appointment process.
    2.  Applications: [Download][18] - [API][19]The Applications dataset represents those individuals who applied or were referred to a specific agency.
    3.  Appointing Authorities: [Download][20] - [API][21]Appointing Authorities data set includes all committees, task forces and other agencies that require the Open Appoint process to fill available seats.

Official Documents (Metadata)
:   [Download][22] - [API][23]
:   The Official Documents dataset includes those individuals or agencies that have taken or have received a particular action. Some actions include delegation or authority, extraditions, proclamations, etc… NOTE: the dataset does not include the PDFs of the documents; it contains the metadata needed to search for official documents.Elements in the dataset include: Type, FileDate, Name of entity receiving the action, Description

## State of Minnesota Geospatial Data Resources

<p dir="ltr">
  The state’s most prominent data catalogs are available at the following locations:
</p>

<li dir="ltr">
  <a href="http://deli.dnr.state.mn.us/">DNR Data Deli</a>
</li>
<li dir="ltr">
  <a href="http://www.mngeo.state.mn.us/chouse/">MnGeo Clearinghouse</a>
</li>
<li dir="ltr">
  <a href="http://www.dot.state.mn.us/maps/gisbase/html/datafiles.html">MnDOT BaseMap Data</a>
</li>

### Minnesota Geospatial Information Office

Minnesota Geospatial Image Service
:   [API][24]
:   MnGeo’s Geospatial Image Service provides versatile access to Minnesota air photos, hillshades, and scanned topographic maps using a Web Map Service (WMS).

Original Public Land Survey Plats
:   [API][25]
:   A statewide mosaic of Minnesota’s original Public Land Survey plats. These are often referred as the General Land Office (GLO) plats or maps. Produced by Foth Infrastructure & Environment, LLC Eagle Point II 8550 Hudson Boulevard North, Suite 100 Lake Elmo, MN 55042 for the Minnesota Department of Transportation (MnDOT).

### Department of Agriculture

[API List][26] 
ExportMDAWebMap
:   [API][27]
:   This tool takes the state of a web application (for example, included services, layer visibility settings, and client-side graphics) and returns a printable page layout or basic map of the specified area of interest.

MN_Agriculture_Admin_Basemap
:   [API][28]
:   A map service for web applications, including administrative features to support queries.

MN_Agriculture_AgChem
:   [API][29]
:   The Minnesota Department of Agriculture is the lead agency for response to, and cleanup of agricultural chemical contamination in Minnesota. Because of this role MDA has tracked spills of agricultural chemicals and sites contaminated with agricultural chemicals since the late 1970's. This service contains information on known and potential sources of agricultural chemical soil and ground water contamination. To view this service in context with query and search tools, see the What's In My Neighborhood? application. For more information on the layers included, see the Layer Metadata.

MN_Agriculture_Artist
:   [API][30]
:   Data can be queried and viewed at <http://gis.mda.state.mn.us/artist>.

MN_Agriculture_BasemapC
:   [API][31]
:   This map service is suitable as a general basemap or as a transparent service that can be drawn over aerial photos or other imagery.

MN_Agriculture_Basemap
:   [API][32]
:   This map service is suitable as a general basemap or as a transparent service that can be drawn over aerial photos or other imagery.

MN_Agriculture_Conservation_Grazing
:   [API][33]
:   MDA has been working with the Minnesota DNR, US Fish and Wildlife Service, and The Nature Conservancy to make conservation lands available for contract grazing as part of their ongoing wildlife management. This map functions as a directory of field staff from multiple agencies in order to provide a listing that can be available to farmers and ranchers.

MN_Agriculture_EAB_Detection
:   [API][34]
:   The Minnesota Department of Agriculture's Plant Protection Division has overall responsibility for excluding exotic or invasive plant pests through the use of quarantines and other regulatory actions. The Invasive Species Unit focuses on accomplishing this through Prevention, Early Detection, and Rapid Response. Through Early Detection, new and emerging invasive pests are detected soon after their arrival by field surveys, response to phone calls, and inspections. This map service contains information on early detection and BioControl efforts for Emerald Ash Borer.

MN_Agriculture_GM_Treatments
:   [API][35]

MN_Agriculture_PLS
:   [API][36]
:   This service is intended to serve as a navigational or reference layer to help identify rural areas that are often described in terms of Township, Range, and Section, or other Public Land Survey identifiers.

MN_Agriculture_Territories
:   [API][37]
:   This map provides general descriptions of inspection territories, including contact information for the inspector when available. The territories are not intended to be strict delineations of responsibility, but to serve as guidelines for regulated facilities, MDA support staff, and the public.

### Department of Natural Resources

[API List][38] 
#### Utilities

Where
:   [API][39]
:   Attributes of administrative and reference features at a point.

Gazetteer
:   [API][40]
:   Search for places in Minnesota.

#### MnDNR Facilities

SNA Detail
:   [API][41]
:   Detailed attributes for individual Scientific and Natural Areas.

SNA List
:   [API][42]
:   Limited attributes for all Scientific and Natural Areas.

#### Climatology

Ice Out by Year
:   [API][43]
:   Summary lake ice out data by year.

### Minnesota Pollution Control Agency

[API List][44] 
Ground Water
:   [API][45]
:   These routes provide data to the MPCA’s Groundwater EDA application.

Surface Water
:   [API][46]
:   These are the routes used for providing the data for the "[Watershed Data Integration Project][47]".

What's In My Neighborhood
:   [API][48]
:   These are the routes used for providing the data for the "What's in my neighborhood"application. "[What's in my neighborhood][49]" offers visitors a way to access a wide variety of environmental information about their community.

### Department of Transportation

*   ESRI API Lists: [1][50] - [2][51]
*   REST API Lists: [1][52] - [2][53]

Geometry
:   [API][54]
:   The geometry service helps applications do geometric calculations such as buffering, simplifying, calculating areas and lengths, and projecting. The geometry service provides an alternative to doing these calculations using fine-grained ArcObjects or a geoprocessing service. The geometry service is especially appropriate for applications built with the ArcGIS REST or JavaScript APIs.

MNDOT_BOUNDARIES
:   [API][55]
:   Contains jurisdictional boundaries used in basemap, state parks, state forests, national parks, national forests, tribal gov, municipalities, townships, counties, state, quad boundaries Updated: 12-10-2008

MNDOT_COMMON_LAYERS
:   [API][56]
:   Contains all of the basemap layers and 2 frames: one with the minnesota layers and one with the state background layers. Last updated 12-11-2008

MNDOT_COMMON_LAYERS_GEOCORTEX
:   [API][57]
:   Contains MNDOT common layers and the background layers. Also contains another frame called Overview and contains MN counties Updated 11-06-2009

MNDOT_COMMON_LAYERS_GEOCORTEX_MSD
:   [API][58]
:   MSD version Contains MNDOT common layers and the background layers. Does not contain imagery. Use in conjunction with MNDOT_IMAGERY service. Also contains another frame called Overview which contains MN counties Updated 07-09-2010

MNDOT_CONSTRUCTIONPROJECTS
:   [API][59]
:   MnDOT Construction Projects

MNDOT_IMAGERY
:   [API][60]
:   Contains fsas, doqs, drgs for the basemap Updated 5-27-2011

MNDOT_MnCMAT_Basemap
:   [API][61]
:   Basemap service for the MnCMAT application

MNDOT_MnCMAT_Dynamic
:   [API][62]
:   Map service for display of MncMat application map from 1:2000 down to 1:1000

MNDOT_MnCMAT_Overview
:   [API][63]
:   Overview map for the MnCMAT Crash application

MNDOT_MnCMAT_WorkArea
:   [API][64]
:   Work area map service for MnCMAT application

MNDOT_OVERVIEW_GREEN
:   [API][65]
:   Minnesota Green Overview Map Service Updated 12-10-2008

MNDOT_RAILROADS
:   [API][66]
:   Contains rail crossings, railroads, speed and volume Updated: 12-11-2008

MNDOT_REALMS_PLUS_BASE
:   [API][67]
:   This map service is used in conjunction with the GPV product and OLM's REALMS database. It includes data specific to REALMS as well as Basemap layers.

MNDOT_ROAD_CHARACTERISTICS
:   [API][68]
:   MNDOT layers containing incident layers which are events that take place on the road. Updated: 12-11-2008

MNDOT_ROADS
:   [API][69]
:   Contains MNDOT road layers Updated: 12-11-2008

MNDOT_RWMM_MSD
:   [API][70]
:   Mapservice to display Mn/DOT Right of Way Maps Deployed: February 8, 2011

MNDOT_SURFACEWATER_MNDNR
:   [API][71]
:   Contains hydro layers from MNDNR. Lakes, rivers, streams, wetlands Updated: 12-11-2008

MNDOT_TRAFFIC
:   [API][72]
:   Map Service that contains traffic layers

signtrack_signs
:   [API][73]
:   This map service contains only the signtrack layer and is wms enabled. 11-3-2008

## Minnesota State Demographic Center

### Population Estimates

[Downloads][74] The Minnesota State Demographic Center is required by law to produce annual population and household estimates for counties, cities and townships. Estimates are released in July and are benchmarked to April 1 of the previous year. The estimates are used to determine local government aid and levy limits. We do not produce independent population estimates for the years when the U.S. Census Bureau conducts the decennial census (2000, 2010, etc.). Population estimates give information on the present and past population. Estimates rely on statistical methods and administrative records. 
### Immigration Population Estimates

[Downloads][75] Population moving to Minnesota from other countries has reached historically high numbers in recent years, sparking keen interest in these populations. Minnesota’s State Demographic Center has produced estimates for some of the largest of these population. Additional information on international immigrants and foreign-born population in the state is available from the U.S. Census Bureau, the Department of Homeland Security’s Office of Immigration Statistics, MN Department of Education, MN Department of Health. None of these sources gives a complete picture of international immigration in Minnesota. Estimates of these population rely on a synthesis of many sources of data and necessarily have fairly large confidence intervals. 
### Population Projections

[Downloads][76] Projections tell about the population at future dates. They illustrate plausible courses of future population changes based on assumptions about future births, deaths and migration. Our most recent projections for total population, age, and sex, extend through 2065 (for the state of Minnesota). State-level labor force participation projections extend through 2045. These projections incorporate 2010 Census data. Users should note that updates are forthcoming to the projection files for counties (through 2045) and for racial groups. 
### 2010 Census Data {#state-demo-census}

[Downloads][77] The State Demographic Center has created several downloadable data tables of Minnesota specific data from the 2010 Census. 
## United States Census

[FactFinder][78] - [API][79] Please note that the [Minnesota State Demographic Center][80] is providing Minnesota focused subsets of Census data. You may wish to explore these subsets before diving into the Census's extensive data ecosystem. The United States Census provides an extensive array of datasets related to national population, demographics, economic conditions. The Census's [Data Access Tools][81] page provides a full list of data exploration and download tools, though the [FactFinder][78] tool is recommended for exploring and downloading data related to the Economic Census, the American Community Survey, and the 2010 Census. 
### Voting Age Population by Citizenship and Race: 2012 ACS 5-year Estimates

[Downloads][82] 
This is a special tabulation of data providing data on the citizen voting age population and other data from the 2008_2012 5-year American Community Survey (ACS). The ACS is the replacement for the decennial census long form. This is the fourth release of this special tabulation of ACS data. The first used the 2005-2009 5-year ACS data, the second used the 2006-2010 5-year ACS data, and the third used the 2007-2011 5-year ACS data. Data from all four releases are available on the Census Bureau’s Redistricting Office web site, www.census.gov/rdo. The data in this tabulation were collected in the American Community Survey between 2008 and 2012.

## Center for Urban and Regional Affairs (CURA) at University of Minnesota

Minneapolis Crime 2010-2013 Centroid
:   [Download][83]
:   Minneapolis Police Data Police Reports from 2010-2013 (mapped by block centroids)

Minneapolis/St. Paul People of Color (with age categories) and AIAN
:   [Download][84]
:   Census 2010 blockgroup data, with calculated categories for: People of Color (including Latino), Children of Color (including Latino) under age 5, Women of Color (including Latino) age 18-39, Seniors of Color (including Latino) over age 65, and American Indian Native Alaskan (in combination with one other race)

 [1]: https://communities.socrata.com/dataset/Capitol-Code-MNSOS-Pollfinder-Feb-2014/em5b-wpgt
 [2]: https://communities.socrata.com/developers/docs/capitol-code-mnsos-pollfinder-feb-2014
 [3]: https://communities.socrata.com/dataset/Capitol-Code-MNSOS-Caucusfinder-Feb-2014/mghc-48gs
 [4]: https://communities.socrata.com/developers/docs/capitol-code-mnsos-caucusfinder-feb-2014
 [5]: https://communities.socrata.com/dataset/Capitol-Code-MNSOS-Election-Results-By-Precinct/7ikx-jdq5
 [6]: https://communities.socrata.com/developers/docs/capitol-code-mnsos-election-results-by-precinct
 [7]: https://communities.socrata.com/dataset/Capitol-Code-MNSOS-Registered-Voters-By-Precinct-O/sb2j-g884
 [8]: https://communities.socrata.com/developers/docs/capitol-code-mnsos-registered-voters-by-precinct-on-election-day
 [9]: https://communities.socrata.com/dataset/Capitol-Code-MNSOS-Google-VIP-Export-11-5-2013/4v7s-iufa
 [10]: https://communities.socrata.com/dataset/Capitol-Code-MNSOS-New-Business-Filings-Oct-2011-T/vxpe-x9ch
 [11]: https://communities.socrata.com/developers/docs/capitol-code-mnsos-new-business-filings-oct-2011-through-dec-2013
 [12]: https://communities.socrata.com/dataset/Capitol-Code-MNSOS-Active-Notaries-Jan-2014/mtj7-yz3x
 [13]: https://communities.socrata.com/developers/docs/capitol-code-mnsos-active-notaries-jan-2014
 [14]: https://communities.socrata.com/dataset/Capitol-Code-MNSOS-Legal-Newspapers-Feb-2014/8m6k-msb3
 [15]: https://communities.socrata.com/developers/docs/capitol-code-mnsos-legal-newspapers-feb-2014
 [16]: https://communities.socrata.com/dataset/Capitol-Code-MNSOS-Open-Appointments-Appointments-/u2pv-8dc3
 [17]: https://communities.socrata.com/developers/docs/capitol-code-mnsos-open-appointments-appointments-fy2013
 [18]: https://communities.socrata.com/dataset/Capitol-Code-MNSOS-Open-Appointments-Applications-/ng8e-7ga5
 [19]: https://communities.socrata.com/developers/docs/capitol-code-mnsos-open-appointments-applications-fy2013
 [20]: https://communities.socrata.com/dataset/Capitol-Code-MNSOS-Open-Appointments-Agencies-FY20/jt74-8jjj
 [21]: https://communities.socrata.com/developers/docs/capitol-code-mnsos-open-appointments-agencies-fy2013
 [22]: https://communities.socrata.com/dataset/Capitol-Code-MNSOS-Official-Documents-2013/c3sr-9645
 [23]: https://communities.socrata.com/developers/docs/capitol-code-mnsos-official-documents-2013
 [24]: http://www.mngeo.state.mn.us/chouse/wms/geo_image_server.html
 [25]: http://em.lmic.state.mn.us/arcgis/rest/services/mngeo/MN_GLO_plats/MapServer
 [26]: http://gis.mda.state.mn.us/ArcGIS/rest/services
 [27]: http://gis.mda.state.mn.us/arcgis/rest/services/ExportMDAWebMap/GPServer
 [28]: http://gis.mda.state.mn.us/arcgis/rest/services/MN_Agriculture_Admin_Basemap/MapServer
 [29]: http://gis.mda.state.mn.us/arcgis/rest/services/MN_Agriculture_AgChem/MapServer
 [30]: http://gis.mda.state.mn.us/arcgis/rest/services/MN_Agriculture_Artist/MapServer
 [31]: http://gis.mda.state.mn.us/arcgis/rest/services/MN_Agriculture_BasemapC/MapServer
 [32]: http://gis.mda.state.mn.us/arcgis/rest/services/MN_Agriculture_Basemap/MapServer
 [33]: http://gis.mda.state.mn.us/arcgis/rest/services/MN_Agriculture_Conservation_Grazing/MapServer
 [34]: http://gis.mda.state.mn.us/arcgis/rest/services/MN_Agriculture_EAB_Detection/MapServer
 [35]: http://gis.mda.state.mn.us/arcgis/rest/services/MN_Agriculture_GM_Treatments/MapServer
 [36]: http://gis.mda.state.mn.us/arcgis/rest/services/MN_Agriculture_PLS/MapServer
 [37]: http://gis.mda.state.mn.us/arcgis/rest/services/MN_Agriculture_Territories/MapServer
 [38]: http://services.dnr.state.mn.us
 [39]: http://services.dnr.state.mn.us/api/where/v1/usage.html
 [40]: http://services.dnr.state.mn.us/api/gazetteer/v1/usage.html
 [41]: http://services.dnr.state.mn.us/api/sna/detail/v1/usage.html
 [42]: http://services.dnr.state.mn.us/api/sna/list/v1/usage.html
 [43]: http://services.dnr.state.mn.us/api/climatology/ice_out_by_year/v1/usage.html
 [44]: http://services.pca.state.mn.us
 [45]: http://services.pca.state.mn.us/groundwater
 [46]: http://services.pca.state.mn.us/surfacewater
 [47]: http://www.pca.state.mn.us/index.php/water/water-types-and-programs/surface-water/watershed-approach/watershed-data-integration-project.html
 [48]: http://services.pca.state.mn.us/wimn
 [49]: http://www.pca.state.mn.us/index.php/data/wimn-whats-in-my-neighborhood/whats-in-my-neighborhood.html
 [50]: http://gisservices.dot.state.mn.us/arcgis/services
 [51]: http://gisservices2.dot.state.mn.us/arcgis/services
 [52]: http://gisservices.dot.state.mn.us/ArcGIS/rest/services
 [53]: http://gisservices2.dot.state.mn.us/ArcGIS/rest/services
 [54]: http://gisservices.dot.state.mn.us/ArcGIS/rest/services/Geometry/GeometryServer
 [55]: http://gisservices.dot.state.mn.us/ArcGIS/rest/services/MNDOT_BOUNDARIES/MapServer
 [56]: http://gisservices.dot.state.mn.us/ArcGIS/rest/services/MNDOT_COMMON_LAYERS/MapServer
 [57]: http://gisservices.dot.state.mn.us/ArcGIS/rest/services/MNDOT_COMMON_LAYERS_GEOCORTEX/MapServer
 [58]: http://gisservices.dot.state.mn.us/ArcGIS/rest/services/MNDOT_COMMON_LAYERS_GEOCORTEX_MSD/MapServer
 [59]: http://gisservices.dot.state.mn.us/ArcGIS/rest/services/MNDOT_CONSTRUCTIONPROJECTS/MapServer
 [60]: http://gisservices.dot.state.mn.us/ArcGIS/rest/services/MNDOT_IMAGERY/MapServer
 [61]: http://gisservices.dot.state.mn.us/ArcGIS/rest/services/MNDOT_MnCMAT_Basemap/MapServer
 [62]: http://gisservices.dot.state.mn.us/ArcGIS/rest/services/MNDOT_MnCMAT_Dynamic/MapServer
 [63]: http://gisservices.dot.state.mn.us/ArcGIS/rest/services/MNDOT_MnCMAT_Overview/MapServer
 [64]: http://gisservices.dot.state.mn.us/ArcGIS/rest/services/MNDOT_MnCMAT_WorkArea/MapServer
 [65]: http://gisservices.dot.state.mn.us/ArcGIS/rest/services/MNDOT_OVERVIEW_GREEN/MapServer
 [66]: http://gisservices.dot.state.mn.us/ArcGIS/rest/services/MNDOT_RAILROADS/MapServer
 [67]: http://gisservices.dot.state.mn.us/ArcGIS/rest/services/MNDOT_REALMS_PLUS_BASE/MapServer
 [68]: http://gisservices.dot.state.mn.us/ArcGIS/rest/services/MNDOT_ROAD_CHARACTERISTICS/MapServer
 [69]: http://gisservices.dot.state.mn.us/ArcGIS/rest/services/MNDOT_ROADS/MapServer
 [70]: http://gisservices.dot.state.mn.us/ArcGIS/rest/services/MNDOT_RWMM_MSD/MapServer
 [71]: http://gisservices.dot.state.mn.us/ArcGIS/rest/services/MNDOT_SURFACEWATER_MNDNR/MapServer
 [72]: http://gisservices.dot.state.mn.us/ArcGIS/rest/services/MNDOT_TRAFFIC/MapServer
 [73]: http://gisservices.dot.state.mn.us/ArcGIS/rest/services/signtrack_signs/MapServer
 [74]: http://www.demography.state.mn.us/estimates.html
 [75]: http://www.demography.state.mn.us/immigration.htm
 [76]: http://www.demography.state.mn.us/projections.html
 [77]: http://www.demography.state.mn.us/Census2010/
 [78]: http://factfinder2.census.gov/
 [79]: https://www.census.gov/developers/
 [80]: #state-demo-census
 [81]: https://www.census.gov/main/www/access.html
 [82]: Voting Age Population by Citizenship and Race: 2012 ACS 5-year Estimates
 [83]: https://communities.socrata.com/Public-Safety/Mpls-Crime-2010-2013-Centroid/uk43-7nkm
 [84]: https://communities.socrata.com/dataset/Mpls-St-Paul-People-of-Color-with-age-categories-a/kbdq-9f48
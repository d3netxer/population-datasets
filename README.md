# population-datasets

##Landscan
###website: http://web.ornl.gov/sci/landscan/
####description: Using an innovative approach with Geographic Information System and Remote Sensing, ORNL's LandScan™ is the community standard for global population distribution. At approximately 1 km resolution (30" X 30"), LandScan is the finest resolution global population distribution data available and represents an ambient population (average over 24 hours). The LandScan algorithm, an R&D 100 Award Winner, uses spatial data and imagery analysis technologies and a multi-variable dasymetric modeling approach to disaggregate census counts within an administrative boundary. Since no single population distribution model can account for the differences in spatial data availability, quality, scale, and accuracy as well as the differences in cultural settlement practices, LandScan population distribution models are tailored to match the data conditions and geographical nature of each individual country and region.

Previous versions of LandScan also relied on night-time light imagery but it was determined that the nighttime lights were more representative of exonomic ativity and has subsequently been replaced with a suite of ancillary land cover data (Doll).

####data resolution and coverage: approximately 1 km resolution (30" X 30"), global scale

####data availability: free of charge for U.S. Federal Government Agencies

####Literature Review

#####LandScan: A Global Population Database for Estimating Populations at Risk (2000)

Jerome E. Dobson, Edward A. Brlght, Phllllp R. Coleman, Rlchard C. Durfee, and Brian A. Worley 

Best available census countrs were distributed to cells based on probability coefficients which, in turn, were based on road provimity, slope land cover, and nighttime lights. 

#####High Resolution Urban Feature Extraction for Global Population Mapping using High Performance Computing
V. Vijayaraj, E. A. Bright, B. L. Bhaduri
Computational Sciences and Engineering Division, Oak Ridge National Laboratory 

Paper discusses an automated parallel algorithm that has been implemented on a high performance computing environment to extract urban regions from high resolution images using texture and spectral features.

LandScan is a dasymetric
geospatial model that decomposes the best available census
data to finer resolutions using geographic, physiographic,
socioeconomic, and cultural indicator data and high-resolution
imagery. The LandScan model uses estimates of urban land
cover as an important factor in decomposing the best available
census data into high-resolution raster cells. For many areas of
the world, existing land cover data does not capture new urban
developments and urban sprawl. The traditional approach for
updating land cover data for the LandScan model has included
manual interpretation of high resolution (1-5 meter) imagery to
augment urban area delineations that are based on medium (30
meter) to coarse (1 km) resolution satellite imagery. The
amount of high resolution imagery that needs to be analyzed is
increasing in the order of terabytes. Manual interpretation of
such a huge volume of imagery data is tedious and expensive.
Various algorithms for automated extraction of urban regions
from remotely sensed imagery have been presented in the
literature but most of these algorithms are compute intensive. 


##WorldPop
###website: http://www.worldpop.org.uk/
####description: The WorldPop project was initiated in October 2013 to combine the AfriPop, AsiaPop and AmeriPop population mapping projects. It aims to provide an open access archive of spatial demographic datasets for Central and South America, Africa and Asia to support development and health applications. The methods used are designed with full open access and operational application in mind, using transparent, fully documented and shareable methods to produce easily updatable maps with accompanying metadata.

WorldPop utilises satellite imagery for mapping settlements - specifically, 30m spatial resolution Landsat Enhanced Thematic Mapper (ETM) satellite imagery, and increasingly a range of other sources. Increasingly, WorldPop is collaborating with groups undertaking high resolution settlement mapping, and integrating these datasets into the modelling process - these include the Global Human Settlement Layer and the Global Urban Footprint .

####Methods: http://www.worldpop.org.uk/data/methods/

Land cover-based mapping approach currently forms the basis for the majority of WorldPop datasets, but is now being replaced by an alternative 'Random Forest' mapping approach described by Stevens et al (2015):

PLoS One. 2015 Feb 17;10(2):e0107042. doi: 10.1371/journal.pone.0107042. eCollection 2015.
Disaggregating census data for population mapping using random forests with remotely-sensed and ancillary data.
Stevens FR1, Gaughan AE1, Linard C2, Tatem AJ3.

####data resolution and coverage: South America, Africa, Asia (http://www.worldpop.org.uk/data/) 

####data availability: Open data

##Global Human Settlement Layer
###website:http://ghslsys.jrc.ec.europa.eu/
####description:The Global Human Settlement Layer (GHSL) is developed and maintained by the Joint Research Centre, the European Commission's in house science service.
The GHSL proposes a new way to map, analyze, and monitor human settlements and the urbanization in the 21st century. 
GHSL integrates several available sources reporting about the global human settlement phenomena, with new information extracted from available remotely sensed (RS) imagery. So far, the GHSL is the largest and most complete known experiment on automatic image information retrieval using high and very high remotely sensed image data input. The GHSL automatic image information extraction workflow integrates multi-resolution (0.5m-10m) multi-platform, multi-sensor (pan, multispectral), and multi-temporal image data.

The first version of the public GHSL platform is only experimental and is delivering a small subset of the information layers currently under test in the internal GHSL platform prototype.

##Global Urban Footprint
###http://www.dlr.de/eoc/en/desktopdefault.aspx/tabid-9628/16557_read-40454/
####description:In this framework, the objective of the “Global Urban Footprint” (GUF) project is the worldwide mapping of settlements with unprecedented spatial resolution of 0.4 arcsec (~12 m). A total of 180 000 TerraSAR-X and TanDEM-X scenes have been processed to create the GUF. 

##Census International Programs

##Global Rural-Urban Mapping Project (GRUMP)
###website:http://sedac.ciesin.columbia.edu/data/collection/grump-v1
####description: This project builds on GPW to construct a common geo-referenced framework of urban and rural areas by combining census data with satellite data.
GRUMP datasets are available for 1990, 1995 and 2000

##Using Night-time lights to estimate population

#####Population detection profiles of DMSP-OLS night-time
imagery by regions of the world
Christopher N.H. DOLL 1,2*
1 United Nations University – Institute of Advanced Studies, 1-1-1 Minato Mirai, Yokohama
Kanagawa-ku, 220-8502, JAPAN
2 Department of Urban Engineering, The University of Tokyo, 7-3-1 Hongo, Bunkyo-ku, Tokyo,
113-8656, JAPAN

Comparing the spatial distribution of light emissions to that of human population reveals the
short comings of using night-time lights as an absolute proxy for the location of human
settlements. Large parts of the developing world remain without access to electricity despite
sizable populations. Nonetheless studies have shown the utility of night-time lights to be a
descriptor of urban location and urban population (Sutton et al., 2001). More recently, studies
have focused on whether night-time light imagery can be used to assess levels of access to
electricity (Doll and Pachauri, 2010; Elvidge et al., 2010). An obstacle in undertaking such
studies is that an appreciation or estimate of the level of population which goes undetected is
helpful to interpret the results. Given the very wide range of levels of development and use of
lighting across the world, this study seeks understand what level of population can be detected in
different regions of the world.


##Esri’s World Population Estimate
###website: http://www.arcgis.com/home/item.html?id=ac0401d78fa24a10a9151ffe50f35afe, http://blogs.esri.com/esri/esri-insider/2015/03/25/map-gives-new-insights-into-global-population/
####description: This layer was created with a model that combines imagery, road intersection density, populated places, and urban foot prints to create a likelihood surface. The likelihood surface is then used to create a raster of population with a cell size of 0.00221 degrees (approximately 250 meters).
 
The population raster is created using Dasymetric cartographic methods to allocate the population values in over 1.6 million census polygons covering the world. The population of each polygon was normalized to the 2013 United Nations population estimates by country.

Each cell in this layer has an integer value depicting the number of people that are likely to reside in that cell. Tabulations based on these values should result in population totals that more accurately reflect the population of areas of several square kilometers.

This layer has global coverage and was published by Esri in 2014.

####data resolution and coverage: World Coverage, cell size of 0.00221 degrees (approximately 250 meters)

####data availability: UNK

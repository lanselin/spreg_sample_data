
chicago_sdoh
============

Chicago Socio-Economic Determinants of Health
---------------------------------------------

* Chi-SDOH.dbf: attribute data (k=65)
* Chi-SDOH.shp: polygon shape file (n=791)
* Chi-SDOH.shx: spatial index
* Chi-SDOH.prj: projection information
* Chi-SDOH_q.gal: spatial weights - queen contiguity
* Chi-SDOH_k6s.gal: spatial weights - symmetric k-nearest neighbors (k=6)
* Chi-SDOH_k10tri.kwt: triangular kernel weights, adaptive bandwidth, k=10

Source: Kolak et al. (2020). Quantification of neighborhood-level social determinants
        of health in the continental United States. JAMA Network Open 3(1): e1919928

See also Anselin (2024). An Introduction to Spatial Data Science with GeoDa. Volume 1,
         Exploring Spatial Data. Boca Raton: CRC Press/Chapman & Hall, Chapter 1.

Variable	Description
---------------------------
ID		unique identifier

OBJECTID	unique census tract identifier (same as ID)

TRACTCE10	tract FIPS code

geoid10		complete GEO ID code
commarea	community area code
Shape_Leng	perimeter
Shape_Area	area
PDENS14		population density (2014)
CarC14P		percent commuting by car (2014)
CAR		indicator variable more than 50 percent car commute
NOCAR		indicator variable less than 50 percent car commute
CTA14P		percent public transit commuter (2014)
CTA		indicator variable more than 50 percent public transit commute
CmTm14		average commute time (in minutes, 2014)
Undr514P	"percent young children (under 5, 2014)"
Wht14P		percent white (2014)
WHT50PCT	original white indicator variable
Wht		new white indicator variable (>= 50 percent)
Blk14P		percent black (2014)
BLCK50PCT	original black indicator variable
Blk		new black indicator variable (>=50 percent)
Hisp14P		percent hispanic (2014)
HISP50PCT	original hispanic indicator variable
Hisp		new hispanic indicator variable (>= 50 percent)
Pop2014		population count (2014)
MEANMI_14	supermarket cost distance in miles (2014)
FACHANGE	change in distance 2014-07 (positive is closer)
PCCRIMERT15	property crime rate (2015)
VCRIMERT15	violent crime rate (2015)
COI_ct		childhood opportunity index
HIS_ct		economic hardshop index
YEARS_LOST	years of life lost
YPLL_rate	premature mortality rate
ForclRt		foreclosure rate (2014)
EP_MUNIT	percent multi-unit housing (2014)
EP_GROUPQ	institutionalized population (2014)
SSWS2USE	streetsmart walkscore
SchHP_MI	distance to high performance school (2012)
BrownF_MI	distance to nearest brownfield I(2012)
MEANMI_07	supermarket cost distance in miles (2007)
MEANMI_11	supermarket cost distance in miles (2011)
EP_MINRTY	percent minority (2014)
Ovr6514P	percent population over 65 (2014)
EP_AGE17	percent children and youth < 18 (2014)
EP_DISABL	percent with disability (2014)
EP_NOHSDP	percent without high school (2014)
EP_LIMENG	percent with limited English proficiency (2014)
EP_SNGPNT	percent single parent households (2014)
Pov14		percent living in poverty (2014)
PerCap1		per capita income (2014)
Unemp14		unemployment rate (2014)
EP_UNINSUR	percent uninsured (2014)
EP_CROWD	percent crowded housing (2014)
EP_NOVEH	percent households without a vehicle (2014)
ChildPvt14	percent children in poverty (2014)
HealthLit	health literacy index (2014)
FORCLRISK	foreclosure risk (2011)
COORD_X		x_coord (km)
COORD_Y		y_coord (km)
C_X		x_coord (m)
C_Y		y_coord (m)
districtno	district code
district	district name
region		region name
regionno	region code


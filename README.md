# Marine Aquaculture in Exclusive Economic Zones (West Coast, US)

The is a GitHub repository of Jaslyn Miura's analysis of suitable living areas for marine aquaculture species, within the designated Exclusive Economic Zones; using NOAA Sea Surface Temperature, General Bathymetric Chart of the Oceans, and Marineregion.org's Exclusive Economic Zone data.

**File Directory:**

```         
aquaculture-eez
├── aquacultre_analysis.html
├── aquacultre_analysis.qmd
├── aquaculture-eez.Rproj
├── data
│   ├── average_annual_sst_2008.tif
│   ├── average_annual_sst_2009.tif
│   ├── average_annual_sst_2010.tif
│   ├── average_annual_sst_2011.tif
│   ├── average_annual_sst_2012.tif
│   ├── depth.tif
│   ├── wc_regions_clean.dbf
│   ├── wc_regions_clean.prj
│   ├── wc_regions_clean.shp
│   └── wc_regions_clean.shx
└── README.md
```

data:

-   average_annual_sst: sea surface temperature raster for years 2008-2012

-   depth: ocean depth raster

-   wc_regions: west coast boundaries of Exclusive Economic Zones

-   aquacultre_analysis.html: Rendered quarto document to a html, with complete code and analysis.

-   aquacultre_analysis.qmd: Quarto document with complete code of the analysis.

**Data Access:**

The sea surface temperature data was access through NOAA’s 5km Daily Global Satellite Sea Surface Temperature Anomaly v3.1, for years 2008-2012. The ocean depth data was accessed through General Bathymetric Chart of the Oceans (GEBCO). The west coast exclusive economic zone boundary data was accessed through Marineregions.org. Suitable temperature and depth ranges of marine aquaculture species were obtained through SeaLifeBase.

**References:**

Flanders Marine Institute (2025): MarineRegions.org. Available online at www.marineregions.org. Consulted on 2025-11-28.

Gridded Bathymetry Data (2025). [depth.tif] General Bathymetric Chart of the Oceans. <https://www.gebco.net/data-products/gridded-bathymetry-data#toc-terms-of-use>

NOAA Coral Reef Watch. 2018, updated daily. NOAA Coral Reef Watch Version 3.1 Daily Global 5km Satellite Coral Bleaching Degree Heating Week Product, Jun. 3, 2013-Jun. 2, 2014. College Park, Maryland, USA: NOAA Coral Reef Watch. Data set accessed 2020-09-01 at <ftp://ftp.star.nesdis.noaa.gov/pub/sod/mecb/crw/data/5km/v3.1/nc/v1.0/daily/dhw/>.

Palomares, M.L.D. and D. Pauly. Editors. 2025. SeaLifeBase. World Wide Web electronic publication. www.sealifebase.org, version (04/2025).

**Author:** Jaslyn Miura

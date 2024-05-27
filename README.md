![image](https://github.com/StanislavHerber/Optical-Remote-Sensing/assets/134272440/7144955c-eed9-45ae-92f6-c53809f885e9)

# Optical remote sensing technology material

# Introduction
One of the first Czech definitions can be found as early as 1998, when P. Dobrovolný "defines remote sensing as a method of obtaining information about the Earth's surface and water surfaces using images taken from a bird's eye view, using electromagnetic radiation in one or more intervals of the spectrum, this radiation is then reflected or emitted from the Earth's surface. "
(in Czech: „definuje dálkový průzkum jako způsob získávání informací o zemském povrchu i vodních plochách s využitím snímků pořízených z ptačí perspektivy, využívající elektromagnetické záření v jednom nebo více intervalech spektra, toto záření je pak odráženo nebo emitováno ze zemského povrchu. “)

Another more specific definition is from (Lillesand, 2015), who describes it as: "Remote sensing is the science and art of obtaining information about an object, area, or phenomenon through the analysis of data acquired by a device that is not in contact with the object, area, or phenomenon under investigation (Lillesand, 2015)."

The National Oceanic and Atmospheric Administration, or NOAA, illustrates RS as "The science of obtaining information about objects from a distance, typically from aircraft and satellites."

In general, I would describe Remote Sensing as a science that deals with obtaining information about objects and phenomena without direct contact.

# What is the principle of optical remote sensing?

Remote sensing (or Earth Observation) is based on principle of measuring the amount of electromagnetic radiation reflected or emitted by the surface of Earth. The source of this energy are all objects on Earth (the rule is for the object to be hotter than absolute zero −273,15 °C but in reality every single objects is warmer than absolute zero). Electromagnetic radiation is produced by the accelarated or decelerated motion of charged particles. This technology uses visible, near-infrared and shortwave infrared radiation to study features in Earths surface. Important factor, which is utilised by optical RS is the fact, that different materials reflect, absorb or transmit different wavelengths of light. Thanks to differences in material the interaction of EM radiation will differ with each physical property of surface of Earth.

The information obtained from optical remote sensing can be used for a wide range of applications, including environmental monitoring, natural resource management, agriculture, urban planning, and disaster management. Optical remote sensing can provide information on a variety of environmental parameters, such as land cover, vegetation health, water quality, and atmospheric conditions.

The image below describes grahically basics of remote sensing. A,D: the source of radiation, B: impacting radiation, D: reciever of reflected/emitted radiation, E: transmittion of recorded radiation to receiving station, F: pre-processing, G: processing of remote sensing data 

<img src="https://github.com/StanislavHerber/Optical-Remote-Sensing/assets/134272440/395c403e-6579-4d78-8689-a37f68787964" width="300" height="200">
Fig. 1: Basics of remote sensing

# Brief history of remote sensing
* 1794 - Battlefield observation via ballons</a>;
* 1858 - Photography from flying kites, remote sensing via pidgeons</a>;
* 1903 - First succesfull flight of brothers Wrights</a>;
* 1908 - First photography from aeroplane unsure - either cpt. Cesare Tardivo, who captured Benghazi, Lybia from plane or L.P. Bonvillain captured France from plane.</a>;
* I. world war - photos of enemies from planes with camera in hand</a>;
* Between WWI and WWII British pilots were noticing monuments -> creation of aerial archeology</a>;
* Cold War 1946 - In New Mexico rocket was launched with camera to 105 km height -> first photo from space</a>;
* 1958 - First espionage satellite - Russian Sputnik (1957) and US Corona (1958)</a>;
* 1972 - First civil system for Earth research - Landsat</a>;
* 1999 - First 1 m satellite IKONOS</a>;
* 2007 - WorldView satellite 50 cm resolutions</a>;

# Hyperspectral remote sensing technology

Hyperspectral remote sensing, also known as imaging spectroscopy, is a specialized field within remote sensing that involves the analysis and evaluation of reflected or emitted radiation detected by sensors capturing a high number of narrow, contiguous, and continuous spectral bands (it consists of dozens up to hundreds of bands within EM spectrum). Compared to multispectral imagery, hyperspectral bands are much narrower wide only couple of nm. All bands create essentialy a complete graph of entire electromagnetic values.

The data collected by hyperspectral sensors is structured in a 3-dimensional format known as a data cube, with spatial dimensions and a spectral dimension, allowing for the extraction of detailed spectral signatures of materials and objects present in the observed area.

![image](https://github.com/StanislavHerber/Optical-Remote-Sensing/assets/134272440/33e983ab-3a63-4d58-8d7d-1c54ec488c68|))
Fig. 2: An AVIRIS hyperspectral datacube of Sullivan’s Island, SC. The image on top is a color composite of just three of the 224 available bands (RGB = near-infrared, red, green).

# Data archives
## Satellite data sources
* [Hyperion](https://www.usgs.gov/centers/eros/science/usgs-eros-archive-earth-observing-one-eo-1-hyperion) - Hyperion (2000)</a>;
* [GOME](https://navigator.eumetsat.int/product/EO:EUM:DAT:0533) - GOME-2 (2006)</a>;
* [OCO](https://disc.gsfc.nasa.gov/datasets?keywords=oco3) - OCO-2 (2024)</a>;
* [SPARK]() - Spark-1 (2016)</a>;
* [TECIS]() - TECIS</a>;
* [EnMAP](https://planning.enmap.org/) - EnMAP(2022)</a>;
* [DESIS](https://geoservice.dlr.de/data-assets/hxom21uqeo90.html) - DESIS(2018)</a>;
* [PRISMA](https://prisma.asi.it/authenticationendpoint/login.do?client_id=HfvpCVmAk24rSdCB4E4xu5Vf3LUa&commonAuthCallerPath=%2Foauth2%2Fauthorize&forceAuth=false&nonce=b408a6558367000360ebeb5678104b69&passiveAuth=false&redirect_uri=http%3A%2F%2Fprisma.asi.it%2Fmissionselect%2F&response_type=code&scope=openid+email&state=96607476446631be450f5c11799b0cb4&tenantDomain=carbon.super&sessionDataKey=a0e8ff9e-f2f0-4288-a595-ef1e46d39840&relyingParty=HfvpCVmAk24rSdCB4E4xu5Vf3LUa&type=oidc&sp=prs-user-Interfaces&isSaaSApp=false&authenticators=BasicAuthenticator:LOCAL) - PRISMA (2019)</a>;
* [FLEX](https://asf.alaska.edu/) - FLEX (planned)</a>;
* [CHIME](https://asf.alaska.edu/) - CHIME (planned)</a>;
* [TANAGER](https://asf.alaska.edu/) - TANAGER Planet (planned)</a>;
* [SHALOM](https://asf.alaska.edu/) - SHALOM (planned)</a>;

## Aerial data sources
* [AVIRIS](https://avirisng.jpl.nasa.gov/) - AVIRIS (1993)</a>;
* [HyMAP](https://crustal.usgs.gov/speclab/index.php?group=Convolved+to+Terrestrial+Spectrometers) - HyMAP (1998)</a>;
* [AISA]() - AisaEAGLE (2000)</a>;
* [Czechglobe](https://olc.czechglobe.cz/flis/) - CASI/SASI/TASI (2000)</a>;
 
## UAV data sources
* [HyperSpec]() - NANO-Hyperspec (1993)</a>;
* [PIXA]() - Pixa XC2 (1993)</a>;

## Handheld sensor sources
* [ASD]() - ASD FieldSpec4 (1993)</a>;


# Websites
## Forums
## Training
# Papers
# Use cases

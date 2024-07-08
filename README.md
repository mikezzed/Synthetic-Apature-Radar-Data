# Synthetic-Apature-Radar-Data
Give full description here of what SAR is, include some images of the different types of reflections and refractions and the types of data you can extract from this.

after exploring some of the data and possible uses, come up with question that this project can answer such as "is melbourne sinking", then extract and analyse data to determine ground movement in melbourne.

# Exploring STAC Metadata
#### SpotioTemporal Asset Catalog
The SpatioTemporal Asset Catalog specification was designed to establish a standard, unified language to talk about SpatioTemporal Assets (such as SAR images). A SpatioTemporal Asset is any file that represents information about the Earth captured in a certain place and at a particular time. The STAC specification allows these assets to be more easily searchable and queryable. STAC is simply a network of JSON files that describes the core features of an asset.

https://stacspec.org/en/tutorials/intro-to-stac/
https://github.com/radiantearth/stac-spec

Describe what is included in STAC and how this will help us determine which data (which images) are useful to us for finding data that we want to extract. e.g. if we want to analyse ground movement around volcanos we can check STAC files to see which SAR images we would need to extract. 

look into stac-utils (i think pystac is the sub-package i need), and stactools.

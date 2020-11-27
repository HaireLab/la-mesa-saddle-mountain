# la-mesa-saddle-mountain

### Data in this repository were used to conduct analyses for the following publications:

Haire, S. L., & McGarigal, K. (2008). Inhabitants of landscape scars: Succession of woody plants after large, severe forest fires in Arizona and New Mexico. Southwestern Naturalist, 53(2), 146–161.

Haire, S.L. (2009). Landscape Ecology of Large Fires in Southwestern Forests, USA. Ph.D. Dissertation, Department of Forest Resources, University of Massachusetts, Amherst.

Haire, S. L., & McGarigal, K. (2009). Changes in fire severity across gradients of climate, fire size, and topography: A landscape ecological perspective. Fire Ecology, 5(2), 86–103.

Haire, S. L., & McGarigal, K. (2010). Effects of landscape patterns of fire severity on regenerating ponderosa pine forests (Pinus ponderosa) in New Mexico and Arizona, USA. Landscape Ecology, 25(7), 1055–1069. https://doi.org/10.1007/s10980-010-9480-3

### Additional publications in which the data were used for a part of the analysis: 
Baker, W. L. (2018). Transitioning western U.S. dry forests to limited committed warming with bet‐hedging and natural disturbances. Ecosphere, 9(6), e02288. https://doi.org/10.1002/ecs2.2288

Korb, J. E., Fornwalt, P. J., & Stevens-Rumann, C. S. (2019). What drives ponderosa pine regeneration following wildfire in the western United States? Forest Ecology and Management, 454, 117663.

### Files in this repository

#### Metadata:

La Mesa data +proj=utm +zone=13 +datum=NAD83 +units=m +no_defs

Saddle Mountain data +proj=utm +zone=12 +datum=NAD83 +units=m +no_defs 

Form from TNC-UM project organizers

metadata_lamesa.xlsx

metadata_saddlemountain.xlsx

#### Tabular data files:

lamesa_data.csv: data for La Mesa fire (1977)

saddlemountain_data.csv: data for Saddle Mountain fire (1960)

#### Spatial data files (raster):

We mapped high severity using aerial photography obtained within 4 years before and after the fire event. Areas where all trees were killed were labeled as high severity, and areas of surviving trees were labeled as lower severity, because they could have experienced low, moderate or mixed fire effects or could represent unburned islands within the fire perimeter. The minimum mapping unit for areas of surviving trees within high-severity patches was two live trees in close proximity to each other. We field-checked the maps
for accurate representation of surviving trees, and modified the maps in a few cases. The origin of the forest opening (i.e., the high-severity patch) was
corroborated in the field by presence of downed wood, stumps, or snags.

lamesa_severity.tif: 1 = high severity (100% tree mortality from aerial photography), 0 = other (unburned/low/moderate severity within the fire perimeter)

saddlemtn_severity.tif: 1 = high severity (100% tree mortality from aerial photography), 0 = other (unburned/low/moderate severity within the fire perimeter)

Cover was mapped at La Mesa using post-fire (1981/1983) aerial photography by Allen (1989); values ranged from 0 to 95%. 
A comparable map for Saddle Mountain, which we developed from aerial photography, was scaled categorically: 1 (<25% cover), 2 (25–60% cover), 3 (>60% cover).

Allen CD (1989) Changes in the landscape of the Jemez Mountains, New Mexico. Dissertation, University of California, Berkeley.

lamesa_post_fire_pipo_cover.tif: Post-fire cover of pipo at La Mesa (0-95%)

saddlemtn_post_fire_pipo_cover.tif: Post-fire cover of pipo at Saddle Mountain 1 (<25% cover), 2 (25–60% cover), 3 (>60% cover)


#### Spatial data files (shape files):

LMfieldpts4_06: Field plot locations at La Mesa, visited in spring 2005

SAfieldpts2_06: Field plot locations at Saddle Mountain, visited in spring 2005


# Landslide Mapping — Pietrzejowice

GIS-based mapping and field investigation of an active landslide in **Pietrzejowice, southern Poland**, combining terrain analysis, UAV imagery, field observations and geomorphological interpretation.

The project focused on identifying the extent and internal morphology of the landslide, documenting evidence of ground movement and preparing a formal landslide registration card.

## Project Overview

The investigated landslide covers approximately **4.39 ha** and extends about **180 m**, with a vertical range of approximately **36 m**.

The feature was interpreted as an **intermittently active translational slide** developed primarily within cohesive soils. Field observations revealed multiple indicators of ongoing and historical mass movement, including:

- a distinct main landslide scarp,
- secondary scarps,
- landslide toe and accumulation zones,
- surface deformation and ground irregularities,
- cracked and deformed road surfaces,
- deformed fencing,
- tilted tree trunks,
- evidence of damage to buildings and infrastructure.

## Workflow

### 1. Terrain Analysis

A Digital Terrain Model (DTM) and derived hillshade were used to examine the morphology of the slope and identify terrain features associated with mass movement.

Terrain interpretation was used to support the delineation of:

- confirmed landslide boundaries,
- inferred landslide boundaries,
- main and secondary scarps,
- landslide toe,
- internal geomorphological features.

### 2. UAV Survey and Orthophotomap

A **drone survey** was conducted to acquire high-resolution aerial imagery of the study area.

The imagery was used to create an **orthophotomap**, providing a detailed contemporary view of the terrain, land cover, buildings and infrastructure within the landslide area.

The orthophotomap was subsequently used together with terrain analysis and field observations to support interpretation of the landslide boundaries and geomorphological features.

### 3. Field Investigation

Field observations were used to verify features identified from remote data and document visible evidence of ground movement.

Observed indicators included:

- pavement deformation,
- cracked road surfaces,
- deformed fencing,
- landslide scarps,
- tilted and deformed tree trunks.

Selected photographs documenting these features are included in the [`field-photos`](field-photos/) directory.

### 4. Landslide Delineation

Evidence from the **DTM, hillshade, UAV-derived orthophotomap and field observations** was integrated in ArcGIS Pro.

The final interpretation distinguishes confirmed and inferred landslide boundaries together with important elements of internal landslide morphology.

## Results

Two complementary cartographic products were prepared:

### [Landslide Hillshade Map](maps/landslide-hillshade-map.pdf)

The landslide interpretation displayed over a DTM-derived hillshade, emphasizing terrain morphology and geomorphological structures.

### [Landslide Orthophoto Map](maps/landslide-orthophoto-map.pdf)

The same interpretation displayed over the UAV-derived orthophotomap, allowing the mapped landslide features to be compared with buildings, roads, vegetation and agricultural land.

## Landslide Registration

A formal landslide registration card was prepared based on the GIS analysis, field investigation and supporting geological information.

The documentation includes:

- landslide location and classification,
- morphological parameters,
- geological setting,
- interpreted causes and activity,
- land use and infrastructure,
- documented damage and potential hazards,
- recommendations for further observation and monitoring,
- photographic documentation.

[View the landslide registration card](documentation/landslide-registration-card.pdf)

## Technologies and Methods

- **ArcGIS Pro**
- UAV / drone surveying
- orthophotomap generation
- Digital Terrain Model (DTM) analysis
- hillshade analysis
- GIS digitization
- geomorphological interpretation
- field mapping and validation
- cartographic visualization

## Repository Structure

```text
landslide-mapping-pietrzejowice/
├── documentation/
│   └── landslide-registration-card.pdf
├── field-photos/
│   ├── cracked_road.jfif
│   ├── deformed_fence.jfif
│   ├── landslide_scarp.jfif
│   ├── paving_deformation.jfif
│   └── tilted_tree_trunks.jfif
├── maps/
│   ├── landslide-hillshade-map.pdf
│   └── landslide-orthophoto-map.pdf
├── project/
│   └── pietrzejowice_landslide_mapping.aprx
└── README.md
```

## Author

**Michał Kuśnierz**

Developed as part of geohazards coursework at **AGH University of Science and Technology**, 2025.

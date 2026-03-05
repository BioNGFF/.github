[![Maintenance](https://img.shields.io/badge/Maintained%3F-Yes!-green.svg)](https://github.com/BioNGFF/vizarr/graphs/commit-activity)
[![Open Source](https://img.shields.io/badge/Open%20Source%3F-Yes!-purple)](https://github.com/BioNGFF/vizarr/blob/main/LICENSE)

## BioNGFF says 👋

BioNGFF is a Wellcome-funded consortium developing open, cloud-native data standards and software to support the **OME Next Generation File Format (OME-NGFF)**. This work is part of the [Next Generation Data Formats For 21st Century Biology](https://wellcome.org/research-funding/funding-portfolio/funded-grants/next-generation-data-formats-21st-century-biology) project, supported by Wellcome Trust Technology Development grants programme. The consortium includes software developers with experimental biologists, imaging scientists using many different modalities, and data repository experts from the University of Dundee (U.K.), University College London (U.K.), King’s College London (U.K.), Newcastle University (U.K.), European Bioinformatics Institute (U.K.) and Centre for Advanced Imaging (Germany) who will collaborate to design and deliver these new data format technologies for use by the global imaging community.

### Current Focus area

Our main focus areas are:

- **Web Viewer (Vizarr)** – developing [Vizarr](https://github.com/BioNGFF/vizarr) to support interactive visualization of multi-modal OME-Zarr datasets.
- **JavaScript Library (ome-zarr.js)** – building [ome-zarr.js](https://github.com/BioNGFF/ome-zarr.js), a JavaScript library to simplify rendering of OME-Zarr images in the browser.
- **OMERO Integration** – developing tools to import public OME-Zarr datasets into [OMERO](https://www.openmicroscopy.org/omero/), a widely used data management platform.
- **OME-NGFF Specification** – contributing to the ongoing development of the [OME-NGFF specification](https://github.com/ome/ngff).
- **Python Libraries**:
  - [OME-zarr-py](https://github.com/ome/ome-zarr-py) – a Python library for reading and writing multi-resolution images stored in Zarr filesets.
  - [OME-zarr-models](https://github.com/ome-zarr-models/ome-zarr-models-py) – a Python library for reading and validating OME-Zarr metadata.

### Community Engagement

- Present at the [September 2025 community call](https://forum.image.sc/t/join-us-for-the-next-ome-ngff-community-call-on-september-23-9-00-cest-and-17-00-cest/115611)
- Attend the [2025 International OME-NGFF workshop](https://www.biovisioncenter.uzh.ch/en/events/Upcoming-Events/2025-OME-NGFF-workshop.html) (10-14/11/2025)

### Progress

#### Web Viewer

- September 2025 community call:
  - [Introduction and roadmap of BioNGFF Web viewer](https://docs.google.com/presentation/d/1azX0kenr0TlkD9J2IHtrvzKv2xjbB3sCZDkN2N_0-Hk/edit?slide=id.g1363ca77dac_0_12#slide=id.g1363ca77dac_0_12)
- November 2025:
  - Became maintainer of [Vizarr](https://github.com/hms-dbmi/vizarr) to support the development of BioNGFF Web viewer.

### Javascript library

- November 2025
  - Release of version [0.0.17](https://github.com/BioNGFF/ome-zarr.js/releases/tag/v0.0.17)
    - Used by [BioFile Finder](https://github.com/allenInstitute/biofile-finder/), [FileGlancer](https://github.com/JaneliaSciComp/fileglancer), [OMEZarrTileSource](https://github.com/TissUUmaps/OMEZarrTileSource)

#### Import public OME-Zarr datasets into OMERO

- September 2025 community call:
  - [Status update](https://zenodo.org/records/17186172)
  - Release of [omero-cli-zarr v0.7.0rc1](https://github.com/ome/omero-cli-zarr/releases/tag/v0.7.0rc1)
  - Release of [omero-zarr-pixel-buffer v0.6.0-rc1](https://github.com/glencoesoftware/omero-zarr-pixel-buffer/releases/tag/v0.6.0-rc1).
- Q4 2025: Import of plates
- Q4 2025: Investigate import of OME-Zarr v0.5 into OMERO

#### Specification

- Q4 2025: Integration of [RFC-5 Coordinate systems and transformations](https://ngff.openmicroscopy.org/rfc/5/index.html). See [Review response](https://github.com/ome/ngff/pull/350)

#### Python libraries

- September 2025
  - Validate the writing of OME-Zarr in OME-zarr py using OME-zarr models.

### Projects you may be interested in:

- [napari-ome-zarr](https://github.com/ome/napari-ome-zarr) A [napari](https://napari.org/) plugin for reading OME-Zarr data.

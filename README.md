### Project Title
 Recovery time and succession of burned areas in protected areas

### Collaborators
Peter Olsoy (Project Lead), Joel Masselink, Sebastian Essink, Marvin Bensch, Ethan Andrews

### The Problem


### Sample Data
WA State Protected Area estate:
- Categorized into public and private management
- Protected areas and easements that are > 1 ha
- Source: Combined World Database on Protected Areas (WDPA) and National Conservation Easement Database (NCED) in August 2017

Fire perimeters in Washington from 1973-2018
- Includes attributes for fire year, cause of fire, fire name, and agency in charge of land
- Fires from earlier years are very limited, with only a single fire in the 70's, with coverage increasing near the mid-80's
- Source: [Washington Geospatial Open Data Portal](https://geo.wa.gov/datasets/6f31b076628d4f8ca5a964cbefd2cccc_0)

### Specific Questions
- fire/burned area boundaries
- classify land condition using raster data (NDVI, optical)
- look at succession / regeneration (**before** and **after** fire)
- investigate breakdown of protected area estate between public and private, and by state
- what is the connection between protection and fire occurrence and post-fire succession?


### Tasks:

- [x] find burned area polygons
- [x] boilerplate Jupyter Notebook to interact with data
- [ ] make widget slider to demonstrate differences in NDVI pre- and post-Fire
- [ ] map time series of total area burned in Washington, as well as subset to protected areas
- [x] import PA & fire perimeter data into Google Earth Engine
- [x] explore GEE datasets for estimating forest recovery in a single fire perimeter
- [ ] generate time series of post-fire recovery in GEE
- [ ] calculate average NDVI within a polygon and extract as CSV from GEE
- [ ] extend GEE script to entire dataset
- [ ] graph average NDVI over time for all burned areas


### Proposed Methods/Tools
Use the Normalized Burn Ratio (NBR) to highlight burned areas within large fire perimeter polygons.

### Background Reading
[Normalized Burn Ratio](https://wiki.landscapetoolbox.org/doku.php/remote_sensing_methods:normalized_burn_ratio)

### Files

* `.gitignore`
<br> Globally ignored files by `git` for the project.
* `environment.yml`
<br> `conda` environment description needed to run this project.
* `README.md`
<br> Description of the project.

### Folders

### `contributors`
Each team member has it's own folder under contributors, where he/she can
work on their contribution. Having a dedicated folder for one-self helps to
prevent conflicts when merging with master.

### `data`
Test datasets for the project including the protected areas and fire perimeters for Washington State.

### `notebooks`
Notebooks that are considered delivered results for the project should go in
here.

### `scripts`
Helper utilities that are shared with the team

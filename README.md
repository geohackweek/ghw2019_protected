### Project Title
 Recovery time and succession of burned areas in protected areas

### Collaborators
Peter Olsoy (Project Lead), Joel Masselink, Sebastian Essink, Marvin Bensch, Ethan Andrews

### The Problem


### Application Example


### Sample Data
WA State Protected Area estate:
> Categorized into public and private management


### Specific Questions
- fire/burned area boundaries
- classify land condition using raster data (NDVI, optical)
- look at succession / regeneration (**before** and **after** fire)
- investigate breakdown of protected area estate between public and private, and by state
- what is the connection between protection and fire occurrence and post-fire succession?


### Tasks:

- [x] find burned area polygons
- [ ] build xarray dataset of satellite imagery / NDVI
- [x] boilerplate Jupyter Notebook to interact with data
- [ ] find fire occurrence points (NASA FIRMS / GlobalForestWatch)
- [x] import PA & fire perimeter data into Earth Engine



### Existing Methods



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

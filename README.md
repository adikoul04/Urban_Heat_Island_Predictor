## Urban Heat Island Predictor
This project is an ML model that predicts urban heat in particular regions of New York City.

## Setup Instructions

### Getting Started
1. Clone this repository:
   ```
   git clone https://github.com/adikoul04/Urban_Heat_Island_Predictor.git
   cd Urban_Heat_Island_Predictor
   ```

2. Create and activate the conda environment:
   ```
   conda env create -f environment.yml
   conda activate UHI_predictor
   ```

### Adding Dependencies
If you need to add new dependencies to the project:

1. First install the package to test it:
   ```
   conda install package_name
   ```
   or
   ```
   pip install package_name
   ```

2. Add the dependency to the `environment.yml` file in the appropriate section

3. Update the project documentation if the new dependency changes any workflows

4. Commit your changes to the repository

### Current Dependencies
- pandas
- matplotlib
- numpy
- geopandas
- folium
- IPython 
- Scipy

### Note
The `.conda` folder is specific to your local setup and should not be committed to the repository.
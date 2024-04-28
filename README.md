# Sonification Scripts for Celestial Bodies
This repository contains the sonification scripts used to generate audio from space weather data. 
The audio is used as a foundation for the compositions in the multi-disciplinary art project, "Celestial Bodies".

The sonified audio can be found in the [wav-files](./wav-files) directory.
The data files from ESA used as the source for the sonification can be found in the [ESA-Swarm-Handbook](./notebooks/ESA-Swarm-Handbook) directory.
More data can be downloaded and added using the [ESA Handbook website](https://swarmhandbook.earth.esa.int/catalogue/index).

## Jupyter Notebook
The sonification scripts were created in a Jupyter notebook. New sonifications can be made using the notebook in the [notebooks](./notebooks) directory.

#### Requirements/packages
To be able to edit and re-run the Jupyter Notebook, first install `jupyter` using `pip`:
```
pip install jupyter
```

To run the sonification script in the Jupyter Notebook, the packages specified in the `requirements.txt` need to be installed. 
This can be done with the following command:
```
pip install -r requirements.txt
```
The [pyrubberband](https://github.com/bmcfee/pyrubberband) package needs to have the [Rubberband](https://breakfastquay.com/rubberband/) library installed in order to work.

Now, the notebook can be started using the following command:
```
jupyter notebook ./notebooks/Celestial_Bodies_Notebook.ipynb
```

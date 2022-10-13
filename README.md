

<img src="https://raw.githubusercontent.com/geolabsoft/mecsuelos/main/logo_ucsc_plain.svg" alt="Logo UCSC" width="350"/>


# Analysis of the influence of geomechanical parameters and geometry on slope stability in granitic residual soils [[Link to the paper]](https://www.mdpi.com/2076-3417/12/11/5574/htm)




This repository contains the resouces used to generate and calculate the numerical models used in the article **Analysis of the influence of geomechanical parameters and geometry on slope stability in granitic residual soils**.

### Publication information

To be fulfilled after publication

## Notebook for model creation and calculation

The Jupyter notebook included in this repository was used to generate limit analysis finite element models for the software OptumG2. Model are generated using Montecarlo samplig with ramdom values of the parameters within the common ranges found in the literature with a uniform probabilit distribution.

The system creates a file for each model resultinf from the Montecarlo sampling using a template file (also included in the repository).

Finally, all models are run and results collected and saved to text files for further analysis. 

### Dependecies

The notebook was developed using the following packages:

* NumPy (1.19.5)

Other packages from Python's standard library were also used.

OptumG2 needs to be installed and working on the computer for the system to run the numerical models. An academic license of the software is enough to run the resulting models. 

## Data access

The source code of the system to generate and calculate the numerical models is available in this repository, along with the OptumG2 template file.

The data presented in this study are available on request from the corresponding authors

## Contributors


The complete author list for this investigation is stated below:

* [Bravo-Zapata, Matías F.] (mailto:mfbravozapata@gmail.com)
* Muñoz, Enrique
* [Lapeña-Mañero, Pablo](mailto:plapenamanero@gmail.com)
* Montenegro-Cooper, José Miguel
* King, Robert W.

The investigation was carried out in the Department of Civil Engineering from the Universidad Católica de la Santísima Concepción (UCSC)

## License


All the code in this repository is licensed under MIT license (See *LICENSE* file)

## Citing

To cite this article or the code in this repository please use the data available in the publication website.

# Frozen Flask webapp with Elsa

[![Build Status](https://travis-ci.org/Patechoc/test_Elsa_0001.svg?branch=master)](https://travis-ci.org/Patechoc/test_Elsa_0001)

https://github.com/pyvec/elsa/blob/master/QUICKSTART.rst

## conda create --name elsa python=3.6
conda env create -f environment.yml


# To activate this environment, use:
# > source activate elsa
#
# To deactivate an active environment, use:
# > source deactivate



## update environment file
# conda list
conda env export > environment.yml

## Run the app
python app.py serve
python app.py freeze --serve

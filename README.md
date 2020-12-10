# State-space encoder model applied on the Nissan leaf steering dataset

The code accompanying a upcoming paper. 

Model Simulation result:

![encoder image](results-encoder.png)

# Instructions

* Get anaconda 3 (python>= 3.6)
* Install pytorch ([Instructions](https://pytorch.org/get-started) CUDA optional)
* Install [deepSI](https://github.com/GerbenBeintema/deepSI) (our preliminary toolbox, version used: `168d2efd36154a27e653be705c6d559170661d2a`)
  * `git clone git@github.com:GerbenBeintema/deepSI.git` 
  * `cd deepSI`
  * `pip install -e .`
* install jupyter notebook
  * (i.e. `conda install -c conda-forge jupyterlab`)
* Use jupyter notebooks to open notebooks.
  * (e.g. `jupyter notebook SS-encoder-modelling.ipynb`)

# State-space encoding structure

![encoder image](Encoder-graphic.png)
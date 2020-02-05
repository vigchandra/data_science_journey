# my_data_science_journey
## List of links to learn from


MDS Required Packages (Ongoing List)

After following the MDS installation instructions, creating an ‘mds’ environment in miniconda, and installing Jupyter Notebook and Jupyter Lab in miniconda, the following packages still needed to be installed:

**Jupyter**
1.	Jupyter RISE:
    conda install -c damianavila82 rise
    jupyter-nbextension install rise --py --sys-prefix
    jupyter-nbextension enable rise --py --sys-prefix

**Python Packages**
1.	Numpy: conda install numpy
2.	Pandas: conda install pandas
3.	Altair (for Jupyter Lab): conda install -c conda-forge altair vega_datasets jupyterlab
4.	Altair (for Jupyter Notebook): conda install -c conda-forge altair vega_datasets notebook vega
5.	Scipy: conda install scipy
6.	Sklearn: conda install scikit-learn
7.	Matplotlib: conda install -c conda-forge matplotlib
8.	Psutil: conda install psutil
9.	Networkx: conda install network
10.	PuLP: conda install -c conda-forge pulp
11.	Snakeviz: conda install snakeviz
12.	Numba: conda install numba
13.	Seaborn: conda install seaborn
14.	Pandas profiling: conda install -c conda-forge pandas-profiling
15.	Pil: conda install pil (didn’t work)
16.	Pillow: conda install pillow
17.	toy_classifier: conda install -c pytorch torchvision
18.	graphviz: conda install graphviz (didn’t work)
19.	graphviz: conda install python-graphviz
20.	sqlalchemy: conda install -c anaconda sqlalchemy
21.	psycopg2: conda install -c anaconda psycopg2
22.	xlrd (optional): conda install xlrd 
23.	conda install -c conda-forge scikit-plot
24.	Mike’s plot_classified: pip install git+git://github.com/mgelbart/plot-classifier.git
25.	conda install -c conda-forge ipython-autotime
26.	conda install py-xgboost
27.	conda install nomkl
28.	pip install lightgbm
29.	(for installing lightgbm) pip install pypi-install 
30.	brew install libomp
31.	(Within Jupyter notebook): !pip install xgboost 
32.	(mds) pip install git+git://github.com/mgelbart/plot-classifier.git
33.	(mds) pip install -U scikit-learn
(to get the latest release of scikit-learn)
34.	(mds) conda install docopt
35.	(mds) conda install nltk
36.	(mds) conda install -c conda-forge librosa
37.	(mds) conda create -n tf tensorflow (didn’t work)
38.	(mds) pip install tensorflow
39.	(mds) conda install -c conda-forge imbalanced-learn #for DSCI 573
40.	(mds) conda install -c conda-forge eli5 #for DSCI 573
41.	(mds) conda install -c conda-forge scikit-image  #for DSCI 572
42.	(mds) conda install -c conda-forge shap # for DSCI 573

**R Packages**
1.	Convertemp: devtools::install_github(“ttimbers/convertemp”)
2.	Gapminder dataset: install.packages(“gapminder”)
3.	NYC Flights dataset: install.packages(“nycflights13”)
4.	install.packages("styler")
5.	install.packages("reticulate")
6.	install.packages(“xaringan”)
7.	install.packages("geojsonio")
8.	install.packages(“ggthemes”)
9.	install.packages(“sf”)
10.	install.packages("cowplot")
11.	install.packages("ggridges")
12.	install.packages(“magick”)
13.	install.packages("janitor")
14.	install.packages("ggimage")
15.	install.packages(“infer”)
16.	install.packages(“gridExtra”)
17.	install.packages(“HistData”)
Not actually necessary; but was used in textbook for DSCI 561
18.	install.packages(“tree”)
19.	install.packages(c('dbplyr', 'RPostgres'))
20.	install.packages(“GGally”)
21.	install.packages(“rsample”)
22.	install.packages(“plotly”)
23.	library(devtools)
install_github(‘plotly/dashR’)
24.	install.packages('tictoc')
25.	install.packages("car")
26.	install.packages("docopt") # for DSCI 522 (workflows)
27.	install.packages("caret")
28.	install.packages("MLmetrics") # for DSCI 562 (Regression II) Lab 1
There is a binary version available but the source version is later:
Do you want to install from sources the package which needs compilation? (Yes/no/cancel) Yes
29.	install.packages("zoo")
30.	install.packages("kableExtra")
31.	install.packages("marmap")
32.	install.packages("mapproj")
33.	remotes::install_github(“yihui/knitr”)
34.	install.packages("robust")
35.	install.packages("here")
36.	install.packages("ggfortify")
37.	install.packages("VGAM") # Must install this using RStudio (Not Jupyter Notebook!)
38.	install.packages("plm")
39.	install.packages("mice")

**Other**
1.	pip install dash
pip install dash-bootstrap-components
pip install gunicorn
2.	conda install "ipywidgets=7.5"
3.	(mds) 
brew tap mongodb/brew
brew install mongodb-community@4.2
•	To run MongoDB as a macOS service:
brew services start mongodb-community
4.	(mds) brew install mongodb/brew/mongodb-community-shell
5.	(mds) brew install hugo
6.	Added ```RETICULATE_PYTHON = ‘/opt/miniconda3/envs/mds/bin/python’ ``` to the .Renviron file by typing `usethis::edit_r_environ()` in the RStudio console
•	I could have added ``` Sys.setenv(RETICULATE_PYTHON = ‘/opt/miniconda3/envs/mds/bin/python’)``` to the .Rprofile file instead, but Jenny Bryan pointed out that it’s better to update the .Renviron file instead.
7.	remotes::install_github('rstudio/rmarkdown') # DSCI 522 trying to update rmarkdown for toc to work when knitting (didn’t work
8.	brew install pandoc-citeproc # DSCI 522 to get toc to work
9.	docker pull ttimbers/makefile2graph #was used to get images for DSCI 522 lecture
10.	docker pull rocker/tidyverse #was used to get images for DSCI 522 lecture
11.	docker pull debian:stable
12.	(not actually required, but I installed it to watch MIT videos) pip install ffmpeg-python

 
**Added to .gitignore_global**
.ipynb_checkpoints/
.DS_Store
altair-data-*.json


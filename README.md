# Kaggle Intro
## Installation 
1. (windows) install [git](https://git-scm.com/download/win)
1. Install [miniconda](https://conda.io/miniconda.html)
1. Install packages
   * conda install numpy scikit-learn pandas matplotlib seaborn
   * conda install jupyter
   * pip install kaggle-cli
1. Install XGBoost
   * [Windows](http://www.picnet.com.au/blogs/guido/post/2016/09/22/xgboost-windows-x64-binaries-for-download/)
   * [Linux/OSX](https://xgboost.readthedocs.io/en/latest/build.html)
      1. Install lib
         ```
         RUN git clone --recursive https://github.com/dmlc/xgboost && \
         cd xgboost && \
         make -j4 
         ```
      1. Install python wrapper package
         ```
         cd xgboost/python-package; python3 setup.py install && cd ../..
         ```
1. Register on Kaggle (if not)

# Follow the Jupyter notebook 

1. Open this repo ```git clone https://github.com/imsedim/intro.kgl.git```
1. Go into the directory ```cd intro.kgl```
1. Download competition files into folder ```input```
   ```
   mkdir input
   cd input
   kg download -u <username> -p <password> -c porto-seguro-safe-driver-prediction
   cd ..
   ```

1. Run ```jupyter notebook```
   

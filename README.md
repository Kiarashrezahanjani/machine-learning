# machine-learning

## Mac setup (python 2.7)
If you are not concern about dependency issues skip virtualenv/activate(enter vm)/deactivate(exit vm) commands
```sh
sudo easy_install pip
# for better dependency mangement
pip install virtualenv
virtualenv myMLEnv
source myMLEnv/bin/activate
# python notebook
pip install jupyter
pip install numpy
pip install matplotlib
pip install scipy
pip install sklearn
pip install pydotplus
pip install graphviz
jupyter notebook&
# set up notbook password
# import this notebook
# once done, deactivate exit(deactivate) virtual env
deactivate```

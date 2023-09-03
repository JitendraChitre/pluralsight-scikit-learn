#########################################################################
# Readme.txt when working from home
#########################################################################

#########################################################################
# One-Off Activity/Installation
#########################################################################
mkdir C:\Personal\Projects\python\pluralsight-scikit-learn
cd C:\Personal\Projects\python\pluralsight-scikit-learn

python --version
python -m venv env
C:\Personal\Projects\python\pluralsight-scikit-learn\env\Scripts\activate.bat

python --version
python -m pip install --upgrade pip

# -U, --upgrade means:
#	Upgrade all specified packages to the newest available version.
#	The handling of dependencies depends on the upgrade-strategy used.

pip install -U numpy
pip install -U pandas
pip install -U matplotlib
pip install -U seaborn
pip install -U scipy
pip install -U scikit-learn
pip install -U jupyter
pip install -U notebook


#########################################################################
# Command to get up and running on a daily basis
#########################################################################
# to run jupyter notebook
Run cmd
c:
C:\Personal\Projects\python\pluralsight-scikit-learn
C:\Personal\Projects\python\pluralsight-scikit-learn\env\Scripts\activate.bat
jupyter notebook
# This should open the jupyter deamon and alos open the notebook in a browser

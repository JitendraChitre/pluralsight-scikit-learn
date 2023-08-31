#########################################################################
# One-Off Activity/Installation
#########################################################################
mkdir c:\Local\projects\python\pluralsight-scikit-learn
cd c:\Local\projects\python\pluralsight-scikit-learn

python --version
python -m venv env
C:\Local\projects\python\pluralsight-scikit-learn\env\Scripts\activate.bat

python --version
python -m pip install --proxy=proxy.ukmkt.ad.ge.corp.local:80 --upgrade pip

# -U, --upgrade means:
#	Upgrade all specified packages to the newest available version.
#	The handling of dependencies depends on the upgrade-strategy used.

pip install --proxy=proxy.ukmkt.ad.ge.corp.local:80 -U numpy
pip install --proxy=proxy.ukmkt.ad.ge.corp.local:80 -U pandas
pip install --proxy=proxy.ukmkt.ad.ge.corp.local:80 -U matplotlib
pip install --proxy=proxy.ukmkt.ad.ge.corp.local:80 -U seaborn
pip install --proxy=proxy.ukmkt.ad.ge.corp.local:80 -U scipy
pip install --proxy=proxy.ukmkt.ad.ge.corp.local:80 -U scikit-learn
pip install --proxy=proxy.ukmkt.ad.ge.corp.local:80 -U jupyter
pip install --proxy=proxy.ukmkt.ad.ge.corp.local:80 -U notebook


#########################################################################
# Command to get up and running on a daily basis
#########################################################################
# to run jupyter notebook
Run cmd
c:
cd c:\Local\projects\python\pluralsight-scikit-learn
C:\Local\projects\python\pluralsight-scikit-learn\env\Scripts\activate.bat
jupyter notebook
# This should open the jupyter deamon and alos open the notebook in a browser

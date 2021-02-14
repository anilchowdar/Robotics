Test that everything works with Python 2 and Python 3:

python2 -m robot login_tests.robot
python3 -m robot login_tests.robot
If needed, move regenerated log and report to https://bitbucket.org/robotframework/robotframework.bitbucket.org/src/master/CDemo/ to make them visible online.

Generate a new download package:

./package.py
Upload the download package to https://bitbucket.org/robotframework/cdemo/downloads

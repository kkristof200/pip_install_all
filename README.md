# pip_install_all

## What does it do
Installs all missing python packages from a directory

## Install
~~~~shell
wget https://raw.githubusercontent.com/kkristof200/pip_install_all/master/pip_install_all -O /usr/local/bin/pip_install_all && chmod u+x /usr/local/bin/pip_install_all
# or
curl https://raw.githubusercontent.com/kkristof200/pip_install_all/master/pip_install_all > /usr/local/bin/pip_install_all && chmod u+x /usr/local/bin/pip_install_all
~~~~

## Usage
1. Navigate to folder where your repo is cloned
2. Type one of the following
~~~~bash
pip_install_all
or
pip_install_all pip
~~~~

## Notes
pip version defaults to pip3, if want to use pip, or other custom, specify is as show in the usage section

## Dependendies
- Python3
- pipreqs (pip_install_all will install that one too)

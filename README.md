# pip_install_all

## What does it do
Installs all missing python packages from a directory

## Setup
1. Move pip_install_all to /usr/local/bin (or any  other forder added to your $PATH)
2. Might need to run 'chmod u+x pip_install_all'

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

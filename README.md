1. Create Python virtual environment using [virtualenvwrapper](https://virtualenvwrapper.readthedocs.io/en/latest/) (or equivalent):

```sh
mkvirtualenv --python=/usr/bin/python3.6 leep-cea
pip install -r requirements.txt
```

2. Download the following data files and unzip in repository root:

- [World Population Prospectus](https://population.un.org/wpp/Download/Files/1_Indicators%20(Standard)/CSV_FILES/WPP2019_PopulationByAgeSex_Medium.csv)
- [GBD Results](http://ghdx.healthdata.org/gbd-results-tool/result/711e32d76f87d29ff994fccef01512ab)

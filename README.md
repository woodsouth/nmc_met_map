# 国家气象中心诊断分析工具(NMC Diagnostic Tool,NMDT)
## Dependencies
Other required packages:

- numpy
- matplotlib
- basemap
- pandas
- cartopy
- cfgrib
- magics
- metpy
- nmc_met_io          请预先安装, 见https://github.com/nmcdev/nmc_met_io
- nmc_met_graphics    请预先安装, 见https://github.com/nmcdev/nmc_met_graphics
- nmc_met_base        请预先安装, 见https://github.com/nmcdev/nmc_met_base
- nmc_met_diagnostic  请预先安装, https://github.com/nmcdev/nmc_met_diagnostic
## Install
Using the fellowing command to install packages:
```
  pip install git+git://github.com/nmcdev/nmc_met_map.git
```

or download the package and install:
```
  git clone --recursive https://github.com/nmcdev/nmc_met_map.git
  cd nmc_met_map
  python setup.py install
```
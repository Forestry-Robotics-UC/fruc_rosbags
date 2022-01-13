# FRUC ROSBAGS
## Version 0.1 (M. Eduarda Andrada)

## Overview

This package includes custom roslaunch and rviz files to launch [zenodo's dataset](https://zenodo.org/record/5751906#.YdRin9vLeV4) in labeled forest


**Keywords:** rosbags, zenodo, semfire

**Note:** save bags *as is* to the folder /rosbags

## 2019/2020 Quinta do Bolao Coimbra
### Rviz custom configuration
Quinta do Bolao Part1
![Bolao part1 image](doc/bolao_part1.png)

Quinta do Bolao Part2
![Bolao part2 image](doc/bolao_part2.png)

### Launch Files
```
roslaunch fruc_rosbags 2019_2020_quinta_do_bolao_coimbra_part1.launch
roslaunch fruc_rosbags 2019_2020_quinta_do_bolao_coimbra_part2.launch
```

## 2021 CTCV Parking Lot Coimbra
### Rviz custom configuration
![CTCV image](doc/ctcv.png)
### Launch Files
```
roslaunch fruc_rosbags 2021_ctcv_parking_lot_coimbra.launch 
```

## 2020 Sete Fontes Forest
### Rviz custom configuration
![Sete Fontes image](doc/sete_fontes.png)
### Launch Files
```
roslaunch fruc_rosbags 2020_sete_fontes_forest.launch
```
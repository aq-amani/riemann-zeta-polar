# About this project
Plots and animates the Riemann Zeta function in polar coordinates for s=0.5+jt (critical line) in 2D and 3D

## :hammer_and_wrench: Setup/ Preparation
```bash
pipenv install --ignore-pipfile --skip-lock --python 3.9
pipenv shell
```
If faced by `UserWarning: Matplotlib is currently using agg, which is a non-GUI backend, so cannot show the figure.`
```bash
sudo apt-get install python3.9-tk
```

## :rocket: Usage examples:

#### Script options
```bash
python riemann_zeta_polar.py -h

  -h, --help     show this help message and exit
  -m , --mode    3d or 2d
  -s , --start   Starting value for imaginary part of input
  -e , --end     Ending value for imaginary part of input
  -a, --animate  Animate flag
```

#### Static plot in 2D
```bash
python riemann_zeta_polar.py -m 2d
```
#### Animated 2D plot
```bash
python riemann_zeta_polar.py -m 2d -a
```
#### Static plot in 3D
```bash
python riemann_zeta_polar.py -m 3d
```
#### Animated 3D plot
```bash
python riemann_zeta_polar.py -m 3d -a
```

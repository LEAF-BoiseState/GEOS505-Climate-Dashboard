# Front End

### Preliminary notebooks and figures for populating the climate dashboard for the Pacific Northwest using Panel.

GEOS 505: Research Computing in the Earth and Environmental Sciences

Fall 2022

__Contributors:__ 
- [Aman KC](https://github.com/amankc)
- [Kachinga Silwimba](https://github.com/kachingasilwimba)
- [Naheem Adebisi](https://github.com/Surfix) 
- [Patricia Oluchi Azike](https://github.com/PatriciaAzike) 
- [Phoebe Kinzelman](https://github.com/phoebekinzelman)
- [Rainey Aberle](https://github.com/RaineyAbe) 


Requirements for running notebooks are listed in the `environment.yml` file. This environment does not include the `panel` package, which should be installed in the base environment. 

See the `figures/` folder for sample interactive figures viewable in a web browser. To generate the figures, run the `make_figures.ipynb` notebook. The figures include:

- `chart_*.html`: line charts displaying the mean and standard deviation of each climate parameter over the selected time window (in this case, over one month). Values are averaged over the entire spatial region displayed. 
- `map_*.html`: map views of the average climate parameter over the entire time period (in this case, over one month)

Each figure listed above exists for the following parameters:
- `prate`: precipitation rate
- `sde`: snow depth
- `t`: air temperature
- `watr`: depth of surface water runoff 

# plant-restoration-size
A project aimed at determining the fasibility of using a monte carlo simulation to determine a minimum sample size. For more details please read my blog post on the project [here](https://medium.com/@f.vasquez.tavera/data-science-and-ecological-restoration-using-stats-to-save-time-and-money-5494726fe531)

This project was motivated by many long hours spent in the field counting plants, with the suspicion at the back of my mind that it was possible to obtain the same results with less work.

## Libraries and Modules Used:

### python:
*[numpy](https://numpy.org/)
*[pandas](https://pandas.pydata.org/)
*[CuPy](https://cupy.dev/)
*[progressbar2](https://pypi.org/project/progressbar2/)
*[matplotlib](https://matplotlib.org/)
*[defaultdict](https://docs.python.org/3/library/collections.html#collections.defaultdict)

## File Structure
plant-restoration-size/  
├── Figures/  
│   ├── croton-magdalenensis.jpg
│   ├── Fig1.png
│   ├── Fig2.png
│   ├── Fig3.png
│   ├── imgur1.png
│   ├── imgur2.png 
│   └── imgur3.png  
├── raw data/  
│   └── esmeraldat4.xlsx  
├── get_stat_params.ipynb
├── process_data.ipynb
├── README.md
└── t4_clean.p 

## How to run:
The data has been processed already. To see data preprocessing steps go to process_data.ipynb. To see the model, go to get_stat_params.ipynb. Any feedback is welcome!
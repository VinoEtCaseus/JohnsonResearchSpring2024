# William Dunnett - Professor Joseph Johnson Research Spring 2024 at Uconn

The goal of this research was to create a RNN model to predict next day prices on the financial market trained on synthetic data created by the TimeGAN generative adversarial network created by Yoon, Jarrett, and van der Schaar. This model would then be backtested on historical price data to determine its potential effectiveness. This research borrows techniques and code from Machine Learning for Algorithmic Trading Second Edition by Stefan Jansen.

## Required Libraries
```
conda install -c conda-forge::numpy scipy matplotlib pandas scikit-learn yfinance seaborn tqdm pathlib
pip install backtesting
pip install bokeh==2.4.3
```
and tensorflow >=2.13

## Credits
Machine Learning For Algorithmic Trading Second Edition by Stefan Jansen
https://github.com/PacktPublishing/Machine-Learning-for-Algorithmic-Trading-Second-Edition
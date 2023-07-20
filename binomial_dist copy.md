{
 "cells": [
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "# copy and paste the following statement\n",
    "# pip install pandas\n",
    "# pip install numpy\n",
    "# pip install scipy\n",
    "# pip install statistics\n",
    "# pip install matplotlib\n",
    "# pip install seaborn"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": []
  },
  {
   "cell_type": "code",
   "execution_count": 1,
   "metadata": {},
   "outputs": [],
   "source": [
    "# import libraries with their accronyms\n",
    "import numpy as np\n",
    "import pandas as pd\n",
    "import matplotlib as map\n",
    "import scipy as sc\n",
    "import statistics as stat\n",
    "from scipy.stats import binom"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 6,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/plain": [
       "0.007978646139382158"
      ]
     },
     "execution_count": 6,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "# Binomial distribution calculation: We need to identify\n",
    "# 1. number of tirals: n\n",
    "# 2. success rate: p\n",
    "# 3. value of interest: x\n",
    "# we are tossing a coin. How many chanses to see 3 times for heads for five tossing\n",
    "n = 10000\n",
    "p = 0.5\n",
    "x = 5000\n",
    "\n",
    "# calculation of binomial prob.\n",
    "binomial_pmf=binom.pmf(x,n,p)\n",
    "binomial_pmf\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": ".venv",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.8.5"
  },
  "orig_nbformat": 4
 },
 "nbformat": 4,
 "nbformat_minor": 2
}

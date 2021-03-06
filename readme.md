# Boston AirBnB Analysis

This is a notebook created to explore the main factors impacting price level and occupancy of an AirBnB
The data is based on Boston between September 2016 & September 2017. 
The hope is that this data can be applied in a general sense to any AirBnB listings.

## Results

The factors influencing the occupancy of an AirBnB are varied, but we've broken down the top factors that relate to having a high occupancy rate, and explored the relationship between pricing and quality of listings.
We found that the price is a marginal indicator of quality, and that the top factor impacting occupancy is the time of year, in combination with the review rating.
We also learned that AirBnB ratings are skewed, with the vast majority (~75%) being over 9/10.

The medium article is linked [here](https://omargurashi1.medium.com/how-to-get-the-most-out-of-your-airbnb-listing-6da32f59b00e)

https://omargurashi1.medium.com/how-to-get-the-most-out-of-your-airbnb-listing-6da32f59b00e



## Installation
Use the package installer (pip/conda) to install the below packages <br />
    1.  pandas <br />
    2.  numpy <br />
    3.  datetime <br />
    4.  seaborn <br />
    5.  matplotlib <br />
    6.  datetime <br />



## Files
rentals.ipynb : Jupyter notebook for the analytics. <br />

calendar.csv : Dataset containing the dates all listings were listed. <br />

reviews.csv : Dataset containing all the available reviews. <br />

listings.csv : Dataset containing each listings and some high-level statistics on it <br />
                - e.g average review rating, description, etc.
## Usage
Using the conda navigator, open the notebook.
Ensure the 3 csv files are in the same containing folder as the notebook in order to run the analytics correctly
Then run the notebook and view the results.
The graphs outputted are stored in the same folder as the notebook & the dataset.




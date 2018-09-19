### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

Requires Python3

First, ensure that you have the latest pip; older versions may have trouble with some dependencies:

```
pip3 install --upgrade pip
```
Then install the required libraries:
```
pip3 install jupyter
pip3 install numpy 
pip3 install pandas
pip3 install scipy
pip3 install matplotlib
pip3 install seaborn
```

## Project Motivation<a name="motivation"></a>
Using the Boston Airbnb dataset I wanted to answer these questions:
1) How have price and availability changed over time, and what time of year has the highest price?
2) What are the differences between Boston neighborhoods in terms of price, availability, and review ratings?
3) What features in the data have the biggest impact on price?

## File Descriptions <a name="files"></a>
I used the data from calendar.csv and listings.csv.
BostonAirbnb.ipynb is the Python notebook with analysis and code.

## Results<a name="results"></a>
I observed:
1) Increased aggregate availability has reduced the average price over time.
2) Which neighborhoods have skews in price distribution positively and skews in rating reviews negatively.
3) Which features in the dataset have the greatest influence on price, primarily neighborhood.

Please see the notebook for more details.

## Licensing, Authors, Acknowledgements<a name="licensing"></a>
This dataset is part of Airbnb Inside, and the original source can be found here: http://insideairbnb.com/get-the-data.html.
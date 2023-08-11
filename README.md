# Starbucks Promotion Analysis

<br>
<div align="center">
<img src="https://opj.ca/wp-content/uploads/2018/02/New-Starbucks-Logo-1200x969.jpg" width="250" height="200">
</div>
<br>

### Table of Contents

1. [Installation](#installation)
2. [Project Description](#project-description)
    - [Background information](#background-info)
    - [Data](#data)
    - [Objectives](#objective)
3. [File Structure](#files)
4. [How to interact](#interact)
5. [Licensing, Authors, and Acknowledgements](#licensing)


## 1. Installation <a name="installation"></a>
* The virtual environment [.starbucks_env]() contains all Python packages to run all notebooks and `.py` file.
* The code should run with no issues using Python versions 3.*. Currently using `Python 3.11.3` on `Windowns 11`.

## 1. Project Description <a name="project-description"></a>

### 1.1. Background information <a name="background-info"></a>

### 1.2. Data <a name="data"></a>

The datasets that were used in this project was originally provided by Starbucks as a take-home assignment for their job candidates. So it's a real Starbucks experiment.

There are about 120,000 data points split in a 2:1 ratio among training and testing set. 

In the experiment simulated by the data, an advertising promotion was tested to see if it would bring more customers to purchase a specific product priced at $10. Since it costs the company 0.15 to send out each promotion, it would be best to limit that promotion only to those that are most receptive to the promotion.

<p ><img src="images/screenshot-data.png" alt="image" ></p>

Each data point includes one column indicating whether or not an individual was sent a promotion for the product, and one column indicating whether or not that individual eventually purchased that product. Each individual also has seven additional features associated with them, which are provided abstractly as V1-V7.

### 1.3. Objectives <a name="objective"></a>

1. Use the training data to understand what patterns in V1-V7 indicate that a promotion should be provided to a user
2. Calculate Incremental Response Rate (IRR) and Net Incremental Revenue (NIR)
3. Build a model to select the best customers to target that maximizes the `IRR (Incremental Response Rate)` and `NIR (Net Incremental Revenue)`.

**Note**:

- **Treatment group**: the group in which customers were sent out promotion

- **Control group**: the group in which customers were NOT sent out promotion


## 2. File Structure<a name="files"></a>



## 3. How to interact<a name="interact"></a>



## 4. Licensing, Authors, and Acknowledgements<a name="licensing"></a>


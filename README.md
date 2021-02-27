<p align="left"><img src="https://cdn-images-1.medium.com/max/184/1*2GDcaeYIx_bQAZLxWM4PsQ@2x.png"></p>

# __ih_datamadpt0420_project_m2__

![Image](https://robbreport.com/wp-content/uploads/2019/05/lab-grown-diamonds.jpg?w=1000)


## :chart_with_downwards_trend: **Introduction**

Our goal is to analyze the key elements that affect diamonds price based on its features. 

:woman_technologist: How can you get this information?

In this repository you will find the following files:

* Data clean
* Exploratory data analysis (EDA)
* Dashboard on Tableau Public

## :chart_with_upwards_trend: Technology Stack

* Python
* Pandas
* Numpy
* Seaborn
* Scipy

## :bar_chart: Key Findings

* **Carat:** is the most relevant metric to stablish a diamond's value, having an exponential relationship.
* **Cut:** is not a major feature to determinate the price. In fact, Fair cut is related to the most expensive diamonds even though it is not the greatest cut. 
* **Color & Clarity:** They both have a linear relationship with average price.

### :rocket: **Bonus: Hypothesis Testing**

**Test 1 - one sample vs constant hypothesis test.** 
Average price of Diamonds is around 4.000USD and validated after testing

**Test 2 - two independent samples.** 

- **Sub-Test 1:** Fair cut + color G vs. Fair cut + color I

- **Sub-Test 2:** Good cut + color E vs. Good cut + color F

- **Sub-Test 3:** Ideal cut + color D vs. Ideal cut + color E

- **Sub-Test 4:** Premium cut + color D vs. Premium cut + color E

- **Sub-Test 5:** Very Good cut + color I vs. Very Good cut + color J

- **Sub-Test 6:** All cuts + color D vs. All cuts + color E

Null Hypthotesis was confirmed as outcome of all tests, which mean that in all tests they have similar prices. 

## :open_file_folder: Folder Structure

``` 
└── ih_datamadpt1120_project_m2
    ├── README.md
    ├── data
    │   ├── diamonds_clean.csv
    │   └── diamonds_train.csv
    ├── notebooks
    │   ├── EDA and ab testing.ipynb
    │   └── cleaning_diamonds_data.ipynb
    └── images
```

## :mailbox: Contact info

For questions, suggestions and other inquiries... here is my email address [marina.fernandez@gmail.com](m.fernandezban@gmail.com)

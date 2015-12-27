# RefDB Data Analysis App

RefDB is a NMR protein database. It collects all the re-correct NMR data which can be used for NMR referencing correction. 

## Background: 
NMR is a powerful tool for studying protein structure, dynamics, and interaction perturbations. However, the quality of these NMR studies directly depend on the quality of the referencing, since chemical shift values for specific nuclei in proteins are relative to a “reference” value. Often, protein NMR studies are inevitably caught in a “chicken-egg dilemma”—a circle between reference correction and assignment: a correct reference is required for a decent assignment, and a coherent assignment is needed to validate the correct referencing. 
We are developing an analysis that circumvents this dilemma utilizing a phenomenon known as “secondary chemical shifts”, representing the correlation between the secondary structure and the chemical shifts. 

## Motivation:
Any research in proteins will encounter two type of technologies: NMR (nuclear magnetic resonance) and crystallography. Due to many reasons, NMR is superior in flexibility and convenience. And the data collected from NMR are easy to much intuitive and easy to understand. However as mentioned in the background, NMR has a fundamental issue: it's need reference before any analysis. 

Therefore, to better understand the RefDB data, I made this app that illustrate all the statistics in the dataset. 

## Instruction:
The uses are not required to input any values, instead defined values will be give in dropbox or sidebars. 

### RefDB Raw Data

![RefDB Raw Data](https://github.com/billchenxi/DataProduct/blob/master/images/RefDBRawData.png)

* To change the amino acid or secondary structure or resonance, the user can use the dropbox showed in the "Control" panel. 

### RefDB statistics

![RefDB Statistics](https://github.com/billchenxi/DataProduct/blob/master/images/RefDBStatistics.png)

* In the RefDB Statistics section, I listed all the mean and standard deviation from the RefDB dataset. You can re-order the data by clicking the double arrow next to the column names. 
* Also You can change the the type of statistics by using the dropbox at the top of the page. Currently there are only two type of statistics: alpha carbon and beta carbon.
* If needed the author can also use the search box to find what they are looking for.

### Normality Test

![Normality Test](https://github.com/billchenxi/DataProduct/blob/master/images/NormalityTest.png)

Normality test section is report images as out put for all the data. The original reason to do the normality test is to verify the classical analysis is applicable to these data.

### More Info

![More Info](https://github.com/billchenxi/DataProduct/blob/master/images/MoreInfo.png)

This section list my contact information and my github link.

# Feel free to send me your comments, questions and request: [Bill (Xi)](billchenxi@gmail.com)







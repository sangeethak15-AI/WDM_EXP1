### EX1 Creation of Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform Preprocessing
### DATE: 
### AIM: 
  To Create Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform preprocessing
### PROCEDURE: 
1) Open Start -> Programs -> Accessories -> Notepad
2) Type the following training data set with the help of Notepad for Employee Table.

```
--------------
Employee Data
---------------
@relation employee 
@attribute name {zoe,luna,viki,suki,gigi} 
@attribute id numeric
@attribute salary {low,medium,high} 
@attribute exp numeric
@attribute gender {male,female} 
@attribute phone numeric

@data
zoe,111,low,5,male,124535 
luna,122,high,4,female,512546 
viki,133,medium,6,male,37123 
suki,144,low,2,female,210345 
gigi,155,high,4,male,501245

--------------
Weather Data
---------------
@relation weather
@attribute outlook {sunny,rainy,overcast}
@attribute temparature numeric 
@attribute humidity numeric
@attribute windy {true,false} 
@attribute play {yes,no}

@data 
rainy,65.0,70.0,false,no 
sunny,80.0,86.0,true,yes 
overcast,63.0,66.0,false,no 
sunny,80.0,76.0,false,no 
sunny,85.0,70.0,false,no 
overcast,65.0,65.0,true,yes 
rainy,64.0,75.0,false,no 
overcast,72.0,65.0,true,yes 
overcast,75.0,70.0,false,yes 
sunny,80.0,75.0,false,yes
```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows employee table on weka.

### OUTPUT:
Training Data Set -> Employee Table
![exp 1a](https://github.com/sangeethak15-AI/WDM_EXP1/assets/93992063/a5b032ea-6b04-4a39-9f8a-922497821f1f)

Training Data Set-> Weather Table
![ex 1b](https://github.com/sangeethak15-AI/WDM_EXP1/assets/93992063/efedb4c0-5a90-4359-833a-1dcecb8864b8)



### PREPROCESSING
### Procedure:
#### 1) Add -> Pre-Processing Technique:
1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Add.
9) A new window is opened.
10) In that we enter attribute index, type, data format, nominal label values for Climate.
11) Click on OK.
12) Press the Apply button, then a new attribute is added to the Weather Table.
13) Save the file.
14) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:

Employee Table after adding new attribute ADDRESS:

![exp 1d add](https://github.com/sangeethak15-AI/WDM_EXP1/assets/93992063/7e35060f-de09-4db4-b259-7f12ccf038c1)

Weather Table after adding new attribute CLIMATE:

![exp 1c add](https://github.com/sangeethak15-AI/WDM_EXP1/assets/93992063/2a201e44-914d-46a2-9b5f-c9929d6f6d7f)

### 2) Remove -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Remove.
9) Select the attributes windy, play to Remove.
10) Click Remove button and then Save.
11) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:

![exp 1c remove](https://github.com/sangeethak15-AI/WDM_EXP1/assets/93992063/a1d7db8f-4ee2-42fd-98b2-7c28495ff580)

![exp 1d remove](https://github.com/sangeethak15-AI/WDM_EXP1/assets/93992063/c963a374-d6d5-4dfc-8a38-90c5bbcc3e5b)


### Normalize -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Normalize.
9) Select the attributes temparature, humidity to Normalize.
10) Click on Apply button and then Save.
11) Click on the Edit button, it shows a new Weather Table with normalized values on Weka.

### OUTPUT:
### RESULT: 
  Thus the program for generating employee and weather datasets has been developed, and preprocessing has been accomplished successfully.

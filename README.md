### EX1 Creation of Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform Preprocessing
### DATE: 10.02.24
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
@attribute name {yuji,hinata,gojo,rin,megumi} 
@attribute id numeric
@attribute salary {low,medium,high} 
@attribute exp numeric
@attribute gender {male,female} 
@attribute phone numeric
@data 
yuji,101,low,5,male,250345 
hinata,102,high,2,female,234567
gojo,103,medium,3,male,278685
rin,104,low,4,female,280695
megumi,105,high,1,male,218384

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
rainy,80.0,90.0,false,no 
overcast,75.0,85.0,true,yes
sunny,85.0,95.0,false,no
rainy,73.0,86.0,false,no 
overcast,87.0,93.0,false,yes 
sunny,63.0,70.0,true,yes 
rainy,78.0,88.0,false,yes 
overcast,93.0,95.0,true,no
sunny,71.0,73.0,false,yes 
rainy,91.0,92.0,false,no

```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows employee table on weka.

### OUTPUT:

* Training Data Set -> Employee Table
![1w](https://github.com/Lakshmipriya-P-AI/WDM_EXP1/assets/93427923/36a6b9fd-2a1c-47f1-9be5-de254ab3464c)

* Training Data Set-> Weather Table

![1bans](https://github.com/Lakshmipriya-P-AI/WDM_EXP1/assets/93427923/77233a56-328c-46a8-8315-321f2c228035)

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
* Employee Table after adding new attribute ADDRESS

![1dadd](https://github.com/Lakshmipriya-P-AI/WDM_EXP1/assets/93427923/44a05854-ace9-4d13-befd-ab36a8ff47a6)

* Weather Table after adding new attribute CLIMATE:

![1cans](https://github.com/Lakshmipriya-P-AI/WDM_EXP1/assets/93427923/5cb982d1-2e6f-4bed-8e1b-553099666eda)

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
* Employee Table after removing attributes SALARY, GENDER:

![idrem](https://github.com/Lakshmipriya-P-AI/WDM_EXP1/assets/93427923/19a03555-080c-4fd0-8853-55aca05e7fe2)

* Weather Table after removing attributes WINDY, PLAY:

![1cansremove](https://github.com/Lakshmipriya-P-AI/WDM_EXP1/assets/93427923/e41d7202-15eb-4ad2-9cfb-bb691a956bb8)

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

* Employee Table after Normalizing ID, EXP, PHONE:

![1dnorm](https://github.com/Lakshmipriya-P-AI/WDM_EXP1/assets/93427923/48a8fa21-451f-49dc-b21d-36e35e9f32a1)

* Weather Table after Normalizing TEMPARATURE, HUMIDITY:

![1cansnorm](https://github.com/Lakshmipriya-P-AI/WDM_EXP1/assets/93427923/97c1c104-aec2-4d9d-a5ab-3709e22a0e72)

### RESULT: 
  Thus the program for generating employee and weather datasets has been developed, and preprocessing has been accomplished successfully.

# WDM-Ex.NO-1B--WEATHER-TABLE
## Name: CHITHRADHEEP R
## Reg.no: 2305002003
## Aim:
To create a Weather Table with the help of Data Mining Tool WEKA.
## Description:
We need to create a Weather table with training data set which includes attributes like outlook, temperature, humidity, windy, play.
## Procedure:
Steps:
1)	Open Start  Programs  Accessories  Notepad
2)	Type the following training data set with the help of Notepad for Weather Table.

@relation weather
```@attribute outlook {sunny,rainy,overcast} 
@attribute temparature numeric
@attribute humidity numeric
@attribute windy {true,false} 
@attribute play {yes,no}

@data 
sunny,85.0,85.0,false,no 
overcast,80.0,90.0,true,no 
sunny,83.0,86.0,false,yes 
rainy,70.0,86.0,false,yes 
rainy,68.0,80.0,false,yes 
rainy,65.0,70.0,true,no 
overcast,64.0,65.0,false,yes 
sunny,72.0,95.0,true,no 
sunny,69.0,70.0,false,yes 
rainy,75.0,80.0,false,yes
```
3)	After that the file is saved with .arff file format.
4)	Minimize the arff file and then open Start  Programs  weka-3-4.
5)	Click on weka-3-4, then Weka dialog box is displayed on the screen.
6)	In that dialog box there are four modes, click on explorer.
7)	Explorer shows many options. In that click on ‘open file’ and select the arff file
8)	Click on edit button which shows weather table on weka.
 
## Training Data Set  Weather Table
<img width="734" height="786" alt="image" src="https://github.com/user-attachments/assets/6b9fc32f-5617-4065-959b-89fe43ba4e4e" />

## Output:
<img width="597" height="516" alt="image" src="https://github.com/user-attachments/assets/7292631c-be7d-443c-b400-b7c16c5320df" />

## Result:
Thus the weather table has been created successfully using weka tool.

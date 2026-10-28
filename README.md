WDM-Ex.NO-1B--WEATHER-TABLE
Name: CHITHRADHEEP R
Reg.no: 2305002003
Aim:
To create a Weather Table with the help of Data Mining Tool WEKA.

Description:
We need to create a Weather table with training data set which includes attributes like outlook, temperature, humidity, windy, play.

Procedure:
Steps:

Open Start  Programs  Accessories  Notepad
Type the following training data set with the help of Notepad for Weather Table.
@relation weather

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
After that the file is saved with .arff file format.
Minimize the arff file and then open Start  Programs  weka-3-4.
Click on weka-3-4, then Weka dialog box is displayed on the screen.
In that dialog box there are four modes, click on explorer.
Explorer shows many options. In that click on ‘open file’ and select the arff file
Click on edit button which shows weather table on weka.
Training Data Set  Weather Table
image
Output:
image
Result:
Thus the weather table has been created successfully using weka tool.

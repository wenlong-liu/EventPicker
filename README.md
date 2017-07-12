# EventPicker version 0.1

This simple Python GUI is to help researchers locate and _pick_ a storm event that fit their standards.

### Usage
Copy the codes to your local directory, then open CMD:

    python ChartPickerGUI.py 
    
### Introduction

#### Input file 
  The input should be a csv file whose format as follows:

Date,Flow, Solute

3/28/2015 0:00,882,23

3/28/2015 0:15,861,25

3/28/2015 0:30,839,124

3/28/2015 0:45,860,56

#### GUI 


draw the scatter picture on the panel.
Click the point you want to save.
export the csv file named "export.csv" which can be generated automatically.

All you have to do is
> python ChartPickerGUI.py

The python module you need install as follows:

wxpython

numpy

matplotlib

mpldatacursor

Recommend:
>pip install pyinstaller

>pyinstaller ChartPickerGUI.py

pyinstaller would be a great idea to convert Python scripts into Windows executable program.


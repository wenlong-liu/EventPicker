# EventPicker version 0.1.1

This simple Python GUI is to help researchers locate and _pick_ a storm event that fit their standards.

### Usage
Copy the codes to your local directory, then open CMD:

    python EventPicker.py 
    
### Introduction

#### Input file 
  The input should be a csv file whose format as follows:


|Date|Flow |Solute|
|----------------|:---------:|---------:|
|3/28/2015 0:00|882|23|
|3/28/2015 0:15|861|25|
|3/28/2015 0:30|839|124|
|3/28/2015 0:45|860|56|

#### GUI 
The GUI should look like this:


![image](https://github.com/wliu2016/EventPicker/blob/master/Resources/GUI.png)

#### Step by Step
* Click _Browse_ to choose file;
* Click import data now! to plot data in the panel;
* You can span, zoom and reset the plot to help you check the data;
* If identifying an event, click once for starting point and another time for ending points.
* If making a mistake, you can _delete selected one_ to remove the pick.
* _Export data now!_ to export data in results.csv.

#### Requirements

The python module you need install as follows:

> wxpython

> numpy

> matplotlib

> mpldatacursor

#### We also have pre-packed exe file, please download below:

Windows 32 bit [Coming soon]()

Windows  [64 bit](https://drive.google.com/a/ncsu.edu/file/d/0BxUa1f0vxQ_kN19mOGVXUjEteVE/view?usp=sharing)

#### License

MIT

#### Problems and Comments, please reply [Issue](https://github.com/wliu2016/EventPicker/issues/1)
![header](https://capsule-render.vercel.app/api?type=waving&color=gradient&height=300&section=header&text=Programming%20for%20Engineers2&fontSize=50&&fontColor=000000&animation=fadeIn&fontAlignY=38&desc=Team%20A2%20Project&descAlignY=51&descAlign=80)
## **Index**

1. [Overview](#overview)  
2. [Installation](#installation)  
3. [Environment](#environment)  
4. [Usage instructions](#usage-instructions)  
5. [Collaborators and contact info](#collaborators-and-contact-info)  

***

## **Overview**

This python project is a tool to analyze measured a single or multiple .xml data frames, with its output being a .png plot and a xml file, according to customer demands.
***

## **Installation**

To install all the required modules just use the following command: 

```
pip install -r requierements.txt
```

***

## **Environment**

  - Windows10/11
  - Python 3.8

***

## **Usage instructions**

  1. Execute run.py
  2. Insert the desired wafers to analyze as shown in the example: 
  ```
  D07 D08
  ```
  In case o wanting to analyze all the wafers use command *all* instead: 
  ```
  all
  ```
  3. Insert the coordinates to analyze following the next format: 
  ```
  -4,-4/-4,3/0,1/1,-1
  ```
  Where the first term is the row the second the column number. To separate the coordinates simply use "/". In case of wanting to analyze all the possible coordinates just use the command *All*
  ```
  all
  ```
  4. Choose if you want to float the png files after executing the code. To accept just type: 
  ```
  y
  ```
  To deny type:
  ```
  n
  ```
  5. Choose if you want to save the plotting. To accept just type: 
  ```
  y
  ```
  To deny type:
  ```
  n
  ```
  6 Choose if you want to save a xlsx file of the selected data. To accept just type: 
  ```
  y
  ```
  To deny type:
  ```
  n
  ```

***

  ## **Collaborators and contact info** 
  Seo Jinchan :
  sjhmp21@hanyang.ac.kr
  
  Kim Chanyoung :
  belljy@hanyang.ac.kr
  
  Jose Alan Barraza Villaverde : 
  al167694@alumnos.uacj.mx

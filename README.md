# YCAC-data-splitter
Script allows split and organize YCAC data frame by titles and composers 

## Installing
Please install pip and run command line below in the same directory where 'requirements.txt' exists in order to install packages required to run.
```
$ pip install -r requirements.txt 
```
## Running the tests
Command looks like
```
$ python splitter.py -i directory_name
```
>for example:
```
$ python splitter.py -i YCAC-data-1
```
>Auto dir generator by composer's names
>>![](dump_files/auto_dir_generator.gif)

>Generating .csv files by title
>>![](dump_files/automation.gif)

## Input & Output
Input
>Link to Yale Classical Archives
>>https://ycac.yale.edu/

Output
>Link to Google drive(private)
>>Single .csv file name format : "title by composer.csv"
>>https://drive.google.com/file/d/1NWwg0FcHZgk-8is8u8rEdqMOwYFiC0YT/view?usp=sharing

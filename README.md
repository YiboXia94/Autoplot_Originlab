# Double-click the data file and automatically generate a line graph in Originlab

### This is a script that allows you to skip selecting the data column and draw simple graphics directly.
Open a text and input:

start `C:\"Program Files"\OriginLab\Origin2017\Origin94_64.exe -r {impasc %1;plotgroup iy:=(A,B) type:=line template:=LINE2}`

and save it as a `.bat` file.

Add it as a default opening method to your data file, and just double-click the file, then you can obtain the plot directly.

### Some settings:
Set the path of Originlab: `C:\"Program Files"\OriginLab\Origin2017\Origin94_64.exe`

Set the plot group & plot style: Column A vs Column B: `iy:=(A,B)`; Column A vs Column B&C: `iy:=(A,B:C)`

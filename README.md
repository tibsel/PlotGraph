# PlotGraph - A Sublime Text 3 Package

Select the numbers you want to see plotted (with one selection). 
If other content is also selected, that's ok,
because the selection will be filtered for numbers.

Once the selection is made, hit [F3] to create a matplotlib window.

If you select one column of numbers, they will be printed over their index.

 0.0
 4.0
 3.0
 5.0
 5.0
 5.0
 4.0
 0.0 


If you select two columns, the first one will be used as the values on the 
abscissa/x-axis and the second column as the values on the ordinate/y-axis.

 1.0 0.0 
 2.0 4.0 
 3.0 3.0 
 4.0 5.0 
 5.0 5.0 
 6.0 5.0 
 7.0 4.0 
 8.0 0.0 


If more than two columns are selected, the first one will be used as the values 
on the abscissa/x-axis. The other columns will be printed as values on the 
ordinate/y-axis for different curves.

 1.0 0.0 11.1
 2.0 4.0 11.2
 3.0 3.0 11.3
 4.0 5.0 11.4
 5.0 5.0 11.5
 6.0 5.0 11.6
 7.0 4.0 11.7
 8.0 0.0 11.8


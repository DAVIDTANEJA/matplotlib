## Matplotlib 
###### is an visualization library in Python for 2D plots of arrays. Matplotlib is a multi-platform data visualization library built on NumPy arrays and designed to work with the broader SciPy stack.


## plots :

-Bar chart             # plt.bar()                                                                                  
-horizontal bar chart   # plt.barh()                                                                                   
-histogram              # plt.hist()                                                                               
-scatter plot           # plt.scatter()                                                                                
-stack plots            # plt.stackplot()                                                                                 
-Pie chart              # plt.pie()                                                                                      
 
** Save chart to file   # plt.savefig()                                                                                 
-doughnut chart         # using 2 times " plt.pie() " with 'radius' and color='w' white                                   

->Using style sheets ,                                                                                                   
print(matplotlib.style.available)   # <- this cmd gives you all available styles                                          
plt.style.use('ggplot')      # by this method use style sheets , but before plotting use this cmd                          
 
->Plot annotations                                                                                                     
 
-Pandas crosstab()   # pd.crosstab().plot()                                                                             

->load data from files                                                                                                   
->live graphs                                                                                                         
->subplots                       #  fig.add_subplot()  ,  plt.subplot2grid()                                            
->3-D plots (scatter, bar)

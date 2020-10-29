# Samples of code which display proficiency working with pandas DataFrames and Numpy, and Matplotlib:

###### I have learned how to read-in, examine, and perform element-wise changes to items to values in pandas DataFrames, as well as index, slice, and clean data, and finally display it. Sample code has been provided below to demonstrate select skills.



    import pandas as pd
    import numpy as np
    import matplotlib.pyplot as plt
    
    dat = pd.read_csv('s10.csv')
    
    dat.head(5)
    
    dat.tail(25)
    
    ##The following code is an example of how I've performed an element-wise change to each item in the column labeled 'column_name' within the .dat DataFrame:
    
    dat.column_name = dat.column_name*1234
    
    ##This line of code displays my integrating Exploratory Data Analysis of the .dat DataFrame with indexing using the pandas .loc accessor: 
    
    np.mean(dat.loc[0:26])
    
    ##This method can be used to remove rows containing NaN values        from the .dat DataFrame:
    
    dat.dropna()
    
    ##I've also become familiar with pandas methods such as .describe(), which have allowed me to quickly analyze and evaluate newly imported data:
    
     dat['column_name_2'].describe()

    ##Finally, I've learned how to visualize data contained in DataFrames using Matplotlib's .pyplot sub-package, and native pandas methods for visualization, including features such as:
    
    dat['column_name_2'].plot()
    
    plt.xlabel('label for x-axis')
    plt.ylabel('label for y-axis')
    plt.title('Title of line plot for data in column_name_2')
    
    plt.show()
    
    ##and, using pandas' own plotting methods, such as:
    
    dat.hist()
    

###### I am currently working on learning more advanced pandas methods for working with data, such as the .groupby() and plot_table() methods, which will help me improve my ability to quickly work with data in a more eloquent way. I look forward to sharing my future progress with you!



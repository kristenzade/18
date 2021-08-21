# 18

## Results
First cleaned the data to find the tradable cryptocurrencies. 
Next, I reduced the dimensions of the dataset using PCA and then clustered the cryptocurrencies using K-Means. Finally, I visualized the results with a 3D scatter plot and an hvplot scatter plot.

The plots show four different groups of cryptocurrencies, two of which
are clustered closely together (these also contain the most cryptocurrencies).


- **3D Scatter Plot with PCA Data and Clusters**

![3D_Scatter](https://user-images.githubusercontent.com/80402142/130336517-02d6fc47-ac79-49f4-8c00-5f418b20dce0.png)


- **hvplot Scatter Plot**
![hvplot_scatter](https://user-images.githubusercontent.com/80402142/130336521-dffaa523-44f5-4922-8635-5231f387bb53.png)



## Dependencies
- Jupyter Notebook
- Python v3.x
    - Pandas
    - hvPlot
    - Path
    - Plotly
    - SciKit-Learn

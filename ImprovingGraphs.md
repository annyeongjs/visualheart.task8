###The Quakers

#####[ecdf.R](https://github.com/SunnySunnia/TheQuakers/blob/master/ECDF/ecdf.R)
  - **Code Functionality**
    - It had trouble opening the 250.csv file but once I figured that out, the code ran smoothly
  - **What to Improve**
    - <del>The plots need an x axis label
    - <del>Does the x-axis represent 100 year intervals? If so, what is the starting year?
    - <del>The x-axis should be shifted so that it starts at 0 instead of -100
  - **Improvements** (by Qi Zhang)

    I improved ecdf.R and made it more user-friendly. The improvement includes
    - Added x axis label in terms of date. This essentially addresses all 3 items mentioned above.
    - Added horizontal grids to make it easier to read.
    - Some important settings are hard coded in the original code, e.g. boundary of magnitude interval, location of vertical grid etc. So it works fine with 250.csv but not the new records which contain 6598 events from 1932 to 2013. The new code will setup these settings adaptively to make it work with data of any size.
    - Wrap up the code as a function, the only argument required is the data frame loaded from data file. I verified the code with both the 250.csv and the new records of events from 1932 to 2013.
    - New code and plots can be found in the ECDF_IMPROVED folder.

#####[etas-training.R](https://github.com/SunnySunnia/TheQuakers/blob/master/MDA/etas-training.R)
  - **Code Functionality**
    - I had to make sure to have the right file name for "socal.txt" and "VS-functions.R" before I could run the code but once I did, the code ran smoothly. 
  - **What to Improve**
      - Better documentation about what csv files you have to download to your computer before running the code. Is there a way to quickly download all the necessary csv files?
      - The graph is already pretty informative and easy to read. Maybe important k-values could be indicated on the graph.
      - For the graph to be descriptive on its own, I think the x and y labels should specify in words what v and t stand for. 

#####[mda_test.r](https://github.com/SunnySunnia/TheQuakers/blob/master/MDA/mda_test.r)
  - **Code Functionality**
    - runs smoothly but slow
  - **What to Improve**
    - The graphs already look pretty good but I think it would be difficult for someone to understand what the graphs are trying to show without more information
    - What do the different colors represent in the "Area under Error Diagram" plot?
    - It's a little hard to distinguish the colors in the "Error Diagrams of the Models" plot
    - The "Training set error diagrams" plot does not have a legend
    - A better x-label for the "Area under Error Diagram" plot if possible
    - If there are any interesting/informative points on the graphs, it would be helpful if they were indicated
      -k values, outliers, etc. 

#####[Quakers-MDAtest250.R](https://github.com/SunnySunnia/TheQuakers/blob/master/MDA/Quakers-MDAtest250.R)
  - **Code Functionality**
    - I got an error at first because I had to install.packages("sfsmisc")
    - otherwise, code runs smoothly
  - **What to Improve**
    - The second graph that is plotted doesn't have any titles and I'm not sure what it is trying to show. A legend needs to be added
    - A legend needs to be added to the "Training Set error Diagrams" plot

#####[Quakers-EarthquakeSuccessors.R](https://github.com/SunnySunnia/TheQuakers/blob/master/Successors/Quakers-EarthquakeSuccessors.R)
  - **Code Functionality**
    - I had a little trouble downloading the DataFrame but once I did, the code ran smoothly
    - DataFrame name was wrong
  - **What to Improve**
    - The graphs are colorful and contain a lot of data
    - I am having a little trouble figuring out what the graph is showing. 
    - The legend is just numbers 1-5. I'm not sure what these numbers correspond to.
    - Spoke with quakers and now understand what the graph is showing
    - The quakers need help figuring out how to obtain the k and mu value from these graphs
  - **Code Readability**
    - Should add comments and headers to the code; what it does and what to expect as an output
    - Should add estimated waiting times
  

###Hashtag

###Dollar Sign

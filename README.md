# lab-in-datascience
4 homework and final project in the class of Lab in DS (COM-490) at EPFL. The homeworks focus on data preprocessing, ETL tasks, predictions and data visualization.  The final project illustrates the entire pipeline from extracting data on CFF database, preprocessing, shortest path algorithm and visualization.

## Final Project
In this final project we built own robust public transport route planner from a SBB dataset. Given a desired arrival time, our route planner will compute the fastest route between departure and arrival stops within a provided confidence tolerance expressed as interquartiles. For instance, "what route from A to B is the fastest at least Q% of the time if I want to arrive at B before instant T". We used the Connection Scan Algorithml, handled data with PySpark and presented resutls with ipywidget.
      Delay Prediction  | Fastest Route
:-------------------------:|:-------------------------:
![](https://i.imgur.com/c5dxqDf.png)  |  ![](https://i.imgur.com/61Nhfta.png)

## Homework 1
The project Carbosense establishes a uniquely dense CO2 sensor network across Switzerland to provide near-real time information on man-made emissions and CO2 uptake by the biosphere. The main goal of the project is to improve the understanding of the small-scale CO2 fluxes in Switzerland and concurrently to contribute to a better top-down quantification of the Swiss CO2 emissions. The Carbosense network has a spatial focus on the City of Zurich where more than 50 sensors are deployed. Network operations started in July 2017.
      Prediction  | Visualization
:-------------------------:|:-------------------------:
![](https://i.imgur.com/C8Up4iy.png)  |  ![](https://i.imgur.com/sWJPhkY.png)

## Homework 2
In this part, we leverage Hive to perform exploratory analysis of data published by the [Open Data Platform Swiss Public Transport](https://opentransportdata.swiss) and to extract the hashtags from the source data, and then perform light exploration of the prepared data.
      Visualization  | Visualization
:-------------------------:|:-------------------------:
![](https://i.imgur.com/mxiXccT.png)  |  ![](https://i.imgur.com/k9l19Rj.png)



## Homework 3
The idea here is that when an event is happening and people are having a conversation about it on Twitter, a set of uniform hashtags that represent the event spontaneously evolves. Twitter users then use those hashtags to communicate with one another. Some hashtags, like #RT for "retweet" or just #retweet are used frequently and don't tell us much about what is going on. But a sudden appearance of a hashtag like #oscars probably indicates that the oscars are underway. In this notebook, we will use temporal information about Twitter hashtags to discover trending topics and potentially uncover world events as they occurred.
      PCA  | Time Series Analysis
:-------------------------:|:-------------------------:
![](https://i.imgur.com/KhQaiWw.png)  |  ![](https://i.imgur.com/lxNEAcA.png)

## Homework 4
For this homework, we worked with the real-time streams of the NS, the train company of the Netherlands. THe idea was to analyse time delay, proceed on live visualization of trains, use Kafka, and TEL on live data.
 ![](https://i.imgur.com/85pqU0l.png)

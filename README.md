# RealTimeDataAnalysisAndVisualization
BDA Project
Title: Real Time Analysis of Social Media’s Data in Multi-Cluster Environment
# !dea
The major goal of our project is to help the client to understand people's opinions and their effect on the market on the fly by capturing live data, processing it, analyzing it, and visualizing the results in real-time. For this project, we used Logical regression for sentiment analysis, naive- bayes classification for domain prediction which is supported by spark and spark streams.

# Technology used:
To achieve low latency we used Spark Eco System to Build ML Models, Preprocess and prediction.
Spark structured streams are core of the project
Visualisation part is handled by SQL and Dash(a Python Library).

![Architecture Big Data](https://user-images.githubusercontent.com/58078466/166297435-96fabb3b-5428-4317-8c31-501e0c68034b.png)


# Launching local server to pass tweets to local spark job
<img width="1209" alt="image" src="https://user-images.githubusercontent.com/58078466/166303240-ca7bf89c-0cc0-4946-8ac5-a530555587bd.png">
# Running spark job on back ground to pull live tweets from local servers as mentioned above and apply few transformation
<img width="1095" alt="image" src="https://user-images.githubusercontent.com/58078466/166303600-c575f7d7-993d-4c15-ae92-8c010ea12734.png">

# finally visuallized using sql, plotly and dash
<img width="989" alt="image" src="https://user-images.githubusercontent.com/58078466/166304110-6cea370e-7da1-4c9b-81c5-03f87425d437.png">
# ML 
<img width="1189" alt="image" src="https://user-images.githubusercontent.com/58078466/166304571-4608526b-89d8-48d3-becd-d5509e596e31.png">

# Outputs:
<img width="1920" alt="Screen Shot 2022-04-30 at 21 20 05" src="https://user-images.githubusercontent.com/58078466/166297497-6b5d09a4-c4f1-43b9-9fbe-542710411583.png">
<img width="1920" alt="Screen Shot 2022-04-30 at 21 20 21" src="https://user-images.githubusercontent.com/58078466/166297503-7c96f49c-7531-4b68-967b-39297628aeb2.png">

<img width="1920" alt="Screen Shot 2022-04-30 at 21 20 14" src="https://user-images.githubusercontent.com/58078466/166297487-892c8921-2b84-44a9-aece-b28e92aff905.png">

# conclusion
In this project, we had captured tweets related to United States stands towards Ukraine- russia war and from that findings more than 65% of tweets are related to Business and political domain, This results are showing war has significant impact on USA’s political and business domains and also social reach of popular tweet are also captured  

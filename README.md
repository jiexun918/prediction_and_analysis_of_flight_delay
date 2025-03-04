# prediction_and_analysis_of_flight_delay
**Research Motivation**
From the perspective of an frequent traveler, the motivation for research on the prediction and analysis of flight delays is centered on improving the overall travel experience and addressing the challenges and inconveniences associated with Tight delays. Here are key motivations:
1. Time Schedule and Management
Travelers have tight schedules and often plan their trips around speciZc timelines. Flight delays can disrupt these plans, leading to missed connections, late arrivals at destinations, and potential disruptions to scheduled activities. Research in this area aims to provide travelers with more accurate information about potential delays, enabling better time and schedule management.
2. Reducing Stress and Anxiety
Flight delays can be stressful and anxiety-inducing for travelers, especially when there is uncertainty about the duration of the delay. Knowing in advance about potential delays allows travelers to better prepare, manage expectations, and reduce the stress associated with unexpected disruptions to their travel plans.
In essence, the motivation for studying Tight delays from the perspective of a traveler is to enhance the predictability and reliability of air travel, ultimately providing a more seamless and stress-free experience for individuals navigating the complexities of modern air transportation.

**Problem Statement**
The world is separated into major continents therefore, air travel is a signiZcant mode of transport in connecting us for various purposes. In addition, air travel plays an important role in economy sectors for their passengers, airports, airline agencies even tourism around the world.
Despite of having a great advantage of connecting world with faster travelling time, one of major challenge in air travelling is Tight delay. Flight delay is not only about the passengers getting late to their destination, but it also carried much more issues especially in terms of economic. Airports needs to relocate their ground staff, rearranging their plane parking while airline agencies need to put up with more fares and fees to be paid to airport management. As for the passengers, some might miss connecting Tights or just having their plan all messed up which reTected badly on their satisfaction survey. Thus, Tight delay signiZcantly causes many economic disturbances to many parties, recognizing them through prediction may improve business decisions making by each parties involved. According to CBS News (2023), the percentage of delays due to circumstances out of the control of airlines increased from 5.2% in 2018 to 7.6% in 2023, resulting in thousands of more delayed Tights.
The purpose of this project is to predict and analyze Tight delays. All of which are intended to increase the effectiveness and dependability of air trafc control. Besides that, it also aimed to optimize operational efciency, and executing targeted interventions requires an understanding of the underlying causes of delays. The goal of the project is to deliver practical insights so that airlines may make wise decisions on scheduling, resource allocation, and strategic planning. 
<ins>https://ietresearch.onlinelibrary.wiley.com/doi/full/10.1049/itr2.12183 https://journalofbigdata.springeropen.com/articles/10.1186/s40537- 020-00380-z</ins> 
<ins>https://www.cbsnews.com/news/the-future-of-flying-more-delays-more-cancellations-more-chaos/</ins>

**Objectives**
1. To explore contributing factors that cause flight delay or through exploratory data analysis.
2. To build a parsimonious regression model to predict the departure delay of flights departing from Dallas/Fort Worth International Airport
(DFW), by including weather data.

**Dataset Overview**
For this project, we consider the dataset titled “2015 Flight Delays and Cancellations”.
This dataset is courtesy of the U.S. Department of Transportation's (DOT) Bureau of Transportation Statistics, retrieved from Kaggle. The department tracks the on-time performance of domestic Tights operated by large air carriers in the United States during the year 2015.
The dataset consists of three CSV Zles. The Brst Ble titled “airlines” contains IATA (International Air Transport Association) airline codes and names. It consists of 14 airline names and their respective IATA codes. The Zle has a dimension of 14 rows and 2 columns.
The second Ble, titled "Airports," contains IATA codes, names, city, state, country, and geographical coordinates of the airports. The Zle has a dimension of 322 rows and 7 columns.
The third Ble, titled "Flights," contains the summary information on the number of on-time, delayed, canceled, and diverted Iights. It includes details such as time, date, departure and arrival details, cancellations, delay reasons, etc. The Zle has a dimension of approximately 5.82 million rows and 31 columns.
https://www.kaggle.com/datasets/usdot/Tight-delays/data
Due to limited computational resorces, we limit our scope to predicting Tight departure delay for Tigts departing from Dallas/Fort Worth International Airport (DFW).
To build a more effctive prediction model, we included the weather data in DFW from https://www.weather.gov/fwd/f6. Selected weather attributes will be analysed and included in our prediction model. 

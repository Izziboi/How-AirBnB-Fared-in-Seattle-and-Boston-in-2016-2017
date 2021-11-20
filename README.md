# How-AirBnB-Fared-in-Seattle-and-Boston-in-2016-2017
This work is an assessment of the tourism business of AirBnB in the cities of Seattle and Boston USA 2016-2017, through data analysis.

Introduction: 
This work used python programs to analyze the data of both cities (Seattle and Boston).
In this repository, there are the following files:
1. boston_airbnb: This is the python program used to analyze the Boston data as compiled by AirBnB. It was created with Jupyter notebook.
2. seattle_airbnb: This is the python program used to analyze the Seattle data as compiled by AirBnB. It was also created with Jupyter notebook.
3. seattle_boston: This is a zip file of the datasets of both cities. Inside it are files boston_data and seattle_data, both of which are csv files.
A quick visualization of the files show that they are identical in structure, with 4 columns each, namely 'listing_id', 'date', 'available' and 'price'.

Analysis and Findings: 
Several analyses were conducted with findings made. It should be noted that Seattle is a large city and so, there were very many listings in the period under review. On the other hand, Boston is not as large and busy as Seattle. These economic factors possibly influenced the business activities that took place over the period. 
In the original datasets, there were 1,393,570 listings in Seattle but 459,028 of them were not available, while in Boston, there were 1,308,890 listings with 665,853 of them unavailable. As a result, only the available listings were analyzed.
In Seattle, a total of 3,723 different listing ids were used to list accommodations, while 2,906 were used in Boston. However, the listing id that was used most frequently, was used for 365 times for each of the cities. For Seattle, there were 678 of such listing ids, while Boston had 103. Furthermore, the listing ids that were used the fewest number of times, were used for only once for both cities. In Seattle, such ids were 7, while in Boston, there were 26.
For listing dates, there were 365 different dates that accommodations were listed for each of the cities. This means that accommodation listings were also done during weekends and holidays. A closer look at the number of listings done per day reveals that for Seattle, the minimum number of accommodations listed per day was 1,735, while the maximum was 2,922. For Boston, minimum number of accommodations was 570, while maximum was 2,207.
In terms of accommodation price, there were 669 different prices quoted for the various Seattle accommodations. In Boston, the range was rather wider – 1,246 different price tags. Coincidentally, the price tag that was quoted for most accommodations for both cities was $150.00. For Seattle accommodations, it was used to quote 36,646 accommodations, while it was the price of 20,752 accommodations in Boston. In both cities again, the price tags that were most rarely quoted were quoted only for one accommodation each. In Seattle, there were 66 of such different price tags, while there were 225 of such in Boston.

More About the Analyses:
In the programs used to analyze the data, there are many functions one can use to further explore and study the data. Most of them are basically meant to help in visualizing some of the feature variables of the data. For instance, some listing ids, dates and prices featured for several times. In order to visualize their distributions in the data, it is easier to take the long lists chunck by chunk. This is made possible by some of the functions. Some other functions display the feature variables side by side for possible comparison. Although there are no definite correlations among the features, it is still a good idea to view them. Moreover, contributors are welcome to make their inputs to further improve the functionalities of the programs.

Summary: 
By the foregoing, it can be deduced that in AirBnB, one listing id can be used repeatedly to list different accommodations. It can also be inferred that hosts can have their accommodations listed on AirBnB platform on any day of the year, including Christmas day. This means that AirBnB works all year round. Furthermore, as many accommodations as possible can be listed in a day, with different price tags according to peculiar factors considered by AirBnB. This means that there is no limit to the number of accommodations that can be listed in one day.

Conclusion: 
Looking at the two cities – Seattle and Boston – it is safe to say that Seattle is more commercial than Boston. This is evident in the fewer number of unavailable listing ids in Seattle, as well as the higher number of maximum accommodation listings per day in Seattle. What this means is that more people list their homes for tourist accommodation in Seattle than in Boston. However, there are more price options in Boston than in Seattle. While Seattle had 669 different price options, Boston had 1,246 options. It will be a good idea to increase the price options of Seattle accommodations to create more possibilities of patronage from members of the public. Meanwhile, it seems that most tourist customers were comfortable with the price of $150.00 as evident in both cities.

Acknowledgement:
I sincerely appreciate AirBnB for allowing its data to be used for this exercise. I also thank Udacity team for her tutorials. They helped me a lot in writing the programs of this project. Next is Mosh Hamedani and Daniel Chen whose videos also helped me in the coding. I salute all the people behind this help and say, thank you.

References:
1. https://classroom.udacity.com/nanodegrees/nd025/parts/5b4ccaa7-bdcd-4ea3-9538-97673aa035c4/modules/12e3e314-fb99-47e1-967b-b6620e3cff34/lessons/1c9dcfa1-01ed-4302-858a-c14bd8173edc/concepts/ac7b8917-6765-46ec-a17a-6ebdd71d67a4
2. https://www.youtube.com/watch?v=iYie42M1ZyU&t=848s
3. https://codewithmosh.com/courses/417695/lectures/9219316

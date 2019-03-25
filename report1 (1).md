# What is the Mother Tongue of U.S. Communities?

By watching the news, a person can assume that diversity is increasing rapidly in the United States. While the Census has praised the U.S. for becoming overall more racial and ethnically [diverse](https://www.census.gov/library/stories/2017/08/changing-nation-demographic-trends.html), FOX newscaster Tucker Carlson has claimed that the rise of immigrants in the U.S. is not happening in "politicians' neighborhoods" and that the increase of racial and cultural groups from non-western countries is changing the culture in American towns to an unprecedented and unmanageable [degree](https://www.youtube.com/watch?v=f9XcdE91ScM).

We wanted to take these two clashing statements and put them both to the test. Has cultural diversity, measured through linguistic diversity, increased significantly in the past few years? How is cultural diversity, through linguistic diversity, spread out throughout the U.S.? Are regions with high ratios of non-English speakers actually linguistically diverse or homogeneously consisting of a non-English speaking community?

In the U.S., citizens are required to answer the Census, including the questions: "Does this person speak a language other than English at home?" and "What is this language?" The Census then conglomerates this data into a dataset, which contains over 380 languages and the corresponding number of respondents which speak them. We looked at three of these datasets: a 2000 dataset, a dataset of accumulated data from 2006 to 2008 and a dataset of accumulated data from 2009 to 2013. From here, we will refer to speakers of non-English languages at home as SONELAHs  and speakers of only English as SOE.

Armed with this Census data about languages spoken at home, we decided to investigate claims about linguistic diversity in the U.S....

We started by creating two tables that shows the temporal and spatial changes of linguistic diversity at the state level. The first table shows the ten states with the greatest percentage of SONELAHs and the second table shows the ten states with the smallest percentage of SONELAHs.

<p align="center">
Rank of Top Ten States' Percentages of SONELAHs
</p>
<p align="center">
<img src ="./RankOfSONELAHs.png"/>
</p>
<p align="center">
Rank of Bottom Ten States' Percentages of SONELAHs
</p>
<p align="center">
<img src ="./low_states.png"/>
</p>
California consistently has the highest percent of SONELAHs. We attributed this to a few different reasons. California previously belonging to Mexico means that there possibly is a higher percentage of Spanish speakers. California being a coastal state that contains many large cities means that it has a lot of places that are practical for an immigrant to come to when immigrating. Similarly, for New Mexico and Texas, which consistently are ranked second and third, we assume that there is Latin heritage is prevalent, due to the regions being once part of Mexico.

Over time, the percentage of SONELAHs in California has also not increased substantially, going from 39 % to 43 % in 13 years. Similarly, the actual rise in percentage of SONELAHs has not risen by a lot in any state. For example, New Jersey, which rose from seventh place to fourth place in rank, has only increased in percentage of SONELAHs by about 5%.

West Virginia has the lowest number of SONELAHs and has consistently stayed at about 2 percent for the entire range of time we are analyzing.  West Virginia is a very small state which means that the number of SONELAHs within the state must be very small, especially in comparison to most of the other states in the country.

Looking at the state level, however, does not tell us a lot about communities. Looking at the county level, we can infer what a community might look like.

Using the two datasets which specified counties, 2000 and 2009-2013, we plotted change in the PMF of SONELAHs per county in California.

<p align="center">
<img src ="./PMF_CA.png"/>
</p>

Los Angeles has the largest population, and thus, the largest number of SONELAHs. However, Los Angeles is a major city in a geographically large state. We see that the distribution of percentage of SONELAHs is more widely spread with so many different places to sample. For example, Los Angeles has the most SONELAHs, at more than 50 % of the population, while Placer County has only about 10 % of its population consist of SONELAHs. That is like every other person being a SONELAH to every tenth person being a SONELAH.

We want to also know if these people represent one culture, or many cultures. One way of looking at this is to abstract a few languages into groups, and see what percentage of the total population falls into these groups. The groups which we picked were :'Spanish and Creole', 'German, Italian and Scandinavian', 'Asian and Pacific Island Languages' and 'Native North American Languages'. Although this list is by no means inclusive, it is simple and the groups are fairly different from one another.

We graphed the counties of California again, this time showing the percentages of SONELAHs in these language groups:  

<p align="center">
<img src ="./PMF_CA_Groups.png"/>
</p>

We see a large population of Spanish and Asian language SONELAHs. This is a result we were expecting, considering the history of Asian immigration to California and the Latin heritage of a state that was formerly part of Mexico.

San Francisco, which has a high percentage of Asian and Pacific Island languages, has the second highest population of Chinese-Americans in the U.S., and yet the percentage of Asian and Pacific Island language SONELAHs in the county is only around 15 %. This means that in one of the most culturally concentrated areas in the U.S., only about every seventh person is an SONELAH of that group. Although it may be difficult to see, there are a few counties with SONELAHs that speak Native North American languages such as San Francisco, San Mateo, and Stanislaus. These bars are so small because less than 1 percent of the population speaks them. We are also not surprised by this because a large number of Native North American languages are slowly fading away.

Looking at the linguistic make-up of the state with the highest percentage of SONELAHs, we wondered if a state with a low percentage of SONELAHs would look similar or different.

We chose to look at Pennsylvania, which ranked low in percentage of SONELAHs, but is also known for having a large Germanic speaking population.

To do so, we graphed the PMF of the previous four language groups:

<p align="center">
<img src ="./PMF_PA_Groups.png"/>
</p>

We can immediately spot an anomaly in Lancaster County : it has a large percentage of Germanic, Italian and/or Scandinavian SONELAHs. Lancaster county is known as a Pennsylvania Dutch county, meaning it is a county in which Pennsylvania Dutch, a variety of German, was created.

We are surprised to see that the percentage of Germanic speaking SONELAHs is so small (about 4%), given that this county is known for its Pennsylvania Dutch speakers. Even more so, it is not even as common as Spanish in the county. The majority of SONELAHs do not speak Spanish within every county, but they make up the largest number of SONELAHs within the state. Also in similar fashion to California, the urban centers of Pennsylvania have the largest percentage of SONELAHs as shown by Philadelphia.

After analyzing the sets of data we can come to some conclusions about the cultural diversity within America. It is clear to see that there has been an increase in the number of SONELAHs in recent years and that they are not always a small part of the population (like California with 43 % of its population being SONELAHs in 2013). However, we can say that the number of SONELAHs is not growing very rapidly. Even New Jersey, in climbing the rank of highest percentage of SONELAHs in the country from the seventh place to the fourth place, only gained 5 % more SONELAHs in between 2000 and 2013. Looking individually by county, it is rare to see anything above a 5 % increase, as well.

The majority of SONELAHs are located in the southwestern United States or in large populated cities especially along the east coast. This is not an uncommon trend as immigrants have historically moved to cities for numerous socio-economic reasons.

 Finally, most of U.S. states aren't homogeneous. Although Spanish is most widely spoken, there is not a clear indicator that any particular language group completely dominates the others.

We believe that the Census Bureau has made a fair assessment: the United States has been becoming more and more culturally diverse. Tucker Carlson, on the other hand, has mistakenly come to the conclusion that we are growing at an incredibly fast rate. Although there are places with extremely high numbers of SONELAHs like California, our data suggests that regions with large SONELAH populations have not seen any large spike in SONELAHs in the recent past. As diversity and the overall population increases, our expectations for what our neighborhoods will look like may change, but in the recent past, there has actually been a drastic change in the culture and makeup of our country, and we expect there not to be one in the future.

# Music-and-Therapy-survey EDA:
The dataset was taken from Respondents who have some issues in their mental health such as Anxiety, Depression, Insomnia, and OCD. For that, this exploratory data analysis(EDA) project was conducted to study the effect of listening to music on respondents' mental health to see if music has improved or worsened their condition. 

#### Dataset:
The dataset contains (736) rows, (33) features, and  (129) Nan values that present 17.5% of the total data. Some columns have been dropped because of containing unique values or unnecessary data.

#### Dealing with Missing Data:
Missingno library has been used to identify and visualise missing data. It is found that 14.6% of missing data were produced only from BPM column.Moreover, it showed that missing values are missing completely at random, which are caused by data entery errors when inputting data. Missing data in BPM column have been replaced with median, and the other missing data presents only 2.9% of the data, wich is less than 5%, so they have been droped.

#### Outliers: 
There were 5 outliers values in BPM column that affected the data, so they have been dropped. 

#### Analysis:
1- Most Respondent's Age range are classified as young adult and younger respondents have higher Anxiety than the elder, 
2- Most Respondents listen to music through Spotify streaming service,
3- On average, Respondents listen to music around 2-3 hours per day,
4- Most Respondents prefare Rock,Pop,and Metal music genre. Latin music is the least prefare genre,
5- Respondents whose fav genre is latin genre, listen to music more often than the others,
5- There is a correlation between Anxity and Depression,
6- Respondents whose fav genre is Folk music has hisgher Anxiety than the other,
7- Respondents whose fav genre is Hip hop music has higher Depression than the other,
8- Respondents whose fav genre is Lofi music has higher depression
9- 75% of respondents showed improvement in thier condition, only 2.3% showed worsen and 22.7% had no effect
10- Respondents whose shown worsen in their case, thier fav genre are video game music,Rock,Pop,Rap and Classical, and most of respondents whose shown improve in thier case, thier fav genre is Gospel. 

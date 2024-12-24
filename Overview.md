
**Main purpose**
Through user input of hourly activity, model predicts user's everyday actions based on geographic (lat, long) and time data (UTC time). Provides user with statistics about how their time is spent.

E.g., if you are usually *exercising* at David Braley Athletic Center, then the model will learn this, and will not prompt you to input your activity. 

**Interacting with the UI**
Minimal user interface where user clicks one of four buttons. Back end collects user data and compiles it alongside geographic and time data. 

Eventually, model surpasses a level of confidence about its predictions, and user no longer needs to input data manually when they do not diverge from their typical routine. 

**Technical considerations**
* Initial app platform will be Android
* Geographic data collection most likely a latitude and longitude coordinate
* Time data a UTC time
* Privacy & security TBD
* Internet access required?
* Freemium 

**Potential features**
* Gamification
* Trend exploration: impact of sleep, exercise on productivity, individual burn out cycles, female hormone cycles impact on productive & mood
- Use "hallucinations" to tell people what their temptations are - and prepare themselves to battle against them

Sample 14-hour day: 
7 am - *Hygiene*
8 am - *Nutrition*
9 am - *Study*
10 am - *Study*
11 am - *Study* 
12 pm - *Social / Nutrition*
1 pm - *Study* 
2 pm - *Study*
3 pm - *Study*
4 pm - *Exercise*
5 pm - *Exercise*
6 pm - *Leisure*
7 pm - *Leisure*
8 pm - *Nutrition / Hygiene*
9 pm - *Leisure*

Benefits
* Provides insights about how users spend their time
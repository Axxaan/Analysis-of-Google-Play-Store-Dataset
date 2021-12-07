
# Google Play Store User Trends Analysis (Temporary Title)

## About us: Name/Github Username
Azan Sikder / Axxaan

Olly Love / gituser1034

## Introduction -
In this report, we will be analyzing the trends that users of the Google Play Store display daily. The data is given by Google for the
public to view and has many potential user trends that will be analyzed in this report. Apps have become one of the biggest devices in today's society
and allow us to connect, learn, and entertain ourselves all within a handheld device. The Google Play Store is one of the biggest app stores leading
in today's tech with over 3000 apps being uploaded every day. We will be explaining the trends that we have analyzed over the technical report and explaining
what users are doing on the play store. Users can download, pay, review these apps with different genres and age groups targetted, all these factors will be analyzed
to see what users download and what types of apps are at the top of the chain. 

The dataset is called Google Play Store Apps and is provided by Lavanya Gupta on kaggle. Link: https://www.kaggle.com/lava18/google-play-store-apps

**NOTE:** This analysis initially had 3 team members working on this but unfortunately has been reduced to 2 members as the third member dropped the course.

## Discussion - 
One interesting finding from the analysis of our dataset was found when answering the question "Do certain genres have more 
paid apps vs free apps?". From using pandas built in groupby function and grouping by the category and app type (types are free or paid),
and seperately grouping free and paid apps, we found that in every category there were significantly more free then paid apps. One example 
is the ART_AND_DESIGN category. Here there were 62 free apps and only 3 paid apps. In the books category there were over 200 free apps
and only 28 paid ones. Then in entertainment there were 147 free compared to only 2 paid apps. From these stats we can conclude that
consumers must be more likely to install an app when its free, compared to paid ones, leading free apps to be significantly more
common then paid ones.

Another interesting finding was regarding the question "How does the content rating affect the number of installs per app?". Through
data analysis techniques we found that the wider an audience an app is created for, the more installs it will get. This is seen
in the Everyone content rating compared to Adults only. The Everyone content rating contains over 114 trillion app installs, whereas
the adults only has only 2 million. Everyone 10+ has more installs then adult and mature content ratings. Teen has significantly 
more installs then mature.

## Conclusion - 
From our in depth data analysis, we found that every genre has more free apps then paid, as well as apps with a wider audience
get more installs. So if one was to create an app it would generally be wise for them to make it free and make the content rating
E for Everyone to get a good amount of people interested in it.

## Acknowledgements -
“This project was submitted as the final course project for CSCI 2000U “Scientific Data Analysis” during Fall 2021. The authors certify that the work in this repository is original and that all appropriate resources are rightfully cited.”

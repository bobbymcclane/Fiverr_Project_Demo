{\rtf1\ansi\ansicpg1252\cocoartf1671\cocoasubrtf600
{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\margl1440\margr1440\vieww16200\viewh13200\viewkind0
\pard\tx566\tx1133\tx1700\tx2267\tx2834\tx3401\tx3968\tx4535\tx5102\tx5669\tx6236\tx6803\pardirnatural\partightenfactor0

\f0\fs36 \cf0 Hi, I am a medical student in the process of an academic appeal involving a simulated patient practical exam. There are 5 locations where this exam took place and in those 5 locations, there were 5 rooms that contained 5 simulated patients (1 patient for each room).\
\
A simulated patient practical exam involves a student being assigned to one of the 5 locations and when he or she arrives in that location they are further assigned to one of the 5 rooms. Once in the room, the student's task is to perform a physical exam and ask the patient questions in order to come up with a diagnosis (predetermined and known by the examiner). The issue I have is that the room I was assigned to had the wrong patient and this affected my score. The other rooms are assumed ok and that they received the correct patient.\
\
I requested the exam results through the freedom of information Act and the school sent me data that is too broad for my basic level of statistics. I would like some indication that the results in my location as a whole had significant noise in the data when compared to the other locations.\
\
The data I received will not divide into the 5 rooms per location, instead, they are just lumped up and grouped by date and location.\
\
If you look at the data the 5 locations can be grouped by date and location. \
e.g \
Group 1 = 7/9/2019 and Non UK\
Group 2 = 7/10/2019 and  UK\
Group 3 = 7/10/2019 and Non UK\
Group 4 = 7/11/2019 and UK\
Group 5 = 7/11/2019 Non UK\
\
I was in Group 3 (7/10/2019 and Non UK) and my grade was 47.5%. The official results had a range from 8.8 to 100%. A 74.9% mean and pass mark cut off 52.3%. The pass mark is a special formula the medical school uses. A score above the pass mark is a Pass (P). A score between the pass mark and 10% below (52.3-10 = 42.3%) is called a Cause for Concern (CC) and a score below 42.3% is a Fail (F). I received a cause for concern and I am making the argument that the patient I saw was wrong for my exam and that other students who went in to see the same patient I saw were also affected. But because I did not receive data split by room and location I am limited but this wrong patient issue happened in one location (group 3 ) and not any other group, so my hypothesis is that the distribution of data in Group 3, when compared to other groups, has a lot of noise that can suggest something was inconsistent in group 3 compared to what other students in other locations experienced.\
\
Special notes\
I tried to look at the data applying boxplot and DBSCAN analysis in python but I failed. I can not account for the noise in Group 3 because of the varying sample sizes in other groups and outliers. \
\
I should mention something important that could affect the scores: Since the groups are separated by date and location. It has been whispered that students on the 10th knew what patient would be present from the students on the 9th and the students on the 11th could technically have had 2 days to prepare.\
\
Task\
Could you come up with a statistical analysis in python that can support my hypothesis that there is sufficient variance or noise in the distribution of data in Group 3, taking into account the group size and time of the exam. If you can accomplish this I will need some visualization in python (standard, nothing fancy) that I will use in my appeal. Please help. \
\
Files\
\
\
\
\
}
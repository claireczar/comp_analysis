---
# Do not edit the text between these lines!
layout: default
title: Home
---

# UNC COMP110 Course Improvement Analysis


## Project Description

This exercise was completed to analyze the data provided by anonymous UNC COMP110 students to lead the course towards improvments. Our belief is that with the incorporation of recorded lecture videos aftr class, students will be able to more easily review the content of the class. Utilizing Python functions and data visualization tools, we were able to compare and anylize data from the survey to assess our idea. We explored factors such as student's understanding of material, interest in live lectures, and rating of effectiveness in lesson videos to come to a conclusion. While the data did not explicitly indicate a direct relationship between course understanding and effectiveness of video lessons, we were able to gather that the students who believe videos are effective are very interested in recording and posting lectures on the course page. While not everyone may need these videos, the people struggling in the class indicated they would be grateful for them, and it is important to support students no matter their understanding of the material.
## Proposed Idea
The course should record and post lecture videos because it will provide well-explained explainations of new material for students who miss class or need extra help reviewing material at their own pace.
## Data Analysis
We used the following survey data:
-Lesson video effectiveness
-Interest in livestreamed lectures 
-Student understanding

These variables were used in Python using seaborn in order to create visualizations depicting their relationships.
## Visualizations 

### Video Effectiveness vs Understanding
<img src="/comp_analysis/static/imgs/video_effectiveness_vs_understanding.png" alt="Image of Comp110 survey data regarding Video Lesson effectiveness and student's course material understanding. "  width="500"/>

### Livestream Interest vs Video Effectiveness
<img src="/comp_analysis/static/imgs/video_demand_vs_video_effectiveness.png" alt="Image of Comp110 survey data regarding Video Lesson effectiveness and demand for live lecture recordings. "  width="500"/>

### Distribution of Video Effectiveness
<img src="/comp_analysis/static/imgs/lesson_video_effectiveness.png" alt="Image of Comp110 survey data regarding Video Lesson effectiveness. "  width="500"/>

### Student Understanding
<img src="/comp_analysis/static/imgs/student_understanding.png" alt="Image of Comp110 survey data regarding student's understanding of course content. "  width="500"/>

## Conclusion
Through this analysis, we aim to highlight the benefits on the COMP110 course should live lecture recordings be included on the course page. The nanalysis explored whether providing recorded lecture videos would create value for students by improving avaiable material to aid their understanding and studies. Through the use of multiple helper functions in python alongside the collected survey data, we were able to conclude that many students do find leson videos helpful, and those students would strongly support recording and posting class lectures. Beyond that, we see by anylizing the "understanding" students have for course material, we see there is a decent general understanding, but few people are incredibly confident in content. We believe that implimenting this new protocol would serve as the final push to help students fully comprehend material. 
When students rated the effectiveness of video lectures, the most popular rating was a 7, which is the most effective something can be. We know from this that video lectures really help students comprehend and review the material. However, when we observed tionship between video effectiveness and understanding, there was an interesting trend. Students who had low levels of understanding, felt like the videos were extremely effective in aiding their learning. When the students had a higher understanding of the material (4-7), we noticed a lower rating for effectiveness of videos. This suggests that students who already grasp the material well are not interested in video lectures to aid their studies. This could be related to different tendencies in students, such as what kind of notes they take during class, previous coding knowledge, or how often they miss class. Despite the data suggesting certain populations of students with greater understanding don't necessarily want videos, we need to care for those students struggling, and offer ammenities which will assist them. 
Comparing the live stream demand and rating of video effectiveness, the trend was positive and linear as predicted. Students who didn't find lecture videos effective in assisting their studies or learning felt no need for lectures to be recorded, and vice versa. 
Overall, while the data does not prove a direct positive relationsip between student understanding and demand for lectures to be recorded and posted, it does prove that many students value video lessons, and it is helpful for those students who need additional help. To further understand this relationship, it would help for us to collect data on how recorded or video-based learning aids in this class affect the performance on exercises and quizzes. It is important that students can access basic materials to aid their education, and we feel recorded lectures would be a massive help.

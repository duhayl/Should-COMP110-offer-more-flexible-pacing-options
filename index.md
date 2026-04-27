---
# Do not edit the text between these lines!
layout: default
---

# Should COMP 110 Offer More Flexible Pacing Options?

<!-- This is a comment. Below, you'll see code for inserting an image. To make this image appear, update <custom-path>. To add an image, save it inside the imgs folder of this repository. -->
<img src="/Should-COMP110-offer-more-flexible-pacing-options/static/imgs/logo.png" alt="Image of Comp110 rainbow logo. "  width="500"/>

## Overview

This project analyzes student survey data from COMP 110 to explore whether 
the course should offer more flexible pacing options, such as allowing students 
to submit assignments within a wider window. The goal is to assess whether 
pace-related stress is a widespread issue and whether flexible pacing could 
better accommodate diverse learning needs.

## The Data

The analysis combined two semesters of COMP 110 student survey responses, 
totaling 764 responses. The key variables examined were self-reported ratings 
of pace, difficulty, and understanding, each on a scale of 1–7, as well as 
year of enrollment.

## Analysis

### Pace Distribution

The histogram below shows how students rated the course pace across all 764 
responses. The distribution is skewed toward the higher end, with the most 
common rating being 4 and a significant number of students rating pace at 5 
or above.

<img src="/Should-COMP110-offer-more-flexible-pacing-options/static/imgs/pace_distribution.png" 
alt="Histogram of pace ratings" width="600"/>

Of the 764 responses, 156 students, roughly 20%, rated pace above 5, 
indicating they found the course moving faster than comfortable.

### Pace vs. Difficulty by Year

The box plots below compare pace and difficulty ratings grouped by year of 
enrollment. Across all years, students who rated pace as higher also tended 
to rate difficulty as higher, suggesting these two stressors compound each 
other.

<img src="/Should-COMP110-offer-more-flexible-pacing-options/static/imgs/pace_difficulty_boxplot.png" 
alt="Boxplot of pace vs difficulty grouped by year" width="700"/>

This trend was consistent across years 26, 27, 28, 29, and 30, strengthening 
the case that pace is not an isolated concern but one that amplifies overall 
course difficulty for affected students.

### Pace vs. Understanding

The scatter plot below examines the relationship between pace and understanding 
ratings. Unlike the pace-difficulty relationship, no strong directional trend 
is visible here — students across all pace ratings reported a wide range of 
understanding scores.

<img src="/Should-COMP110-offer-more-flexible-pacing-options/static/imgs/pace_understanding_scatter.png" 
alt="Scatter plot of pace vs understanding" width="600"/>

This suggests that while fast pace correlates with higher perceived difficulty, 
its direct impact on comprehension is less clear-cut from this data alone.

## Conclusion

The data collected from 764 combined survey responses partially supports the recommendation to implement more flexible pacing options in COMP 110. Of the total responses, 156 students, about 20%, rated the course pace above 5, indicating that they found the course moving faster than comfortable. The pace distribution histogram reinforced this finding, showing that while the modal rating was 4, responses clustered heavily between 4 and 6, meaning a meaningful portion of the class is operating at or near the upper boundary of their pacing comfort zone. This alone suggests that a non-trivial segment of students would benefit from additional flexibility in submission windows.

Beyond the raw distribution, the catplot comparing pace and difficulty across enrollment years revealed a consistent positive relationship: students who rated pace as higher also tended to report higher difficulty ratings, and this pattern held across years 26, 27, 28, 29, and 30. This compounding effect is significant and suggests that students experiencing a fast pace are not simply midly inconvenienced, but are also finding the material harder, creating a dual source of academic stress. The relplot scatter of pace versus understanding, however, was less conclusive. Points were spread across almost all combinations of the 1-7 scales without a clear directional trend, making it difficult to draw a strong connection between faster pace and reduced comprehenshion at the individual response level. This limits how confidently the data can be used to argue that flexible pacing would directly improve understanding outcomes.

Given these findings, implementing a modest flexibility measure, like an extra 48 to 72 hour grace window for assignment submissions, appears to be a reasonable and low-cost recommendation. The 20% of students experiencing high pace stress, combined with the observed pace-difficulty correlation, identifies a real population that could benefit without requiring any restructuring of course content or learning objectives. Future extensions worth exploring include corelating pace ratings with actual grade outcomes, investigating whether high-pace responses cluster disproportionately among specific year groups, and surveying students directly about whether they would use flexible windows or prefer the accountability of firm deadlines. 

That said, this proposed change does carry meaningful costs and trade-offs that should not be overlooked. Teaching staff and TAs would bear the greatest operational burden, as staggered submission windows complicate grading timelines, feedback turnaround, and the timing of solution releases. Students who thrive under structured deadlines may perceive flexible extensions as an unfair advantage, specifically if peers with later submissions use office hours or have assignment conversations, informal or not, after the nominal due date. Academic integrity is also a legitimate concern under this model. Finally, the approximately 80% of students who rated pace at 5 or below may see little to no personal benefit from this change, while indirectly experiencing reduced instructor availability if administrative overhead increases. Any implementation of flexible pacing should be designed carefully, with clear guardrails to protect fairness and course integrity while still serving the students who need it most.
# PISA 2012 Dataset

## Installation

- Clone the existing repository
- run Summary_slides.slides.html to see the slide deck
__or__
- launch jupyter notebooks and run to check the code
- run Exploration_template.ipynb
  (This can also be run without jupyter notebooks, open Exploration_template.html)

## Dataset

PISA is a survey of students' skills and knowledge as they approach the end of compulsory education. It is not a conventional school test. Rather than examining how well students have learned the school curriculum, it looks at how well prepared they are for life beyond school.

Around 510,000 students in 65 economies took part in the PISA 2012 assessment of reading, mathematics and science representing about 28 million 15-year-olds globally. Of those economies, 44 took part in an assessment of creative problem solving and 18 in an assessment of financial literacy.
<br>


## Summary of Findings
In the exploration phase I tried looking for patterns. I proceeded systematically starting with univariate visualizations such as the split of students interviewed in OECD, and non-OECD countries, the overall grade distribution, the number of books owned, the highest education achieved by the parents. But nothing was immediately apparent. In the second phase of my exploration (bivariate) I tried visualizing the effect of stay at home mothers on the grades of the students...this is where it started getting interesting. I found that students with mother's that stayed at home generally had better grades. I decided to expand my search around a specific theme. What are the factors that are out of the student's control that are highly correlated with grades. Through my different visualization I found that the following variables were correlated with grades: 1) correlations between the mother/father staying at home, 2) the SQ ISEI (a proxy for socio-economic status),and 3) the age of the students.
I also tried grouping all the perceived control questions (which was meant to be a high internal locus proxy) and the sense of belonging questions (which was meant to be a social affinity) into two variables to be able to correlate them with the presence of either the father/mother at home. I also found that the presence of parents at home had an impact on both these variables.

Finally, my multivariate analysis was meant to compare the presence of the father and the mother at home to see who had the greatest impact on the student's grades.


## Key Insights for Presentation

For the presentation, I focused on one question: Do all students compete on an equal footing ? In other words, I tried to highlight the fact that given similar students but in different circumstances, notably born in families with different socio-economic realities, or in a family in which one of the parents could afford to stay at home, or even his month of birth, that the student would not perform the same way.

## Downloading the Dataset

The PISA 2012 dataset can be downloaded [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud507/pisadict2012.csv)

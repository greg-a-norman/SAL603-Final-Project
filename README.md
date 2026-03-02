# SAL603 Final Project
## Greg A. Norman

I decided to look at the use and effectiveness of the bunt in major league baseball. This was inspired by Game 7 of the World Series, where in spite of everything I've been told about how the bunt is a losing proposition, there I watched as the Blue Jays repeatedly tried to execute bunts. So the (rhetorical) question I asked myself was whether the bunt truly was dead or were the Jays just being foolish? 

The specific questions looked at in this research were:

1. How has the use of the bunt changed?
2. In recent years has usage decreased, stablize or rebounded?
3. How good are players/teams at executing the bunt?
4. How/when are teams using the bunt?
5. Are there situations where bunting is advantageous?

I use parsed Retrosheet event data to analyze these research questions. The research questions associated were looked at both with long-term and short term trend data and due to the size of the retrosheet data files I limited the number of data points. For long-term trend data I took data from 5 year intervals starting in 1988. The starting point was chosen because that is as far back as Retrosheet has pitch sequence data. The 5 year interval was selected because it avoids those years with fewer than 162 games (due to work stopages, Covid-19, etc.) For recent data, I picked all years from 2022 to 2025. This interval was chosen as this standardized things to the years since the full time DH as well as the extra innings ghost runner. Due to small sample sizes associated with individual years, for the recent data I grouped the 4 years together to enhance my opportunity to make meaningful inferences.

The python code and results of this review have been posted in this repository. A video presentation summarizing the findings can be found here: https://www.youtube.com/watch?v=fiW-U057GpE



Project 1 - SAT and ACT Participation

We are tasked to aggregate SAT and ACT scores and participation rates from each state in the United States. This will allow identification of trends in the data combined with outside research to identify likely factors influencing participation rates and scores in various states.

The 2017 and 2018 state-by-state average results and participation for the SAT are made available for analysis. 2018 ACT state-by-state mean composite scores and participation rates are available as well.  This data has been compiled into CSV files.

The SAT and ACT scores for the entire U.S are taken from not the raw scores themselves. For example, each of the numeric columns seem to represent the arithmetic mean of all results of a given state for 2017.


The new format for the SAT was released in March 2016. The goal of the data science team is to track statewide participation and recommend where money is best spent to improve SAT participation rates. We are tasked to provid data and outside research to make recommendations about how the College Board might work to increase the participation rate in a <state>


The four top SAT states; Minnesota, Wisconsin, North Dakota, and Iowa, do not require the SAT for graduation.

When being a high school student these days requires so much to do to compete why would these mid-western schools. 



Problem Statement

The new format for the SAT was released in March 2016. As an employee of the College Board - the organization that administers the SAT - you are a part of a team that tracks statewide participation and recommends where money is best spent to improve SAT participation rates.

Executive Summary
Data files are uploaded and 'cleaned' based on what is found. The cleaned data is then combined into one file that is used for Exploratory Data Analysis.

Data Dictionary

| Feature             	| Type   	| Dataset  	| Description                                                   	|
|---------------------	|--------	|----------	|---------------------------------------------------------------	|
| state_act           	| string 	| act_2017 	| U.S. state participant in the ACT exam                        	|
| participation_act   	| float  	| act_2017 	| Amount of participants for the state ( 0 - 1 )                	|
| english_act         	| float  	| act_2017 	| English ACT report score for the state.                       	|
| math_act            	| float  	| act_2017 	| Math ACT report score for the state.                          	|
| reading_act         	| float  	| act_2017 	| Reading ACT report score for the state.                       	|
| science_act         	| float  	| act_2017 	| Science ACT report score for the state.                       	|
| state_sat           	| string 	| sat_2017 	| U.S. state participant in the SAT exam.                       	|
| participation_sat   	| float  	| sat_2017 	| Amount of participants for the state ( 0 - 1 )                	|
| reading_writing_sat 	| float  	| sat_2017 	| Combined ACT reading and writing score for the state.         	|
| math_sat            	| float  	| sat_2017 	| Math ACT report score for the state.                          	|
| total_sat           	| float  	| sat_2017 	| Total combined for SAT writing and mathematics for the state. 	|
|                     	|        	|          	|                                                               	|


Conclusions/Recommendations

The best review for how to identify likely factors influencing state SAT Participation rate and scores is to find the states who are top in the SAT rankings. With these states we develop a more granular study. Findings from this study indicate that a few Midwest and Plains states are good candidates. Minnesota, Wisconsin, North Dakota and Iowa have maintained in the top 5 SAT scores for the last few years. Are there seasonal or socio-economic factors that encourage high SAT scores for these states? Recent changes in standardized tests such as the ACT or SAT has created disenchantment among colleges and university. Schools are opting for test-optional admissions requirements.





References:

https://magoosh.com/hs/sat/sat-scores/2018/average-sat-scores-by-state-how-does-your-state-stack-up/



{google_docs}https://docs.google.com/presentation/d/1MGiwQT8M6xA_aXYLk_NJO-42Xudlrx-_mNJCudulH28/edit#slide=id.gc6f9544c1_0_0{/google_docs}









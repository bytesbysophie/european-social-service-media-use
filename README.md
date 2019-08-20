# Table of Contents
1. [Installation](#Installation)
2. [Project Motivation](#Project-Motivation)
3. [File Descriptions](#File-Descriptions)
4. [Results](#Results)
5. [Licensing, Authors, and Acknowledgements](#Licensing-Authors-Acknowledgements)

## Installation <a name="Installation"></a>

Beyond the Anaconda distribution of Python version 3, following libraries should be installed:
* seaborn
* sklearn
* imblearn
* pydotplus

## Project Motivation <a name="Project-Motivation"></a>

Journalism plays a crucial role in securing democratic structures like in Germany by informing citizens and empowering them to participate in politics. All the more worrying is the worsening economic situation of the newspaper business, which has not yet been managed to compensate by new digital products and business models (apart from a few exceptions propably).
Thus, understanding the media use and it's implications for the political participation and opinions is crutial for both, media publishers and politics.
As a first attempt, following questions have been investigated, using data provided by the [European Social Survey](https://www.europeansocialsurvey.org/data/country.html?c=germany) in several rounds/ years:

1. Traditionalism & Newspaper Use: Are respondents who affirm the importance to follow traditions and customs more likely to read newspapers than respondents who disagree?
2. Political newspaper use & participation in the last national vote: Are respondents who regularly use newspapers for political information more likely to have voted in the last national election?
3. Demographics & Party Preference Of Non Newspaper Users: Can we identfy people who don't use newspapers based on their socio-demographic profile and their answer to which party they feel closer to?

## File Descriptions <a name="File-Descriptions"></a>

* [media-use-germany-data-prep.ipynb](https://github.com/bytesbysophie/european-social-survey-media-use/blob/master/media-use-germany-data-prep.ipynb): Initial data preparation (cleaning naming inconsistencies and missing data) 
* [media-use-germany-data-analysis.ipynb](https://github.com/bytesbysophie/european-social-survey-media-use/blob/master/media-use-germany-data-analysis.ipynb): Exploratory data analysis and analysis of the above mentioned questions
* data/EuropeanSocialSurvey_Round_1-8_Germany.csv: Data downloaded from [European Social Survey](https://www.europeansocialsurvey.org/downloadwizard/)
* data/EuropeanSocialSurvey_Round_1-8_codebook.html: Data documentation provided with the raw data
* data/EuropeanSocialSurvey_Round_1-5_Germany_clean.csv: Cleaned data created in [media-use-germany-data-prep.ipynb](https://github.com/bytesbysophie/european-social-survey-media-use/blob/master/media-use-germany-data-prep.ipynb)

## Results <a name="Results"></a>

The results of this analysis will be published on Medium.

## Licensing, Authors, and Acknowledgements <a name="Licensing-Authors-Acknowledgements"></a>

Credit to the European Social Survey (ESS) for providing the data. Please respect the [conditions of use](https://www.europeansocialsurvey.org/data/conditions_of_use.html) published by the ESS when working with ESS data.

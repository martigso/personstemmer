# Notes on the variables
| Variable name           | Variable description                                                                       |
|:------------------------|:-------------------------------------------------------------------------------------------|
| kandidat                | name of the candidate                                                                      |
| valg                    | year of election                                                                           |
| parti                   | candidate's party                                                                          |
| rangering               | rank on list _after_ election                                                              |
| rangering_original      | rank on list _before_ election                                                             |
| valgt                   | was the candidate elected?                                                                 |
| personstemmer           | personal votes of party voters                                                             |
|                         |                                                                                            |
| slengere                | personal votes from voters of other parties                                                |
| partistemmer            | number of votes the candidate's party got in total                                         |
| parti_original          | the name of the candidate's party                                                          |
| count                   | total personal votes                                                                       |
| election                | the date of the election                                                                   |
| total_hits              | number of articles the candidate has been mentioned in from last election to next election |
| decay                   | sum of articles with applied exponential decay function (half life = 1 month)              |
| hits_after_list_public  | number of articles the candidate was mentioned in from june 6th till the election          |
| cum_hits                | number of articles the candidate was mentioned in from 1945 till the election              |
| hits_before_list_public | cum_hits - hits_after_list_public                                                          |

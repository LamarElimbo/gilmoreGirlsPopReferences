#### Purpose of project:
  For this project I wanted to use named-entity recognition to suss out pop culure references used in Gilmore Girls and analyze how they were used by some of the main characters.

#### Existing Datasets Used:
* http://crazy-internet-people.com/site/gilmoregirls/pages/s1/s1s.html 
  * __Description__: A list of scripts from every episode of gilmore girls.

#### Datasets Created & Available:
* Gilmore Girls References
  * Description: A list of unique pop culture references per episode of Gilmore Girls
  * Column Headings: (episode, reference, season, ref_type, figure_type, speaker)
  * Length: 1692 rows
  * Where data was collected from:
    * http://crazy-internet-people.com/site/gilmoregirls/pages/s1/s1s.html 
      * __Description__: A list of scripts from every episode of gilmore girls.

#### How data was collected:
* For this project I used a named-entity recognizer to crawl through each of the 154 scripts and enter any suspected named entity into a database.
* I used nltk to create the NER and pandas to create the dataframes.

#### Analysis:
* I used the pandas library to aid in my analysis of the data, alongside bokeh in order to create some rudimentary visualizations.

#### Visualizations:
* I used powerpoint to create the main infographic

#### Journal Entries:
* This was the first full page infographic that I've made and I was pleasantly surprised to find that powerpoint made a pretty good low-budget substitution for something a little more high tech.

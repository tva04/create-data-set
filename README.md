# create-data-set
Create dataset from different source for learning purpose

The logic is

* Get data from Wikipedia for the below Titles:
  * Cricket_World_Cup
  * FIFA_World_Cup
  * Olympic_Games
  * 2027_Cricket_World_Cup
* Clean up the data to readable format - Remove unwanted lines (\n), other characters (===), etc.
* Create a python dataframe: Create multiple rows for each titles, each row can be sections or sub sections; The columns are: Title, Sections, Subsections, Content
* Save it to csv.

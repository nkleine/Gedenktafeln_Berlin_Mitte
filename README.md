# Gedenktafeln_Berlin_Mitte


- Starting Point:
  The project is based of the open data file 'Gedenktafeln_Mitte', which contains all memorial plates of the district 'Mitte' in Berlin, Germany.
  The source is https://daten.berlin.de/datensaetze/gedenktafel-datenbank-berlin-mitte (last updated on 19th of November 2020 by the city of Berlin)

- First adjustments:
  In order to make the original csv-file more usable, I added following columns: Gender, Category, Activity and Context. 
  The information I used are from within the original csv-file.
  The product of these manual addings is 'Gedenktafeln_Mitte-erweitert'

- Cleaning the data:
  You can find the DA cleaning process in the Notebook 'BerlinerGedenktafelMitte_1'.
  The products of this cleaning process are the files 'Gedenktafeln_Mitte_data1' (contains Names and NaNs in numerical columns) 
  and 'Gedenktafeln_Mitte_data2' (Names and all NaNs are dropped).

- Exploratory DA:
  You can find the Exploratory DA process in the Notebook 'BerlinerGedenktafelMitte_2'.
  The products of this cleaning process are the files 'Gedenktafeln_Mitte_data1_EA' (contains Names and NaNs in numerical columns), 
  'Gedenktafeln_Mitte_data2_EA' (Names and all NaNs are dropped) and 'Gedenktafeln_Mitte_data3_EA' (data2 standardized and encoded).

- Presentation of the results:
  You find the Tableau presentation of the results under https://public.tableau.com/app/profile/nadine.kleine/viz/Presentation_Nadine_v2/PresentationNadine

# DS4A_project_team226
## Link GitHub repository:

https://github.com/andrescar18/DS4A_project_team226.git

This is the project carried out by team 26 during the data science training program (DS4A) Colombia.

## This main script for the processing of data from public calls published on the official page of the U.S. department of state state.gov

The content of this folder is designed to run from the google cloud drive on My drive section.

Move the root of this shared folder to your drive.

Open the 'script_final'.ipynb from google colab and executing all the cells. The instalation of packages and frameworks is predefinied in the first two cells.

The 'url_list.csv' file contains the list of links for each call, the requests are made to each link and the extracted text content will be uploaded in the file_txt subfolder.

'all_countries.txt' file contains all the countries in English language to be scrapying in each call title and in this way determine which country/region it involves.

'ods.csv' file contains the keywords with their respective id to later be compared with the keywords obtained from the model and determine the one with the highest percentage of similarity.

The final result of the execution of the script_final will be reflected in the data_loaded.csv file, this is the source for dashboard.

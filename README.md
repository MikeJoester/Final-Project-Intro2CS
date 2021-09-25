# Final-Project-Intro2CS
Made by Nguyen The Dan - VNUK's CSE20 student

## Data: 

- To complete these tasks, you will be provided the dataset of around 21.7 million user reviews of around 300 different games on Steam in 2021, with provided columns:

  - **app_id** --> The game's ID
  
  - **app_name** --> Name of the game
  
  - **review_id** --> ID of the review post
  
  - **language** --> The review post's language
  
  - **recommended** --> The author's recommendation ( True / False )
  
  - **votes_helpful** --> The likes of the review post
  
  - **steam_purchase** --> The author purchased the game or not ( True / False )
  
  - **author.steamid** --> The author's steam ID 
  
  - **author.playtime_forever** --> The total hours the author spent on playing that game
  
- The data is provided in three files in [this Google Drive Folder](https://drive.google.com/drive/folders/1pVFPfh-mUGuUgl80saViOk7kfzkV8_IZ?usp=sharing) :
  No. | Dataset | Length | 
  ------------ | ------------ | ------------- 
  1 | data_steam_small.csv | 10.000 lines
  2 | data_steam_medium.csv | 1.000.000 lines
  3 | data_steam_large.csv | ~21.700.000 lines

## Requirements:
  No. | Criteria | Requirements | 
  ------------ | ------------ | ------------- 
  1 | Write the functions by your own code, do not use the functions in the library if not required | 25
  2 | Code can run as required | 50
  3 | Code styling | [PEP - 8](https://www.python.org/dev/peps/pep-0008/)
  4 | Code performance ( measured by milliseconds ) | Maximum of 10 seconds

## Questions:
### A. Data and setup:
  1. Import essential and visualization libraries / packages: numpy, pandas, statistics, matplotlib, seaborn;
  2. Read in the csv files as a dataframe called **df_small, df_medium, df_large**;
  3. Check the information of the imported csv files and print the **first 5 rows** of each dataframe.

### B. Basic Questions: 
Type in the game ID, and code:
  1. A function to print the most helpful reivews of the game in each dataset;
  2. **min, max, mean** functions to print the **game's name**, and the **smallest, largest, average** gaming hours of it in each dataset;

### C. Algorithms:
Type in the game ID, and code:
  1. A search function to find and count the number of **newbies** (0 to 100 hours), **casual players** (100 to 1000 hours) and **veteran players** (above 1000 hours) of the game in each dataset;
  2. A function to list **three** most recommended games by the players in each dataset;
  3. A sort function to find out the most reviewed **non - english** language of the game in each dataset.
### D. Chart illustration:


# Final-Project-Intro2CS
Made by Nguyen The Dan - 20020006 

VNUK's CSE20 student

## I. Data: 

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
  
- The data is provided in three files in [this Google Drive Folder](https://drive.google.com/drive/folders/1pVFPfh-mUGuUgl80saViOk7kfzkV8_IZ?usp=sharing):
  No. | Dataset | Length | Size 
  ------------ | ------------ | ------------- | -------------
  1 | data_steam_small.csv | 10.000 lines | 788 KB
  2 | data_steam_medium.csv | 1.000.000 lines | 76,9 MB
  3 | data_steam_large.csv | ~21.700.000 lines | 1,63 GB

## II. Requirements:
  No. | Criteria | Requirements | 
  ------------ | ------------ | ------------- 
  1 | Write the functions by your own code | Do not use the functions in the library ( if not required )
  2 | Code styling | Use the [PEP - 8](https://www.python.org/dev/peps/pep-0008/) coding style
  3 | Code performance ( measured by seconds ) | Maximum of 30 seconds

## III. Questions:

There are **ten questions** that can be divided into three levels: 'Easy'(E), 'Medium'(M), and 'Hard'(H).

### A. Data and setup:
  1. Import essential and visualization libraries / packages: numpy, pandas, matplotlib; (E)
  2. Read in the csv files as a dataframe called **df_small, df_medium, df_large**; (E)
  3. Print the **last 5 rows** of each dataframe. (E)

### B. Basic Questions: 
Type in the game ID, and code:
  1. A function to count the number of games in each datasets; (E)
  2. **min, max, mean** functions to print the **game's name**, and the **smallest, largest, average** gaming hours of it in each datasets; (M)

### C. Algorithms:
Type in the game ID, and code:
  1. A function to detect even or odd number, and list all of the review IDs that is even and odd in each datasets; (E)
  2. A search function to find and count the number of **newbies** (0 to 100 hours), **casual players** (100 to 1000 hours) and **veteran players** (above 1000 hours) of the game in each datasets; (M)
  3. A sort function to list **ten of the richest players** by ID in each of the datasets (who has a lot of Steam purchases). (H)
### D. Chart illustration:
  1. Draw pie charts to display all of the languages of the game reviews (You can use pandas's **value_counts** function); (M)
  2. Draw bar plots to show the total players of 5 of the most reviewed game in the dataset and their **three types of players (Newbies, Casuals and Veterans)**. (H)

## IV. Instructors:

Thank you Mr. Vu and Mr. Thien for all the supports and provided us many meaningful projects to improve our coding skill day by day.

## V. Contacts:
 **Dan Nguyen :**
```
Email: dan.nguyen200206@vnuk.edu.vn
LinkedIn: dan-nguyen-2904
```

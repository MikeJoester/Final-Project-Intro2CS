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
  No. | Criteria | Weight (%)| 
  ------------ | ------------ | ------------- 
  1 | Write the functions by your own code, do not use the functions in the library if not required | 25
  2 | Code can run as required | 50
  3 | [Code styling](https://www.python.org/dev/peps/pep-0008/) | 15
  4 | Code performance ( measured by milliseconds ) | 10

## Questions:
There are total 10 questions, each question will have the total score of 10 with three levels of difficulties:
No. | Dataset | Max score| 
  ------------ | ------------ | ------------- 
  1 | data_steam_small.csv | **5** points
  2 | data_steam_medium.csv | **3.5** points
  3 | data_steam_large.csv | **1.5** points
  **Total** || 10 points
  <table>
    <thead>
        <tr>
            <th>Layer 1</th>
            <th>Layer 2</th>
            <th>Layer 3</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan=4>L1 Name</td>
            <td rowspan=2>L2 Name A</td>
            <td>L3 Name A</td>
        </tr>
        <tr>
            <td>L3 Name B</td>
        </tr>
        <tr>
            <td rowspan=2>L2 Name B</td>
            <td>L3 Name C</td>
        </tr>
        <tr>
            <td>L3 Name D</td>
        </tr>
    </tbody>
</table>


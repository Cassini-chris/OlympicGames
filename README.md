# Olympic Games Participants 1896 -2024
Analytics Use Case of Olympic Participants

![Hello Olympia](path/to/pic.jpg)

#### This repository contains code for analyzing data on Olympic Games participants, focusing on age and sex distribution.

### Data Source:
The code expects a CSV file containing data on Olympic participants. The format of the data is not explicitly specified, but it should include columns for:

year: Year of the Olympic Games (integer)
medal: Medal awarded (string, e.g., "Gold", "Silver", "Bronze", or "NA")
age: Participant's age (integer)
sex: Participant's sex (string, likely "M" or "F")

### Functionality:
Age Distribution: The animation displays a bar chart showing the number of participants at each age.
Accumulated Statistics: The code keeps track of overall statistics like:
Total number of participants across all years
Youngest and oldest participants (with their counts)
Age with the highest number of participants
Average and median age (calculated on the fly)
Male and female participant percentages
Average age of participants for each medal category (Gold, Silver, Bronze)

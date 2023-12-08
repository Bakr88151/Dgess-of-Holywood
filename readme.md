# Degrees of Holywood: 
The "Six Degrees of Kevin Bacon" is a whimsical theory positing that any Hollywood actor can be linked to Kevin Bacon through a series of film collaborations in six steps or fewer. It highlights the tightly interconnected nature of the entertainment industry, suggesting that actors are unexpectedly intertwined through their roles in movies.

Expanding upon this concept, this program not only uncovers the connection between Kevin Bacon and any Hollywood actor but also establishes links between any two Hollywood actors. This is accomplished by searching through three CSV files: one for movies, another for actors, and a third for linking the previous two together. The Depth-First Search algorithm facilitates this exploration. While using an SQL database would be a more efficient choice, I opted for CSV files due to limitations in my proficiency with the sqlite3 Python library at the time of developing this project.

### How to use:
  #### For testing: Run: 
    python3 degrees.py small and then input the names one at a time whens prompted for them.
  #### For Propper use:
    python3 degrees.py and then input the names one at a time whens prompted for them.
    this version is extremly slow as it supports 1 044 499 actors,it would faster if it had sql database instead of CSV files, but the entire point of this Project was to Practice the DFS algorithm any way.

### Note:
It's essential to note the existence of two sets of CSV files sets: one labeled "small," primarily utilized for testing, and another named "large" with significantly more actors and movies. The small dataset offers quicker results, while the large one increases the likelihood of finding the desired connection.

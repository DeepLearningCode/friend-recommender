# friend-recommender
friend recommender is a python script that builds a networkx graph object
and makes friend recommendations for a given user

### Dependencies
* NumPy
* Pandas
* networkx

### Example
To generate friend recommendations for a given user, either:
* Update variable `user_id = 123456`
* or include as a command line argument, e.g. `python friend_rec.py 123456`

### Recommendation Algorithm

FriendGraph algorithm makes recommendations by finding the friends-of-friends
of a user that are the most connected in the social graph

### Input Data

The input data file should be in .csv format and list user id's in next to each other
in a given row to indicate a connection

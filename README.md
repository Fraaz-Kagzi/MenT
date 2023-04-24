# MenT
Mentor Matching app creating for a 2nd year university (Software Engineering) module for FDM group 
Register or Login using username and password ,
if registering you will be asked to create a profile with details such as role (mentor/mentee), field , experience and requirements
using the profiles the algorithm with show you similar profiles with the opposite role (mentor/mentee) to match with and you will be able to send match requests
*Currently the feature to accept requests has not been added so we have added some pre-matched profiles in the db.json file
If a user is matched they will be able to communicate with a built in chat messenger to the person they are matched with.

We have also added admin accounts where admin can monitor mentorships and currently can match any users and also unmatch matched users.


MenT folder is the react project folder will need that whole folder to run the app
MenT:
  public: - contains media files such as logo used in app
  
  src: - contains all the scripts and files to run the app
    Classes: contains the scripts of classes we planned on using -- *"Currently not all classes are being uses"*
    
    csv: unused folder - contains previously used json files before using db.json
    
    pages:
    
   db.json - database file used with json.server to create remote api server. Contains Users.json (username & password) and Profiles.json

# BBRR
aka: BloodBowl Replay Reader

BBRR I felt a need to create a way for parsing the BB replay files generated by BloodBowl Chaos Edition (BBCE). My personal league was using BBManager before that project disappeared, and we wanted access to some type of stats again. 

BBCE replay files are stored in SQLite format (https://www.sqlite.org/) and I recommend downloading a reader such as https://sourceforge.net/projects/sqlitebrowser/ or https://sourceforge.net/projects/sqlitemanager/ for opening your .db files locally if you choose to.

The BBRR project is a test platform for discovering data within the replay files and displaying them in an intelligent manner. My hope is to use the data that comes from this project and use it to develop a web-based application that people can use, similar to BBManager, for logging into & uploading their replay files for storing data into the future and managing their own leagues. 

NOTE: In order to connect to the sqlite databases, you currently need to install the sqlite PDO package on the server you will run this code from. `sudo apt-get install php5-sqlite` will install the necessary package on your machine if necessary.

Contact: dmchale@gmail.com

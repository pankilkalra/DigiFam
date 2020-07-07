# DigiFam
### Abstract
As families grow bigger, houses grow smaller. People don't live with their families and feel disconnected. Enter: DigiFam. DigiFam aims to create a virtual image of your family. It enables you to digitise your family and connect with them. Plan events with your cousins, go to that flea market with your aunt, and how about a surprise anniversary celebration for your mum and dad? DigiFam allows you to create events, and invite family members to them. It also suggests family members to invite, and gives you reminders when a loved one has a special occasion approaching, so that you can plan something special. After the event is over, family members can upload the photos on a shared folder that is automatically created and shared only with the invitees. That's not all. DigiFam also offers a feature to share subscriptions within your family.  Netflix won't seem too costly now. Just invite your cousins to pitch in and buy a group subscription. This also extends to family insurances, and other shared resources. It will also suggest events based on interests, and give you targeted suggestions. So if you and your cousin are both into horror movies, the app will suggest you go see Grudge 3 with your cousin. DigiFam will enable you to conveniently connect with your family, turning your phone into your home.

We have maintained a family database and have built a query builder in python.

Python3 and MySQL is needed.

## Python Dependencies:
1) mysql-connector-python
2) pickle
3) tabulate
4) numpy
5) matplotlib
6) math

Final_dump.sql is the database dump file.

## Instructions for importing the dump file
1) Execute the command 'mysql -u root -p'
2) Enter password
3) Execute mysql command: 'create database digifam'
4) Exit mysql command line
5) Execute command: 'mysql -u root -p -h localhost digifam < final_dump.sql'

## Instructions for running the query-builder
1) For feeding the password in the mysql-python connection, I have stored the password using pickle in a file and I then pass it to the connection. You can comment the lines 332-334 and pass the password directly in line 361.
2) You can run the main project script using command 'python main_script.py'.

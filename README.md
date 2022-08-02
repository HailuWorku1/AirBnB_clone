# AirBnB_clone

Definition:
According to Wikipedia:

Airbnb, Inc., is an American online marketplace and hospitality service brokerage company based in San Francisco, California, United States. Members can use the service to arrange or offer lodging, primarily homestays, or tourism experiences.

Block Diagram of the Project:
holberton-pipeline

Tech
AirBnB-clone uses a number of open source projects to work properly:

Python - Python programming language
Console
Installation:
AirBnB-clone requires Python version. 3.4.3 to run.

How to run:
# First clone the repo
$ git clone https://github.com/HeimerR/AirBnB_clone.git
# Second executes the file "console.py" inside the folder AirBnB_clone
$ cd AirBnB_clone && ./console.py
# Start using the console!
How to use it:
You will get a prompt like this:

(hbnb) 
You can now start typing console commands to create, update or destroy users, places, etc.

(hbnb) create User
697d2586-e3ca-451a-8221-88ead0eb8283
(hbnb)
Commands available:
The following commands are available to use:

Command	Arguments
create	<class name>
show	<class name> <id>
destroy	<class name> <id>
all	[OPTIONAL <class name>]
update	<class name> <id> <attribute name> "<attribute value>"
<class name>.<command>(arguments)	it depends on the type of command you use
Classes available:
The following commands are available to use:

Class name	Default Attributes
BaseModel	id, created_at, updated_at
User	email, password, first_name, last_name
Place	city_id, user_id, name, description, number_rooms, number_bathrooms
Place	max_guest, price_by_night, latitude, longitude, amenity_ids
State	name
City	state_id, name
Amenity	name
Review	place_id, user_id, text
Example
Let's create a user:

(hbnb) create User
dcc89f74-2663-4f2d-b647-9c829d2b4797
(hbnb)
Now, let's see what it has this instance:

(hbnb) show User dcc89f74-2663-4f2d-b647-9c829d2b4797
[User] (dcc89f74-2663-4f2d-b647-9c829d2b4797) {'updated_at': datetime.datetime(2019, 7, 3, 19, 14, 32, 536201), 'id': 'dcc89f74-2663-4f2d-b647-9c829d2b4797', 'created_at': datetime.datetime(2019, 7, 3, 19, 14, 32, 536180)}
(hbnb)

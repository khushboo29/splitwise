# Problem statement:-
Design and implement a web application that enables a person to share money expenses within his group of friends. User should be able to login/create account which is unique. The following features are needed when a user logs in:

Option to Add an expense(with details like date, name etc), and split it amongst 2 or more people. Split can be in equal ratio or manual ratio (30-70, 40-60, etc). (These can be deleted or edited at a later stage).(Note that expenses can be added only amongst the people who are registered on the application)
At the top, show the total money to be received and total money to be paid by the person.
On the dashboard, user gets a summary of money he owes from his friends.
On clicking the name of each friend, show the details of the expenses added by the friend (description, date, split ratio etc).
Add a button to pay the debts. Make a note of the amount paid and also note the time of the same.
Once any expense or debt is updated, the same should be reflected to the other users on next login. (Notifications not needed).

############################################################################################ 


#Setting up project and initializing data
create a virtualenv

virtualenv env

cd env

./Scripts/activate

pip install -r requirements.txt

python manage.py migrate

python manage.py runserver

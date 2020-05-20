ABOUT This Repo is a Website with a Java Script Game. After creating an account you are able to login and play spaceinvaders viewing your highscores compared to others. 

HOW TO INSTALL/RUN
1.Clone the Repo

2.Create a Virtual Environment 
(In Terminal)
-virtualenv venv

3.Activate the Venv
(In Terminal)
-source venv/bin/activate

4.Install requirements.txt with the command "pip3 install -r requirements.txt"

5.Do migrations
(In Terminal)
-flask db init
-flask db migrate
-flask db upgrade

6.Run the server by typing "flask run" in the terminal window and enter the website by entering "http://127.0.0.1:5000/" in your local browser
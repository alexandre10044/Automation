# Automation
 
This project aims to teach you configuration management and automated deployment using ansible.The application you are working on during this project is a simple poll web application. Poll is a Python Flaskweb application that gathers the votes to push them into a Redis queue. The Java Worker consumes thevotes stored in the Redis queue, then pushes it into a PostgreSQL database. Finally, the Node.js Result webapplication fetches the votes from the DB and displays the result.

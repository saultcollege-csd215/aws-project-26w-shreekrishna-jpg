it sits in front of our Flask application and handles all incoming web traffic.

## Purposes
Instead of letting users talk directly to our Python code (Flask), they talk to Nginx first. Nginx then passes the message to Flask. It is like having a receptionist at a front desk taking messages for the workers in the back office.

## Benifits
It protects our Flask app by acting as a shield. If a hacker tries to attack the web address, they hit Nginx, not our actual application code.
It is very fast at handling many visitors at once. It can manage multiple people trying to use the site without crashing the Python app.
It allows us to use standard web settings (like Port 80) easily, making the website much more stable and reliable.

# kich
Full registration and event management system for the Order of the Arrow. Named after Kichkinet, the guide of ceremonies.

## How to install
This is a flask python app, so install it on your server by downloading the code, creating an enviromnent, then setting up wsgi how you see fit. I follow [this guide](https://www.digitalocean.com/community/tutorials/how-to-serve-flask-applications-with-gunicorn-and-nginx-on-ubuntu-18-04) from digitalocean for Ubuntu and Nginx.
You then need to set up the config file. You need a sendgrid and twilio account and an api key for both.

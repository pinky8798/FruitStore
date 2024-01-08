
Pyshop -> urls (i.e input urls we use in the browser)

Pyshop.urls -> we define include() where we tell Django that if the url start with products/ then interpret products/urls module

Products.urls -> here we take the input after products/ and check for the function to be called from view module which has the response to be given when a particular url is browsed

Products.models -> Here we give the basic model of our website.i.e; her we created a model for our products for which name, price, stock,image_url are defined


Now we create a new table using pycharm by adding our config present in apps.py to settings of pyshop and then run below command to create a table in dbsqlite3 


python3 manage.py makemigrations
python3 manage.py migrate



**Commands to run to start the webserver**

django-admin startproject pyshop (We run this command only once i.e; while we create a webpage for the first time)
python3 manage.py runserver

Refer : https://www.youtube.com/watch?v=_uQrJ0TkZlc&list=RDCMUCWv7vMbMWH4-V0ZXdmDpPBA&start_radio=1

# books_rest_api
A basic rest api with python, flask and sqlite3 

# To run the application
on your terminal:
 cd <projectfoldername>
 python api.py
You will see : * Running on http://127.0.0.1:5000/
Open this in your browser. This will take you to the homepage '/'
  
  
# How to query
http://127.0.0.1:5000/api/v1/resources/books/all
http://127.0.0.1:5000/api/v1/resources/books?author=Connie+Willis
http://127.0.0.1:5000/api/v1/resources/books?author=Connie+Willis&published=1999
http://127.0.0.1:5000/api/v1/resources/books?published=2010

*implemented only get methods for id,author,published*
 

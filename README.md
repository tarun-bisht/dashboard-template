# dashboard-template
Live Demo:::::::    https://tarun-bisht.github.io/dashboard-template/

Simple Dashboard template.
Optimized Dashboard template. Uses Jquery and ajax to optimize and load content of dashboard on flow.

To run template in machine make sure to use webserver else it will prompt a error 
"cross-origin-requests-are-only-supported-for-http-error-when-loading-a-local" that it cannot load file using ajax.

-----------------Python 2-----------------
Change directory into the folder where your file some.html or file(s) exist using the command cd /path/to/your/folder
Start up a Python web server using the command python -m SimpleHTTPServer
This will start a web server to host your entire directory listing at http://localhost:8000
You can use a custom port " python -m SimpleHTTPServer 9000 "giving you link: http://localhost:9000

------------------Python3--------------------
move to directory where template is placed
Use command--- " python3 -m http.server  "

-------------------Node.js--------------------
Alternatively, if you demand a more responsive setup and already use nodejs...

Install http-server by typing npm install -g http-server

Change into your working directory, where yoursome.html lives

Start your http server by issuing http-server -c-1

This spins up a Node.js httpd which serves the files in your directory as static files accessible from http://localhost:8080

----------------------Ruby------------------------
ruby -run -e httpd . -p 8080

----------------------PHP-------------------------
php -S localhost:8000

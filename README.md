# SE_Nu_Server


Source Description:
Nu Server aims to provide a simple interface for storing and viewing HTML files that are uploaded through FTP / SFTP. The FTP server was switch to an HTTP server because the upload attribute could not be implemented. However, features of downloading, accessing, viewing, and removing remain in the server.

Build Instructions:
The code for the server was built from using two modules and two classes from the python standard library. The code for the html files used the HTML element reference or tags. 

The html code was built by using different HTML elements. The following elements and attributes used:
•	html
•	title
•	body
•	p
•	h1
•	DOCTYPE html
•	a
•	download
•	href
•	alt
•	width
•	height

How is the code organized:
All of the code for the server is contained in one folder. Each file name depicts what the file is and its file type. The server’s code is organized by using code indentation to make the code more readable and the last two lines of code belong to the function stated above it. The httpd is the Apache HyperText Transfer Protocol.  It runs in the background of a web server and waits for the incoming server requests. This allows the server to listen for any request made by a user or an administrator. Most of the HTML code for the files is structure by <html>→<head>→<title>→< body>→<h1>→<p>.All of the tags are code by its corresponding end tag.

3rd party library:
The code for the server was built using two modules from the python standard library.  The http server and socket server are these modules. The socketserver.TCPServer is a class of the socket server module. The SimpleHTTPRequestHandler is a class of the http server. The code for the html files used the HTML tags. 

Each file was created individually to keep the code readable and clean. All tags and the python library was used in creating the code files. Some of the code could be reused for another file. For example, the index page displays text and a header. Its code is reused for the project description of Nu Server. Each file requires different attributes. The image files required the download, height, and width attributes in its code. Code like the index page or project description did not need these extra attributes. The purpose of those files was only used to give information to the user.


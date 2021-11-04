

# ToDo
This is a ToDo-List WebAPP showing the easy implementation of CRUD operations and Template Inheritence in python FLASK using Bootstrap.


### CRUD
CRUD app means an application that has ” **Create, Read, Update, and Delete** ” functionalities, which are used in relational database applications and executed by mapping to a SQL statement.

### Template Inheritence
Template inheritance allows us to reuse an HTML file for other pages. We can create one master HTML file that has the skeleton of what each page is going to look like,
and we can inherit that to other pages. So, it reduces the line of codes that we need to write.<br>
This is done with the help of the ***Jinja template engine***. <br>
Flask uses Jinja for its template functionalities.<br><br>
#### How to apply Template Inheritence?
- [x] Create a new file called ‘base.html’ inside templates folder. This file will be base template.
- [x] we can open the index.html file and inherit the base.html file to it using the keyword ‘extends’.
<br>
This video demostrates the webapp and shows CRUD operations implementing.<br>
https://user-images.githubusercontent.com/60935490/129556789-8d27721c-e491-443c-a62e-096e70f2a142.mp4

#### Deploying App on Elastic Beanstalk
Necessary Conditions to follow-
- [x] Flask app name must be application, as well as file name must be 'application.py'.
- [x] Create a `.ebextensions` folder containing file 'python.config'. To configure your environment and customize the AWS resources that it contains.
- [x] Compress all files in `.zip` extension and upload it to new Elastic Beanstalk environment.
Patiently wait until it deploys🙃.

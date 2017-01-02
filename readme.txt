Prequistes:
1.	install latest python: https://www.python.org/downloads/
2.	enter cmd(administrator) and go to where get-pip.py(included in root map called Requirements) is located, type "python get-pip.py" and click enter.
	Now that you've got pip installed, things get easier
3.	type pip install virtualenv
4. 	now we're going to make an developement environment
5.	now type "virtualenv <name>"  replace name with whatever you desire
6. 	now that you've made your virtual environment, you'll want to activate the environment, this is done by navigating your cmd to the root folder.
7.	now type "Scripts\activate". Now you're inside your test environment.
8.	install flask by typing "pip install Flask"
9.	the following structure is the best(in my opinion)
	+-- app
	¦   +-- static
	¦   ¦   +-- css
	¦   ¦   +-- img
	¦   ¦   +-- js
	¦   +-- templates
	¦   +-- routes.py
	¦   +-- README.md

how to run your project:
1.	be inside the root folder
2.	open cmd with administrator privileges
3.	navigate to your project folder	(C:\User\Jaron-pc\Desktop\app\container\app
4.	type Scripts\activate to enter the virtualenv
5.	inside virtualenv navigate to the project folder(which is container in my case)
6.	navigate to the project root folder
7.	inside the root folder is a file called "routes.py"
8.	activate it by typing "python routes.py"
9.	navigate to "localhost:5000"
10. 	you've just entered your first python-based website using the flask framework(windows)
11.	inside the templates map is where the html files are located. There is also an "about"-link found here, to get here type "localhost:5000/about"

It's as easy as that

Project pseudo twitter:


	Versions:
		*Django 3.2.6
		*Python 3.10.7


Why Django?

Because Django has a lot of user stuff built into it, it does a lot of the DDBB level, heavy lifting for us.
It is a nice layer on top of a database that helps us to develop for.

I used Flask in the past and loved how simple things appeared. Django has much more to offer, with all the learning involved.
For sure I will keep on getting to know it better :)	



STRUGGLES:

- Difficulties to install pipenv due to PATH -> solved by: https://www.jetbrains.com/help/pycharm/pipenv.html#c18c14b6
- Forgetting to add csrf_token to forms
- Tweets not showing up when JavaScript is introduced

  -  Module rest_framework not working. It was solved by changing the Interpreter, it was not set to the virtual environment

- React learning curve... O_o
- Uploading React modules to GitHub
- CORS policy. Solved by (pipenv install django-cors-headers)



LEARNING BULLETS:

1. Django templates use string substitution.
2. The app we create by (python3 manage.py start app <name> allows us through models.py to store data in our DB.
3. CSRF TOKEN is a security token used so, no other web page can submit this data.
4. Foreign Key, we can tie one model to another, as in associate a blog post to a specific user.
5. Never forget, after any change in models.py:   python3 manage.py makemigrations + python3 manage.py migrate.
6. Pay attention to the spelling, it will save you hours.
7. ctrl + C and python3 manage.py runserver will be the answer, but not always.
8. Bootstrap is the most used template framework, for a good reason.
9. Try to avoid conditional logic inside the templates. The safe way is to write it in views.py
10. Git guardian will send you a warning message because you exposed the Django secret key the moment you uploaded your code to GitHub.

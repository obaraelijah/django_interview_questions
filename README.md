# django_interview_questions
#### Difference between Flask and Django?
| Comparison Factor     | Django    | Flask   |
| :------------- | :----------: | :----------- |
|  Project Type | Supports Large Projects| Built for smaller projects |
| Templates,Admin, ORM  | Built in  | Needs to be installed |
| Flexibility  | Allows complete web development without the need for third-party tools| More flexible as the user can select any third-party tools according to their choice and requirements |
| Visual Debugging |	Does not support Visual Debug	| Supports Visual Debug |
| Type of framework |	Batteries included |	Simple, lightweight |
|Bootstrapping-tool |	Built-it|	Not available | 
<br>
Nb: Batteries are libraries and tools that are required for common use cases and ORM is the object relational mapping layer which is used to interact with other relational databases.<br>
#### What is  Django?
Django is a Python-based free and open-source web framework that follows the model-template-view architectural pattern.It was also named after Django Reinhardt who was a jazz guitarist from the 1930s.<br>
#### Which companies use Django?
Pinterest, Instagram, Coursera, Udemy, Spotify, Youtube, Bitbucket, Mozilla,Eventbrite, Dropbox [others](https://stackshare.io/django
#### What are the features of Django?
SEO Optimized -as from the name it means that adding your website to the search engine such that it appears in the top results. This is because Django maintains the built website through URLs rather than the IP addresses on the server, which makes it easy for SEO engineers to add the website to the server while the web-developer doesn’t have to convert the URL into some numeric code.<br>
Rapid Development -Django was designed with the intention to make a framework which takes less time to build web application. The project implementation phase is takes time  but Django creates it rapidly.<br>
Fully loaded framework -Django includes various helping task modules and libraries which can be used to handle common Web development tasks. Django takes care of user authentication, content administration, site maps, RSS feeds etc.<br>
High security -tDjango includes built-in security features such as protection against cross-site scripting (XSS), cross-site request forgery (CSRF), and SQL injection attacks. It encourages secure development practices
It is exceptionally scalable which in turn helps meet the heaviest traffic demands<br>
Versatile -The logical project structure and MVT architecture of Django provides us with a solid foundation which can then be used to make whichever application we want to create.<br>
Scalability -Django is scalable in nature and has ability to quickly and flexibly switch from small to large scale application project.<br>
#### How do you check the Django version installed in a PC?
Open CMD command prompt and type python -m django --version <br> 
You can also try to import Django and use the get_version() method as follows:<br>
```python
import django
print(django.get_version())
```
#### What are the advantages of using Django?

#### Explain Django architecture? 

#### Give a brief about "django-admin"?

#### How do you connect your django project to the database?

#### What are the various files that are created when you create a Django Project? Explain briefly.

#### What are ‘Models’?

#### What are ‘views’?

#### What are ‘templates’?

#### What is the difference between a Project and an App?

#### What are the different inheritance styles in Django?

#### What are static files

#### What are ‘signals’?

#### Briefly explain Django Field Class.

####  How do you create a Django project?

#### What is mixin?

#### What are sessions?

#### What do you mean by context?

#### When can you use iterators in Django ORM?

#### Explain the caching strategies of Django?

#### Explain the use of Middlewares in Django?

#### What is the significance of manage.py file in Django?

#### Explain the use of ‘migrate’ command in Django?

#### How to view and filter items from the database?


#### Explain how a request is processed in Django?

#### How did Django come into existence?

#### How to use file-based sessions?

#### Explain the Django URLs in brief?

#### Give the exception classes present in Django?

#### Does the Django framework scale?

#### Is Django a CMS?

#### Does Django support NoSQL?

#### How can you customize the functionality of the Django admin interface?

#### Give an example of a Django view?


#### What should be done in case you get a message saying “Please enter the correct username and password” even after entering the right details to log in to the admin section?


#### What should be done in case you are not able to log in even after entering the right details and you get no error message?

####  How can you limit admin access so that the objects can only be edited by those users who have created them?

#### What to do when you don’t see all objects appearing on the admin site?

#### What do you mean by the csrf_token?

#### Does Django support multiple-column Primary Keys?

####  How can you see the raw SQL queries that Django is running?

#### Is it mandatory to use the model/ database layer?

#### How to make a variable available to all the templates?
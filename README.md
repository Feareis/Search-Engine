<h3 align="center">
        <samp>&gt; Search Engine
        </samp>
</h3>


<p align="center"> 
  <samp>
    <br>
    「 A program for understanding the basis of certain search engines using similarity calculations 」
    <br>
    <br>
  </samp>
</p>
<br/>

## Use To Code -

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)
![VSCode](https://img.shields.io/badge/Visual_Studio-0078d7?style=for-the-badge&logo=visual%20studio&logoColor=white)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Javascript](https://img.shields.io/badge/Javascript-F0DB4F?style=for-the-badge&labelColor=black&logo=javascript&logoColor=F0DB4F)

<hr/>
<br/>

## About the project -


## Installation - 

After cloning and setting up the project files on your local machine, run the following command in your terminal
```
pip install -r requirements.txt
```
Once the packages are installed you are ready to run the server. But first you need to manually add some nltk packages. run the following command in your terminal
```
py
>>> import nltk
>>> nltk.download()
```


## Project Structure - 

```php
├── app/
│   └── views.py
├── intranet/
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── media/
│   ├── documents/
│   │   ├── doc1.txt
│   │   ├── doc2.txt
│   │   ├── ...
├── static/
│   ├── assets/
│   │   ├── css/
│   │   │   ├── fontawesome-all.min.css
│   │   │   ├── main.css
│   │   │   └── noscript.css
│   │   ├── js/
│   │   │   ├── breakpoints.min.js
│   │   │   ├── browser.min.js
│   │   │   ├── jquery.min.js
│   │   │   ├── jquery.scrollex.min.js
│   │   │   ├── jquery.scrolly.min.js
│   │   │   ├── main.js
│   │   │   └── util.js
├── staticfiles/
│   ├── assets/
│   │   ├── css/
│   │   │   ├── fontawesome-all.min.css
│   │   │   ├── main.css
│   │   │   └── noscript.css
│   │   ├── js/
│   │   │   ├── breakpoints.min.js
│   │   │   ├── browser.min.js
│   │   │   ├── jquery.min.js
│   │   │   ├── jquery.scrollex.min.js
│   │   │   ├── jquery.scrolly.min.js
│   │   │   ├── main.js
│   │   │   └── util.js
├── templates/
│   ├── search.html
│   └── sim.html
├── index.txt
├── manage.py
├── Moteurderecherche.py
├── requirements.txt
└── README.md
```


# nltk
import nltk
nltk.download()
select snowball_data, stopword and punkt


# server
open cmd
go to the project file
run this command :

python manage.py migrate

python manage.py runserver


# Browser
Go to browser and in url tape : 127.0.0.1:8000

<h3 align="center">
        <samp>&gt; Search Engine
        </samp>
</h3>


<p align="center"> 
  <samp>
    <br>
    「 A program for understanding the basis of several search engines using similarity calculations 」
    <br>
    <br>
  </samp>
</p>

## Use To Code -

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)
![VSCode](https://img.shields.io/badge/Visual_Studio-0078d7?style=for-the-badge&logo=visual%20studio&logoColor=white)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Javascript](https://img.shields.io/badge/Javascript-F0DB4F?style=for-the-badge&labelColor=black&logo=javascript&logoColor=F0DB4F)

<br/>

## About the project -

This project was carried out during my studies in France to complete my DUT in Networks and Telecommunications, in 2nd year. Its aim was to learn how to manage and develop a Python project using the knowledge acquired during the courses of the last 2 years.

<br/>

Overall, the program will retrieve all the words contained in each of the documents in [media/documents](https://github.com/Feareis/Search-Engine/tree/main/media/documents), then it will retrieve the root of all these words, classify them and give them all the following characteristics in the [index.txt](https://github.com/Feareis/Search-Engine/blob/main/index.txt) file :
```
{word root}        {file}   :   {occurrence % in all documents combined}   {appearance number all documents combined}
```

<br/>

The main code is [Moteurderecherche.py](https://github.com/Feareis/Search-Engine/blob/main/Moteurderecherche.py) and it is fully documented.

<br/>

## Installation - 

After cloning and setting up the project files on your local machine, run the following command in your terminal
```
pip install -r requirements.txt
```
Once the packages are installed you are ready to run the server. But first you need to manually add some nltk packages. Move to your project folder, open your best python interpreter and run the following commands
```
import nltk
nltk.download()
```
A window should open. Select All packages then download snowball_data, stopword and punkt

![nltk.dowload()](media/documents/nltk.download().PNG)

Once done, You can run the server. Go back in terminal and type
```
python manage.py migrate
python manage.py runserver
```
To access your new little search engine, open your browser and go to the following address [127.0.0.1:8000](http://127.0.0.1:8000)

<br/>



## Tech Stack - 

- [NLTK](https://www.nltk.org/index.html)
- [Django](https://www.djangoproject.com/)

<br/>

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
└── README.md
```

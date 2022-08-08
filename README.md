# A Complete Beginner's Guide to Django

[![Python Version](https://img.shields.io/badge/python-3.6-brightgreen.svg)](https://python.org)
[![Django Version](https://img.shields.io/badge/django-1.11-brightgreen.svg)](https://djangoproject.com)

Code samples from the Django tutorial series.

![Django Boards Screenshot]![68747470733a2f2f73696d706c6569736265747465727468616e636f6d706c65782e636f6d2f6d656469612f7365726965732f626567696e6e6572732d67756964652f312e31312f706172742d342f6d61696e6d656e752e706e67](https://user-images.githubusercontent.com/110183225/183378291-9309a23e-e350-4c7a-b9bb-38c6926699a1.png)



## Running the Project Locally

First, clone the repository to your local machine:

```bash
git clone git@github.com:sibtc/django-beginners-guide.git
```

Install the requirements:

```bash
pip install -r requirements.txt
```

Setup the local configurations:

```bash
cp .env.example .env
```

Create the database:

```bash
python manage.py migrate
```

Finally, run the development server:

```bash
python manage.py runserver
```

The project will be available at **127.0.0.1:8000**.


## License

The source code is released under the [MIT License](https://github.com/sibtc/django-beginners-guide/blob/master/LICENSE).

[![Creative Commons License](https://i.creativecommons.org/l/by-nc-sa/3.0/88x31.png)](http://creativecommons.org/licenses/by-nc-sa/3.0/)

The tutorials, documentations, comics are licensed under the
[Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported License](https://creativecommons.org/licenses/by-nc-sa/3.0/).

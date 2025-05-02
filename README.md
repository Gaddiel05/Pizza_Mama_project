# 🍕 Pizza Mama – Django Web Application

Welcome to the **Pizza Mama** project! This is a Django-based web application developed as part of the Udemy course [*Développeur Python | Formation Complète*](https://www.udemy.com/course/developpeur-python-formation-complete/), created by [CoderAvecJonathan](https://www.udemy.com/user/jonathan-roux/). The project aims to provide hands-on experience in building a full-fledged web application using Python and Django.

## 🌐 Live Demo

Experience the live application here: [http://gaddiel.pythonanywhere.com/](http://gaddiel.pythonanywhere.com/)

## 📂 Project Structure

The repository comprises the following key components:

- `pizzamama/`: Main Django application containing views, models, templates, and static files.
- `menu/`: Django app managing the pizza menu, including models and views related to pizza items.
- `db.sqlite3`: SQLite database file storing application data.
- `manage.py`: Django's command-line utility for administrative tasks.

## 🚀 Features

- Dynamic display of pizza menu items.
- User-friendly interface with responsive design.
- Database integration for storing and retrieving menu items.
- Modular code structure following Django best practices.

## 🛠️ Installation

### Create a virtual environment:

<pre>
<code>python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
</code>
</pre>

### Install dependencies:

<pre>
<code>pip install -r requirements.txt
</code>
</pre>

### Apply migrations:

<pre>
<code>python manage.py migrate
</code>
</pre>

### Run the development server:

<pre>
<code>python manage.py runserver
</code>
</pre>

### Access the application:

Open your browser and navigate to [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

## 🎓 Acknowledgments

Special thanks to **[CoderAvecJonathan](https://www.udemy.com/user/jonathan-roux/)** for creating the comprehensive Udemy course [*Développeur Python | Formation Complète*](https://www.udemy.com/course/developpeur-python-formation-complete/), which served as the foundation for this project. The course offers in-depth knowledge and practical experience in Python development, covering various aspects from basics to advanced topics.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Project Overview
This is a simple polls website built using the Django web framework. The website allows users to create, vote, and view polls. Each poll can have multiple choices, and users can select their preferred choice to vote.

## Features
* Create new polls with multiple choices.
* Vote for a choice in a poll.
* View the results of a poll.
* See a list of all polls.

## Prerequisites
Before running the polls website, make sure you have the following installed:

* Python (version 3.6 or later)
* Django (version 3.0 or later)

## Installation
1. Clone the repository or download the source code.
```bash
git clone https://github.com/silentwraith03/VoteNexus.git
```
2. Navigate to the project directory.
```bash
cd VoteNexus
```
3. Create the database and apply the migrations.
```bash
python manage.py migrate

```
4. Start the development server.
```bash
python manage.py runserver
```
5. Open your web browser and visit http://localhost:8000/ to access the polls website.

## Project Structure
```arduino
VoteNexus/
  |- images/
  |- pollster/
  |- |- pages/
  |- |- polls/
  |- |- pollster/
  |- |- templates/
  |- |- db.sqlite3
  |- |- manage.py
  |- LICENSE
  |- README.md
```

## Screenshots
<img src='images/sc1.png'>
<img src='images/sc2.png'>
<img src='images/sc3.png'>
<img src='images/sc4.png'>
<img src='images/sc5.png'>

## Tech Used
* Python
* Django
* HTML
* CSS
* JavaScript
* SQLite

## License
[MIT](LICENSE)
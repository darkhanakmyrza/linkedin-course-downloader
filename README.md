# linkedin-course-downloader
script for download video from linkedin


A simple python scraper tool that downloads video lessons from Linkedin Learning

## How to use

In the `config.py` file, write your login info and fill the `COURSES` array with the slug of the courses you want to download, for example:

`https://www.linkedin.com/learning/it-security-foundations-core-concepts/` -> `it-security-foundations-core-concepts`

```python
USERNAME = 'user@email.com'
PASSWORD = 'password'

COURSES = [
    'it-security-foundations-core-concepts',
    'javascript-for-web-designers-2',
    ...
]
```

First install the requirements:

```bash
pip install -r requirements.txt
```

Then execute the script:

```bash
python script.py
```
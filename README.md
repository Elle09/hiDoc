# hiDoc



A website which based on symptoms entered by user gives the **probable disease** he/she may have and recommends nearby hospitals/clinics (within 10 KM).


### Machine Learning Techniques :

- Natural Language Processing
- Multiclass Classification
- Data Visualization
- Data Manuplation


### How To Run Our App Locally:



```

```

- Make sure you have Django installed:

```
python -m django --version
```

- Run:

```
pip install -r requirements.txt
```

- Configure .env in hacknitp/.env.example:

```
SECRET_KEY=YOUR_HEX_24_KEY
DEV_HOST='127.0.0.1'
PRODUCTION_HOST=YOUR_REMOTE_HOST
MAP_API_KEY=YOUR_MAP_API_KEY_FROM_HEREMAPS
ENV=dev OR production depending on environment
```

- To generate SECRET_KEY:

```
Run in python-shell:

import secrets
secrets.token_hex(24)
```

### Languages and Frameworks:

- Python
- Django (Framework for python)
- HTML/CSS
- JavaScript
- Bootstap
- JQuery

### Tools:

- Jupyter Notebook

### Machine Learning Libraries:

- Numpy
- Pandas
- Matplotlib
- Wordcloud
- NLTK
- Scikit-Learn

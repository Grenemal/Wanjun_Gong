---
title: Blog with Jupyter Notebooks!
date: '2023-11-04'
summary: Easily blog from Jupyter notebooks!
---


```python
from IPython.core.display import Image
Image('https://www.python.org/static/community_logos/python-logo-master-v3-TM-flattened.png')
```


    

```python
print("Welcome to Academic!")
```

    Welcome to Academic!

## Organize your notebooks

Place the notebooks that you would like to publish in a `notebooks` folder at the root of your website.
    
![png](Product1.png)

## Import the notebooks into your site

```bash
pipx install academic
academic import 'notebooks/**.ipynb' content/post/ --verbose
```
![png](Product2.png)

The notebooks will be published to the folder you specify above. In this case, they will be published to your `content/post/` folder.

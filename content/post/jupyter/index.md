---
title: Display Jupyter Notebooks with Hugo
subtitle: Learn how to blog in Hugo using Jupyter notebooks :pen:.
summary: Learn how to blog in Hugo using Jupyter notebooks :pen:.
authors:
- admin
tags:
- jupiter
- notebook
- data
- python
- graphs
categories:
- Blog
- DevTools
projects: []
date: "2022-01-05T00:00:00Z"
lastMod: "2022-01-05T00:00:00Z"
image:
  caption: ""
  focal_point: ""
  placement: 3
---

```python
from IPython.core.display import Image
Image('https://www.python.org/static/community_logos/python-logo-master-v3-TM-flattened.png')
```




![png](./index_1_0.png)




```python
print("Welcome to Hugo!")
```

    Welcome to Hugo!


## Install Python and JupyterLab

[Install Anaconda](https://www.anaconda.com/distribution/#download-section) which includes Python 3 and JupyterLab.

Alternatively, install JupyterLab with `pip3 install jupyterlab`.

## Create or upload a Jupyter notebook

Run the following commands in your Terminal, substituting `<MY-WEBSITE-FOLDER>` and `<SHORT-POST-TITLE>` with the file path to your Academic website folder and a short title for your blog post (use hyphens instead of spaces), respectively:

```bash
mkdir -p <MY-WEBSITE-FOLDER>/content/post/<SHORT-POST-TITLE>/
cd <MY-WEBSITE-FOLDER>/content/post/<SHORT-POST-TITLE>/
jupyter lab index.ipynb
```

The `jupyter` command above will launch the JupyterLab editor, allowing us to add Academic metadata and write the content.

## Edit your post metadata

The first cell of your Jupyter notebook will contain your post metadata ([front matter](https://sourcethemes.com/academic/docs/front-matter/)).

In Jupyter, choose _Markdown_ as the type of the first cell and wrap your Academic metadata in three dashes, indicating that it is YAML front matter: 

```
---
title: My post's title
date: 2019-09-01

# Put any other Academic metadata here...
---
```

Edit the metadata of your post, using the [documentation](https://sourcethemes.com/academic/docs/managing-content) as a guide to the available options.

To set a [featured image](https://sourcethemes.com/academic/docs/managing-content/#featured-image), place an image named `featured` into your post's folder.

For other tips, such as using math, see the guide on [writing content with Academic](https://sourcethemes.com/academic/docs/writing-markdown-latex/). 

## Convert notebook to Markdown

```bash
jupyter nbconvert index.ipynb --to markdown --NbConvertApp.output_files_dir=.
```

## Example

This post was created with Jupyter. The original files can be found at https://github.com/gcushen/hugo-academic/tree/master/exampleSite/content/post/jupyter

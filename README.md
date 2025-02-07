# Overview
This is the source code location for https://wiki.betterpvp.net/

# Installation for local development
Once you have cloned into your fork or this repository, navigate to the root directory. This site is built using [MkDocs](https://www.mkdocs.org/getting-started/).

First, you will need to install the needed packages.
`pip install mkdocs`

Then the following add-ons (you can check these by running `python -m mkdocs get-deps`)
`pip install mkdocs-material`
`pip install mkdocs-minify-plugin`

# Running for local development
Now, in the root directory, you can use `python -m mkdocs serve` to run a local development servver.
This will update changes you have on `http://127.0.0.1:8000/` so that you can see what they would look like in the browser.

# Docs
`docs/` is where content for the site is stored.

# First Pelican Site

I've been curious about static site generators for a while and I was excited to find two platforms powered by Python: Pelican and Nikola.

I'm giving [Pelican](https://blog.getpelican.com/) a shot first.

## Virtualenv

Installing virtualenv with Python 3:

`virtualenv -p python3 venv`

## Install Pelican

With Markdown:

`pip install pelican markdown`

## Create a project

Run this command and follow the instructions:

`pelican-quickstart`

Then create a piece of content in Markdown, save under `/content/` and generate the site with:

`pelican content`

## Preview site

In `/output/`, run:

`python -m pelican.server`


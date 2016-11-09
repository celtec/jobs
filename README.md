Celtec Github Site
==================

Jobs website generated with [Python Pelican](https://github.com/getpelican/pelican) with [Nest theme](https://github.com/molivier/nest).

## Setup

```
pip install pelican
```

For more details, check [Pelican docs](http://docs.getpelican.com/en/stable/install.html)

## Preview

```
./develop_server.sh start
```

Then access [localhost:8000](http://localhost:8000)

To stop server just run:

```
./develop_server.sh stop
```

## Publishing

```
pelican content/ -o output/ -s publishconf.py
ghp-import output/
git push origin gh-pages
```

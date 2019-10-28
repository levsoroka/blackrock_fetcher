# blackrock_fetcher [![Build Status](https://travis-ci.org/ccnmtl/blackrock_fetcher.svg?branch=master)](https://travis-ci.org/ccnmtl/blackrock_fetcher)
data fetcher and processor for Blackrock forest

### Python compatibility
This fetcher script was originally written to be compatible with
Python 2.6, since that's what was available on cunix at the time.
This script is now deployed using pyenv on cunix, so we no longer have
the Python 2.6 limitation.

Here's how to create a virtualenv for the blackrock fetcher and set
everything up for the cron job:

```
pyenv local 3.6.9
python -m venv ve
./ve/bin/pip install -r requirements.txt
```

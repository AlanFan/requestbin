web: bin/python setup.py develop && bin/python -c "__requires__ = 'gservice'; import sys; from pkg_resources import load_entry_point; sys.exit(load_entry_point('gservice', 'console_scripts', 'gservice')())" -C ./config/heroku.conf.py run
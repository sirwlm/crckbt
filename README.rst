
* ``EMAIL``: the e-mail address to sign in with Discord
* ``PASSWORD``: the password to sign in with Discord (who would've guessed huh)
* ``DJANGO_SETTINGS_MODULE``: used to figure out which settings to load. Set to
  ``bot.settings`` or a custom settings file. Used by Django to be able to load
  the settings.
* ``SECRET_KEY``: required by Django. See https://docs.djangoproject.com/en/1.9/ref/settings/#std:setting-SECRET_KEY

Set these envvars in your shell (see discord-bot.ini).

Then make the db tables through django, and launch the bot using main.py

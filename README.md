# askbot-dictionary
This is a askbot customization that turns it to a word translation forum

## Changes in settings.py
If you're going to use custom translation files 
* add the path of your files to your settings file

  ```LOCALE_PATHS = [
  '/PRODUCTION/ASKBOT/web/askbot/locale',
  ]```


* compile files on server in the askbot folder

  ```django-admin.py compilemessages``` 

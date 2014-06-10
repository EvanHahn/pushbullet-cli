Pushbullet CLI interface
========================

Use [Pushbullet](https://www.pushbullet.com/) from the command line. In beta!

*Requires `requests` to be installed.*

You can clone this repo and then add the following to your bashrc (or your zshrc, or whatever):

    $ echo 'alias pushbullet="/path/to/pushbullet-cli/pushbullet.py'" >> ~/.bashrc
    $ source ~/.bashrc

Push text:

    $ pushbullet burritos
    $ pushbullet "I love burritos"
    $ pushbullet Make sure you remember to eat a burrito

Push links:

    $ pushbullet http://losaltostaqueria.org/
    $ pushbullet https://www.pushbullet.com/

Push files:

    $ pushbullet /path/to/burrito_photo.jpg
    $ pushbullet /path/to/burrito_recipe.txt

Change title from "Note" or "Link":

    $ pushbullet --title="New title" Title is changed.
    
Set target where message to:

    $ pushbullet --target=iphone This message will go to iphone without asking.

I'm not too experienced with Python, so please feel free to send a pull request!

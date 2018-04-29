# John Nash Home Page at Princeton 

http://web.math.princeton.edu/jfnj/texts_and_graphics/ 

This torrent version has all the files resulting of running the `wget` command plus a few changes.

There was a lot of files named `index?*.html` that I removed with

`find . -iname "index.html?*" -exec rm {} \;`

And I also edited three `index.html` files to allow navitation to levels bellow and back to the top level.


## Content 

At `John_Nash_Home_Page/` you will find one txt files with a tree of all the content:

`John_Nash_Home_Page_tree_2.txt` - Tree of the content 


## Usage

Open index.html on the `web.math.princeton.edu`and browse at your will.


## How it was done

http://web.math.princeton.edu/jfnj/texts_and_graphics/ mirrored with wget:

`wget --wait=2 -m -e robots=off --random-wait --mirror -pc --convert-links -P ./ http://web.math.princeton.edu/jfnj/texts_and_graphics/`


## Donations

![alt text](https://i.imgur.com/OimJ5Up.png "Logo Title Text 1")

You are free to donate.

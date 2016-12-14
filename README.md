# food_com_scraper
Will scrape a recipe from the food.com website into a html file. Can also take a file with a list of recipes.

HELP

usage: food_com_scrapper.py [-h] [-v] [-i INPUT] [-f FILE]

This will download the recipe from the url provided from food.com. The output
will be written to the current directory. The output filename is reqired to be
entered on the command line.

optional arguments:
  -h, --help            show this help message and exit
  -v, --version         show program's version number and exit
  -i INPUT, --input INPUT
                        a recipe URL from food.com
  -f FILE, --file FILE  A file that contains a list of urls to download
  
 You need to enter either a url (-i) or a file with a list of urls (-f).
 
 Before you can use it, you need to change the location of the output file... I've hardcoded it to a specific locaton on my computer.

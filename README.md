
jemdoc is a light text-based markup language designed for creating websites. It
takes a text file written with jemdoc markup, an optional configuration file and
an optional menu file, and makes static websites that look something like
http://jemdoc.jaboc.net/.

It was firstly written by Jacob Mattingley, in 2007. Much more info at http://jemdoc.jaboc.net/.

Modified by Pantoria. Much more info at https://pantoria.github.io/new_jemdoc/.

## How to use

1. Clone this repo 
2. Change "./css/mysite.css" with your name (2 positions)
3. Edit the content of "./MENU"
4. Edit "./*.jemdoc"
5. Run 
  ``` bash
    make update
  ```

If you want to clean all the html files, please run 
```bash
  make clean
```

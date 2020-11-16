## Website for Goosesstats (project: Gooseswell)

[ [gooseswell](https://gooseswell.mooo.com/) / [goosesstats](https://goosesstats.mooo.com/) ]

If you want to render this page you need **pug** and **sass** installed on your machine.

To render the page:

```
$ git clone https://github.com/skorotkiewicz/goosesstats
$ chmod +x render.sh
$ ./render.sh
```

or:

```
$ pug-cli ./source/site/ -o dist/
$ sass styles.sass dist/styles.css
```

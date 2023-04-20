# Welcome to MkDocs


AAPS is an abbreviation, which gets its tooltip from a single glossary file without having to include anything special... AAPS1 is the same thing across mutliple lines but it is is a bit ugly to code...

AAPS here


For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.


TOOLTIP Options (for glossary &al!)
test

this is an example 1 of[multiline tooltip 1](" line1&#10line2")
``` md
this is an example 1 of[multiline tooltip 1](" line1&#10line2")
```


[tooltip_example_2]: ## "this is line 1 of my tooltip &#10this &NewLine is line 2 of my tooltip"
this is an example2 of [multiline  tooltip][tooltip_example_2]
``` md
[tooltip_example_2]: ## "this is line 1 of my tooltip &#10this &NewLine is line 2 of my tooltip"
this is an example2 of [multiline  tooltip][tooltip_example_2]
```


this is example 3 of [multiline tooltips with a link](https://example.com 
"I'm a tooltip! again &#10
and again? &#10
foo")
``` md
this is example 3 of [multiline tooltips with a link](https://example.com 
"I'm a tooltip! again &#10
and again? &#10
foo")

```
AAPS there

<br>
<br>
<br>

this is example 4 of :material-information-outline: foo {  title="line1&#10 <br>line2" }
``` md
this is example 4 of :material-information-outline: foo {  title="line1&#10 <br>line2" }
```
<br>
<br>
<br>

here is anohter tooltip in html
<button title="This is a tooltip.
     .
    It has multiple lines.">Hover over me</button>

``` md
here is anohter tooltip in html
<button title="This is a tooltip.
     .
    It has multiple lines.">Hover over me</button>
```



AAPS everywhere
<br>
<br>
<br>


this ia an example of glossary: 
``` md
*[HTML]: Hyper Text Markup Language &#10  and more
*[W3C]: World Wide Web Consortium
*[AAPS]: Android Artificial Pancreas System 
*[AAPS1]: (Android Artificial Pancreas System &#10&#10&#10 An implementation of the open source OPEN-APS designed to run on commodity android cell phones and tablettes.) 
```

<br>
<br>
<br>


<details><summary> this is an example of a summary with multiple lines details </summary>
this is line 1 of my details.<br>
this is line 2 of my details.<br>
</details>

``` md
<details><summary> this is an example of a summary with multiple lines details </summary>
this is line 1 of my details.<br>
this is line 2 of my details.<br>
</details>
```


## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.



## Icons and Emojis
:smile:

:fontawesome-regular-face-laugh-wink:

:fontawesome-brands-twitter:{ .twitter }

:octicons-heart-fill-24:{ .heart }

## Progress Bar... 

<>[=80% "almost done 80%"]
<>
[comment]: <> ({: .candystripe .candystripe-animate})
# Welcome to MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.


TOOLTIP Options (for glossary &al!)
test

this is an example 1 of[multiline tooltip 1](" line1&#10line2")

[tooltip_example_2]: ## "this is line 1 of my tooltip &#10this is line 2 of my tooltip"
this is an example2 of [multiline  tooltip][tooltip_example_2]

this is example 3 of [multiline tooltips with a link](
    https://example.com "
    I'm a tooltip! again &#10 <br>
    and again? 
    foo")

this is example 4 of :material-information-outline:{ title="line1&#10 <br>line2" }


<details><summary> this is an example of a summary with multiple lines details </summary>
this is line 1 of my details.<br>
this is line 2 of my details.<br>
</details>




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

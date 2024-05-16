# Welcome to MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.


## Blocks

!!! name-of-block

    content

!!!

!!!  note | Did you know?

You can create a note with Blocks!

!!!

## Nested Blocks
//// note | Some title

/// details | Summary

    type: warning

content

///

Content

////




## Definitions
/// define

Apple



- Pomaceous fruit of plants of the genus Malus in

  the family Rosaceae.



///

## Multiple Definitions
/// define

Apple



- Pomaceous fruit of plants of the genus Malus in

  the family Rosaceae.



Orange



- The fruit of an evergreen tree of the genus Citrus.



///



### Details
/// details | Some summary

Some content

///


### Tabs
/// tab | Tab 1 title

Tab 1 content

///



/// tab | Tab 2 title

Tab 2 content

///


### Tab groups
/// tab | Tab A title

Tab A content

///



/// tab | Tab B title

Tab B content

///



/// tab | Tab C Title

    new: true



Will be part of a separate, new tab group.

///

### Details
??? optional-class "Summary"

    Here's some content.



??? multiple optional-class "Summary"

    Here's some content.

### Nested Details
???+ note "Open styled details"



    ??? danger "Nested details!"

        And more content again.
### Classes from titles
??? success

   Content.



??? warning classes

   Content.

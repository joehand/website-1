# Stencila website design guide

> This is a design guide for the Stencila website at https://stenci.la.
It outlines the goals of each of the site's areas, pages and sections.
We love contributions! Please see [`CONTRIBUTING.md`](CONTRIBUTING.md) if you'd
like to help out.



## Terminology

- An "area" is a top level part of the site (e.g. `/learn/`) and can have "sub-areas" (e.g. `/learn/getting-started/`).
- A "page" is a web page inside an area (e.g. `/learn/getting-started/installation.html`).
- A "section" is a section of a page and usually represented by a `<div class="section">` element and/or a header (i.e. using `#` in Markdown).



## Area `/learn`

### Sub-area `/learn/languages`

The goals and structure of each page in this sub-area are the same (but obviously the context differs for each language).

> Goal: A reader wanting to use language X within Stencila documents (e.g. writing code cells, creating new functions) will understand how to do that and know that they can come back to the page as a reference (e.g. for the syntax for functions).

Each page will have plenty of examples for the language and links to references/tutorials for that language. 

There is a page for each language supported by Stencila.

#### Page `/learn/languages/javascript.html`
#### Page `/learn/languages/mini.html`
#### Page `/learn/languages/python.html`
#### Page `/learn/languages/r.html`
#### Page `/learn/languages/sql.html`

The sections in each page will be:

##### Section `Data`

- a table of the mapping between Stencila data types and the language's native data types

##### Section `Cells`

- how cell `inputs` and `output` are determined
- any gotchas with writing cells for the language

##### Section `Functions`

- how to implement functions in the language
	- argument type checking
	- repeatable and extensible parameters

- how to document functions in the language
	- function description, examples etc
	- parameter types, description etc
	- return type


## Area `/blog`

> Goal: Highlight new things in the Stencila universe (features, partnerships, workshops etc) to demonstrate ongoing activity and progress.

- aim to have at least two new posts each month
- invite blog post contributions from members of the community


## Area `/about`

> Goal: Give visitors a feel for how the project started, the people behind it, our partners and funders.

- include a TOC sidebar with links to sub-areas...

### Sub-area `/about/people`

- include staff, advisory board members, contributors
- don't group people hierarchically, alphabetically or chronologically, instead list them randomly (e.g. on each build)
- have a small blurb on each person
- a call to action for contributors to add their name to the wall.
- similar examples:
	- https://buffer.com/about
	- https://web.hypothes.is/team/

### Sub-area `/about/partners`

- list of partners including a few words on how we partner with them

### Sub-area `/about/funders`

- a list of funders including what they have funded

### Sub-area `/about/giants`

> Goal: Acknowledge the giants who's shoulders we stand upon: open source projects that Stencila uses and integrates with.

- a list of projects and how Stencila uses/integrates with them
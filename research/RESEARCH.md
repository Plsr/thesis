# Research
Notes of studies and articles used for research

For a list of papers yet to be read, consult [the issues](https://github.com/Plsr/thesis/labels/to%20read)

### [Interactive Genetic Algorithms for User Interface Design](http://ieeexplore.ieee.org/document/4424630/)

#### Summary
* Use Genetic algorithms to help lowering user fatigue (by building interfaces in the XUL Interface language).
* Fitness of individual calculated based on combination of user input and design guidelines.
* User only chooses best and worst solution from a subset of nine proposals one every _t_ generations (_t_ was varied)
* First step in the field, there is ambition to improve on the findings of the study

#### Critique
* Widgets are judged objectively only based on color
* Were the users designers? How good was the individual input?
* The end UIs still don't look good.
* Focus rather on  reducing user fatigue than building a UI with algorithms which shows in the end results (UIs do not look good at all)


### [Successful User Interface Design from Efficient Computer Algorithms](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.27.2962&rep=rep1&type=pdf)

#### Summary
* The user interface was considered as a data structure and a better structure was built with the help of algorithms
* Users would navigate through the functions of the device by typing the names of functions with the number keys of the device and selecting the matching one from the results.
* User preferred the new design
* The new design was measured as more performant

#### Critique
* As the experiment is rather old (2000), the UI was textual rather than graphical. For the purpose of my thesis its not that helpful.
* It’s at least a use case where someone combined design and algorithms, even if not in the way I’m looking for.


### [Interactive design of web sites with a genetic algorithm](https://pdfs.semanticscholar.org/4f26/61bfc4301758c36bfd6010a4f1cf926c25db.pdf)

#### Summary
* Use IGAs to build layouts and designs (mostly color) of websites
* User is presented 12 evolutions and can choose however many he likes
* Styles are limited to 14 predefined options

#### Critique
* The user can choose which designs he likes, but maybe the user does not have any knowledge about design
* End results are not that pretty, even though they are very limited in layout and styling

### [Imagine: a tool for generating HTML style sheets with an interactive genetic algorithm based on genes frequencies](http://ieeexplore.ieee.org/document/823287/)

#### Summary
* Use IGA to show user stylesheets for a website and let them choose the one that looks best
* User can set the Diversity and Importance of choices
* User can edit one result directly if they just want to alter one specific element and all the other elements are already fine

#### Critique
* You can sense from the way web pages are built that this study is pretty old and may not have to much impact nowadays (i.e. usage of  `.gif` files for almost all website elements)
* Only five elements are used to define the design of a webpage, which is way to less for today’s standards
* For text styling, many values are possible where most of the can be ruled out rather simply (i.e. text size, color, …)

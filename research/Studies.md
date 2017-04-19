# Studies
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

### [What is beautiful is usable](http://www.ise.bgu.ac.il/faculty/noam/papers/00_nt_ask_di_iwc.pdf)

#### Summary
* The researchers examined the affects of aesthetic design to the relationship of a user with a product as a whole, as well as the effects it had on the overall subjective usability of a user
* The experiment was executed with different layouts of an ATM, differing both in ratings of usability and preserved aesthetic design.

#### Critique
* In terms of my thesis this merely is another point emphasising the importance of aesthetics in design

#### [Evaluating the consistency of immediate aesthetic perceptions of web pages](http://www.sciencedirect.com/science/article/pii/S1071581906000863)
* Same here, “just” an experiment supporting Lindgaards study.

### [How will the use of graphics affect visual aesthetics? A user-centered approach for web page design](http://www.sciencedirect.com/science/article/pii/S1071581912001656)
#### Summary
* The whole experiment was conducted around defining which elements on a webpage generated a certain feeling for users and then teaching a Neural Network how recommend elements that will generate a certain feeling for a user
* This was achieved in several steps:
	* First, a group of experts defined the seven most influential design elements on the chosen pages in different types
	* Then, subjects were asked to apply the semantic differential on the pages.  On the three most influential pairs of emotion than a Grey Relational Analysis was applied.
	* The relation between the web page feeling and the importance of a design element was then taught to the neural network.
	* The Network was then able to tell a designer which elements should be designed in which way to cause a certain feeling for a user.

#### Notes
* Can graphics on a webpage be seen as whitespace?

#### Related
* Cheng, H.-I., Patterson, P.E., 2007. Iconic hyperlinks on e-commerce websites. Applied Ergonomics 38, 65–69.
* Yeh, C.-H., Lin, Y.-C., Chang, Y.-H., 2007. A neural network approach to website design. Dynamics of Continuous, Discrete and Impulsive Systems: Series B, Applications and Algorithms (DCDIS Series B) 14
(S2), 1598–1601.

### [Web aesthetics and usability: An empirical study of the effects of white space](https://www.researchgate.net/publication/269639066_Web_Aesthetics_and_Usability)

#### Summary
* The study aims to investigate the effects of used amount of whitespace on the users of a (fictive) travel booking website.
* The study looked at the relative amount of whitespace used in the webpage.
* The researchers aimed to prove 7 hypothesises regarding the amount of whitespace used:
* Perceived attractiveness, efficiency, effectiveness and satisfaction of a webpage will be grater when the total amount of whitespace approaches 50%.
* The greater the level of perceived attractiveness of a website is, the grater its perceived efficiency, effectiveness and satisfaction will be.
* The results suggest that
* There is a general difference of Perceived attractiveness, efficiency, effectiveness and satisfaction regarding whitespace
* All the above dropped when the amount of whitespace was raised from 50% (and 25%) to 75%
* There was no significant drop when the amount of whitespace was reduced from 50% to 25%
* The above suggests that there is a certain amount of whitespace that is perceived as “good” by users. Reducing that amount is not perceived as bad as increasing it.

#### Notes
* High number of test participants (94)

#### Critique
* Manipulation of whitespace was done by reducing the amount of information and by shrinking font-sizes, buttons etc. This may not be the best approach to gain more Whitespace in an document.
* There are no images of the used designs included.

#### Related
* Steven J. Harrington, J. Fernando Naveda, Rhys Price Jones, Paul Roetling, and Nishant Thakkar. 2004. Aesthetic measures for automated document layout. In Proceedings of the 2004 ACM symposium on Document engineering (DocEng '04). ACM, New York, NY, USA, 109-111. DOI=http://dx.doi.org/10.1145/1030397.1030419
* Jinwoo Kim, Jooeun Lee, and Dongseong Choi. 2003. Designing emotionally evocative homepages: an empirical study of the quantitative relations between design factors and emotional dimensions. Int. J. Hum.-Comput. Stud. 59, 6 (December 2003), 899-940. DOI=http://dx.doi.org/10.1016/j.ijhcs.2003.06.002

# ISCB Tutorial - cobrapy, escher, cameo and DD-DeCaF

Most modern biotechnology applications depend on efficient algorithms for modeling metabolic flux and predicting viable strain designs. The [packages](http://opencobra.github.io/cobrapy/packages) in the rapidly growing [cobrapy community](http://opencobra.github.io/cobrapy/) provide implementations of numerous popular analysis and simulation methods for constraints-based metabolic flux models, as well as search  optimization algorithms for designing novel pathways, all implemented in the widely popular and freely available programming language Python.

In this tutorial, we will first give an introduction to the micro-service/web-based *data-driven design of cell factories  communities platform ([DD-DeCaF](http://app.dd-decaf.eu))*, which aims to bring efficient data management, visualization and strain design methods to a broad audience.

Following that, we provide a detailed, hands-on session using the cobrapy related packages that power the DD-DeCaF platform directly in a [Jupyter notebook](http://jupyter.org/). We will demonstrate how to use the [cobrapy](http://opencobra.github.io/cobrapy) package itself to create constraints-based metabolic flux models and to manipulate them programmatically. Examples will be given showing how to apply popular algorithms such as parsimonious flux balance analysis, flux variability analysis, flux sampling, and how to analyze the impact of knocking-out genes, finding blocked reactions, and much more. After the demonstration of cobrapy, we will proceed by providing an introduction to using [escher](https://escher.github.io/) to create elegant pathway visualizations. Finally, we will show-case the [cameo](http://cameo.bio) package allowing participants to predict heterologous pathways for selected targets and to optimize these using different genetic manipulation strategies.

# Schedule and format

We start each section with a short presentation of the introduced methods and algorithms to provide the necessary background and then interactively, step-by-step reproduce the analysis together with the participants. For the demonstration of DD-DeCaF, participants are encouraged to try the platform online. For the tutorial on cobrapy and cameo, users may either follow the presenter with their own local Python installation, or by using the interactive server [FIX](fix)

To enable as participants of different backgrounds to join, we will start the second part by giving a gentle introduction to programming in Python and using the Jupyter notebook.

| Time       | Topic                                                                                                         |
|------------|---------------------------------------------------------------------------------------------------------------|
| **9:00**   | (45 min) Demonstration of the DD-DeCaF platform                                                               |
| **15 min** | Break                                                                                                         |
| **10:00**  | (45 min) [Gentle introduction to programming in Python using Jupyter notebooks](python-01-crash-course.ipynb) |
| **15 min** | Break                                                                                                         |
| **11:30**  | (1 h) [Modeling metabolic flux using cobrapy](cobra-schedule.md  )                                            |
| **1 h**    | Lunch                                                                                                         |
| **13:15**  | (1 h) [Modeling metabolic flux using cobrapy (continued)](cobra-schedule.md)                                  |
| **15 min** | Break                                                                                                         |
| **14:15**  | (1 h) Model and data visualization with Escher                                                                |
| **15 min** | Break                                                                                                         |
| **15:30**  | (1 h 30 min) [Computational strain design using cameo](cameo-schedule.md)                                     |
| **17:00**  | Finish                                                                                                        |


No prior knowledge of programming is needed only familiarity with fundamental systems biology concepts. Just bring your laptop (installation instructions will be given for Linux, Mac and Windows).

# Names and affiliations of main organizers

-   Moritz E. Beber (DTU Biosustain)
-   Danny Dannaher (DTU Biosustain)
-   Svetlana Galkina (DTU Biosustain)
-   Zachary King (UC San Diego)
-   Henning Redestig (DTU Biosustain)
-   Nikolaus Sonnenschein (DTU Biosustain)

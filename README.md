<div class="cell markdown">

<img src="petrel2python.png" style="width:1000px" align="center">

<h1><center>Exporting and analizing Petrel's data to Python</h1></center>

<h2>Notebook creator</h2>

Manuel **David** Soto. MSc in Geological Sciences, University of Texas
at Austin, USA.

<h2>About this notebook</h2>

Petrel is a powerful and widely used program by geoscientists and engineers who work with subsurface data. With it you can make from a simple map  map from well markers to a complex model of a reservoir with its corresponding surfaces, faults and fluids. Despite these tremendous capabilities of Petrel, certain simple data analysis tasks, such as a histogram or regression, are complicated, cumbersome or incomplete. Although there are plugins that solve these shortcomings of Petrel, Python is a flexible and free alternative for analysis of data residing in Petrel.

The objective of this Notebook is to show through an example how Python can be used as a complement to Petrel's data analysis tasks. The example compares thickness obtained in Petrel from tops and from a seismic surface, and then finds the best regression between them.

<h2>Libraries for notebook</h2>

Here is a list of libraries necessary for this notebook:

    numpy
    matplotlib
    pandas
    scikit-learn

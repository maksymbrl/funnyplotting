# funnyplotting

Description:

Created by Maxim Brilenkov at the Innsbruck University on January 2017

Notebook Page 1: Name is '2D'. It Here you can create a 2D plot, with a given (your function). For this just type your function in the first
                 TextCtrl. Besure to type special function (e.g. cos, sin, exp etc.) using np. extention. For instance: np.exp(x). Also be sure that you typed some math operations like '^' correctly (for '^' it is '**', i.e. x^2 should be typed like x ** 2).
                 There are other TextCtrls, which are for defining the range of the plot (x from 'some value' to 'some value').
                 'Plot' button will plot your function in the canvas on the left.
                 'Erase' button will erase your graph.
                 'Save' button will save your graph in to the same directory as the programs files (!).
                 'X' button(s) will delete the text from the TextCtrls.
                 Also there are 'Advanced' settings which allows you to choose your graphs output parameters, such as Color and LineStyle

Notebook Page 2: Name is '3D'. The structure is similar to that you have in '2D': we have Buttons 'Plot', 'Erase' and 'Save' and also the
                 ranges for x and y variables (TextCtrls). Also there is ComboBox appeared in which you can choose the type of the graph 
                 you want to plot.

INSTALLATION NOTES

To install the code in your computer, you need first to install the anaconda python (https://www.continuum.io/downloads). 
You will have to use the Python 2.x distribution since the code uses wxpython which is still not ported to Python 3.

Then clone the repository: git clone https://github.com/hroney/funnyplotting.git

Build the conda package: conda build funnyplotting

And install it locally:

conda install --use-local funnyplotting

At this point you can start the code everywhere by typing:

funnyplotting

since the executable is in the ~/anaconda/bin directory.

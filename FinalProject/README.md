<b>HW 6:</b> Final Project

<b>Due:</b> 26 April 2019

<b>Individual:</b> Dieu My Nguyen

<b>Project title:</b> Firefly Mating Strategy Agent-Based Model

<b>Description of Jupyter notebooks in this directory:</b>

The 4 notebooks in this directory encapsulate the whole code base for the model. Each notebook includes comments and indications where certain design patterns are used.

- Firefly.ipynb: Contains the abstract base class ```Firefly```, its derived class ```MaleFirefly```, the factory class ```MaleFireflyFactory``` to generate  ```MaleFirefly``` object, and ```FireflyCollection``` to use the ```MaleFireflyFactory``` to generate and contain all male fireflies for a given  simulation.

- World.ipynb: Contains the class ```World``` that represents the entire model where fireflies behave and interact with the environment (2D space and time). This is also recording data and plotting them to update the GUI widgets. This notebook requires importing Firefly.ipynb.

- GUI.ipynb: Contains the class ```WidgetCollection```, in which a widget is an object of a class from the ```ipywidgets``` package. The widgets and the layout containing all the widgets define the GUI. This notebook also contains the class ```SimulationGUI``` which uses the widgets and the world to generate a NetLogo-like GUI where users can choose parameters, run the model, and watch the simulation's data plotted over time. This notebook requires importing Firefly.ipynb and World.ipynb.

- Firefly Mating Strategy Agent-Based Model.ipynb: Acts as the primary user interface, with background information and references about the model and usage information to generate a GUI to run the model.  This notebook requires importing World.ipynb and GUI.ipynb. The GUI looks like this:

<img src="HW6 - Final Report/model.png" alt="model" width="850"/>

<b>Instructions to run code:</b>
The interface to run all code is the Firefly Mating Strategy Agent-Based Model.ipynb notebook. Simply run all the cells currently there. Sample output is retained to show examples of what to expect.

<b>Necessary Python packages:</b>
- ```abc```
- ```importlib```
- ```io```
- ```ipywidgets```
- ```ipynb```
- ```IPython```
- ```matplotlib```
- ```numpy```
- ```random```
- ```scipy```
- ```seaborn```
- ```sys```

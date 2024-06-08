Graph Visualization with Tkinter and PyVis
This script uses Tkinter for the graphical user interface (GUI) and PyVis for graph visualization. It allows users to create and visualize different types of graphs, including normal graphs, path graphs, cycle graphs, star graphs, complete graphs, and bipartite graphs.

Prerequisites
Python 3.x
PyVis
Tkinter (comes with Python standard library)
NumPy

Explanation
-----------
Graph Visualization Functions:

show3 and show functions render the graph using PyVis and save it as an HTML file.
show_adj function displays the adjacency matrix and dictionary of the graph in a Tkinter window.
Graph Type Functions:

bipartite_graph, star_graph, complete_graph, cycle_graph, path_graph, and normal_graph create and visualize specific types of graphs based on user input.
Tkinter GUI:

Sets up the main window with labels, dropdown menu, entry box, and a submit button.
show1 function calls the appropriate graph type function based on user selection from the dropdown menu.
Event Handling:

When the user enters the number of nodes and clicks the submit button, the show1 function determines which graph type function to call and visualizes the graph.

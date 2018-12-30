# Plotly-Visualization
cleaned_data.csv: cleaned data used to create visualizations

treemap - interactive.py: plots tree map of movie gross of 1987, 1997, 2007, 2017.

<img src = "Images/squarify-treemap-interactive-1.png" height = "400">

slider - interactive.py: plots bubble chart of movie rating as x-axis, movie runtime as y-axis, movie gross as the size of bubble, movie year as the slider and movie genre as the color of the bubble. It should run in the Jupyter notebook in order to see the output animation. This python script will not show the animation but runs well.
<img src = "Images/radar chart.png">

valence line chart - interactive.py: selects four Harry Potter movies and plot the valence, the level of positiveness or negativeness of a track, change in the order of the soundtracks in the album (which happen to follow the order of when they are used in the movie, thus a good indicator of movie plots). The name of the track could serve as a short summary of the plot of the whole story.
<img src = "Images/valence line interactive-1.png" height = "400">

radar chart- interactive.py: plots radar chart comparing two sound tracks’ six musical attributes in a single movie based on users’ choice. It’s actually an Dash app supported by poorly. The code running result is a domain where the result is showed. Must open the domain manually and then select anything you want.
<img src = "Images/radar chart.png" height = "400">

movie genre network - interactive.py: plots a giant network where movies and genres are nodes and the edges represents ‘belong to’. Note a movie may have more than one genres. The size of the nodes represents the degrees. Allow for selected different color scale for both nodes and edges.

networkanalysis.py: extracts desired subset of cleaned data and conducts basic network analysis and clustering analysis.
<img src = "Images/Genre Network NX.png" height = "400">

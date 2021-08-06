# A K-Nearest Neighbors Visualization
By Braden McClean and Kristie Colton

## How to open the project: 
	You must run a server to load the data into the project. 
	First, navigate to the root of our project folder in terminal. Then enter the following command: 
		
		python -m SimpleHTTPServer 8888

	After running the server, use the following as a URL in your browser:
		
		http://localhost:8888/index.html

## Project Description
	Our project demosntrates a way to visualize KNN. The grey box highllights the k-closest neighbors to your mouse cursor by highlighting the closest nodes in red. Assuming your mouse cursor represents a datapoint, the circle in the corner represents what color the datapoint would be classified as. You can choose between two different datasets by clicking on the buttons at the bottom of the project. 
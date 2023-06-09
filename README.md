# Strava
This is a project I started in 2023 to explore and visualise my own strava data.

For a quick look at the final output, **download and open the 'activity_group_map.html'** file (click the file, right click on 'raw', and click 'save link as') which visualises 200 of my activities.
You can click and drag the map to move the view around and scroll to zoom in and out.
You can click on activity types in the legend to hide and show different activity types.

# Creating a map of your own data
You're welcome to use this code to create a map of your own data, however please credit me when sharing the output.

To do this, open the 'get_data.ipynb' file and follow the instructions to set up the api authorisation.
After the data has been saved using this script you should be able to run the 'map_data.ipynb' file.
(You may need to modify a few paramaters including bike names to make the categorisation work properly)

# Other files
the 'exploring_data.ipynb' file visualises some related categorical data to show things like which bikes I have ridden the most over time.

# Future ideas
I'd love to add more functionality and better optimise the heatmap. It would be interesting to add more data to this view to see things like where I tend to go at different times of year.

I'd love to add some different visualisations to show more relationships in the data, such as the relationship between how hard I run/ride and the kudos my activities get.

I'd also like to streamline the project to make it a little more user-friendly for other people to visualise their own data without having to modify code.


**Contributions and feedback are welcome!**

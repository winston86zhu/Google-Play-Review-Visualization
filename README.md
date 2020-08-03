# cs498-ddv-final
D3.js visualization for CS498 Data Visualization course final project

# Live Project
This proejct is hosted live on Github Pages at 

## Visualization Principles
This visualization uses interactive slideshow structure which takes the user through the Dataset of the Google Review Analysis in the year of 2019
    . The dataset itself aggregates user rating for more than 10,000 Applications from the Google Play Store. However, due to
    the consideration of loading time, this analysis filter the data to the size of 2,000. This visualization focuses on the Content Rating
    applied to different age groups. Inp articular, they are 18+, 15+, 7+(mature) and everyone(all-age).
## Interactive Slideshow structure
The pattern will investigate some tangent that you might be interested in, in our case, they will be the relayionship between
    content rating and rate score as well as content rating verses installation numbers. Users have the freedom to
    choose just to continue on if you're not interested in the details of that slide.
## Managing the Dataset
With such a large dataset, creating a visualization with the raw data turned out to be very difficult. The first step for created 
	this visualization was to process the dataset and focus on the data pertaining restaurants in the United States only.
## Templates Structure
 To facilitate a cohesive and smooth look for the interactive visualization, the transition is implemented to capture users' scroll activities. Additionally there is a page navigation bar to help user navigate between different pages. With mose hover on the navigation dots,
the user can see the title of all pages alter alters the display sequence.
This helps user better understanding the thinking pattern from the author.
## Annotations
Annotations have been used in all visualizations with a generic css pattern to annotate key findings. For example, user might get lost
	when looking through the overview bubble chart becuase the size of data is overwhelming. Then in between of each user activities, such like
	clicking buttons, the annotation which the author wants to convey will pop up on the screen to remind the user what the problem is.
	Certainly, the annotation will disappear when user is performing the next activity.

## Parameters and Triggers
Both parameters and triggers are used in all visualizations. For the Bubble Chart Visualization, parameters for the
	x,y co-ordinates of each bubble are set to an initial central position for the All Reviews Visualization. As a user selects menu 
	items to chose between All Reviews, Reviews by State and Reviews by Stars, it triggers the change of bubble’s x,y co-ordinates 
	parameter to their respective groupings.
 In the bar chart presentation, to help user partition the dataset and narrow down to the specific group of users,
	These parameters are triggered to be updated as mouseover tooltips as well as the dropdown selection for free and paid Apps.
	This can provide the user with a snapshot of the amount of installations for a given group. Meanwhile, the sort bar will help the
    user to view all the bars in a sequence if they need to.

# Reference Materials

## Dataset

[Google Play Data Source](https://www.kaggle.com/lava18/google-play-store-apps)

## Images

[Pexels - Analytics](https://www.pexels.com/photo/analytics-text-185576)
[Pexels - Answering Test Pape](https://www.pexels.com/photo/wavelength-1093161)
[Pexels - Wood](https://www.pexels.com/photo/wood-texture-background-pine-82256/)
[Pexels - Essay Background(https://www.pexels.com/photo/background-board-chart-data-590041/)
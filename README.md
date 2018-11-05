<p align="center">
  <img src="https://bikeshare.metro.net/wp-content/themes/lametro/library/images/logo.png">
</p>

# What is this?
This project is a web app for visualizing [Los Angeles bike sharing data](https://bikeshare.metro.net/about/data/). It was made as an entry for [Capital One's Winter 2019 Software Engineering Summit](https://www.mindsumo.com/contests/bikeshare-data).

# Usage
To check out my submission, simply go to [https://seantaylorlane.github.io/CapitalOne-SES-W2019](https://seantaylorlane.github.io/CapitalOne-SES-W2019)

# Tech stack
### Data manipulation
I used Python 3.6 and [pandas](https://pandas.pydata.org/) or cleaning and aggregating data. I chose pandas because I never used Python for data science before and it seemed like it had the most support by the Python community.

All of the data manipulation happened within multiple [Jupyter](http://jupyter.org/) notebooks. I created a notebook for each prompt of the assignment, which helped me organize my thoughts better. You can see all the notebooks inside the `/data` directory.

Everything python-related in this project lives inside a [virtual environment](https://docs.python.org/3/tutorial/venv.html) located in the `/venv` directory. This way, I could work on the project from different machines without having to handle dependencies or versioning for each machine. It also makes it easier for you to run the project from your machine. 

NOTE: I had to remove the virtual environment entirely to get GitHub pages to work. Revert to [this commit](https://github.com/SeanTaylorLane/CapitalOne-SES-W2019/tree/3ae2bb3086759b9ade227c8de6456a490d17643b) if you're trying to run this project on your machine.

### Data visualization
After playing around with the data in my Jupyter notebooks, I ported the output to and generated visualizations with [chart.js](http://www.chartjs.org/). I organized the charts, handled typography, and made the app responsive with [Bootstrap 4](https://getbootstrap.com/).

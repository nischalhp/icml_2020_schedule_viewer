# ICML 2020 Interactive Calendar

ICML stands for The International Conference on Machine Learning. This year due to the pandemic it is taking place remotely. This opens the conference to everyone who is a machine learning practisioner from around the world. After registering for the [event](https://icml.cc/), I found that the schedule page was cumbersome to work with. I am spoiled by the likes of integrated calendars and calendar views for various conferences which can also be filtered. With that in mind, I realized this could also be a problem for many others attending the conference that starts tomorrow. This led to some simple python scripting to convert the schedule HTML page into a CSV with `beautifulsoup` and `pandas`. Added a few filters to visualizing the CSV in `jupyter` notebook with `ipythonwidgets`. 

In order to use the CSV directly, you will find in the `ICML_2020_data` folder. 
In case you want to use the interactive calendar and want to run the notebook, do as follows:

```
git clone repository
mkdir repository
create virtualenv using venv command
activate virtualenv
pip install -r requirements.txt
jupyter nbextension enable --py widgetsnbextension
```

You know have an environment to use the notebooks. To interactively run the calendar open the notebook:

`jupyter notebook` and open the notebook `icml_2020_interactive_schedule`

![](https://github.com/nischalhp/icml_2020_schedule_viewer/blob/master/day_filter.gif)



Enjoy the conference :)

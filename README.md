# YouTube Data

Shows data from trending YouTube videos in the US with the ratio between likes and dislikes (likes minus dislikes) being on the x-axis, and the number of views for the video on the y-axis. There is a total of 6351 videos in which this data was drawn from.

## Description

I start by bringing in the CSV data into Python program. I then parse the data using the CSV package. Lastly, I close the CSV file after I have read the information. For trending YouTube videos in the US, I sort data by the amount of views, compared to the difference of their likes and dislikes (ratio) to shed light on any correlation between the two variables. After the data is parsed, I use matplotlib to create a graph, which is the end product of this code.

## Getting Started

### Note:
All of the steps seen below are under the assumption you are using a Windows device. If you happen to be using another operating system, be sure to find the commands specific to you.

#### Get the Data:
1. Get the data csv from
[kaggel.com](https://www.kaggle.com/datasnaek/youtube-new?select=USvideos.csv)

2. Add it to the data folder

#### Install Dependencies (from the main repository folder):
1. Make a Virtual Environment:
```
    python -m venv venv
```

2. Activate it:
```
    .\venv\Scripts\Activate.ps1
```

3. Install Req:
```
    python -m pip freeze > requirements.txt
    python -m pip install -r requirements.txt
```

4. (If Viewing on jupyter lab)
    Before Running:
```
    python -m ipykernel install --user --name=youtube_data_visualization
```

    To Run:
```    
    jupyter lab
```  
   
## Authors

[conner-cochran](https://github.com/conner-cochran)
# Football Player Detection in OpenCV

This project uses OpenCV to detect and track football players on a pitch during a Chelsea vs Manchester City match. The project is based on color detection and blob analysis techniques.

## Requirements
- OpenCV (3.4 or later)
- Python (3.6 or later)
- Numpy
- Matplotlib (optional, for visualization)

## Usage
1. Run the script with a video file of the match as the input: `python detect_players.py --video path/to/video.mp4`
2. The script will display the original video with player detections overlaid in blue for Chelsea players and red for Manchester City players. Press `q` to exit.
3. (Optional) To save the output video with player detections, add the `--output` flag: `python detect_players.py --video path/to/video.mp4 --output path/to/output.mp4`

## Note
- The color detection parameters (lower and upper bounds) are currently set for Chelsea's blue home kit and Manchester City's red away kit. These will need to be adjusted for different teams and different lighting conditions.
- The player detection is not perfect and may not detect all players or may detect non-players. Further improvements can be made to the detection algorithm.
- This is a simple example of object detection using OpenCV and the results are not optimal.

## References
- The project is inspired by the blog post "Simple Color Detection in Python with OpenCV" by [Adrian Rosebrock](https://www.pyimagesearch.com/2014/08/04/opencv-python-color-detection/)

## Future Work
- Try different color space to achieve more robust detection
-
![footstat-simulation](https://user-images.githubusercontent.com/37596854/214179282-38484f58-ab57-4651-b17d-7c9e5a33b1d2.png)

# World Cup Winner Prediction 

This project aims to predict the winner of the FIFA World Cup using machine learning techniques. The dataset used for training and testing the model includes past World Cup results and statistics.

## Requirements
- Python 3.x
- scikit-learn
- pandas
- numpy

## Data
The dataset used in this project can be found in the `data` folder. It includes information on past World Cup matches, teams, and statistics.

## Usage
1. Run `pip install -r requirements.txt` to install the necessary packages.
2. Run `python main.py` to train and test the model.
3. The predicted winner of the World Cup will be printed in the console.

## Model
The model used in this project is a Random Forest Classifier. The features used for training and prediction are past performance of the team and their statistics.

## Results
The model shows an accuracy of X% on the test set.

## Note
This is a prediction model and it is based on the past performance of the team and statistics. The actual winner of the World Cup can be different.

![Screenshot 2023-01-15 015822](https://user-images.githubusercontent.com/37596854/214179281-e87d4334-eeb8-47f6-a667-072caa511449.png)

# English Premier League Data Scraper

This project is a web scraper that collects data about the English Premier League (EPL). The scraper uses the Python library BeautifulSoup to extract data from the EPL website and stores it in a CSV file.

## Installation

To run this project, you will need to have Python and pip installed on your computer.

1. Clone the repository
```
git clone https://github.com/[username]/epl-scraper.git
```

2. Navigate to the project directory
```
cd epl-scraper
```

3. Install the required packages
```
pip install -r requirements.txt
```

## Usage

To run the script, use the following command:
```
python epl_scraper.py
```

The script will scrape data from the EPL website and store it in a CSV file named `epl_data.csv` in the project directory.

## Customization

You can customize the script to scrape data for a specific season or team by modifying the `URL` variable in the script and adjusting the parsing accordingly.

## Note

Please note that scraping the website too frequently may cause your IP to be blocked. It's best to use this script with a reasonable frequency and make sure you understand the terms and conditions of the website.

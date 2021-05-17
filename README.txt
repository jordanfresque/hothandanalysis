Report:

	"Hot Hand" Analysis Using NBA Shot Charts.pdf



Video:

	https://www.youtube.com/watch?v=7VHp50g33vE&t=1s



Jupyter Notebooks:

	Hot_hand_analysis.ipynb

Hot hand analysis for Steph Curry's 2015-2016 and 2016-2017 seasons using the shot charts found at basketball-reference.com

Data dictionary:
quarter - quarter of game
outcome - make or miss
time_remaining_secs - time remaining in quarter
follows_make - identifies shots following makes
follows_two_makes - identifies shots following two makes
follows_two_misses - identifies shots following two misses


	Predicting_makes_and_misses.ipynb

Fitting a baseline logistic using the same shot charts found at basketball-reference.com

Data dictionary:
quarter - quarter of game
outcome - make or miss
point_value - 2 or 3 pt shot
distance_ft - distance from basket in feet
y_coordinate - pixel coordinate y value
x_coordinate - pixel coordinate x value
time_remaining_secs - time remaining in quarter
score_differential - score differential at time of shot
follows_make - identifies shots following makes
follows_two_makes - identifies shots following two makes
follows_two_misses - identifies shots following two misses
follows_three_makes - identifies shots following three makes
follows_three_misses - identifies shots following three misses
follows_four_makes - identifies shots following four makes
follows_four_misses - identifies shots following four misses
left_side - identifies shots taken from the left side
down_10 - identifies shots taken when down 10 or more
up_10 - identifies shots taken when up 10 or more
down_5 - identifies shots taken when down 5 or more
up_5 - identifies shots taken when up 5 or more
buzzer_beater - identifies shots taken within the last 3 seconds
game - distinct identifier for each game
	
	Advanced_predictions.ipynb

Finding advanced features to better predict makes using the NBA stats API and .csv data downloaded from NBAsavant.com.

Data dictionary:
period - quarter of game  
minutes_remaining - minutes remaining in quarter
seconds_remaining - seconds remaining in quarter
shot_made_flag - make or miss
action_type - type of shot (dunk, layup, jump shot etc.)
shot_type - point value (2 or 3)
shot_distance - distance of shot in feet
opponent - opposing team name
x - pixel coordinate x value
y - pixel coordinate y value
dribbles - number of dribbles taken before shooting
touch_time - how long the player had the ball before shooting (seconds)
defender_name - name of the closest defender
defender_distance - distance to the nearest defender (feet)
shot_clock - time remaining on shot clock (seconds)
SHOT_ZONE_BASIC - region of shot (in the paint, corner 3 etc.)
SHOT_ZONE_AREA - side of court (left side, left centre, centre etc.)
SHOT_ZONE_RANGE - range of shot (<8 feet, 8-16 feet etc.)
HTM - home team name
follows_make - identifies shots following makes
follows_two_makes - identifies shots following two makes
follows_two_misses - identifies shots following two misses
follows_three_makes - identifies shots following three makes
follows_three_misses - identifies shots following three misses
follows_four_makes - identifies shots following four makes
follows_four_misses - identifies shots following four misses



 
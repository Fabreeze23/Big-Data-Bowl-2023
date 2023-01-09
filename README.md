# Big-Data-Bowl-2023
"The xP Philosophy",  Metrics Track

Project datasets:

NFL Play by Play Through 2018: https://www.kaggle.com/datasets/maxhorowitz/nflplaybyplay2009to2016

Big Data Bowl 2021 (2018 season): https://www.kaggle.com/competitions/nfl-big-data-bowl-2021

Big Data Bowl 2023: https://www.kaggle.com/competitions/nfl-big-data-bowl-2023

For the No Hurries data that is commented out please make sure to remove the extra nflId if you want to create it:
# PRESSURE: Without Hurries
#pass_rush_tracking_data_df['is_pressure'] = ((pass_rush_tracking_data_df['pff_hit'] == 1) | (pass_rush_tracking_data_df['pff_sack'] == 1)) 
#pass_rush_tracking_data_df["is_pressure"] = pass_rush_tracking_data_df["is_pressure"].astype(int)
#pass_rush_tracking_data_df = pass_rush_tracking_data_df[['nflId','gameId', 'playId', <b>'nflId'</b>, 'frameId','time','jerseyNumber','team','playDirection','x','y','s','a','dis','o','dir','event', 'is_pressure', 'week']].copy()

We had it ran but not saved then didn't want to show a commit after the competition deadline.

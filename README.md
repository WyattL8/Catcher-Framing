The “production” script looks for a csv titled “new_data.csv” in the same directory, and outputs a csv titled “new_output.csv” in that same directory. 
The csv output from the “production” script includes the following fields:

•	Catcher ID

•	Year

•	Opportunities (total “takes” with tracking data received by a catcher in each season)

•	Actual Called Strikes (How many actual called strikes did the catcher receive in that season?)

•	Called Strikes “added” (How many called strikes did the catcher contribute relative to the average catcher? Can be a negative number)

•	Called Strikes “added” per 100 opportunities. (How many called strikes did the catcher contribute relative to average per 100 opportunities? Can be a negative number)

The framing_model_random_forest.rds file is the model itself that determines the likelihood of a pitch being called a strike. This is so we can best isolate catcher framing impact.

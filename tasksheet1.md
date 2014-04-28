#Task Sheet 1

##Task 3a Answer

1. The function responsible for getting the name from the user is "GetPlayerName".
2. I will ensure that the player is asked for the name repeatedly by using a while loop.
3. The additional variable I will need is "valid name" which is a boolean datatype. 

	ValidName: Boolean
	PlayerName: String
	FUNCTION GetPlayerName()
		OUTPUT ""
		ValidName <- False
		WHILE not ValidName:
			OUTPUT "Please enter your name: "
			INPUT PlayerName
			IF PlayerName = ""
				OUTPUT "You must enter something for your name!"
			ELSE
				ValidName <- True
			END IF
		END WHILE
		OUTPUT ""
		RETURN PlayerName
	END FUNCTION
			
			
##Task 3b Answer

1. The function responsible for adding scores to the table is "UpdateRecentScores".

##Additional Task - Variable roles

###A variable is a memory location which we can refer to using its identifier. 
Fixed Value - a variable initialised without any calculation and not changed thereafter.
Stepper - a variable stepping through a systematic, predictable succession of values.
Most recent holder - a variable holding the latest value encountered when processing a succession of unpredictable values or simply the latest value obtained as input
Most wanted holder - a variable holding the most appropriate value encountered so far
Gatherer - a variable accumulating the effect of individual values
Transformation - a variable that always gets its new value from a fixed calculation of values of other variables
Follower - a variable that gets its new value from the old value of some other data item
Temporary - a variable holding some value for a short time only

Fixed Value example - NO_OF_RECENT_SCORES
Stepper example - Count
Most recent holder example - RecentScores
Most wanted holder example - 
Gatherer example - Choice
Transformation example - Deck
Follower example - Name
Temporary example - Ace
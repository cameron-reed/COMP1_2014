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
Gatherer - a variable gathering the total of the values so far
Transformation - a variable that always gets its new value from a fixed calculation of values of other variables
Follower - a variable that gets its new value from the old value of some other data item
Temporary - a variable holding some value for a short time only

Fixed Value example - NoOfSwaps - line 98 - never changes
Stepper example - Count - line 85 - always increments by 1 each time
Most recent holder example - Choice - line 197 - holds the most recent value
Most wanted holder example - NextCard - line 188 - the value that the program or user wants most
Gatherer example - no examples
Transformation example - FoundSpace - line 171 
Follower example - LastCard - line 187
Temporary example - SwapSpace - line 102

##Additional Task - Functions and parameters

1. Pass by value makes a copy of the original whereas pass by reference changes the actual value
Score - line 139 - passed by value
Deck - line 83 - passed by reference (list always passed by reference)
ThisCard - line 109 - passed by reference (record always passed by reference) 
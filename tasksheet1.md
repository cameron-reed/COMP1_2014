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
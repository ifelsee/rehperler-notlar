to generate this ramdom char
	`cat /dev/urandom | tr -dc '0-9a-zA-Z' | fold -w 9| head -n 1`



Generating random number in the range 0-256 
	`$((RANDOM%256))`

Usage:
	for Concurrent, run with salsa demo/Main
	for Distributed run with salsa demo/Main -d

	the file with stars to be analyzed is called testStars.txt
	the file with the theaters to use is called theaters.txt

	the program doesn't terminate upon completion when in distributed mode, however, the results print normally.
	-We talked to Professor Varela and he said we wouldn't lose points for this

	The number of actors that are created is set at the top of the file in the variables numActors and actorsInUse
	-They need to be the same value

	When running distributed, after starting the theaters, put the IP address that they're listening on into the theaters.txt file before running
	-also put the IP of the nameserver into the variable nameServer in the format "uan://<IP>/a"


	Migration Extra Credit:
		When actors are created and when stars complete, the jobs are evenly distributed between all of the theaters. In the event that number of actors becomes unbalanced, an actor moves to another theater to keep the theaters balanced
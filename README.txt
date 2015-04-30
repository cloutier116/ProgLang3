Usage:
	for Concurrent, run with salsa demo/Main
	for Distributed run with salsa demo/Main -d

	the file with stars to be analyzed is called testStars.txt
	the file with the theaters to use is called theaters.txt

	the program doesn't terminate upon completion when in distributed mode, however, the results print normally.
	-the salsa release tutorial seems to indicate that this is normal behavior

	The number of actors that are created is set at the top of the file in the variables numActors and actorsInUse
	-They need to be the same value

	When running distributed, after starting the theaters, put the IP address that they're listening on into the theaters.txt file before running
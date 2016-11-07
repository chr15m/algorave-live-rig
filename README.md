Launch Pd app:

	./launch &

Set the BPM:

	. ./bpm 180

Set notehash environment variables:

	. ./notes

Build stems with notehash environment and load into channels:

	./slot # get a list of generators
	./slot 0 bleep_crunch
	./slot 1 808er

Record

	./record
	./record --stop


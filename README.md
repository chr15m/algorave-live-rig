Launch Pd app:

	./bin/launch [--gui] &

Get into virtualenv:

	. ./virtualenv/bin/activate

Set the BPM:

	. ./bin/bpm 180

Set notehash environment variables:

	. ./bin/notes

Build stems with notehash environment and load into channels:

	./bin/slot # get a list of generators
	./bin/slot 0 bleep_crunch
	./bin/slot 1 808er

Record

	./bin/record
	./bin/record --stop

Volume

	. ./bin/send mix/mixer/0/vol 1


# count-em
Simple counter for linux terminal

Simple Batch script, compatible with all linux systems, no dependencies required.

It's a counter, can be invoked to increment a specific count routine.
It saves values in a folder and keep track of the latest active count routine.

With list option can resume previous saved count routine.

### HELP
	COUNT-EM-ALL - A simple counter...

		Uso: count-em-all [OPTIONS]

	OPTIONS:
		Used without options it'll increment by 1 the last active counter OR it'll create a new counter if no one is active yet.

	last	View last active couter
	list	List all counters saved and prompt to choose which make the active one
	new	Create a new counter
	reset	Reset all counters
	help	View help page

# Intro

The system is actually pretty simple: it comes down to a stripped down cheapo USB keyboard, with custom switches and a board.

# Opening up a keyboard

It's pretty easy, remove the tabs or the screws and take everything out of the case. At this point you should trace all the keys you need by looking at the traces top and bottom. I chose to save the keys I needed using the binary system for the two traces that are connected. [traces.csv](traces.csv) stores this data for my keyboard (Trust Classicline BE.).

# Picking up the switches

At this point you can connect two wires to the traces that are the wanted keys, and in the middle a press switch that can easily be pushed, or for some things you could add a toggle switch, but you'll probably have to check your software repeat rate.

# Designing your layout

You can then layout the switches on some board, my design will be in [design.svg](design.svg) (first sketch is at [sketch.jpg](sketch.jpg)).
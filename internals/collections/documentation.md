# Here is how the memory logic works

*title.collection* is the Main Menu where there is obviously the credits, play button game and whatever else the dev includes. *global.collection* is the bootstrap collection but also is a collection that remains loaded globally throughout the entire game's life cycle. This may contain references to collection proxies for loading levels, store global flags, or generally anything to do with global data. 

On first startup the *global.collection* is expected to initialize the title screen.

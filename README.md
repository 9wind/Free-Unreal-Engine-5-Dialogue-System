# Free Unreal Engine 5 Dialogue System
Free, versatile and simple Unreal Engine 5 Dialogue System driven by Data Tables.

System is very simple. It's driven completely by Data Tables. It supports audio files, animation montages, decision making, custom cameras and custom events.
To play decision just add values in "Decisions" array. To end dial after certain row just mark ShouldEnd in the DataTable. 
There is a function related to the custom event that fires during the dialogue. You can override it and play your own custom events. I implemented example that switches string on chosen option and changes color of the cube.
For camera changes I use tags. Just add a tag to "Dialogue Camera" after your place it in your level, then use this tag in the database. It will blend automatically if tag of camera is valid.

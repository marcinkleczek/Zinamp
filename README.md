#ZINAMP
a web-based local audio player made in HTML and JS.
http://zinamp.com
http://twitter.com/zinamp

#####ABOUT
On December 20th, 2013, Winamp will have shut down forever. Zinamp is by no means a web-based Winamp clone, just another project paying respect to one of the greats. 

#####RESPECT
Thanks to Antimatter15 for writing the original code from 2010 and posting it to github for us to use. To my knowledge, AM15 was the first person to demonstrate this type of functionality in a web-based medium, as noted in the original code.

#####USABILITY
######Browse
Click browse to add tracks to the playlist. Chrome users can add entire folders, Firefox users can only add groups of files (due to limitations of Firefox, not Zinamp's code). Firefox users can also add entire .Zip archives full of tracks in order to bring in larger numbers of files.

######Search
The top bar that says ^Zinamp is actually a search bar. Click it, and then start typing to search through your current library of tracks. AutoComplete is turned on by default, but SpellCheck is disabled. Both of these options can be changed in the code by changing "on" to "off" near the respective commands.

######Library
The majority of the window is occupied by the Library which is blank until you add tracks. The main scroll bar of your browser should run through all of the tracks in your library, where all of the ID3 info is available: genre, title, artist etc. As of the time of this writing, there is a popup dialogue that pretty much forces you to add tracks first, so by the time you see the rest of the application, you already have tracks in the library, and it should be pretty obvious.

######Playlist
The right side of the window is the Playlist. You add tracks to the current playlist by clicking any track in the library. As of this time there is no way to remove individual tracks from the playlist. Also, the browse button breaks the CLEAR and SHUFFLE buttons when added into the same div.

######Clear and Shuffle
This should be self explanatory.
	

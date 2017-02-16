# Youtube Via Facebook Messenger  

For the lazy folks (of _IIT Roorkee_ and elsewhere) who listen to music on YouTube, now you don't have to go anywhere from Facebook or get up from the bed if you're using FB Messenger on your phone, to change a song on YouTube.  

A tool to control YouTube using Facebook messenger. Run the script and once set up, just fire up Facebook chat or messenger on any of your devices and start chatting with yourself to control YouTube.  
  
### Dependencies  
**selenium** - `pip install selenium`  

### Usage  

##Running The Program:

python2 main.py -e user@domain -p Password

-e EMAIL, --email EMAIL facebook / messenger login email

-p PASSWORD, --password PASSWORD facebook / messenger login password
                        

* `play <search term>` : Returns top 5 videos from YouTube, waits for an integer response to play video
*	`play-now <search term>` : Plays first video from search results (I'm feeling lucky)
*	`seek-to <time in seconds>` : Seeks to the said time
*	`pause` : Pauses the video
*	`unpause` : Unpauses the video
*	`mute` : Mutes the video
*	`unmute` : Unmutes the video  

#### Note
The tool is not idiot proof yet. Kindly fork and help in making it idiot proof.

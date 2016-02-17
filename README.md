# Spotify Playlist Downloader

Download an entire spotify playlist ( FROM SPOTIFY @ 160kbps ) to your local machine.

Also upon download it writes the ID3 data to the file.

###To install:
Install nodejs if you haven't already. ([NodeJS Downloads](http://nodejs.org/download/))  
Then download this repository (*"Download ZIP"* button on this page)  
Unpack the repository and run the following command in the root of where all the files are (main.js, readme.md, ...):  

    npm install


###Available Options

	
	Usage: node main.js [options]
	
	Options:

	    -h, --help                   output usage information
	    -V, --version                output the version number
	    -u, --username [username]    Spotify Playlist Username (required)
	    -p, --playlist [playlist]    Spotify Playlist (required)
	    -d, --directory [directory]  Directory you want to save the mp3s to, default: HOME/spotify-mp3s
	    -f, --folder                 create sub-folder for playlist
	


####So if you wanted to download "Top 100 Hip-Hop Tracks on Spotify", you would use the following command:
    Playlist Uri looks like this: spotify:UserXYZ:spotify:playlist:06KmJWiQhL0XiV6QQAHsmw

	node main.js -u UserXYZ -p 06KmJWiQhL0XiV6QQAHsmw

####The output should look something like:

![image](spotify-downloader.png)



###Must haves:

- ~~Spotify Premium Account ( haven't tried it on a free account )~~  
_Works fine with a free account as well, get's limited after a while though, but starts downloads again afterwards_ 

# idea-boi
Project ideas that pops into our heads that we want to create a project around.

## Teamspeak 3 Bot (Ariana Grenade 2.0) 
 * Spotify (if possible - very attractive), Youtube, Soundcloud and Vimeo support
 * Music player support.
   * Normal player functionality. (Play, pause, stop, next etc.)
   * Playlist support. (Add, save, copy from Spotify/YT/SC etc.)
 * Browser extension.
   * Add the song in the active tab to a desired playlist or queue.
   * Add whole playlist from a an active tab.
 
## Public key infrastructure management system
 * Generate client/server PEM certificates
 * Handle CSR (certificates signing request)
 * Revoke PEM certificates
 * ReactJS webapp to perform the above
 
## Magic Mirror
 * RaspberryPi powered monitor w/ semi-transparent film/mirror
 * ReactJS or Win10 Core powered GUI
 * Connects with social media (Facebook, Twitter, Reddit ect.)
 * Connect with a secure messaging product (Wire, Keybase etc.) (Discuss whether to show messages or just notification)
 * Campusnet notifications.
   * Current courses.
   * Assignment deadlines.
   * Messages.
   
## Game server manager
 * A contanerized dedicated game server management system powered by Docker
 * Spin up new game server with a single click
 * Change port, settings & configuration files for each server
 * ReactJS web app to configure game servers
 * Backup game servers (snapshotting) 
 * Browser text editor (IDE) to write configuration files for each game server
 * Whitelisting option using *iptables*

## Password manager
 * Modern **self-hosted**, open source password manager
 * Platform support for Linux, Windows, MacOS (using Electron framework)
 * Platform support for Android, iOS (Using Flutter framework)
 * Browser plugins for Chrome, Safari, Firefox
 * Stateless password storage using hash of master password, username site hostname
 
 ## PlayStation DualShock 4 Bluetooth Audio Device
  * A sound driver to use your PlayStation 4 controller as playback device on Windows
  * Connect your PlayStation DualShock 4 controller to Windows
  * Add a virtual sound device to playback devices
  * Play back audio and stream the audio to the controller using bluetooth
  * Use the built in mini-jack in the controller to listen
  
 ## Router Management Webapplication
  * ReactJS webapplication to manage DIY router (linux/bsd based)
  * Firewall configuration (blacklist/whitelist/portforwarding)
  * VPN configuration (using OpenVPN)
  * DHCP configuration
  * DNS configuration
  
 ## Subtitle Matching using Speech Recognition
  * Match subtitles against audio
    * Look up a phrase in the *.srt* file and extract the audio
    * Convert the audio to text using speech recognition
    * Correlate the original phrase with the processed phrase
    * Continue to pick phrases U.A.R. to increase confidence
  * Use [Sphinx](http://www.sphinx-doc.org/en/master/) library for speech recognition
  * Use machine learning to find correlation between text and voice
    * Find most commonly used words in english language/subtitles
    * Make a bag of words (BOW) from those words
    * Train a neural network to estimate the BOW from speech
    * Input can be MFCC fed to an RNN, output will be a 1D-tensor with size of BOW
  
 ## OpenVPN GUI client using Electron framework
  * A GUI wrapper for the OpenVPN binary
  * For Windows, MacOS & Linux
  * Replacement for Tunnelblick (MacOS)
  
 ## SET: The Family Game of Visual Perception
  * A solver for the SET game ([https://www.setgame.com/set](https://www.setgame.com/set))
  * Scan the cards using mobile phone's camera
    - Use SIFT features to find cards
    - Search for any of the 27 figures in each card
    - Cluster localized object using K-means
  * Search for solution using brute force or state based search
  
## Mobile Jukebox
 * People can join a jukebox lobby together
 * Use spotify API to search and queue music
 * People can upvote and downvote music suggestions
 * Music is played according to the priority queue of the music
 
## CSGO damage counter
 * Inspects the game console and extracts damage inflicted on enemy players
 * Keeps track of enemy players remaining health
 * Optionally shares data with team member also using the program
 * HUD overlay (or other GUI) to keep track of enemies with low health

## CampusNet Sync
 * Login with your CampusNet account
 * Get a list about which courses you have
 * Choose which to sync
 * Sync will download filesharing files/folders to specified directory
 * `campussync --course 02232`
 * `campussync --all`

## Privacy Enhanced Messenger
 * When opening messenger.com, all recent contacts are shown on the left and the most recently used conversation will be opened
 * This is convenient sure, but can be troublesome if some conversations are private
 * Research whether it is possible to open up a specific conversation in messenger by using a keyword e.g. "John"

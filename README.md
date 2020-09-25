## Download the bot files
 * [MUsic bot files are here](https://drive.google.com/drive/folders/1nV4k69aIyrdvRo5epIU4YlB4Qn06Lxlh?usp=sharing)
## Features
  * Easy to run (just make sure Java is installed, and run!)
  * Fast loading of songs
  * No external keys needed (besides a Discord Bot token)
  * Smooth playback
  * Server-specific setup for the "DJ" role that can moderate the music
  * Clean and beautiful menus
  * Channel-topic playback bar
  * Supports many sites, including Youtube, Soundcloud, and more
  * Supports many online radio/streams
  * Supports local files
  * Playlist support (both web/youtube, and local)

## Example
![Loading Example...](https://i.imgur.com/kVtTKvS.gif)

## Setup
  
 * Download the latest JMusicBot-X.Y.Z.jar (and optionally, example config.txt file) from the releases page (or, get the URL from the releases page and then use wget or similar command-line tool to download).

## Edit the config file
  * token = Your_bot_token
    owner = ID_of_bot_owner
    prefix = "Your_desired_prefix"

## Run the Jar file
  
  * Run the jar file (choose one of these options):
Double-click the jar file (on desktop environments), OR
Run java -Dnogui=true -jar JMusicBot-X.Y.Z.jar from the command line (replace X, Y, and Z with the release numbers), OR
Run nohup java -Dnogui=true -jar JMusicBot-X.Y.Z.jar & to run in the background (Linux only)
Provide the requested information, if prompted.
Wait for the "Finished Loading" message.
 



## Editing
This bot (and the source code here) might not be easy to edit for inexperienced programmers. The main purpose of having the source public is to show the capabilities of the libraries, to allow others to understand how the bot works, and to allow those knowledgeable about java, JDA, and Discord bot development to contribute. There are many requirements and dependencies required to edit and compile it, and there will not be support provided for people looking to make changes on their own. Instead, consider making a feature request (see the above section). If you choose to make edits, please do so in accordance with the Apache 2.0 License.

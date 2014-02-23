# Music playlist sync to USB Key

Having problems managing music on usb devices using iTunes, this is your answer!

## Key features
* Take iTunes playlist and sync it to a USB key
* Take any organised m3u playlist and sync it to USB key
* Maintains folder structure 
* Can be used to compress audio to fit more on USB key
* Maintains metadata when compressing
* Use repeatedly to sync a playlist
* Will remove tracks no longer on playlist that remain on USB key

## Usage
	
 playlist_sync playlist.m3u [options]

 OPTIONS:
   
   -c bitrate : Bitrate to convert audio to, default no conversion.

## Idiots guide, on a Mac

1. Extract the files to a folder (e.g. Downloads/playlist_sync)
2. Save your playlist as an m3u file into the same folder
  * In iTunes right click the playlist and click export!
3. Click 'spotlight' (the magic wand at the top of your screen)
4. Type 'terminal' (without the quotes) and hit enter
5. Type 'cd Downloads/playlist_sync' (or whatever folder you used)
6. Type './playlist_sync playlist.m3u -c 128'
   * This will sync the playlist called playlist.m3u and convert all songs to 128kb/s if they are higher than 128+32 in bitrate currently.

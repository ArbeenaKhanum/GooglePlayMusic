# Music Player App

###### Music Player application contains a list of songs.

## Technologies
* Java
* Services
* Content Provider

## Features

* The Music Player app displays a list of songs. With the help of Content Provider, all the songs from mobile device are provided to this music player app.
* The app allows you to Play, Pause and Stop songs with the help of Services.
* This app also provides the feature to shuffle and repeat songs.
* As per the requirement, the songs from the app can be deleted.

## Screenshots and description

After opening the application, you will find the welcome screen that stays in for 2 seconds. Afer that you can see the main home screen of the application. It displays the songs
from mobile device using content provider. 

It consists of 4 fragments namely, "Home", "Songs", "Albums" and "Artists". It also contains a search view and menu button at the top right corner of the screen.

|**Welcome screen**|**Main Home screen**|
|:---|:--|
|<img src=images/music_splash.jpeg height="500px"/>|<img src=images/music_home.jpeg height="500px"/>|

<br/><br/>

The Home, Songs, Albums and Artists fragments contains its respective contents which is that the Home fragments displays all the songs present in the device. The Albums displays the list of all songs as per the albums name and the Artists fragment displays the songs based on the list of artists' name.

|**Albums screen**|**Artists screen**|
|:---|:--|
|<img src=images/music_album.jpeg height="500px"/>|<img src=images/music_artists.jpeg height="500px"/>|

<br/> <br/>

The Songs fragment displays the list of all the songs with the song name. On click of the song, its respective Music Play screen appears and the service starts so song starts playing. 

Using Services, user can play, pause & stop the song on click of play button. It provides the feature to shuffle the songs in the device and play it and if the user wants a song to play on repeat mode, user can click on repeat song option. It also consists of seek bar and it displays the duration of the current playing song. 

|**SongsList screen**|**Music Play screen**|
|:---|:--|
|<img src=images/music_song_list.jpeg height="500px"/>|<img src=images/music_song_play.jpeg height="500px"/>|

<br/> <br/>

The user can search the songs as per their choice with the help of seach view option. The list of songs are filtered according to the search input. 
The songs can be sorted based on the songs alphabets, date and size. It also provides the options to delete the song from the device. If the user wants to do it, they can click on the menu option at the end of the song and delete it.

|**Search view**|**Sort songs**|**Delete songs**|
|:---|:--|:--|
|<img src=images/music_search.jpeg height="500px"/>|<img src=images/music_sort.jpeg height="500px"/>|<img src=images/music_delete.jpeg height="500px"/>

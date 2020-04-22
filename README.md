# Music Playlist

A client wants to listen to the music tracks in from differnt playlists to get a sense for what they sound like. The playlist are given in a CSV format downloaded from spotify. The given playlists: [JPOP](https://open.spotify.com/playlist/3a8sD1YogCRwItfuUBoWtv), [KPOP](https://open.spotify.com/playlist/7MilJ9i1Fo38oLVRTxbjUo), and [Latin](https://open.spotify.com/playlist/37i9dQZF1DWVcbzTgVpNRm).

## Dependencies

* [Java 8](https://docs.oracle.com/javase/8/docs/api/index.html)


## Setup

These are the steps to compile and run `MyApp.java`. 
The Source code is available in the `src` folder.
These steps are for use with command line workflow such as with a terminal.

1. Clone this repository `git clone https://github.com/MAzhar43/AssignmentTwo.git` to your machine to get a copy.
2. Move into the project's root directory with `cd src`
3. Compile the java file using the java compiler command `javac MyApp.java`
4. Run the compiled java program with the java command `java MyApp`

Running the program will prompt you with the following:

```bash
Print Play[L]ist | | [P]lay | [R]ecent | [S]top
```

Selecting `L` will print a merged list of all the three playlists.
Selecting `P` will print out the name of the current track playing.
Selecting `N` will print out the name of the next track in the playlist.
Selecting `R` will print out the name of the previous track from the playlist.
Selecting `S` will exit the program.

## Folder Structure 

* Code is saved into the `src` folder.
* Data is saved into the `data` folder.

## Developer

Muhammad Azhar

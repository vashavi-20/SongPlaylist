# SongPlaylist

This repository contains the Java implementation for a simple song playlist manager. It demonstrates the use of object-oriented programming concepts to manage songs in albums and playlists.

## Code

```java
package com.vashavi;

import java.util.*;

public class Main {
    private static ArrayList<Album> albums = new ArrayList<>();

    public static void main(String[] args) {
        // Album and song creation code here...
    }

    // Additional methods...
}

package com.vashavi;

public class Song {
    private String title;
    private double duration;

    // Constructors, getters, and toString methods..
}

package com.vashavi;

import java.util.ArrayList;
import java.util.LinkedList;

public class Album {
    private String name;
    private String artist;
    private ArrayList<Song> songs;

    // Constructors, song management methods...
}
```

## Overview

The SongPlaylist project is a Java application that allows users to create albums with songs, add songs to playlists, and navigate through the playlist. It includes classes Main, Song, and Album, each serving a specific purpose in the playlist management system.

- Main: Orchestrates the creation of albums and playlists, and handles user interactions.
- Song: Represents a song with a title and duration.
- Album: Manages a collection of songs and provides functionality to add songs to albums and playlists.

## Usage

To use this application, compile and run the Main class. The application will prompt you to interact with the playlist through a simple command-line interface.


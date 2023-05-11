# TerminalMusicPlayer-in-C
A simple terminal music player written in C, which uses `ffplay` (a part of `ffmpeg`) for playing music.
# C Terminal Music Player

## Features

- Play/Pause/Stop a track
- Switch to the next or previous track
- List all available tracks

## Prerequisites

You need to have `ffmpeg` installed on your machine to run this music player.

### Installing ffmpeg

- On Ubuntu or other Debian-based systems, you can install `ffmpeg` with `apt`:

    ```
    sudo apt update
    sudo apt install ffmpeg
    ```

- On macOS, you can install `ffmpeg` with `Homebrew`:

    ```
    brew install ffmpeg
    ```

## Compilation

Compile the music player using `gcc`:
```
gcc -o music_player main.c
```

## Usage

To run the music player, you need to provide a directory containing your music files as a command-line argument:



Once the music player is running, you can use the following commands:

- `play`: Starts playing the current track or resumes if paused
- `pause`: Pauses the current track
- `stop`: Stops the current track
- `next`: Plays the next track
- `prev`: Plays the previous track
- `list`: Lists all available tracks
- `exit`: Exits the music player

## License

This project is licensed under the MIT License.



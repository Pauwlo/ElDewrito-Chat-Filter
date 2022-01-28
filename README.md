# ElDewrito Chat Filter

Unofficial patch for ElDewrito 0.6.1 that allows users to filter (mute) certain players or words in text chat.

## Install

1. [Download this repository](https://github.com/Pauwlo/ElDewrito-Chat-Filter/archive/refs/heads/main.zip).
2. Extract the `mods` folder into your ElDewrito installation folder.
3. Replace existing files.

## Uninstall

1. [Download this repository](https://github.com/Pauwlo/ElDewrito-Chat-Filter/archive/refs/heads/main.zip).
2. Extract the `Default files\mods` folder into your ElDewrito installation folder.
3. Replace existing files.

## Usage

This patch adds a couple buttons to your game:

- You can "Mute text" and "Unmute text" a player by right-clicking their name on the scoreboard.
- You can temporarily disable the chat filter by unchecking the checkbox (visible when chat is opened and mouse is hovering it).

## Filter words or players permanently

1. Open [`mods\ui\web\screens\chat\chat.js`](https://github.com/Pauwlo/ElDewrito-Chat-Filter/blob/main/mods/ui/web/screens/chat/chat.js) in a text editor.
2. Add names to the `filteredNames` array, or words to the `filteredWords` array.

Please follow JavaScript's syntax: see [here](https://www.w3schools.com/js/js_arrays.asp).
